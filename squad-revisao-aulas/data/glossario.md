# Glossário

Termos usados nos registros e protocolos deste projeto. As definições resumem o uso documentado. As fontes fornecem material suficiente para um glossário operacional, mas não para definir rigorosamente todos os conceitos filosóficos apenas mencionados; estes não foram completados com definições externas.

## Organização e revisão

| Termo | Significado no projeto | Fonte |
|---|---|---|
| Corpus | Conjunto das 45 aulas HTML, distribuídas em 15 encontros com 3 aulas cada. | [Workflow, abertura](../workflows/revisar-aulas.md) |
| Squad de revisão | Conjunto de papéis que analisa progressão, cobertura, teoria, fluidez e pedagogia e consolida um veredito por aula. | [Workflow, Passos 1–3](../workflows/revisar-aulas.md) |
| Mapa de Progressão | Produto da leitura global: avaliação do arco, blocos inéditos, transições, ajustes por aula e padrão das perguntas. É insumo obrigatório da revisão pontual. | [Revisor de Progressão, Papel e Formato de Saída](../agentes/revisor-progressao.md) |
| Arco de complexidade crescente | Percurso em cinco fases: definição, expansão, comparação/aprofundamento histórico, síntese e avaliação crítica/fechamento. | [Revisor de Progressão, O Arco de Complexidade Esperado](../agentes/revisor-progressao.md) |
| Blocos escritos do zero | Bloco 2, Encontros 4–6, e Bloco 4, Encontros 12–14: conteúdo produzido para esta disciplina sem material equivalente anterior para adaptar. | [Revisor de Progressão, Atenção redobrada](../agentes/revisor-progressao.md) |
| Progressividade interna | Encadeamento em que as aulas de um bloco retomam e aprofundam o que as anteriores estabeleceram. | [Revisor de Progressão, checagens dos Blocos 2 e 4](../agentes/revisor-progressao.md) |
| Amarração conceitual | Retomada explícita de um conceito já trabalhado para sustentar o argumento seguinte, além de uma frase de transição decorativa. | [Mapa, Leitura geral do arco](../mapa-progressao.md) |
| Ponte entre blocos | Ligação conceitual pela qual a abertura do bloco seguinte reconhece o que o anterior concluiu; as três transições verificadas são 1→2, 2→3 e 3→4. | [Revisor de Progressão, As 3 transições](../agentes/revisor-progressao.md) |
| Aula ilhada | Aula das Fases 2–5 sem referência ao percurso anterior, embora devesse apoiar-se em conceitos já vistos. Definir do zero na Fase 1 não constitui esse problema. | [Revisor de Progressão, critérios gerais](../agentes/revisor-progressao.md) |
| Parecer | Registro de um revisor, no formato definido em seu arquivo, com avaliação e apontamentos da sua dimensão. | [Workflow, Passo 2](../workflows/revisar-aulas.md) |
| Item bloqueante | Problema que exige PRECISA REVISAR: erro conceitual, ausência de conceito-chave, violação de fluidez, jargão não explicado, exemplo incompreensível ou falha de amarração/ponte. | [Aprovador, Critério de Decisão](../agentes/aprovador.md) |
| PRONTO | Veredito de ausência de itens bloqueantes; admite observações menores que não comprometam a aula. | [Aprovador, Critério de Decisão](../agentes/aprovador.md) |
| PRECISA REVISAR | Veredito que identifica ao menos um bloqueio e exige ajustes objetivos rastreáveis aos pareceres. | [Aprovador, Critério de Decisão e Formato de Saída](../agentes/aprovador.md) |
| Observação não bloqueante | Ressalva que não impede a aprovação. O relatório inclui extensão reduzida sem subdesenvolvimento e retomada adicional do Bloco 2 como reforço opcional. | [Relatório final, Observações não bloqueantes](../../relatorio_final.md) |

## Conteúdo e linguagem

| Termo | Significado no projeto | Fonte |
|---|---|---|
| Cobertura de conteúdo | Presença substantiva dos temas e conceitos esperados pelo plano e pela bibliografia do bloco. | [Conteudista, Papel e Critérios](../agentes/conteudista.md) |
| Uso decorativo de conceito | Citação de autor ou termo sem aplicação efetiva de sua lógica ao argumento ou caso. | [Revisor Teórico, critérios 1–2](../agentes/revisor-teorico.md) |
| Jargão não explicado | Termo técnico usado sem explicação em linguagem comum na sua primeira aparição na aula. | [Revisor Pedagógico, critério 1](../agentes/revisor-pedagogico.md) |
| Ancoragem histórica | Situar conceitos em processos, datas e contextos históricos concretos, aproveitando o repertório dos estudantes de História. | [Revisor Pedagógico, critério 3](../agentes/revisor-pedagogico.md) |
| Voz autoral | No protocolo de fluidez, inclui perguntas metodológicas dirigidas ao aluno e ressalvas específicas que evitam generalizações; esses trechos devem ser preservados. | [Revisor de Fluidez, O que Preservar sem Alterar](../agentes/revisor-fluidez.md) |
| Caixa de destaque | Bloco HTML como `.callout` ou `.highlight`, com rótulos como “Conceito-chave” ou “Tese central”; limitado a uma ocorrência por aula. | [Revisor de Fluidez, padrão (b)](../agentes/revisor-fluidez.md) |
| Caso / `.caso` | Seção do exemplo cuja interpretação filosófica deve integrar a narrativa em prosa contínua. | [Revisor de Fluidez, padrão (c)](../agentes/revisor-fluidez.md) |
| Leitura filosófica / `.leitura` | Interpretação teórica que o protocolo manda incorporar ao caso quando aparece como bloco visual separado ao final dele. | [Revisor de Fluidez, padrão (c)](../agentes/revisor-fluidez.md) |
| Redundância lexical | Repetição de palavras, como “Compare” abrindo perguntas nas Fases 3–4, mesmo quando o tipo de operação intelectual é adequado. | [Mapa, Padrão das perguntas de discussão por fase](../mapa-progressao.md) |
| Intencionalidade husserliana | “A consciência é sempre consciência de algo”: explicação introdutória explicitamente aceita pelo Revisor Teórico. | [Revisor Teórico, critério 3](../agentes/revisor-teorico.md) |
| Cogito cartesiano | No critério do Revisor Teórico, busca de certeza absoluta e universal; tratá-lo como sinônimo de posição subjetivista/relativista é apontado como erro. | [Revisor Teórico, critério 3](../agentes/revisor-teorico.md) |
| Ser-no-mundo | Termo técnico de Heidegger com dimensão existencial estruturante; não pode ser reduzido a estar em algum lugar nem alternado sem explicação com “estar no mundo”. | [Revisor Pedagógico, critério 2](../agentes/revisor-pedagogico.md); [Revisor Teórico, critério 5](../agentes/revisor-teorico.md) |

## Limite das fontes

Os agentes citam outros termos, como `arché`, `eudaimonia`, excentricidade posicional e Lebenswelt, principalmente para orientar a checagem de cobertura e de explicação. Não há, nesses registros, definições completas suficientes para transformar essa lista em um glossário filosófico abrangente. A inclusão futura dessas definições exige consultar as aulas e a bibliografia correspondentes.
