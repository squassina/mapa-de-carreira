# Roadmap e Evoluções Sugeridas (TO-DO)

Este documento reúne melhorias planejadas para expandir as funcionalidades, a precisão analítica e a experiência de uso da aplicação **Diagnóstico Tridimensional de Carreira**, mantendo a premissa arquitetural de execução integral no navegador (*client-side*).

## 1. Exportação e Compartilhamento de Resultados

- [ ] **Exportação do Parecer em PDF:** Implementar folha de estilo dedicada para impressão (`@media print`) ou integração com biblioteca *client-side* para gerar um relatório técnico formatado, contendo os gráficos renderizados e o parecer completo.
- [ ] **Compartilhamento via URL Parametrizada:** Codificar o vetor de respostas em parâmetro na URL (*hash* ou *query string*), permitindo que o usuário envie o link do seu diagnóstico para um consultor, mentor ou recrutador visualizar o painel sem necessidade de banco de dados.
- [ ] **Cópia Rápida do Resumo:** Adicionar botão para copiar o diagnóstico sintetizado em texto estruturado para a área de transferência, facilitando o envio por e-mail ou mensagens.

## 2. Experiência do Usuário (UX) e Persistência Local

- [ ] **Salvamento Automático (`localStorage`):** Persistir o progresso da entrevista no armazenamento local do navegador para evitar a perda das respostas em caso de fechamento ou recarregamento acidental da página.
- [ ] **Histórico Comparativo de Avaliações:** Permitir que o usuário salve diagnósticos datados localmente e compare a evolução do seu perfil ao longo do tempo (por exemplo, a cada 12 ou 24 meses).
- [ ] **Navegação por Teclado:** Adicionar atalhos de teclado (teclas alfabéticas ou numéricas para selecionar alternativas e setas direcionais para avançar ou retroceder) visando agilizar o preenchimento em computadores.

## 3. Aprofundamento Psicométrico e Analítico

- [x] **Modo de Entrevista Estendida (Opcional):** Oferecer ao usuário a escolha entre o modo padrão revisado (24 questões com pareamento balanceado) e o modo aprofundado (42 questões) para aumentar a granulometria estatística e reduzir empates entre dimensões.
- [ ] **Análise Dinâmica de Perfis Híbridos:** Expandir o motor de regras para gerar pareceres específicos com base no cruzamento exato das três letras do Código Holland (RIASEC) combinadas ao perfil DISC primário e secundário.
- [ ] **Guia de Preparação para Entrevistas:** Incluir uma aba ou seção complementar no diagnóstico traduzindo os pontos fortes e pontos cegos identificados em argumentos práticos para processos seletivos e negociações de carreira.

## 4. Acessibilidade, Internacionalização e SEO

- [ ] **Auditoria de Acessibilidade (WCAG):** Revisar atributos `ARIA`, ordem de foco, contraste de cores e descrições textuais alternativas para os gráficos em `<canvas>`, garantindo compatibilidade plena com leitores de tela.
- [ ] **Internacionalização (i18n):** Estruturar dicionários de tradução para disponibilizar o questionário e os pareceres em Inglês (`en-US`) e Espanhol (`es-ES`), ampliando o alcance do repositório.
- [ ] **Metadados de Compartilhamento (Open Graph):** Adicionar tags `og:title`, `og:description` e `og:image` no `<head>` do `index.html` para aprimorar a pré-visualização do link quando compartilhado no LinkedIn ou outras redes.
