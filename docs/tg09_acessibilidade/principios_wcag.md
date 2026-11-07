# TG09 — Princípios da WCAG: critérios de avaliação

Esta página reúne os critérios do guia, agrupados pelos quatro princípios da WCAG: **Perceptível**, **Operável**, **Compreensível** e **Robusto**. Os níveis de conformidade usados aqui estão descritos na [introdução](introducao.md#niveis-de-conformidade), e o [checklist](checklist.md) resume os itens para avaliação.

---

## 3 Perceptível

O princípio Perceptível estabelece que as informações e os componentes de uma interface devem ser apresentados de maneira que os usuários consigam identificá-los e compreendê-los por meio de diferentes sentidos. Para isso, é necessário considerar recursos como contraste de cores, legibilidade dos textos, descrição de imagens, legendas e adaptação do conteúdo a diferentes telas. Essas práticas reduzem barreiras de acesso, especialmente para pessoas com deficiência visual ou auditiva e para usuários com diferentes necessidades de leitura (W3C, 2023; NIC.br, 2023).

### 3.1 Cores e contraste

As cores devem ser usadas de modo que as informações continuem compreensíveis para pessoas com diferentes formas de percepção visual. Por isso, não se deve usar somente a cor para indicar situações, erros, alertas ou ações. Por exemplo, um formulário não deve indicar um campo inválido apenas com uma borda vermelha: também deve apresentar uma mensagem explicativa ou outro indicador visual.

Além disso, é necessário garantir contraste suficiente entre o texto e o fundo. Esse requisito está previsto na seção 5.11.3 da NBR 17225:2025, que estabelece uma relação de contraste mínima de **4,5:1** para textos comuns e de **3:1** para textos grandes. O contraste dos componentes de interface é tratado separadamente na seção 5.11.4, e os objetos gráficos ficam a cargo da seção 5.11.5. Esses cuidados facilitam a identificação de informações, botões, ícones e outros elementos da página (ABNT, 2025; W3C, 2023).

### 3.2 Texto: fontes, espaçamento, alinhamento e largura

Os textos devem ser claros e legíveis, com fontes adequadas, tamanho confortável e espaçamento que facilite a leitura. Parágrafos muito extensos, linhas excessivamente compridas e pouco espaço entre as linhas podem dificultar o acompanhamento do conteúdo. Sempre que possível, recomenda-se alinhamento à esquerda em textos corridos, pois isso mantém um início de linha previsível.

Esses aspectos estão reunidos na seção 5.12 da NBR 17225:2025, que trata de espaçamento entre linhas, parágrafos, letras e palavras, alinhamento e largura dos blocos de texto. Também é importante permitir que o usuário aumente o texto sem perder informações ou funcionalidades: a seção 5.12.7 estabelece que o redimensionamento de até 200% não deve causar essa perda. Essas medidas beneficiam pessoas com baixa visão, dificuldades de leitura e outras necessidades relacionadas à apresentação textual (ABNT, 2025; W3C, 2023).

### 3.3 Imagens e textos alternativos

As imagens que transmitem informações importantes devem ter texto alternativo que descreva seu conteúdo ou sua finalidade. Esses textos dão a quem usa leitores de tela acesso à informação transmitida visualmente. A descrição deve ser objetiva e adequada ao contexto, evitando informações desnecessárias.

A seção 5.2 da NBR 17225:2025 diferencia imagens de conteúdo, funcionais, decorativas, complexas, imagens de texto e mapas de imagens. Assim, uma imagem informativa deve ter descrição equivalente ao seu conteúdo; uma imagem que funciona como botão deve indicar sua finalidade; e uma imagem puramente decorativa pode ser ignorada pelas tecnologias assistivas. Quando um gráfico ou diagrama contém informações complexas, pode ser necessária uma descrição mais detalhada, além do texto alternativo (ABNT, 2025; W3C, 2023).

### 3.4 Áudio e vídeo: legendas, audiodescrição e Libras

Os conteúdos de áudio e vídeo devem oferecer recursos que permitam o acesso por pessoas com diferentes necessidades sensoriais. Vídeos pré-gravados com áudio devem ter legendas sincronizadas e equivalentes ao conteúdo sonoro, incluindo falas e outros sons relevantes. Para conteúdos exclusivamente em áudio, deve haver uma alternativa textual adequada.

Também é importante considerar a audiodescrição, que apresenta informações visuais relevantes, como ações, expressões e mudanças de cena que o áudio original não explica. Legendas, transcrições e audiodescrição são tratadas em conjunto na seção 5.14 da norma brasileira, que classifica as legendas descritivas para vídeos pré-gravados com áudio e a audiodescrição para vídeos pré-gravados como **requisitos**, enquanto alternativas complementares, como a janela de Libras, aparecem como **recomendações**. A escolha dos recursos deve considerar o conteúdo e os critérios de acessibilidade aplicáveis (ABNT, 2025; W3C, 2023).

### 3.5 Design responsivo e zoom

Uma interface acessível deve se adaptar a diferentes tamanhos de tela e permitir que o usuário amplie o conteúdo sem perder informações ou funcionalidades. Textos, imagens, menus e botões precisam continuar disponíveis e utilizáveis em celulares, tablets e computadores. Também se deve evitar que o usuário precise rolar a página horizontal e verticalmente ao mesmo tempo para ler conteúdos comuns.

A adaptação a diferentes dispositivos é prevista na seção 5.10.4 da norma (design responsivo), e a possibilidade de ampliar o texto retoma a seção 5.12.7, já mencionada. A seção 5.13.5 estabelece que a página não deve bloquear o recurso de zoom do navegador. Esses cuidados favorecem pessoas com baixa visão e usuários que acessam o conteúdo por dispositivos com diferentes dimensões de tela (ABNT, 2025; W3C, 2023).

---

## 4 Operável

O princípio Operável da WCAG 2.2 trata de garantir que os componentes da interface e a navegação possam ser usados por qualquer pessoa, independentemente do dispositivo de entrada. Isso importa porque muitas pessoas não usam mouse: quem tem deficiência visual navega com leitor de tela e teclado, e quem tem deficiência motora pode depender de teclado, comandos de voz ou dispositivos adaptados (NASCIMENTO et al., 2023, p. 8-9). As cinco subseções a seguir reúnem o que o Guia UK, a NBR 17225:2025 e a WCAG 2.2 pedem sobre teclado e foco, links, botões, animações e tempo. Nas citações da norma, cada item é identificado como requisito ou recomendação, conforme a NBR, e traz o critério de sucesso (C.S.) da WCAG que ele atende.

### 4.1 Teclado e foco

Todo recurso do site precisa ser usado apenas com o teclado. A NBR classifica isso como recomendação (item 5.1.12, C.S. 2.1.1, nível A) e, como requisito, exige que o que não for acessível por teclado tenha um modo de operação equivalente (item 5.1.13). Nenhum componente pode prender o usuário, bloqueando ou interrompendo a navegação por teclado (requisito 5.1.6, C.S. 2.1.2, nível A). Atalhos de teclado de uma única tecla devem poder ser desativados ou remapeados, ou só funcionar com um componente em foco, para não serem acionados por engano por quem usa comandos de voz (requisito 5.1.11, C.S. 2.1.4, nível A).

Os elementos focados precisam receber o foco em ordem lógica e intuitiva (requisito 5.1.4, C.S. 2.4.3, nível A) e ter um indicador de foco visível (requisito 5.1.1, C.S. 2.4.7, nível AA). A WCAG 2.2 adicionou o C.S. 2.4.11 (nível AA): o elemento em foco não pode ficar totalmente escondido por outros elementos, como barras fixas, banners de cookies ou janelas de chat (requisito 5.1.3). O ideal, como recomendação, é que ele fique completamente visível (item 5.1.2). Conteúdos que aparecem por foco do teclado ou por posicionamento do cursor, como submenus e dicas, devem permanecer visíveis até o usuário retirar o foco e poder ser dispensados sem mexer o cursor (requisitos 5.1.8 e 5.1.9, C.S. 1.4.13, nível AA). Para quem navega por teclado, deve haver também um link ou mecanismo para pular os blocos repetidos e chegar ao conteúdo principal (requisito 5.7.12, C.S. 2.4.1, nível A).

O Guia afirma que "Todas as funcionalidades de uma página web devem estar disponíveis por teclado." (NASCIMENTO et al., 2023, p. 30) e que, sobre o foco, "Quando o foco desaparece ou inexiste, navegar apenas pelo teclado se torna uma ação muito desafiadora." (NASCIMENTO et al., 2023, p. 30). Sobre a ordem, diz que "é importante ter um ordenamento lógico ao focar os elementos" (NASCIMENTO et al., 2023, p. 31) e lembra que "o WCAG recomenda que o primeiro item interativo da página seja um link para o conteúdo principal" (NASCIMENTO et al., 2023, p. 27). A NBR exige que "Todos os elementos focados possuem um indicador de foco visível." (ABNT, 2025, p. 10) e que "Não há componentes que bloqueiam, impedem ou interrompem a navegação por teclado." (ABNT, 2025, p. 11).

### 4.2 Links e navegação

O texto de um link deve dizer para onde ele leva ou o que ele faz. A NBR exige, como requisito, que o link informe sua função ou destino em conjunto com o contexto (item 5.7.4, C.S. 2.4.4, nível A), e recomenda que o texto do link faça sentido mesmo sozinho (item 5.7.3, C.S. 2.4.9, nível AAA). Isso pesa para quem usa leitor de tela, que muitas vezes percorre a página só pela lista de links, onde textos como "clique aqui" ou "saiba mais" ficam sem sentido. A norma também recomenda avisar quando o link abre em nova guia ou janela, leva a um arquivo (com formato e tamanho) ou a um site externo (itens 5.7.6 a 5.7.8), e não ter links com o mesmo texto que levam a destinos diferentes (item 5.7.5, C.S. 3.2.4, nível AA). O Guia pede ainda que o texto do link seja contínuo, sem cortes com reticências (NASCIMENTO et al., 2023, p. 44).

Na navegação, cada página deve ter um título único que a identifique (requisito 5.13.1, C.S. 2.4.2, nível A) e deve haver mais de uma forma de chegar a uma página dentro do site, como menu, busca ou mapa do site (requisito 5.7.13, C.S. 2.4.5, nível AA). Os mecanismos de navegação que se repetem devem manter a mesma ordem relativa entre as páginas (requisito 5.7.15, C.S. 3.2.3, nível AA). O Guia cita o título de nível 1 (NASCIMENTO et al., 2023, p. 34), o campo de busca (NASCIMENTO et al., 2023, p. 29) e as trilhas de navegação, ou *breadcrumbs* (NASCIMENTO et al., 2023, p. 35), como apoios para o usuário se localizar, e a NBR recomenda informar a localização do usuário em relação às demais páginas (item 5.7.14, C.S. 2.4.8, nível AAA).

O Guia orienta: "Evite, portanto, links com textos do tipo "Saiba Mais", "Clique Aqui", "Baixe Agora"." (NASCIMENTO et al., 2023, p. 27). Ele reforça que "a descrição de links e botões deve ser suficiente para sua compreensão de forma isolada" (NASCIMENTO et al., 2023, p. 52) e que "Pessoas devem ser informadas sobre sua localização atual em um conjunto de páginas relacionadas." (NASCIMENTO et al., 2023, p. 35). A NBR determina que "Todos os links possuem texto, texto alternativo ou nome acessível que, em conjunto com o contexto do link, informa sua função ou destino." (ABNT, 2025, p. 17).

### 4.3 Botões, controles e áreas de clique

Botões e controles devem ser usados para o que foram feitos: link para navegar e botão para acionar uma funcionalidade (NBR, requisitos 5.7.2 e 5.8.2). Cada botão precisa de um nome acessível que indique sua função (requisito 5.8.3, C.S. 4.1.2 e 2.4.6), que pode ficar oculto visualmente quando o botão só tem ícone (NASCIMENTO et al., 2023, p. 46), e esse nome deve conter o texto que aparece na tela (requisito 5.13.7, C.S. 2.5.3, nível A). Quando a ação do botão muda, como expandir e retrair, o texto também deve mudar (NASCIMENTO et al., 2023, p. 46).

Quanto ao tamanho, a NBR exige, como requisito, que os elementos interativos tenham área de acionamento de pelo menos **24 por 24 pixels CSS**, ou espaçamento que complete esse tamanho em relação aos vizinhos (item 5.8.7, C.S. 2.5.8, nível AA, novo na WCAG 2.2), e recomenda **44 por 44 pixels CSS** (item 5.8.6, C.S. 2.5.5, nível AAA). O Guia UK vai na mesma linha, com 44 por 44 pixels, 48 por 48 como recomendação do Google, e mínimos de 24 por 24 no computador e 48 por 48 no celular. Também é preciso deixar espaço entre os alvos, para quem tem mobilidade reduzida não tocar no botão errado.

Funções que dependem de gestos com vários dedos ou de trajetos precisam ter uma alternativa de toque simples (requisito 5.8.12, C.S. 2.5.1, nível A), e funções de arrastar precisam ter alternativa sem arrastar (requisito 5.8.13, C.S. 2.5.7, nível AA, novo na 2.2). A ação não deve ser disparada no momento em que o ponteiro é pressionado, para o usuário poder desistir antes de soltar (requisito 5.8.11, C.S. 2.5.2, nível A), e funções operadas por movimento do aparelho precisam de alternativa (requisito 5.8.14, C.S. 2.5.4, nível A).

O Guia diz que "o recurso que aciona o alto contraste deve ser marcado como "Botão" e não como "Link", porque executa uma ação." (NASCIMENTO et al., 2023, p. 26). Sobre o tamanho, afirma: "Ela deve ser de 44px (pixels) de altura e 44px de largura. O Google recomenda 48px por 48px." (NASCIMENTO et al., 2023, p. 36) e "No desktop, o tamanho mínimo deve ser de 24px por 24px; em dispositivos móveis, de 48px por 48px." (NASCIMENTO et al., 2023, p. 44). Sobre o nome, diz que "é importante criar um nome acessível, que pode estar oculto visualmente, com uma classe CSS adequada." (NASCIMENTO et al., 2023, p. 46). A NBR prevê, entre as alternativas do requisito 5.8.7, que "Todos os elementos interativos têm área de acionamento de pelo menos 24 pixels CSS de altura e largura" (ABNT, 2025, p. 20).

### 4.4 Animações

Conteúdo que se move, pisca ou muda sozinho pode atrapalhar a leitura e a concentração, principalmente de pessoas neurodivergentes (NASCIMENTO et al., 2023, p. 20), e em casos mais graves causar crises em pessoas com epilepsia fotossensível. Por isso, nada na página pode piscar mais de três vezes por segundo, ou então o piscar deve ficar abaixo dos limites de flash geral e de flash vermelho (requisito 5.15.4, C.S. 2.3.1, nível A).

Quando uma animação começa sozinha, dura mais de cinco segundos e aparece junto de outros conteúdos, como carrosséis, banners animados e vídeos de fundo, o usuário precisa de um mecanismo para pausar, parar ou ocultá-la (requisito 5.15.1, C.S. 2.2.2, nível A). O mesmo vale para atualizações automáticas de conteúdo (requisito 5.16.3). O Guia recomenda evitar movimentos automáticos e, quando forem necessários, oferecer pausa e redução de movimento (NASCIMENTO et al., 2023, p. 35). Como recomendação de nível AAA, a NBR pede que animações de movimento acionadas pela interação, como o efeito *parallax* ao rolar a página, possam ser desativadas (item 5.15.2, C.S. 2.3.3).

O Guia afirma que "Evite, também, movimentos que pisquem mais de 3 vezes por segundo, pois podem causar episódios de epilepsia ou convulsões." (NASCIMENTO et al., 2023, p. 45) e que "É importante deixar o controle de animações com quem navega, com opções de parar, pausar e retomar o movimento." (NASCIMENTO et al., 2023, p. 45). Sobre carrosséis, diz que "Para conteúdos em movimento, como carrosséis, é importante permitir que a pessoa usuária possa pausá-los" (NASCIMENTO et al., 2023, p. 35). A NBR explica que "Animações podem gerar barreiras ou distrações para usuários que têm dificuldade para acompanhar o movimento ou que possuem déficit de atenção." (ABNT, 2025, p. 33-34) e que "Todo conteúdo que pisca está abaixo dos limites de flash geral e flash vermelho." (ABNT, 2025, p. 34).

### 4.5 Tempo

Quando o site impõe um limite de tempo, como um código de validação que expira ou uma sessão que se encerra por inatividade, o usuário precisa poder desligar, ajustar ou estender o limite antes de atingi-lo (requisito 5.16.2, C.S. 2.2.1, nível A). A exceção são os casos em que o limite é intrínseco ao conteúdo, essencial ou superior a 20 horas, como em leilões e eventos ao vivo. Se uma sessão autenticada expira, o usuário deve poder continuar a atividade sem perda de dados após autenticar de novo (recomendação 5.16.5), e o site deve avisar sobre o limite de inatividade antes de perder os dados (recomendação 5.16.6). O motivo é não penalizar quem usa tecnologia assistiva e leva mais tempo para ler, digitar ou localizar o botão certo.

O Guia explica que o problema ocorre "quando o tempo para realizar uma tarefa é muito curto, como ter 30 segundos para digitar um código de validação" (NASCIMENTO et al., 2023, p. 9) e que "Não ter tempo suficiente prejudica, também, as pessoas com deficiência visual e com mobilidade reduzida." (NASCIMENTO et al., 2023, p. 10). A NBR afirma que "Esses limites devem considerar pessoas que necessitam de mais tempo para ler ou completar tarefas." (ABNT, 2025, p. 34) e exige que "Há um mecanismo para desligar, ajustar ou estender o limite de tempo antes de atingi-lo" (ABNT, 2025, p. 35).

---

## 5 Compreensível

As aplicações devem implementar, no mínimo, os níveis A e AA das *Web Content Accessibility Guidelines* (WCAG). Além disso, não se deve ficar preso exclusivamente a essas diretrizes, mas se aprofundar na realidade de usuários que necessitam de acessibilidade (NASCIMENTO et al., 2023, p. 20-21). O princípio da Compreensibilidade da WCAG merece destaque porque abrange desde a compreensão de palavras e informações até a clareza das mensagens de erro apresentadas aos usuários.

### 5.1 Formulários e mensagens de erro

A previsibilidade da visualização e do funcionamento das páginas contribui para uma experiência mais acessível às pessoas com deficiência, além de prevenir situações de fuga de contexto. Por exemplo, recomenda-se evitar a abertura automática de novas janelas ou abas a partir de links ou, quando isso for necessário, informar previamente o usuário, conforme o critério 3.2.1, de nível A da WCAG. Além disso, as mudanças de contexto devem ocorrer em decorrência de uma ação do usuário ou ser previamente sinalizadas, como no caso do envio de um formulário, conforme o critério 3.2.2, de nível A. Vale ressaltar que uma mudança de conteúdo nem sempre representa uma mudança de contexto. Por fim, quando o site oferece mecanismos de ajuda, é importante disponibilizá-los em locais consistentes ao longo das páginas, seguindo o critério 3.2.6 (WORLD WIDE WEB CONSORTIUM, 2023).

Outro ponto é a consistência da navegação e da identificação dos componentes do site. Recomenda-se que os mecanismos de navegação repetidos em diferentes páginas sejam apresentados na mesma ordem relativa, facilitando a localização das informações, conforme o critério 3.2.3, de nível AA, da WCAG. Além disso, componentes com a mesma funcionalidade devem ser identificados de maneira consistente entre as páginas, com etiquetas, nomes e alternativas de texto padronizados, de acordo com o critério 3.2.4, de nível AA (WORLD WIDE WEB CONSORTIUM, 2023).

Embora a previsibilidade da navegação e a clareza da linguagem sejam essenciais, é importante considerar também a assistência oferecida durante o preenchimento de formulários. Nesse contexto, a diretriz 3.3 da WCAG recomenda que os erros sejam identificados e descritos em texto, além de haver rótulos e instruções claras para orientar o preenchimento, conforme os critérios 3.3.1 e 3.3.2, ambos de nível A. Quando houver sugestões de correção para um erro identificado, elas também devem ser apresentadas, de acordo com o critério 3.3.3, de nível AA (WORLD WIDE WEB CONSORTIUM, 2023). De forma complementar, a ABNT estabelece que as mensagens de erro devem descrever o problema em texto e identificar o campo correspondente, além de fornecer sugestões de correção quando conhecidas, conforme os requisitos 5.9.9 e 5.9.10, respectivamente (ABNT, 2025, p. 23).

Também é importante implementar mecanismos que permitam revisar e corrigir informações antes de ações importantes, como transações financeiras ou exclusão de dados, conforme o critério 3.3.4, de nível AA, da WCAG. Além disso, recomenda-se usar elementos HTML semânticos adequados para cada campo, manter os formulários objetivos, facilitar o preenchimento e apresentar mensagens de erro visíveis e compreensíveis, com orientações de correção próximas ao campo correspondente (NASCIMENTO et al., 2023, p. 30-31). A ABNT também recomenda que os formulários permitam reverter, verificar ou confirmar os dados, conforme o requisito 5.9.11, e estabelece essa prática como requisito para formulários críticos, no item 5.9.12 (ABNT, 2025, p. 24). Por fim, a WCAG aborda a redução da necessidade de inserir novamente informações já fornecidas e a acessibilidade dos mecanismos de autenticação, por meio dos critérios 3.3.7 e 3.3.8, respectivamente (WORLD WIDE WEB CONSORTIUM, 2023). Essas práticas ajudam a prevenir erros e tornam os sites mais acessíveis a diferentes usuários.

### 5.2 Linguagem e conteúdo

O idioma do site deve ser definido programaticamente, para que diferentes agentes de usuário e tecnologias assistivas o identifiquem. Para isso, pode-se usar o atributo `lang` no elemento HTML ou especificar o idioma no cabeçalho HTTP (*Hypertext Transfer Protocol*), de acordo com o critério 3.1.1, de nível A (WORLD WIDE WEB CONSORTIUM, 2023). Além disso, mudanças de idioma em trechos específicos devem ser identificadas por atributos linguísticos, facilitando a interpretação do conteúdo pelas tecnologias assistivas. Essas orientações correspondem ao critério 3.1.2, de nível A, da WCAG (2023) e também são incluídas nos requisitos 5.13.2 e 5.13.3 da ABNT (2025, p. 30).

Convém ressaltar os casos em que são usadas expressões idiomáticas ou jargões. Suas definições podem ser fornecidas na primeira ocorrência ou em todas, por meio de listas de descrição, glossários, dicionários on-line ou explicações no próprio texto. Quando as expressões têm significados diferentes na mesma página, suas definições devem ser fornecidas em cada ocorrência, conforme o critério 3.1.3, de nível AAA (WORLD WIDE WEB CONSORTIUM, 2023). Da mesma forma, o critério 3.1.4, de nível AAA, trata das abreviações e recomenda mecanismos para identificar sua forma expandida ou seu significado, como apresentar a forma completa na primeira ocorrência, vincular definições ou disponibilizar glossários. Quando uma abreviação tem diferentes significados na mesma página, sua explicação deve ser fornecida em cada ocorrência.

Quando um texto exige habilidades de leitura mais avançadas do que as do ensino médio inferior, é importante disponibilizar recursos que facilitem sua compreensão, como resumos, ilustrações, imagens, símbolos, versões faladas ou versões em língua de sinais. Essas alternativas tornam o conteúdo mais acessível a pessoas com diferentes níveis de habilidade de leitura, conforme o critério 3.1.5, de nível AAA (WORLD WIDE WEB CONSORTIUM, 2023). Por fim, quando uma palavra tem significado ambíguo que depende de sua pronúncia, é necessário oferecer recursos que permitam identificá-la corretamente, como indicações de pronúncia próximas à palavra, links para áudios, glossários com informações de pronúncia ou outros recursos linguísticos adequados. Essa recomendação corresponde ao critério 3.1.6, de nível AAA.

---

## 6 Robusto

O princípio Robusto diz respeito à forma como o conteúdo é escrito no código. Um leitor de tela só anuncia o que o código declara, então a página precisa estar estruturada de um jeito que navegadores e tecnologias assistivas consigam interpretar de maneira confiável, hoje e conforme essas ferramentas mudam (WORLD WIDE WEB CONSORTIUM, 2023). É a base técnica dos outros três princípios.

### 6.1 Codificação e semântica

Semântica HTML é usar cada elemento para o que ele foi feito. Segundo o Guia, o mais importante no desenvolvimento é escrever um bom código semântico, porque isso deixa a fase de testes mais tranquila e evita boa parte das barreiras de acesso (NASCIMENTO et al., 2023, p. 25). A WCAG recomenda os elementos nativos, como campos de formulário, links e botões, que já funcionam por teclado sem nenhum código extra. Quando outro elemento é colocado no lugar deles, a tecnologia assistiva pode não reconhecer a função (NASCIMENTO et al., 2023, p. 11).

Na prática, muitos desenvolvedores usam `div` ou `span` e fazem esses elementos se comportarem como botões ou links com JavaScript. No celular, a navegação por toque procura justamente os elementos interativos nativos, então o leitor de tela não entende que aquilo é um botão (NASCIMENTO et al., 2023, p. 25-26). O Guia dá o exemplo do recurso de alto contraste, que deve ser um botão e não um link, já que executa uma ação, e reforça que links e botões devem ser definidos pela função e não pela aparência (NASCIMENTO et al., 2023, p. 26, 44-45).

O critério 4.1.2 (Nome, Função, Valor, nível A) exige que todo componente de interface tenha nome e papel identificáveis por software, e que seus estados possam ser lidos e alterados programaticamente (WORLD WIDE WEB CONSORTIUM, 2023). Quando não existe um elemento nativo adequado, dá para usar o WAI-ARIA, com atributos como `role`, `aria-label` e `aria-expanded`. O Guia indica essa especificação, mas lembra que o HTML deve ser priorizado e combinado com alguns atributos ARIA (NASCIMENTO et al., 2023, p. 60).

A WCAG traz ainda outros critérios que levam a estrutura para dentro do código:

- **1.3.1 (nível A):** tudo o que a aparência comunica, como títulos, listas e rótulos, deve estar disponível programaticamente.
- **1.3.2 (nível A):** a ordem do código deve fazer sentido lida em sequência, mesmo que o CSS reorganize a tela. O Guia lembra que o leitor de tela lê de cima para baixo e da esquerda para a direita, o que nem sempre coincide com a leitura de quem enxerga (NASCIMENTO et al., 2023, p. 31).
- **4.1.3 (nível AA):** mensagens como "item adicionado ao carrinho" devem ser anunciadas sem mover o foco, com `role="status"` ou `role="alert"`.
- **3.1.1 (nível A):** atributo `lang`, já tratado na seção 5.2.

O Guia também avisa que o CSS pode esconder conteúdo das tecnologias assistivas: `display:none` e `visibility:hidden` removem o elemento tanto da tela quanto do leitor (NASCIMENTO et al., 2023, p. 46). Sobre a validação do código, o critério 4.1.1 (Análise Sintática) foi removido da WCAG 2.2, mas manter o HTML válido, sem identificadores repetidos, continua sendo uma boa prática, e o Guia indica o validador do W3C para isso (NASCIMENTO et al., 2023, p. 59). Por fim, o Guia alerta que não existe solução mágica e que a acessibilidade muitas vezes está em um código bem escrito, e não em um *plugin* visível (NASCIMENTO et al., 2023, p. 21).

### 6.2 Cabeçalhos, regiões, listas e tabelas

**Cabeçalhos.** Os cabeçalhos (`h1` a `h6`) funcionam como um índice da página, e muitos usuários de leitor de tela navegam por eles. De acordo com o Guia, um erro comum é usar o cabeçalho só para mudar o tamanho da fonte, dando a ele uma função que não tem. A hierarquia vem da lógica do conteúdo: toda página deve ter um H1 que a descreve, cada seção um H2, e assim por diante (NASCIMENTO et al., 2023, p. 34). O exemplo do Guia usa um H1 "Notícias", com H2 para "Cidades" e "Esportes" e H3 para os itens de cada um, sem pular níveis, como ir de H2 direto para H4. Os critérios relacionados são o 1.3.1 (nível A), o 2.4.6 Cabeçalhos e Rótulos (nível AA) e o 2.4.10 Cabeçalhos de Seção (nível AAA) (WORLD WIDE WEB CONSORTIUM, 2023). Para conferir a estrutura, o Guia indica a extensão HeadingsMap, que mostra a hierarquia de cabeçalhos da página (NASCIMENTO et al., 2023, p. 57).

**Regiões (*landmarks*).** Dividem a página em áreas reconhecíveis: `header`, `nav`, `main`, `aside` e `footer`. Com elas, o usuário vai direto à área que quer, e elas ajudam no mecanismo de pular blocos repetidos (critério 2.4.1), tratado na seção 4.1, que o Guia relaciona ao primeiro link da página levando ao conteúdo principal (NASCIMENTO et al., 2023, p. 27). Cada página deve ter um único `main` e, havendo mais de uma `nav`, cada uma deve ter um nome próprio, como `aria-label="Principal"` e `aria-label="Rodapé"` (WORLD WIDE WEB CONSORTIUM, 2023).

**Listas.** Conjuntos de itens relacionados, como menus, passos e enumerações, devem usar `ul`, `ol` ou `dl`, para que o leitor de tela avise que é uma lista e quantos itens ela tem. Simular lista com hifens, `br` ou parágrafos soltos faz o usuário perder essa informação (WORLD WIDE WEB CONSORTIUM, 2023). O Guia indica a extensão Disable-HTML, que desativa o estilo da página e permite conferir se listas e estrutura estão bem construídas (NASCIMENTO et al., 2023, p. 58).

**Tabelas.** Servem para apresentar dados e não para organizar o layout. O Guia orienta colocar cabeçalhos que expliquem os dados, de preferência visíveis, embora possam ficar disponíveis só para o leitor de tela (NASCIMENTO et al., 2023, p. 34). Tecnicamente, isso é feito com `th` e o atributo `scope`, que indica se o cabeçalho vale para a linha ou para a coluna, e com um `caption` descrevendo a tabela. Nas tabelas complexas, com cabeçalhos em mais de um nível, usam-se `id` e `headers`. Em telas pequenas, tabelas largas devem rolar dentro de um contêiner próprio, sem criar rolagem horizontal na página toda (WORLD WIDE WEB CONSORTIUM, 2023).

---

## Referências

ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225: Acessibilidade em conteúdo e aplicações web: requisitos.** Rio de Janeiro: ABNT, 2025. Disponível em: <https://www.gov.br/governodigital/pt-br/acessibilidade-e-usuario/acessibilidade-digital>. Acesso em: 28 out. 2026.

NÚCLEO DE INFORMAÇÃO E COORDENAÇÃO DO PONTO BR (NIC.br); CENTRO DE ESTUDOS SOBRE TECNOLOGIAS WEB (Ceweb.br) (coord.). **Guia de boas práticas para acessibilidade digital:** Programa de Cooperação entre Reino Unido e Brasil em Acesso Digital. São Paulo: NIC.br, 2023.

WORLD WIDE WEB CONSORTIUM (W3C). **Web Content Accessibility Guidelines (WCAG) 2.2.** W3C Recommendation, 5 out. 2023. Disponível em: <https://www.w3.org/TR/WCAG22/>. Acesso em: 28 out. 2026.
