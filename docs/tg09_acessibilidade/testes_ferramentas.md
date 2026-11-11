# Testes e ferramentas

A avaliação da acessibilidade digital pode ser realizada por meio de testes automáticos e manuais, que se complementam na identificação de barreiras de acesso. As avaliações devem considerar os princípios da WCAG 2.2, os requisitos da ABNT NBR 17225:2025 e as boas práticas do Guia de Boas Práticas para Acessibilidade Digital.

## Testes automáticos e manuais

Os **testes automáticos** utilizam ferramentas que analisam páginas web e identificam possíveis problemas de acessibilidade, como ausência de textos alternativos, falhas na estrutura dos elementos e contraste insuficiente.

Sua principal vantagem é a rapidez, permitindo verificar diferentes páginas e detectar problemas comuns. Entretanto, não conseguem avaliar todos os aspectos da experiência de uso.

Já os **testes manuais** consistem na avaliação direta da interface por uma pessoa avaliadora. Permitem verificar aspectos como:

- Navegação utilizando apenas o teclado;
- Ordem e visibilidade do foco;
- Compreensão das informações anunciadas por leitores de tela;
- Identificação e funcionamento dos componentes;
- Facilidade de utilização das funcionalidades.

Embora exijam mais tempo, são essenciais para identificar barreiras que não podem ser detectadas exclusivamente por ferramentas automáticas.

Portanto, recomenda-se combinar as duas abordagens: utilizar testes automáticos para identificar problemas iniciais e testes manuais para verificar a experiência de navegação e complementar os resultados.

## Ferramentas de avaliação

Entre as ferramentas disponíveis, destacam-se o WAVE, o Lighthouse e os leitores de tela, que atendem a diferentes necessidades durante a avaliação de acessibilidade.

| **Ferramenta** | **Finalidade** | **Principais verificações** |
|---|---|---|
| **WAVE** | Apresenta indicadores visuais sobre possíveis problemas de acessibilidade na página. | Imagens sem texto alternativo, questões estruturais e problemas de contraste. |
| **Lighthouse** | Realiza auditorias automáticas e gera relatórios com problemas identificados e sugestões de melhoria. | Acessibilidade e outros aspectos da qualidade das páginas web. |
| **NVDA** | Leitor de tela utilizado para verificar como o conteúdo é anunciado às pessoas que utilizam tecnologias assistivas. | Identificação dos elementos, ordem de navegação e disponibilidade das funcionalidades. |

O WAVE é especialmente útil para uma primeira análise visual da interface. O Lighthouse, disponível nas ferramentas de desenvolvedor do Google Chrome, permite gerar relatórios automatizados. Já o NVDA, combinado com a navegação por teclado, possibilita avaliar a experiência de utilização sem o mouse.

É importante lembrar que nenhuma ferramenta isolada garante a conformidade com as diretrizes de acessibilidade. Os resultados devem ser complementados por verificações manuais e pela análise da experiência dos usuários.

## Referências bibliográficas

[Acesse as referências bibliográficas](referencias.md)