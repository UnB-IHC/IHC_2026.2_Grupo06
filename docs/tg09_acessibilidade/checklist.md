# TG09 — Checklist de avaliação de interfaces

Use este checklist para avaliar um site. Em cada item, marque **S** (sim), **N** (não) ou **NA** (não se aplica). A classificação indica o nível de conformidade (veja os [níveis](introducao.md#niveis-de-conformidade)): **Nível 2** = requisito; **Nível 3** = recomendação ou boa prática.

| Tópico | Item | Classificação | Referências | S | N | NA |
| :--- | :--- | :--- | :--- | :---: | :---: | :---: |
| **Cores e contraste** | As informações não dependem exclusivamente de cores para serem compreendidas. | Nível 2 (Requisito) | NBR 17225 (5.11); WCAG 2.2 | ☐ | ☐ | ☐ |
| | A relação de contraste é de no mínimo 4,5:1 para textos comuns e 3:1 para textos grandes. | Nível 2 (Requisito) | NBR 17225 (5.11.3) | ☐ | ☐ | ☐ |
| | Componentes de interface e objetos gráficos possuem contraste adequado. | Nível 2 (Requisito) | NBR 17225 (5.11.4, 5.11.5) | ☐ | ☐ | ☐ |
| **Textos** | A página suporta zoom de até 200% sem perda de informações ou de funcionalidades. | Nível 2 (Requisito) | NBR 17225 (5.12.7) | ☐ | ☐ | ☐ |
| | Textos corridos alinhados à esquerda, com espaçamento adequado entre linhas, parágrafos e palavras. | Nível 3 (Recomendação) | NBR 17225 (5.12) | ☐ | ☐ | ☐ |
| **Imagens e textos alternativos** | Imagens informativas ou funcionais possuem atributo de texto alternativo (`alt`) correspondente e claro. | Nível 2 (Requisito) | NBR 17225 (5.2) | ☐ | ☐ | ☐ |
| | Imagens puramente decorativas possuem texto alternativo vazio para serem ignoradas por leitores de tela. | Nível 2 (Requisito) | NBR 17225 (5.2) | ☐ | ☐ | ☐ |
| **Áudio e vídeo** | Vídeos pré-gravados possuem legendas sincronizadas e audiodescrição para informações visuais. | Nível 2 (Requisito) | NBR 17225 (5.14) | ☐ | ☐ | ☐ |
| | Conteúdos audiovisuais disponibilizam janela com interpretação em Libras. | Nível 3 (Recomendação) | NBR 17225 (5.14) | ☐ | ☐ | ☐ |
| **Design responsivo** | O layout se adapta à tela, não exigindo rolagem horizontal e vertical simultânea para leitura. | Nível 2 (Requisito) | NBR 17225 (5.10.4) | ☐ | ☐ | ☐ |
| | A página não bloqueia o recurso de zoom nativo do navegador do usuário. | Nível 2 (Requisito) | NBR 17225 (5.13.5) | ☐ | ☐ | ☐ |
| **Teclado e foco** | A interface inteira pode ser navegada e operada exclusivamente pelo teclado, sem prender o foco do usuário. | Nível 2 (Requisito) | NBR 17225 (5.1.6, 5.1.12, 5.1.13); WCAG (2.1.1, 2.1.2) | ☐ | ☐ | ☐ |
| | O elemento focado pelo teclado possui um indicador visual visível e nítido. | Nível 2 (Requisito) | NBR 17225 (5.1.1); WCAG (2.4.7) | ☐ | ☐ | ☐ |
| | O elemento focado não fica totalmente escondido por banners, chats ou cabeçalhos fixos sobrepostos. | Nível 2 (Requisito) | NBR 17225 (5.1.3); WCAG (2.4.11) | ☐ | ☐ | ☐ |
| | Há um link acessível via teclado para "pular conteúdo" e ir direto ao conteúdo principal. | Nível 2 (Requisito) | NBR 17225 (5.7.12); WCAG (2.4.1); Guia UK (p. 27) | ☐ | ☐ | ☐ |
| **Links e navegação** | O texto do link identifica seu destino ou função (evitando textos genéricos como "clique aqui"). | Nível 2 (Requisito) | NBR 17225 (5.7.4); WCAG (2.4.4); Guia UK (p. 27, 44, 52) | ☐ | ☐ | ☐ |
| | O site possui mecanismos consistentes de navegação. | Nível 2 (Requisito) | NBR 17225 (5.7.13, 5.7.15); WCAG (2.4.5, 3.2.3); Guia UK (p. 29) | ☐ | ☐ | ☐ |
| **Botões e cliques** | Botões (executam ação) e links (navegação) são usados semanticamente para suas funções corretas. | Nível 2 (Requisito) | NBR 17225 (5.7.2, 5.8.2); Guia UK (p. 26) | ☐ | ☐ | ☐ |
| | A área de clique (alvo) possui tamanho mínimo de 24x24 pixels CSS. | Nível 2 (Requisito) | NBR 17225 (5.8.7); WCAG (2.5.8); Guia UK (p. 44) | ☐ | ☐ | ☐ |
| | A área de clique possui tamanho expandido de 44x44 ou 48x48 pixels CSS. | Nível 3 (Boa prática) | NBR 17225 (5.8.6); WCAG (2.5.5); Guia UK (p. 36) | ☐ | ☐ | ☐ |
| | Funções de arrastar e gestos complexos possuem alternativas de clique simples. | Nível 2 (Requisito) | NBR 17225 (5.8.12, 5.8.13); WCAG (2.5.1, 2.5.7) | ☐ | ☐ | ☐ |
| **Animações** | Nenhum elemento da interface pisca mais do que 3 vezes por segundo (prevenção de convulsões). | Nível 2 (Requisito) | NBR 17225 (5.15.4); WCAG (2.3.1); Guia UK (p. 45) | ☐ | ☐ | ☐ |
| | Animações automáticas que duram mais de 5 s possuem controles de pausa. | Nível 2 (Requisito) | NBR 17225 (5.15.1); WCAG (2.2.2); Guia UK (p. 35) | ☐ | ☐ | ☐ |
| **Tempo** | O usuário consegue desligar, ajustar ou estender o tempo em limites de sessão ou de preenchimento. | Nível 2 (Requisito) | NBR 17225 (5.16.2); WCAG (2.2.1); Guia UK (p. 9-10) | ☐ | ☐ | ☐ |
| **Formulários e erros** | Erros de preenchimento são identificados em formato de texto, associados ao campo e com sugestão de correção. | Nível 2 (Requisito) | NBR 17225 (5.9.9, 5.9.10); WCAG (3.3.1, 3.3.3); Guia UK (p. 30) | ☐ | ☐ | ☐ |
| | O usuário pode revisar, reverter e confirmar as informações inseridas antes da submissão de dados importantes. | Nível 2 (Requisito) | NBR 17225 (5.9.11, 5.9.12); WCAG (3.3.4); Guia UK (p. 30) | ☐ | ☐ | ☐ |
| | Não ocorrem aberturas de novas abas ou submissões de dados sem aviso ou ação explícita do usuário. | Nível 2 (Requisito) | WCAG (3.2.1, 3.2.2) | ☐ | ☐ | ☐ |
| **Linguagem e conteúdo** | O idioma principal do site está corretamente definido na estrutura do código. | Nível 2 (Requisito) | NBR 17225 (5.13.2); WCAG (3.1.1) | ☐ | ☐ | ☐ |
| | Jargões e siglas são explicados e há alternativas para linguagem complexa (resumos ou símbolos). | Nível 3 (Recomendação) | WCAG (3.1.3, 3.1.4, 3.1.5) | ☐ | ☐ | ☐ |
| **Codificação e semântica** | O código faz uso correto de HTML semântico (elementos nativos) ou compensa com marcações WAI-ARIA. | Nível 2 (Requisito) | NBR 17225 (5.13.7); WCAG (4.1.2); Guia UK (p. 25, 60) | ☐ | ☐ | ☐ |
| | Mudanças de status são informadas ao leitor de tela sem a necessidade de mudar o foco atual do teclado. | Nível 2 (Requisito) | WCAG (4.1.3) | ☐ | ☐ | ☐ |
| **Cabeçalhos e listas** | A hierarquia de cabeçalhos é mantida em ordem lógica (H1 único, seguindo para H2, H3), sem pular níveis. | Nível 3 (Boa prática) | WCAG (1.3.1, 2.4.6); Guia UK (p. 34) | ☐ | ☐ | ☐ |
| | Regiões e listas estão estruturadas com a marcação de código adequada. | Nível 2 (Requisito) | WCAG (1.3.1); Guia UK (p. 27, 58) | ☐ | ☐ | ☐ |
| | Tabelas são utilizadas estritamente para apresentar dados relacionais e não para estruturar o leiaute da página. | Nível 2 (Requisito) | WCAG (1.3.1); Guia UK (p. 34) | ☐ | ☐ | ☐ |

## Referências

ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225: Acessibilidade em conteúdo e aplicações web: requisitos.** Rio de Janeiro: ABNT, 2025. Disponível em: <https://www.gov.br/governodigital/pt-br/acessibilidade-e-usuario/acessibilidade-digital>. Acesso em: 28 out. 2026.

NÚCLEO DE INFORMAÇÃO E COORDENAÇÃO DO PONTO BR (NIC.br); CENTRO DE ESTUDOS SOBRE TECNOLOGIAS WEB (Ceweb.br) (coord.). **Guia de boas práticas para acessibilidade digital:** Programa de Cooperação entre Reino Unido e Brasil em Acesso Digital. São Paulo: NIC.br, 2023.

WORLD WIDE WEB CONSORTIUM (W3C). **Web Content Accessibility Guidelines (WCAG) 2.2.** W3C Recommendation, 5 out. 2023. Disponível em: <https://www.w3.org/TR/WCAG22/>. Acesso em: 28 out. 2026.
