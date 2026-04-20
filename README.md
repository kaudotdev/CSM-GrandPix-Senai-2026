# CSM Simulação — Carenagem Sustentável

## Visão Geral

Este projeto é um protótipo interativo para simulação de substituição de carenagem frontal de caminhão, focado em sustentabilidade, circularidade e indicadores ESG. Desenvolvido para o Grand Prix SENAI 2026, ele demonstra, de forma visual e didática, os benefícios ambientais e econômicos da adoção de um módulo monomaterial em polipropileno (PP) em substituição ao tradicional ABS multipeça.

## Funcionalidades

- **Simulação 3D Interativa:**
  - Arraste e solte o chip verde para aplicar o módulo sustentável ao caminhão em um ambiente 3D realista (Three.js).
  - Visualização de mudanças visuais e indicadores em tempo real.
- **Indicadores ESG Dinâmicos:**
  - Emissão de CO₂/ciclo, reciclabilidade, custo de desmontagem, índice de reuso, rastreabilidade e mais.
  - Antes e depois da substituição, com animações e gráficos comparativos.
- **Plataforma Cliente (Modal Mobile):**
  - Visualização do passaporte digital do módulo, histórico de uso, recomendações de destino circular e integração com logística reversa.
  - Registro detalhado do material, vantagens circulares e economia de CO₂ em tempo real.
- **Painel IVECO (Modal PC):**
  - Dashboard de triagem, lotes em processamento, distribuição de destinos e valor circular gerado.
  - Fluxo de classificação (coleta, triagem, reuso, remanufatura, reciclagem).
- **Animações e Feedback Visual:**
  - Confetes, crescimento de planta, logs de substituição e tooltips explicativos.

## Tecnologias Utilizadas

- **HTML5, CSS3 (custom properties, grid, flexbox, animações)**
- **JavaScript (ES6+)**
- **Three.js** para renderização 3D
- **Chart.js** para gráficos dinâmicos
- **SVG** para elementos gráficos e animações
- **Google Fonts** (IBM Plex Mono, DM Sans)

## Como Usar

1. Abra o arquivo `prototipo.html` em um navegador moderno (preferencialmente Chrome ou Edge).
2. Interaja com o chip verde (PP) e arraste-o até a cabine azul do caminhão para simular a substituição.
3. Observe as mudanças nos indicadores ESG, gráficos e logs.
4. Explore as plataformas mobile (Cliente) e PC (IVECO) clicando nos botões no topo.

## Estrutura do Projeto

- `prototipo.html`: Arquivo principal contendo todo o código (HTML, CSS, JS) e lógica da simulação.
- `Caminhão.gltf`: Modelo 3D do caminhão (necessário para renderização 3D, não incluso neste repositório).

## Indicadores e Métricas

- **CO₂/ciclo:** Redução de 12,4 kg para 6,2 kg por peça (~50%)
- **Reciclabilidade:** De 38% (ABS/PA/PU) para 94% (PP monomaterial)
- **Custo de desmontagem:** De R$ 320 para R$ 140/unidade
- **Índice de reuso:** De 0,28 para 0,82
- **Materiais distintos:** De 6 para 1
- **Rastreabilidade:** Passaporte digital QR + ID único

## Diferenciais Técnicos

- **Design for Disassembly (DfD):** Snap-fit, sem adesivos, facilita desmontagem e reuso.
- **Monomaterialidade:** Elimina etapas de triagem, aumenta pureza do reciclado.
- **Passaporte Digital:** Rastreabilidade completa, integração com logística reversa.
- **Visualização Didática:** Gráficos, logs e animações para facilitar entendimento dos ganhos ESG.

## Fontes e Referências

- PlasticsEurope / ETC-WMGE 2021
- ISO 14040/14044 — Avaliação do Ciclo de Vida (LCA)
- Dados simulados para fins de prototipagem

## Créditos

- Protótipo desenvolvido por Dant'z para o Grand Prix SENAI 2026
- Feito com muito amor e carinho 🍀

## Licença

Este projeto é um protótipo educacional e não possui fins comerciais. Sinta-se livre para estudar, adaptar e evoluir para fins acadêmicos ou de demonstração.
