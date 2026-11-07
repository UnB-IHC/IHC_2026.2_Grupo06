# TG09 — Guia de Acessibilidade: Introdução e fundamentos

## 1 Introdução

Este guia reúne, em um só documento, as principais orientações de acessibilidade digital e as transforma em critérios práticos para avaliar interfaces web.

No Brasil, são 18,6 milhões de pessoas com deficiência, segundo a PNAD Contínua (NASCIMENTO et al., 2023, p. 6). Quando a interface não é acessível, essas pessoas perdem autonomia: um botão sem descrição, por exemplo, impede uma pessoa cega de finalizar uma compra (NASCIMENTO et al., 2023, p. 7). A acessibilidade também beneficia pessoas idosas e com baixo letramento digital (NASCIMENTO et al., 2023, p. 5).

Por isso, ela é também um direito. O artigo 63 da Lei Brasileira de Inclusão obriga a acessibilidade nos sítios da internet (NASCIMENTO et al., 2023, p. 7), e a NBR 17225:2025 define os requisitos técnicos de acessibilidade para conteúdo e aplicações web (ABNT, 2025).

O guia está organizado em oito seções: a seção 2 apresenta os fundamentos; as seções 3 a 6 reúnem os critérios, agrupados pelos quatro princípios da WCAG ([Princípios WCAG](principios_wcag.md)); a seção 7 trata de testes e ferramentas ([Ferramentas e testes](ferramentas_testes.md)); e a seção 8 traz o [checklist](checklist.md), que serve para avaliar um site e indica, em cada item, a fonte e o nível de conformidade.

Neste guia, "Guia UK" designa o *Guia de boas práticas para acessibilidade digital*, produzido pelo NIC.br e pelo Ceweb.br no Programa de Cooperação entre Reino Unido e Brasil em Acesso Digital (2023).

## 2 Fundamentos

A deficiência pode ser congênita, adquirida ou temporária, e cada grupo navega na web de um jeito (NASCIMENTO et al., 2023, p. 8). Pessoas com deficiência visual usam leitores e ampliadores de tela. Pessoas com deficiência física, que muitas vezes não conseguem usar o mouse, recorrem ao teclado, a *joysticks*, à voz ou ao movimento dos olhos. Pessoas surdas dependem de legendas e da interpretação em Libras, e pessoas neurodiversas se beneficiam de conteúdo objetivo e sem distrações (NASCIMENTO et al., 2023, p. 8-9).

A NBR 17225 parte dessa lógica de desempenho funcional: atender a seus requisitos permite que "pessoas com limitações para enxergar, ouvir, falar, mover-se ou compreender" usem a web com segurança e autonomia (ABNT, 2025, p. 10), e seu escopo inclui necessidades situacionais, temporárias ou permanentes (ABNT, 2025, p. 1). O Guia lembra ainda que a acessibilidade "beneficia também pessoas idosas e de baixo letramento" (NASCIMENTO et al., 2023, p. 5). Por isso, avaliar uma interface exige pensar em perfis diversos de uso, e não em um único tipo de usuário.

### Acessibilidade como direito

A acessibilidade digital é um direito. O Guia lembra que a Declaração Universal dos Direitos Humanos (1948) e a Convenção sobre os Direitos das Pessoas com Deficiência (2006), sancionada no Brasil em 2009 com caráter de emenda constitucional, antecedem a Lei Brasileira de Inclusão (Lei 13.146/2015), cujo artigo 63 "obriga a acessibilidade nos sítios da Internet" (NASCIMENTO et al., 2023, p. 7). Essa obrigação alcança organizações com sede ou representação comercial no Brasil (NASCIMENTO et al., 2023, p. 53), o que inclui sites de governo e de empresas.

No plano técnico, a NBR 17225:2025 afirma que "a conformidade com esta norma visa atender à legislação vigente" (ABNT, 2025, p. 1) e adota a WCAG 2.2 como base (ABNT, 2025, p. 1), a mesma referência que o Guia associa às boas práticas internacionais de acessibilidade citadas pela lei (NASCIMENTO et al., 2023, p. 12).

### Níveis de conformidade

Para classificar o resultado da avaliação, este Guia adota três níveis próprios de conformidade, construídos a partir da NBR 17225, que divide suas diretrizes em requisitos e recomendações (ABNT, 2025, p. 9):

| Nível | O site... | Correspondência |
| :---: | :--- | :--- |
| **1** | atende apenas a parte dos requisitos obrigatórios, ou seja, ainda tem barreiras de acesso a corrigir. | Abaixo da conformidade regular. |
| **2** | atende a todos os requisitos obrigatórios. | Conformidade regular da norma, alinhada ao nível AA da WCAG 2.2 (ABNT, 2025, p. 9). |
| **3** | além dos obrigatórios, atende às recomendações e às boas práticas. | Aproxima-se da conformidade plena, que "abrange todos os requisitos e também as recomendações" (ABNT, 2025, p. 10). |

Entram no Nível 3 as boas práticas do Guia UK, pois a norma esclarece que atendê-la não dispensa outras práticas, como os princípios de usabilidade (ABNT, 2025, p. 9). Assim, cada avaliação termina com um único nível para o site, e as falhas dos requisitos obrigatórios são as primeiras a serem corrigidas.

## Referências

ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225: Acessibilidade em conteúdo e aplicações web: requisitos.** Rio de Janeiro: ABNT, 2025. Disponível em: <https://www.gov.br/governodigital/pt-br/acessibilidade-e-usuario/acessibilidade-digital>. Acesso em: 28 out. 2026.

NÚCLEO DE INFORMAÇÃO E COORDENAÇÃO DO PONTO BR (NIC.br); CENTRO DE ESTUDOS SOBRE TECNOLOGIAS WEB (Ceweb.br) (coord.). **Guia de boas práticas para acessibilidade digital:** Programa de Cooperação entre Reino Unido e Brasil em Acesso Digital. São Paulo: NIC.br, 2023.
