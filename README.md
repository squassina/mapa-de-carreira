# Diagnóstico Tridimensional de Carreira (RIASEC, Schein & DISC)

Aplicação web interativa (Single-Page Application) concebida como instrumento de apoio à consultoria de carreiras e orientação vocacional. O sistema conduz uma entrevista estruturada com dois níveis de profundidade — **Versão Padrão (24 questões)** e **Versão Estendida (42 questões)** — gerando um parecer analítico consolidado que cruza interesses profissionais, valores decisórios e padrões comportamentais.

O instrumento foi projetado para atender profissionais, estudantes e gestores de diferentes áreas de atuação — incluindo saúde, direito, educação, engenharia, artes, administração, setor público e tecnologia.

## Visão Geral e Funcionalidades

* **Entrevista Estruturada com Pareamento Balanceado:**

  * **Versão Padrão (24 questões):** 8 questões por módulo (RIASEC, Schein e DISC), garantindo equilíbrio entre agilidade e precisão estatística.

  * **Versão Estendida (42 questões):** 14 questões por módulo com cenários situacionais e dilemas comparativos de aprofundamento, preservando automaticamente as respostas já preenchidas na versão padrão.

  * **Design de Blocos Incompletos Balanceados (BIBD):** As oito Âncoras de Schein são avaliadas em questões objetivas de 4 alternativas combinadas ciclicamente, eliminando a sobrecarga cognitiva de questões extensas e garantindo exposição estatística idêntica a todas as dimensões.

* **Painel Analítico e Visualização de Dados:** Geração imediata de gráficos interativos (radar, barras horizontais e rosca), índices de nitidez psicométrica e indicadores-chave (KPIs) consolidando o código Holland, a âncora de carreira predominante e o estilo comportamental DISC.

* **Síntese Diagnóstica e Cruzamento de Variáveis:**

  * Identificação do ecossistema organizacional compatível e mapeamento de funções correlatas em diversos setores.

  * Sinalização de tensões internas decorrentes de eventuais divergências entre valores centrais (Schein) e estilo de execução (DISC).

  * Diretrizes estratégicas de desenvolvimento profissional e mapeamento de pontos de atenção.

* **Fundamentação Metodológica:** Seção dedicada à exposição teórica dos três modelos psicométricos, acompanhada de uma matriz interativa filtrável por perfil comportamental.

## Arquitetura e Tecnologias

* **HTML5 e JavaScript (ES6+):** Processamento de pontuação, gerenciamento de estado e geração dinâmica de pareceres executados integralmente no navegador (*client-side*), dispensando infraestrutura de servidor ou banco de dados.

* **Tailwind CSS (via CDN):** Estilização responsiva orientada à legibilidade e organização visual.

* **Chart.js (via CDN):** Renderização de gráficos analíticos em elemento `<canvas>`.

* **Google Fonts:** Composição tipográfica utilizando *Plus Jakarta Sans* e *Lora*.

## Implantação e Execução

Como toda a aplicação reside no arquivo único `index.html`, não há necessidade de instalação de dependências ou etapas de compilação:

1. **Execução Local:** Baixe o arquivo `index.html` e abra-o diretamente em qualquer navegador moderno.

2. **Publicação via GitHub Pages:**

   * Acesse a aba **Settings** do repositório no GitHub.

   * No menu lateral esquerdo, selecione **Pages**.

   * Em **Build and deployment > Branch**, selecione `main` (diretório `/root`) e clique em **Save**.

## Referências Teóricas

A arquitetura diagnóstica deste questionário fundamenta-se na convergência de três modelos consagrados da psicologia organizacional e da orientação profissional:

1. **Modelo RIASEC (Código Holland) — Interesses Vocacionais**

   * **Referência:** HOLLAND, John L. *Making Vocational Choices: A Theory of Vocational Personalities and Work Environments*. 3. ed. Odessa, FL: Psychological Assessment Resources, 1997. (Obra original publicada em 1959).

   * **Aplicação:** Baseado também na taxonomia do **O\*NET Interest Profiler** (*U.S. Department of Labor / Employment and Training Administration*), avaliando os vetores *Realista, Investigativo, Artístico, Social, Empreendedor e Convencional*.

2. **Âncoras de Carreira (Career Anchors) — Valores e Motivações Centrais**

   * **Referência:** SCHEIN, Edgar H. *Career Dynamics: Matching Individual and Organizational Needs*. Reading, MA: Addison-Wesley, 1978; e SCHEIN, Edgar H. *Career Anchors: Discovering Your Real Values*. San Francisco: Pfeiffer/Wiley, 1990.

   * **Aplicação:** Mapeamento das oito âncoras decisórias (*Competência Técnico-Funcional, Competência Gerencial Geral, Autonomia/Independência, Segurança/Estabilidade, Criatividade Empreendedora, Serviço/Dedicação a uma Causa, Desafio Puro e Estilo de Vida*).

3. **Teoria Comportamental DISC — Estilo de Ação e Comunicação**

   * **Referência:** MARSTON, William Moulton. *Emotions of Normal People*. London: Kegan Paul, Trench, Trubner & Co., 1928.

   * **Aplicação:** Classificação dos padrões observáveis de resposta ao ambiente em quatro dimensões (*Dominância, Influência, Estabilidade e Conformidade*).

## Licença

Este projeto e o conteúdo textual do questionário diagnóstico estão licenciados sob a licença **Creative Commons Atribuição-CompartilhaIgual 4.0 Internacional (CC BY-SA 4.0)**.

Você tem o direito de compartilhar e adaptar o material para qualquer finalidade, desde que atribua os devidos créditos aos autores originais e distribua eventuais derivações sob a mesma licença. Para mais detalhes, consulte o texto integral em [creativecommons.org/licenses/by-sa/4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.pt-br).
