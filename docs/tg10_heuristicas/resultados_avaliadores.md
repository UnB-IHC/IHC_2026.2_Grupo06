# TG10 — Resultados e tabelas

Nas tabelas a seguir estão os problemas encontrados pelos avaliadores nas funcionalidades analisadas, as heurísticas que cada problema fere (**HN** = Nielsen; **HGE** = governo eletrônico) e a gravidade, conforme a [escala definida no planejamento](planejamento_escopo.md#gravidade-do-problema).

## Avaliador 1

| Problema | Heurísticas | Gravidade |
| :--- | :--- | :---: |
| 2ª via: o texto diz que o QR Code é gerado "nos Postos do BRB Mobilidade específicos (consulte aqui)", mas o link "consulte aqui" leva à tela de login do sistema, e não a uma lista de postos. | HN4, HN10 | 3 |
| 2ª via: a página orienta a não fazer PIX comum, mas a FAQ diz que o pagamento é "nos postos BRB Mobilidade por meio de PIX". Quem lê só a FAQ pode pagar do jeito errado, e a solicitação trava. | HN5, HN2, HGE02 | 3 |
| Tela inicial e cadastro: os links do sistema trazem o identificador de sessão na URL (`;jsessionid=...`), o que expõe a sessão se o link for copiado ou compartilhado. | HGE01 | 3 |
| 2ª via: o pagamento da taxa de R$ 5,40 exige ir a um posto (QR Code) ou a uma agência ou loja BRB (depósito identificado). Não há pagamento totalmente online. | HN7 | 2 |
| Tela inicial: o aviso de cookies só tem o botão "Aceitar". Não há opção de recusar ou configurar. | HN3, HGE01 | 2 |
| Tela inicial: o mesmo serviço aparece com nomes diferentes ("Cartão Estudantil", "Passe Livre Estudantil", "sistema web do Passe Livre" e "BRB Mobilidade"). | HN4 | 2 |
| Tela inicial: links com texto genérico ("consulte aqui", "Clique aqui") e o mesmo texto "sistema web do Passe Livre" levando a páginas diferentes (login, cadastro, início), o que dificulta saber o destino, principalmente com leitor de tela. | HN4, HGE05 | 2 |
| Tela inicial: os títulos da página não seguem hierarquia. "Cartão Estudantil" é H2 e vem antes de vários H1, há saltos de H1 para H4 e H5, e H6 é usado em itens que não são títulos ("Chatbot", "Central de Atendimento"). | HGE05 | 2 |
| Tela inicial: a página repete as mesmas informações em vários blocos (requisitos, documentos, 2ª via e prazos aparecem no texto e de novo na FAQ), às vezes com redações diferentes (comprovante de residência: "máximo de 3 meses" e "últimos 90 dias"), o que alonga a leitura e dificulta achar o essencial. | HN8, HGE03 | 2 |
| Tela inicial: aparecem siglas e termos sem explicação ("SCIE", "FEDF", "validador") e muito texto normativo, com 8 portarias, decretos e leis listados. | HN2, HGE03 | 2 |
| Tela inicial: o rodapé mostra "© 2022", a página não exibe data de atualização visível, e o conteúdo cita normas de 2025. | HGE02 | 2 |
| Tela inicial: há erros de escrita ("Chatbot BRB Moblidade", "realizar o bloquei imediato", "A declaração escolar pode ser enviado", "calendário envio de calendário acadêmico"). | HGE02 | 1 |

## Avaliador 2

| Problema | Heurísticas | Gravidade |
| :--- | :--- | :---: |
| Acompanhe seu cadastro (celular): os círculos da linha do tempo ficam por cima da primeira letra de cada status ("Aberto", "Em Análise", "Aprovado") e as barras ficam desalinhadas, porque o layout não se adapta à tela pequena. | HN4, HN8 | 3 |
| Acompanhe seu cadastro (celular): o título "Status do Cadastro:" fica colado na borda esquerda e a página exige rolagem horizontal, violando o critério 1.4.10 (Reflow) do WCAG. | HN4, HGE05 | 3 |
| Tela inicial e menu do Cartão Estudantil: contraste insuficiente em textos, como o título "Cartão Criança" em amarelo sobre branco (1,46:1) e o texto branco sobre verde-água (2,10:1), abaixo do mínimo de 3:1 para texto grande e 4,5:1 para texto comum (critério 1.4.3 do WCAG). | HGE05 | 3 |
| Tela inicial: o FAQ não aparece na página principal, só dentro da seção "Cartão Estudantil". | HN10, HN6, HGE03 | 2 |
| Tela inicial: o ícone de login (boneco com cadeado) não tem texto, e não fica claro que é para entrar no sistema. | HN6, HN2, HGE05 | 2 |
| Menu do Cartão Estudantil: "Sobre" e "FAQ" usam praticamente o mesmo ícone de interrogação, o que dificulta diferenciar as opções. | HN4, HN6, HGE03 | 2 |
| Menu do Cartão Estudantil: todas as opções têm o mesmo peso visual, sem agrupamento por tarefa, e as opções do cartão físico ("2ª Via", "Liberar cartão", "Local de Retirada") ficam espalhadas. | HN8, HN6, HGE03 | 2 |
| Menu do Cartão Estudantil: "Resp. Processo Administrativo" é abreviado e técnico, e o ícone de alerta não esclarece do que se trata. | HN2, HGE03 | 2 |
| Menu do Cartão Estudantil: a faixa amarela "Local de Retirada do Cartão" tem estilo e fonte diferentes do resto, e não fica claro se é clicável. | HN4, HN6 | 2 |
| Acompanhe seu cadastro: na seção "Status do Benefício" aparece o rótulo "Status Cadastro", o que confunde as duas informações. | HN2, HN4, HGE03 | 2 |
| Menu do Cartão Estudantil: inconsistência visual nos botões (texto "Acompanhe seu cadastro/frequência" vazando, botões com larguras e alinhamentos diferentes). | HN4, HN8 | 1 |

## Avaliador 3

| Problema | Heurísticas | Gravidade média |
| :--- | :--- | :---: |
| Menu do Cartão Estudantil: os campos obrigatórios utilizam apenas um asterisco preto de tamanho reduzido e sem destaque de cor, dificultando a rápida identificação visual antes de iniciar o preenchimento. | HN4, HGE05 | 2 |
| Menu do Cartão Estudantil: campos numéricos ou de documentos (como CPF) não possuem máscara automática de formatação (pontos e traços), obrigando o usuário a adivinhar o padrão aceito pelo sistema sob risco de erro. | HN5, HN2 | 2 |
| Menu do Cartão Estudantil: quando ocorre um erro de preenchimento ou validação em formulários, os avisos de erro aparecem agrupados no topo da página ou distantes do campo afetado, dificultando que o usuário associe rapidamente o erro ao local a corrigir. | HN9, HN2 | 2 |
| Menu do Cartão Estudantil e Cadastro: na etapa de envio de documentos (comprovante de matrícula ou residência), a interface não informa antecipadamente os formatos aceitos (ex.: PDF, PNG) nem o limite de tamanho do arquivo, resultando em mensagens de erro genéricas apenas após a tentativa de envio. | HN9, HGE02 | 3 |
| Menu do Cartão Estudantil e Cadastro: campos que exigem datas (como data de nascimento ou vigência) não possuem máscara automática de formatação (DD/MM/AAAA) ou componente visual de calendário (*datepicker*), exigindo digitação manual rigorosa e facilitando erros por parte do usuário (*slips*). | HN5, HN2 | 2 |

## Avaliador 4

| Problema | Heurísticas | Gravidade |
| :--- | :--- | :---: |
| Tela inicial: subtítulo e "Recarga Online" em texto pequeno sobre imagem desfocada. | HN8, HGE05 | 2 |
| Tela inicial: ícone de livro em "Acompanhe seu cadastro" não remete a acompanhamento. | HN2 | 1 |
| Menu: item "Especial" não deixa claro do que se trata. | HN2, HGE03 | 1 |
| Botão flutuante "Fale via Chat" pode cobrir conteúdo. | HGE05 | 1 |
| Botão "Acesse seu BRB Mobilidade" volta à mesma tela, sem *feedback*; o login só é achado pelo menu "Estudantil". | HN1, HN4, HGE02 | 2 |
| Recuperação de senha e cadastro dão respostas contraditórias ("nenhum cadastro correspondente" e "CPF já utilizado"), ambas sem link ou orientação. | HN9, HN1, HGE02 | 3 |
| Postos de Atendimento sem telefone ou contato. | HGE02 | 2 |
| Postos de Atendimento sem data de atualização. | HGE02 | 1 |
| Postos de Atendimento sem mapa nem "Como chegar", só o endereço em texto. | HN6, HN7 | 1 |
| Postos de Atendimento sem filtro por cidade ou região. | HN7 | 1 |
| Troca de senha sem regras nem indicador de força da senha. | HN6, HGE01 | 2 |
| Mensagem "as senhas divergem" aparece no topo da tela, usa termo formal e não orienta. | HN2, HN9 | 1 |
| 2ª via e troca de instituição ficam no fim da tela, sem indicação de que há mais conteúdo. | HN6, HN7 | 1 |
| Troca de instituição: "Instituição de ensino" é campo de texto livre. | HN5 | 2 |

## Tabela final

Consolidação dos problemas dos quatro avaliadores. A coluna de gravidade lista as notas registradas para cada problema.

| # | Problema | Heurísticas | Gravidade |
| :---: | :--- | :--- | :---: |
| 1 | **Avisos de erro genéricos, distantes ou contraditórios:** mensagens ("senhas divergem" ou erro de formulário) surgem no topo da tela, longe do campo afetado. Erros no envio de documento e contradições na recuperação de senha não orientam o usuário. | HN1, HN2, HN9, HGE02 | 3, 3 |
| 2 | **Vulnerabilidades de privacidade e segurança:** exposição do identificador de sessão (`jsessionid`) na URL, falta de regras e força visual na troca de senha, e aviso de cookies sem opção de recusa ou configuração. | HN3, HN6, HGE01 | 3, 2 |
| 3 | **Links, redirecionamentos e botões confusos:** links genéricos (ex.: "consulte aqui") levando a páginas erradas (login), e botões principais (ex.: "Acesse BRB") que apenas recarregam a página em vez de agir. | HN1, HN4, HGE02, HGE05 | 3, 2 |
| 4 | **Problemas de responsividade e sobreposição:** falta de adaptação para telas menores causando sobreposição de textos (status na linha do tempo, exigência de rolagem horizontal) e botões flutuantes cobrindo o conteúdo. | HN4, HN8, HGE05 | 3, 1 |
| 5 | **Baixa legibilidade visual e contraste:** contraste de cor insuficiente (abaixo do padrão WCAG) em títulos, hierarquia de cabeçalhos quebrada (H1 a H6 desordenados) e texto pequeno aplicado sobre imagem desfocada. | HN8, HGE05 | 3, 2, 2 |
| 6 | **Ausência de prevenção de erro (máscaras e seletores):** campos como CPF e data exigem digitação livre sem autocompletar; o campo "Instituição" não possui caixa de seleção, facilitando falhas humanas na digitação. | HN2, HN5 | 2, 2 |
| 7 | **Desorganização da informação e menus vitais ocultos:** opções essenciais (FAQ, 2ª via, troca de instituição) ficam escondidas em submenus sem agrupamento ou totalmente no final da página sem indicativo de rolagem. | HN6, HN7, HN10, HGE03 | 2, 2, 1 |
| 8 | **Falta de clareza nos ícones de interação:** ícones que não remetem à ação (livro para acompanhamento), uso do mesmo ícone para abas diferentes ("Sobre" e "FAQ") e ícone de login sem descrição em texto. | HN2, HN4, HN6, HGE03 | 2, 1 |
| 9 | **Jargões, siglas e inconsistência de nomenclaturas:** o mesmo serviço tem nomes diferentes; excesso de textos normativos; siglas sem explicação; menu rotulado apenas como "Especial" e conflito entre "Status Cadastro" e "Benefício". | HN2, HN4, HGE03 | 2, 2, 1 |
| 10 | **Informações contraditórias e exigência física na 2ª via:** a interface proíbe o PIX comum, mas a FAQ o recomenda. Pagamento online é impossível, forçando o cidadão a ir a um posto presencialmente. | HN2, HN5, HN7, HGE02 | 3 |
| 11 | **Página de Postos de Atendimento precária:** a lista não possui telefone de contato, ferramentas de mapa ("como chegar"), datas de atualização ou mesmo filtros de busca por cidade/região. | HN6, HN7, HGE02 | 2 |
| 12 | **Sinalização fraca de preenchimento obrigatório:** o uso apenas de um asterisco pequeno sem cor de destaque prejudica o rastreio visual do formulário. | HN4, HGE05 | 2 |
| 13 | **Erros textuais e desatualização:** presença de erros de ortografia (ex.: "Moblidade", "bloquei") e o ano do rodapé (2022) contrasta com legislações de 2025 citadas no texto. | HGE02 | 1 |

## Conclusão

A avaliação heurística do portal BRB Mobilidade Estudantil combinou os princípios clássicos de usabilidade de Jakob Nielsen com as heurísticas de governo eletrônico propostas por Maciel e Medeiros (2026). Essa combinação permitiu diagnosticar barreiras que vão além da estética da interface e alcançam dimensões críticas do setor público digital, como segurança da informação, transparência, previsibilidade e acessibilidade universal (MACIEL; MEDEIROS, 2026).

Os quatro avaliadores registraram 42 problemas, dos quais 8 têm gravidade 3, e a consolidação os reuniu em 13 grupos. Alguns pontos se destacam:

- **Segurança e privacidade (HGE01):** o identificador de sessão aparece na URL, o aviso de cookies não permite recusar nem configurar e a troca de senha não informa regras nem a força da senha.
- **Acessibilidade e responsividade (HGE05, HN8):** em dispositivos móveis, a linha do tempo de acompanhamento do cadastro tem elementos sobrepostos e exige rolagem horizontal (violação do critério de *Reflow* da WCAG), e vários textos têm contraste inferior ao mínimo exigido.
- **Mensagens e fluxos críticos (HN9, HGE02):** os avisos de erro são genéricos ou ficam longe do campo, e a recuperação de senha e o cadastro dão respostas contraditórias, sem orientar o usuário.
- **Segunda via:** a página e a FAQ se contradizem sobre o pagamento por PIX, e não há opção de pagamento 100% online.
- **Prevenção de erros (HN5):** campos de CPF e datas não têm máscara, e o campo de instituição é texto livre, sem validação.

Conclui-se que, embora o portal desempenhe um papel fundamental na concessão do transporte público estudantil no DF, é indispensável corrigir, com prioridade, os problemas de gravidade 3 (falhas maiores de usabilidade e de governo eletrônico). Com isso, e com o alinhamento às diretrizes da WCAG e da NBR 17225 (veja o [Guia de Acessibilidade](../tg09_acessibilidade/introducao.md)), o serviço pode se tornar seguro, acessível, transparente e centrado nas necessidades do estudante.

## Referências

MACIEL, Karenina Medeiros; MEDEIROS, Francisco Petrônio A. de. **A Set of Heuristics for Evaluating Usability and User Experience in E-Government Information Systems.** iSys - Journal of Information Systems, [S. l.], v. 19, n. 1, 2026. DOI: 10.5753/isys.2026.6100.
