# TG09 — Testes e ferramentas

A avaliação da acessibilidade digital pode combinar testes automáticos e manuais, que se complementam na identificação de barreiras de acesso. Essas avaliações devem considerar os princípios da WCAG 2.2, os requisitos da ABNT NBR 17225:2025 e as boas práticas do Guia de Boas Práticas para Acessibilidade Digital.

## 7.1 Testes automáticos e manuais

**Testes automáticos** usam ferramentas que analisam aspectos do site e identificam possíveis problemas, como ausência de textos alternativos, falhas na estrutura dos elementos e contraste insuficiente. Sua principal vantagem é a rapidez, que permite verificar várias páginas e encontrar problemas comuns. Entretanto, essas ferramentas não conseguem avaliar todos os aspectos da experiência de uso.

**Testes manuais** consistem na verificação direta da interface por uma pessoa avaliadora. Permitem analisar a navegação apenas com o teclado, a ordem do foco, a compreensão das informações anunciadas por leitores de tela e a facilidade de uso dos componentes. Exigem mais tempo, mas são essenciais para identificar barreiras que as ferramentas automáticas não detectam.

Por isso, recomenda-se combinar as duas abordagens: usar ferramentas automáticas para identificar os problemas iniciais e realizar testes manuais para verificar a experiência de navegação e complementar os resultados.

## 7.2 Ferramentas de avaliação

| Ferramenta | Tipo | Para que serve |
| :--- | :--- | :--- |
| **WAVE** | Visual / automática | Mostra indicadores visuais de possíveis problemas na página: imagens sem texto alternativo, questões estruturais e problemas de contraste. Útil para uma primeira análise visual. |
| **Lighthouse** | Automática | Disponível nas ferramentas de desenvolvedor do Google Chrome. Realiza auditorias automáticas e gera relatórios com problemas detectados e sugestões de melhoria, além de avaliar outros aspectos da qualidade das páginas. |
| **NVDA** (leitor de tela) | Manual | Permite verificar como o conteúdo é anunciado a quem usa leitor de tela. Com a navegação por teclado, avalia a identificação dos elementos, a ordem de navegação e a disponibilidade das funcionalidades sem mouse. |

## 7.3 Procedimentos de utilização

### WAVE — análise visual da página

1. Acesse <https://wave.webaim.org/> e informe o endereço da página pública que será analisada.
2. Examine os indicadores na interface e o painel de resultados, verificando os erros identificados e os alertas que exigem análise adicional.
3. Registre os problemas relevantes e relacione-os aos critérios de acessibilidade correspondentes.
4. Após as correções, repita a análise para verificar os resultados.

### Lighthouse — auditoria automática

1. Abra a página no Google Chrome e acesse as ferramentas de desenvolvedor (tecla **F12** ou menu do navegador).
2. Na seção Lighthouse, selecione a categoria de acessibilidade e execute a auditoria.
3. Use o relatório para identificar os problemas detectáveis automaticamente e consultar as sugestões de melhoria.
4. Registre os resultados e compare-os com os critérios aplicáveis. Repita a auditoria após as alterações.

### NVDA e navegação por teclado — avaliação manual

1. Abra a página no navegador e percorra seus elementos com a tecla **Tab**, observando a visibilidade e a ordem do foco.
2. Com o NVDA em execução, examine títulos, links, campos de formulário e demais componentes, verificando se são anunciados de forma compreensível e se suas funcionalidades podem ser usadas.
3. Registre as dificuldades encontradas e relacione-as aos critérios pertinentes da WCAG 2.2.
4. Após as correções, repita os testes.

!!! note "Interpretação dos resultados"
    Os resultados das avaliações devem ser interpretados em conjunto: a ausência de erros nas ferramentas automáticas não garante que uma interface seja totalmente acessível. A avaliação manual contínua é necessária para identificar barreiras relacionadas à experiência real de navegação.

## Referências

ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. **ABNT NBR 17225: Acessibilidade em conteúdo e aplicações web: requisitos.** Rio de Janeiro: ABNT, 2025.

WORLD WIDE WEB CONSORTIUM (W3C). **Web Content Accessibility Guidelines (WCAG) 2.2.** W3C Recommendation, 5 out. 2023. Disponível em: <https://www.w3.org/TR/WCAG22/>. Acesso em: 28 out. 2026.
