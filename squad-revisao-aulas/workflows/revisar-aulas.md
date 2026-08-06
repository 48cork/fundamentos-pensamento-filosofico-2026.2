# Workflow: Revisar Aulas

Ordem de execução do squad de revisão sobre os 45 arquivos HTML de aula em
`fundamentos-pensamento-filosofico-2026.2/aulas/` (15 encontros × 3 aulas).

## Passo 1 — Revisor de Progressão (roda uma vez, sobre o conjunto)

`agentes/revisor-progressao.md` lê as 45 aulas em sequência e produz o **Mapa de
Progressão do Curso** (ver formato de saída no próprio arquivo do agente): leitura geral
do arco de complexidade crescente, checagem dedicada dos Blocos 2 e 4 (escritos do zero),
checagem dedicada das 3 transições entre blocos (1→2, 2→3, 3→4), tabela de ajustes por
aula, avaliação do padrão das perguntas de discussão por fase, e conclusão.

Este passo roda **antes** de qualquer revisão pontual. Nenhuma aula individual é corrigida
neste passo — o produto é só o mapa. As seções sobre Blocos 2/4 e as 3 transições são
obrigatórias no relatório, mesmo quando não há problema a apontar.

## Passo 2 — Revisão por aula (roda 45 vezes, uma por arquivo)

Para cada arquivo, nesta ordem, cada agente já ciente de:
- em que fase do arco (1 a 5, conforme o Mapa de Progressão) aquela aula está;
- os apontamentos específicos que o Revisor de Progressão fez para aquele arquivo,
  incluindo apontamentos de bloco escrito do zero ou de transição entre blocos, quando
  aplicável.

1. `agentes/conteudista.md` — cobertura de conteúdo vs. bibliografia do bloco.
2. `agentes/revisor-teorico.md` — correção dos conceitos e autores filosóficos citados.
3. `agentes/revisor-fluidez.md` — fluidez de prosa e voz autoral (padrões a/b/c/d).
4. `agentes/revisor-pedagogico.md` — adequação da linguagem ao público de História.

Cada um produz seu parecer no formato definido no próprio arquivo do agente. Os quatro
pareceres de uma mesma aula são produzidos independentemente uns dos outros (não há
dependência sequencial de conteúdo entre eles, só a dependência comum do Mapa de
Progressão do Passo 1).

## Passo 3 — Aprovador (fecha, aula por aula)

`agentes/aprovador.md` lê os quatro pareceres do Passo 2 mais os apontamentos específicos
daquele arquivo no Mapa de Progressão do Passo 1, e emite o veredito: **PRONTO** ou
**PRECISA REVISAR**, com lista objetiva e rastreável do que falta ajustar. Para aulas dos
Blocos 2/4 ou das 3 transições, o Aprovador confirma explicitamente que o Mapa de
Progressão não sinalizou problema de progressividade interna ou de ponte antes de emitir
PRONTO.

## Passo 4 — Aplicação das correções

Quando o veredito for **PRECISA REVISAR**, os ajustes obrigatórios listados pelo Aprovador
são aplicados diretamente no arquivo HTML da aula. Depois de aplicados, a aula não volta a
passar pelo Passo 2 automaticamente — a aplicação dos ajustes já listados pelo Aprovador é
considerada suficiente para fechar o ciclo, salvo indicação em contrário de quem executa o
workflow.

## Passo 5 — Relatório final

Consolidar em `relatorio_final.md`, na raiz de `fundamentos-pensamento-filosofico-2026.2/`:
- o Mapa de Progressão do Curso (Passo 1), na íntegra, incluindo as seções dedicadas aos
  Blocos 2/4 e às 3 transições entre blocos;
- o veredito de cada uma das 45 aulas (Passo 3), incluindo se houve aplicação de ajustes
  (Passo 4) e um resumo de uma linha do que foi corrigido em cada caso.

## Resumo do fluxo

```
revisor-progressao (1x, todas as 45 aulas)
        │  [checagem dedicada: Bloco 2, Bloco 4, transições 1→2, 2→3, 3→4]
        ▼
   Mapa de Progressão
        │
        ▼
┌───────────────────────────────────────────────────┐
│  para cada uma das 45 aulas, em paralelo:          │
│  conteudista → revisor-teorico → revisor-fluidez   │
│              → revisor-pedagogico                  │
│                       │                             │
│                       ▼                             │
│                   aprovador                          │
│                       │                             │
│                       ▼                             │
│         PRONTO  ou  PRECISA REVISAR + ajustes       │
│                       │                             │
│                       ▼                             │
│            aplicação direta no arquivo               │
└───────────────────────────────────────────────────┘
        │
        ▼
   relatorio_final.md
```
