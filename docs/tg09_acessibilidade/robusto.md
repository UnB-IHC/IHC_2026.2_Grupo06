# Robusto

O princípio **Robusto** trata da estrutura técnica do conteúdo, garantindo que navegadores e tecnologias assistivas consigam interpretá-lo de maneira confiável. Para isso, o código deve ser organizado e utilizar elementos semânticos adequados, permitindo que a interface continue acessível mesmo com a evolução das tecnologias (W3C, 2023).

## Codificação e semântica

A semântica HTML consiste em utilizar cada elemento de acordo com sua finalidade. Um código bem estruturado facilita os testes e evita diversas barreiras de acessibilidade (NASCIMENTO et al., 2023, p. 25).

Devem ser priorizados elementos HTML nativos, como `button`, `a` e campos de formulário, pois já possuem comportamentos e funcionalidades reconhecidos por navegadores e tecnologias assistivas. Substituí-los por elementos genéricos, como `div` e `span`, exige implementações adicionais e pode comprometer a acessibilidade.

Por exemplo, um recurso de alto contraste deve ser implementado como botão, pois executa uma ação, enquanto um link deve ser utilizado para navegação. A escolha deve considerar a função do componente, e não apenas sua aparência (NASCIMENTO et al., 2023, p. 25-26, 44-45).

O critério 4.1.2, de nível A, estabelece que os componentes de interface devem possuir nome e papel identificáveis programaticamente, além de disponibilizar seus estados e propriedades para as tecnologias assistivas. Quando não houver um elemento HTML nativo adequado, pode-se utilizar atributos WAI-ARIA, como `role`, `aria-label` e `aria-expanded`, priorizando sempre o HTML semântico (W3C, 2023; NASCIMENTO et al., 2023, p. 60).

Outros critérios da WCAG relacionados à estrutura e à interpretação do conteúdo são:

| **Critério WCAG** | **Orientação** | **Nível** |
|---|---|---|
| 1.3.1 | Disponibilizar programaticamente informações sobre estrutura, como títulos, listas e rótulos. | A |
| 1.3.2 | Garantir que a sequência do conteúdo faça sentido quando apresentada em outra ordem. | A |
| 4.1.2 | Garantir que componentes tenham nome, papel e estados identificáveis por software. | A |
| 4.1.3 | Permitir que mensagens de status sejam identificadas por tecnologias assistivas sem exigir mudança de foco. | AA |

O critério 4.1.3 é importante para mensagens dinâmicas, como a confirmação de que um item foi adicionado ao carrinho. Recursos como `role="status"` e `role="alert"` podem auxiliar na comunicação dessas informações sem deslocar o foco do usuário.

Também é necessário ter cuidado com elementos ocultos por CSS. Propriedades como `display: none` e `visibility: hidden` retiram o conteúdo tanto da apresentação visual quanto da árvore de acessibilidade. Portanto, seu uso deve considerar se a informação também precisa estar disponível para tecnologias assistivas (NASCIMENTO et al., 2023, p. 46).

Embora o critério 4.1.1 (Análise Sintática) tenha sido removido da WCAG 2.2, manter um código HTML válido continua sendo uma boa prática. Isso inclui evitar identificadores duplicados e utilizar ferramentas de validação, como o validador do W3C (NASCIMENTO et al., 2023, p. 59).

## Cabeçalhos, regiões, listas e tabelas

A estrutura semântica da página facilita a navegação e permite que usuários de tecnologias assistivas compreendam a organização das informações.

**Cabeçalhos**

Os cabeçalhos HTML (`h1` a `h6`) organizam o conteúdo hierarquicamente e funcionam como um índice da página, permitindo que usuários de leitores de tela naveguem diretamente pelas seções.

Recomenda-se utilizar um `h1` para identificar o assunto principal da página, seguido de `h2` para suas seções e `h3` para subseções, respeitando a hierarquia e evitando saltos sem justificativa entre níveis.

Por exemplo, uma página de notícias pode apresentar `h1` para “Notícias”, `h2` para “Cidades” e “Esportes” e `h3` para os respectivos assuntos de cada seção.

Os critérios relacionados são:

- **1.3.1 (nível A):** informações e relações devem estar disponíveis programaticamente.
- **2.4.6 (nível AA):** cabeçalhos e rótulos devem descrever claramente seu assunto ou finalidade.
- **2.4.10 (nível AAA):** cabeçalhos de seção devem ser utilizados para organizar o conteúdo.

A extensão HeadingsMap pode auxiliar na verificação da hierarquia dos cabeçalhos (NASCIMENTO et al., 2023, p. 34, 57).

**Regiões (landmarks)**

As regiões semânticas dividem a página em áreas reconhecíveis, facilitando a navegação direta por partes específicas do conteúdo. Entre os elementos utilizados estão:

| **Elemento HTML** | **Finalidade** |
|---|---|
| `header` | Cabeçalho da página ou de uma seção. |
| `nav` | Área de navegação. |
| `main` | Conteúdo principal da página. |
| `aside` | Conteúdo complementar. |
| `footer` | Rodapé da página ou de uma seção. |

Cada página deve possuir uma região principal `main`. Quando houver mais de uma região `nav`, recomenda-se identificá-las com nomes distintos, utilizando recursos como `aria-label`, por exemplo, “Navegação principal” e “Navegação do rodapé”.

As regiões também facilitam o uso de mecanismos para pular blocos repetidos, relacionados ao critério 2.4.1 (nível A), abordado na seção 4.1 (W3C, 2023; NASCIMENTO et al., 2023, p. 27).

**Listas**

Conjuntos de itens relacionados devem utilizar elementos HTML próprios, conforme sua finalidade:

- `ul`: listas não ordenadas;
- `ol`: listas ordenadas;
- `dl`: listas de descrição.

Esses elementos permitem que leitores de tela reconheçam a estrutura da lista e informem a quantidade de itens. Simular listas utilizando hífens, quebras de linha (`br`) ou parágrafos isolados pode fazer com que essas informações sejam perdidas.

A extensão Disable-HTML pode auxiliar na verificação da estrutura da página ao desativar os estilos visuais (NASCIMENTO et al., 2023, p. 58).

**Tabelas**

As tabelas devem ser utilizadas para apresentar dados relacionados, e não para organizar o layout da página. Para garantir sua acessibilidade, é importante:

- Utilizar `th` para identificar os cabeçalhos das linhas e colunas.
- Aplicar o atributo `scope` para indicar a quais células o cabeçalho se refere.
- Utilizar `caption` para fornecer uma descrição ou título à tabela.
- Em tabelas complexas, utilizar `id` e `headers` para relacionar os cabeçalhos às respectivas células.
- Em telas pequenas, permitir a rolagem horizontal da tabela dentro de um contêiner próprio, evitando que toda a página precise ser rolada horizontalmente.

Os cabeçalhos devem ser claros e, preferencialmente, visíveis, embora também possam ser disponibilizados especificamente para leitores de tela (NASCIMENTO et al., 2023, p. 34; W3C, 2023).

## Referências bibliográficas

[Acesse as referências bibliográficas](referencias.md)