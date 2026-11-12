# Operável

O princípio **Operável**, da WCAG 2.2, estabelece que os componentes da interface e os mecanismos de navegação devem permitir a interação por diferentes dispositivos de entrada, como teclado, mouse, comandos de voz e tecnologias assistivas.

Esse princípio é especialmente importante para pessoas com deficiência visual ou motora, que podem utilizar leitores de tela, teclados e dispositivos adaptados para navegar na web (NASCIMENTO et al., 2023, p. 8-9).

## Teclado e foco

Todas as funcionalidades de uma interface devem permitir a navegação por teclado, sem exigir o uso exclusivo do mouse.

### Critérios de acessibilidade

<div style="display: flex; align-items: center; gap: 24px;" markdown="1">
<div style="flex: 1;" markdown="1">

- **Operação por teclado:** disponibilizar acesso às funcionalidades por teclado (NBR 5.1.12 – recomendação; C.S. 2.1.1, nível A).
- **Alternativa de operação:** oferecer uma forma equivalente de utilização quando determinada funcionalidade não puder ser operada por teclado (NBR 5.1.13).
- **Sem bloqueio de teclado:** não impedir ou interromper a navegação por teclado (NBR 5.1.6 – requisito; C.S. 2.1.2, nível A).
- **Atalhos de teclado:** permitir desativar ou remapear atalhos de uma única tecla, ou restringi-los ao componente em foco (NBR 5.1.11 – requisito; C.S. 2.1.4, nível A).
- **Ordem do foco:** organizar a sequência de navegação de maneira lógica e intuitiva (NBR 5.1.4 – requisito; C.S. 2.4.3, nível A).
- **Indicador de foco:** garantir que o elemento selecionado pelo teclado apresente um indicador visual perceptível (NBR 5.1.1 – requisito; C.S. 2.4.7, nível AA).
- **Foco visível:** impedir que o elemento em foco fique totalmente escondido por outros componentes, como menus fixos, banners ou janelas de chat (NBR 5.1.3 – requisito; C.S. 2.4.11, nível AA).
- **Foco completamente visível:** priorizar que o elemento em foco permaneça totalmente visível (NBR 5.1.2 – recomendação).
- **Conteúdo adicional:** garantir que menus, dicas e outros conteúdos exibidos pelo foco ou posicionamento do cursor possam ser dispensados, permaneçam visíveis e sejam acessíveis (NBR 5.1.8 e 5.1.9 – requisitos; C.S. 1.4.13, nível AA).
- **Pular blocos repetidos:** disponibilizar um mecanismo para ignorar menus e outros conteúdos repetitivos e acessar diretamente o conteúdo principal (NBR 5.7.12 – requisito; C.S. 2.4.1, nível A).

**Boa prática:** disponibilizar um link de acesso direto ao conteúdo principal como primeiro elemento interativo da página.

</div>
<div>
  <img src="/guia_acessibilidade/../imagens/icon/teclado.png" alt="ícone teclado" width="150">
</div>
</div>

## Links e navegação

Os links devem apresentar textos claros e descritivos, permitindo que o usuário compreenda sua finalidade ou destino, inclusive quando utiliza leitores de tela.

### Critérios para links

<div style="display: flex; align-items: center; gap: 24px;" markdown="1">
<div style="flex: 1;" markdown="1">

- **Descrição contextual:** informar a função ou o destino do link considerando seu contexto (NBR 5.7.4 – requisito; C.S. 2.4.4, nível A).
- **Texto independente:** utilizar descrições que façam sentido mesmo quando o link é apresentado isoladamente (NBR 5.7.3 – recomendação; C.S. 2.4.9, nível AAA).
- **Links com destinos diferentes:** evitar links com o mesmo texto que direcionam para destinos distintos (NBR 5.7.5 – requisito; C.S. 3.2.4, nível AA).
- **Informações adicionais:** avisar quando um link abre em nova guia ou janela, direciona para um arquivo ou leva a um site externo (NBR 5.7.6 a 5.7.8 – recomendações).
- **Texto completo:** evitar descrições de links cortadas ou substituídas por reticências.

</div>
<div style="display: flex; flex-direction: column; align-items: center; gap: 16px; margin: 20px 0;">
  <img src="/guia_acessibilidade/../imagens/icon/barra-de-pesquisa.png" alt="Barra de pesquisa" width="120">
  <img src="/guia_acessibilidade/../imagens/icon/navegador-da-web.png" alt="Navegador da web" width="120">
</div>
</div>

**Evite:** textos genéricos como "Clique aqui", "Saiba mais" e "Baixe agora", quando não deixam clara a finalidade do link.

### Critérios para navegação

- **Título da página:** cada página deve possuir um título único e descritivo (NBR 5.13.1 – requisito; C.S. 2.4.2, nível A).
- **Múltiplas formas de navegação:** oferecer diferentes maneiras de localizar páginas, como menus, mecanismos de busca ou mapas do site (NBR 5.7.13 – requisito; C.S. 2.4.5, nível AA).
- **Consistência:** manter a mesma ordem relativa dos mecanismos de navegação repetidos entre as páginas (NBR 5.7.15 – requisito; C.S. 3.2.3, nível AA).
- **Localização do usuário:** informar a posição da página dentro da estrutura do site, preferencialmente por meio de trilhas de navegação (*breadcrumbs*) (NBR 5.7.14 – recomendação; C.S. 2.4.8, nível AAA).

**Boas práticas:**

- Utilizar títulos de nível 1 para identificar o conteúdo principal.
- Disponibilizar um campo de busca.
- Utilizar breadcrumbs para indicar o caminho percorrido e a localização atual.

## Botões, controles e áreas de clique

Botões e controles devem apresentar funções claras e ser utilizados de acordo com sua finalidade: links realizam navegação, enquanto botões executam ações.

### Critérios de acessibilidade


<div style="display: flex; align-items: center; gap: 24px;" markdown="1">
<div style="flex: 1;" markdown="1">

- **Finalidade dos elementos:** utilizar links para navegação e botões para executar ações (NBR 5.7.2 e 5.8.2 – requisitos).
- **Nome acessível:** fornecer uma identificação que descreva a função do botão, inclusive quando ele apresenta somente um ícone (NBR 5.8.3 – requisito; C.S. 4.1.2 e 2.4.6).
- **Texto do nome acessível:** garantir que o nome acessível contenha o texto apresentado visualmente no componente (NBR 5.13.7 – requisito; C.S. 2.5.3, nível A).
- **Área de acionamento:** garantir tamanho mínimo de 24 × 24 pixels CSS ou espaçamento suficiente em relação aos elementos vizinhos (NBR 5.8.7 – requisito; C.S. 2.5.8, nível AA).
- **Área de acionamento ampliada:** preferencialmente, utilizar alvos de pelo menos 44 × 44 pixels CSS (NBR 5.8.6 – recomendação; C.S. 2.5.5, nível AAA).
- **Gestos complexos:** oferecer alternativas para funções que dependem de gestos com vários dedos ou trajetos específicos (NBR 5.8.12 – requisito; C.S. 2.5.1, nível A).
- **Ações de arrastar:** disponibilizar uma alternativa que não exija arrastar elementos (NBR 5.8.13 – requisito; C.S. 2.5.7, nível AA).
- **Cancelamento de ações:** permitir que o usuário desista de uma ação antes de sua conclusão, evitando acionamentos irreversíveis ao pressionar o ponteiro (NBR 5.8.11 – requisito; C.S. 2.5.2, nível A).
- **Movimento do dispositivo:** oferecer alternativas para funcionalidades acionadas pelo movimento ou orientação do aparelho (NBR 5.8.14 – requisito; C.S. 2.5.4, nível A).

</div>
<div style="display: flex; flex-direction: column; align-items: center; gap: 16px; margin: 20px 0;">
  <img src="/guia_acessibilidade/../imagens/icon/botao-de-emergencia.png" alt="Barra de pesquisa" width="150">
</div>
</div>

### Tamanhos recomendados para áreas de clique

| Dimensão | Tamanho | Referência |
|---|---:|---|
| Mínimo de acessibilidade | 24 × 24 px CSS | WCAG 2.2 – nível AA |
| Recomendação ampliada | 44 × 44 px CSS | WCAG – nível AAA |
| Recomendação do Google | 48 × 48 px | Guia de acessibilidade utilizado |

Além do tamanho, é importante manter espaçamento adequado entre os elementos interativos, reduzindo acionamentos acidentais, especialmente para pessoas com mobilidade reduzida.

## Animações e movimentos

Animações, conteúdos piscantes e movimentos automáticos podem causar distrações, dificultar a leitura e prejudicar a concentração. Em determinadas situações, também podem provocar crises em pessoas com epilepsia fotossensível.

### Critérios de acessibilidade

<div style="display: flex; align-items: center; gap: 24px;" markdown="1">
<div style="flex: 1;" markdown="1">

- **Conteúdo piscante:** impedir que conteúdos ultrapassem três flashes por segundo, respeitando também os limites de flash geral e flash vermelho (NBR 5.15.4 – requisito; C.S. 2.3.1, nível A).
- **Movimentos automáticos:** oferecer mecanismos para pausar, interromper ou ocultar conteúdos que se movimentam automaticamente por mais de cinco segundos e aparecem em conjunto com outros conteúdos (NBR 5.15.1 – requisito; C.S. 2.2.2, nível A).
- **Atualizações automáticas:** permitir o controle de conteúdos que são atualizados automaticamente (NBR 5.16.3 – requisito).
- **Animações acionadas por interação:** permitir a desativação de animações de movimento, como efeitos parallax (NBR 5.15.2 – recomendação; C.S. 2.3.3, nível AAA).

</div>
<div style="display: flex; flex-direction: column; align-items: center; gap: 16px; margin: 20px 0;">
  <img src="/guia_acessibilidade/../imagens/icon/animacao.png" alt="Navegador da web" width="150">
</div>
</div>

### Boas práticas

<div style="display: flex; align-items: center; gap: 24px;" markdown="1">
<div markdown="1">

- Evitar movimentos automáticos desnecessários.
- Disponibilizar controles para pausar, parar e retomar animações.
- Permitir o controle de carrosséis e banners animados.
- Considerar opções para redução de movimento.
- Evitar efeitos visuais excessivos que possam prejudicar a concentração.

</div>
<div style="display: flex; flex-direction: column; align-items: center; gap: 16px; margin: 20px 0;">
  <img src="/guia_acessibilidade/../imagens/icon/ligar.png" alt="Navegador da web" width="80">
  <img src="/guia_acessibilidade/../imagens/icon/desligar.png" alt="Navegador da web" width="80">
</div>
</div>

**Atenção:** conteúdos que piscam devem respeitar os limites de segurança estabelecidos pela WCAG, mesmo quando oferecem controles para pausar ou interromper a animação.


## Tempo e limites de sessão

Interfaces que estabelecem limites de tempo para determinadas atividades devem permitir que o usuário tenha tempo suficiente para concluir suas tarefas.

Exemplos incluem códigos de validação que expiram, formulários com tempo limitado e sessões encerradas automaticamente por inatividade.

### Critérios de acessibilidade

<div style="display: flex; align-items: center; gap: 24px;" markdown="1">
<div style="flex: 1;" markdown="1">

- **Controle do limite de tempo:** permitir desligar, ajustar ou estender o tempo antes que ele expire (NBR 5.16.2 – requisito; C.S. 2.2.1, nível A).
- **Preservação dos dados:** permitir que o usuário retome sua atividade sem perder informações após uma nova autenticação (NBR 5.16.5 – recomendação).
- **Aviso de expiração:** informar antecipadamente sobre o encerramento da sessão por inatividade, evitando a perda inesperada de dados (NBR 5.16.6 – recomendação).
</div>
<div>
   <img src="/guia_acessibilidade/../imagens/icon/limite-de-tempo.png" alt="Limite de tempo" width="150">
</div>
</div>

### Exceções

O controle de tempo pode não ser aplicável quando o limite:

- É essencial para a atividade, como em leilões ou eventos ao vivo.
- Faz parte de uma condição intrínseca do conteúdo.
- É superior a 20 horas.

### Importância para a acessibilidade

<div style="display: flex; align-items: center; gap: 24px;" markdown="1">
<div style="flex: 1;" markdown="1">

Limites de tempo muito curtos podem prejudicar pessoas que utilizam tecnologias assistivas ou que precisam de mais tempo para ler, digitar e localizar elementos da interface.

Por isso, os sistemas devem oferecer mecanismos de controle do tempo, evitando que usuários sejam penalizados por suas diferentes necessidades de interação (NASCIMENTO et al., 2023; ABNT, 2025).

</div>
<div>
   <img src="/guia_acessibilidade/../imagens/icon/acessibilidade _web.png" alt="Limite de tempo" width="150">
</div>
</div>

## Referências

Para consultar as normas, diretrizes e materiais utilizados neste princípio, acesse a página de [referências bibliográficas](referencias.md).