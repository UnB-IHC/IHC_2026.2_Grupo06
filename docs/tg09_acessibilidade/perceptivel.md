# Perceptível

O princípio **Perceptível**, da WCAG, estabelece que informações e componentes da interface devem ser apresentados de maneira que possam ser identificados pelos usuários, independentemente de suas capacidades sensoriais.

Para isso, devem ser considerados aspectos como contraste, legibilidade dos textos, descrição de imagens, alternativas para conteúdos multimídia e adaptação a diferentes telas. Essas práticas reduzem barreiras de acesso, especialmente para pessoas com deficiência visual ou auditiva e usuários com diferentes necessidades de leitura (W3C, 2023; NIC.br, 2023).

## Cores e contraste

As cores devem ser utilizadas de forma que as informações permaneçam compreensíveis para diferentes usuários. **A cor não deve ser o único recurso utilizado para transmitir informações**, indicar erros, alertas ou identificar ações.

**Exemplo:** um formulário não deve indicar um campo inválido apenas por meio de uma borda vermelha. Deve apresentar também uma mensagem explicativa ou outro indicador.

### Requisitos de contraste

A NBR 17225:2025 estabelece os seguintes valores mínimos de contraste:

| Elemento | Contraste mínimo | Referência |
|---|---:|---|
| Textos comuns | 4,5:1 | Seção 5.11.3 |
| Textos grandes | 3:1 | Seção 5.11.3 |
| Componentes de interface | Conforme seção específica | Seção 5.11.4 |
| Objetos gráficos | Conforme seção específica | Seção 5.11.5 |

O contraste adequado facilita a identificação de textos, botões, ícones e demais elementos da interface (ABNT, 2025; W3C, 2023).

## Textos: fontes, espaçamento, alinhamento e largura

Os textos devem apresentar características que facilitem a leitura e a compreensão, considerando:

- **Fontes e tamanho:** utilizar fontes legíveis e tamanhos confortáveis.
- **Espaçamento:** manter distância adequada entre linhas, parágrafos, letras e palavras.
- **Alinhamento:** priorizar o alinhamento à esquerda em textos corridos.
- **Largura:** evitar linhas excessivamente compridas e blocos de texto muito extensos.
- **Redimensionamento:** permitir o aumento do texto sem perda de conteúdo ou funcionalidades.

### Requisitos da NBR 17225:2025

A seção 5.12 aborda os critérios relacionados à apresentação textual. Já a seção 5.12.7 estabelece que o texto deve permitir redimensionamento de até **200% sem perda de informações ou funcionalidades**.

Essas práticas beneficiam pessoas com baixa visão, dificuldades de leitura e outras necessidades relacionadas à apresentação dos conteúdos (ABNT, 2025; W3C, 2023).

## Imagens e textos alternativos

Imagens que transmitem informações importantes devem possuir **textos alternativos (alt text)**, permitindo que usuários de leitores de tela compreendam o conteúdo ou a finalidade dos elementos visuais.

As descrições devem ser objetivas, contextualizadas e evitar informações desnecessárias.

### Tipos de imagens e tratamento

| Tipo de imagem | Tratamento de acessibilidade |
|---|---|
| Informativa | Descrever o conteúdo transmitido pela imagem. |
| Funcional | Informar a finalidade da ação, como em um botão. |
| Decorativa | Permitir que seja ignorada pelas tecnologias assistivas. |
| Complexa | Oferecer descrição detalhada das informações apresentadas. |
| Imagem de texto | Disponibilizar alternativa textual equivalente. |
| Mapa de imagem | Descrever as áreas interativas e suas respectivas funções. |

A seção 5.2 da NBR 17225:2025 apresenta os critérios para diferentes tipos de imagens. Gráficos e diagramas complexos podem exigir uma descrição complementar mais detalhada, além do texto alternativo (ABNT, 2025; W3C, 2023).

## Áudio e vídeo: legendas, audiodescrição e Libras

Conteúdos multimídia devem oferecer alternativas que permitam o acesso às informações por pessoas com diferentes necessidades sensoriais.

### Principais recursos de acessibilidade

- **Legendas:** apresentam falas e sons relevantes de vídeos, permitindo o acesso às informações sonoras por pessoas surdas ou com deficiência auditiva.
- **Transcrições:** disponibilizam em texto o conteúdo de materiais exclusivamente em áudio.
- **Audiodescrição:** apresenta informações visuais relevantes, como ações, expressões e mudanças de cena que não são transmitidas pelo áudio original.
- **Libras:** a janela de interpretação permite que pessoas surdas tenham acesso ao conteúdo por meio da Língua Brasileira de Sinais.

### Classificação na NBR 17225:2025

A seção 5.14 aborda critérios relacionados a legendas, transcrições e audiodescrição.

- **Requisitos:** incluem legendas descritivas para vídeos pré-gravados com áudio e audiodescrição para vídeos pré-gravados, conforme os critérios aplicáveis.
- **Recomendações:** incluem recursos complementares, como a janela de interpretação em Libras.

A escolha dos recursos deve considerar o tipo de conteúdo e os critérios de acessibilidade aplicáveis (ABNT, 2025; W3C, 2023).

## Design responsivo e zoom

Uma interface acessível deve adaptar seu conteúdo a diferentes tamanhos de tela e permitir que os usuários ampliem as informações sem perder funcionalidades ou conteúdo.

Textos, imagens, menus e botões devem permanecer disponíveis e utilizáveis em celulares, tablets e computadores.

### Critérios importantes

- Adaptar o conteúdo a diferentes dimensões de tela.
- Evitar rolagem horizontal e vertical simultânea para leitura de conteúdos comuns.
- Permitir ampliação do conteúdo sem perda de informações.
- Não bloquear o recurso de zoom do navegador.

## Referências

Para consultar as normas, diretrizes e materiais utilizados neste princípio, acesse a página de [referências bibliográficas](referencias.md).
