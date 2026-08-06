# Squad de Revisão de Aulas — Fundamentos do Pensamento Filosófico 2026.2

Squad de revisão para os 45 arquivos HTML de aula em
`fundamentos-pensamento-filosofico-2026.2/aulas/` (15 encontros × 3 aulas).

## Estrutura

```
squad-revisao-aulas/
├── agentes/
│   ├── conteudista.md          — cobertura de conteúdo vs. bibliografia do curso
│   ├── revisor-teorico.md      — correção dos conceitos e autores filosóficos citados
│   ├── revisor-fluidez.md      — fluidez de prosa e voz autoral
│   ├── revisor-pedagogico.md   — adequação da linguagem a alunos de História
│   ├── revisor-progressao.md   — arquitetura do curso como um todo (lê as 45 aulas juntas)
│   └── aprovador.md            — veredito final por aula
└── workflows/
    └── revisar-aulas.md        — ordem de execução do squad
```

## Lógica

Cada agente em `agentes/` é uma definição de papel: o que avalia, com que critérios, e em
que formato devolve o parecer. Nenhum agente edita o arquivo de aula diretamente — quem
aplica a correção final é sempre quem executa o workflow (humano ou IA orquestradora), com
base nos pareceres. A exceção lógica é o `revisor-fluidez`, cujo parecer já vem no formato
"trecho original → trecho corrigido", pronto para aplicação direta.

O `revisor-progressao` é o único agente que não olha para uma aula isolada — ele lê o
conjunto das 45 aulas antes de qualquer revisão pontual começar, para que os demais
agentes revisem cada aula já sabendo em que fase do arco de complexidade do curso ela se
encontra.

## Particularidade deste curso: Blocos 2 e 4 escritos do zero

Diferente de outras disciplinas do docente, os **Blocos 2 (Encontros 4-6, cosmologia →
antropologia filosófica)** e **4 (Encontros 12-14, mundo percebido e ser-no-mundo)** não
vieram de reaproveitamento de curso já testado em sala — foram escritos diretamente para
esta disciplina (ver `Plano_Aulas_Fundamentos_Pensamento_Filosofico.md`, seção
"Observações"). Por isso, o `revisor-progressao` tem seções dedicadas e obrigatórias de
checagem para esses dois blocos e para as três transições entre blocos (1→2, 2→3, 3→4),
além da varredura geral que já fazia nos cursos anteriores — ver o próprio arquivo do
agente para o detalhe dessa checagem.

Ver `workflows/revisar-aulas.md` para a ordem exata de execução.
