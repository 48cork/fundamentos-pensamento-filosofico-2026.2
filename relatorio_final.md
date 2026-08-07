# Relatório Final de Revisão — Fundamentos do Pensamento Filosófico 2026.2

**Curso:** Fundamentos do Pensamento Filosófico (História, UFCG-Cajazeiras, 2026.2)
**Corpus revisado:** 45 aulas (`aulas/encontro-01-aula-01.html` a `encontro-15-aula-03.html`)
**Workflow aplicado:** `squad-revisao-aulas/workflows/revisar-aulas.md` (Passos 1-5 completos)

## Resumo executivo

As 45 aulas passaram pelo squad de revisão completo — Revisor de Progressão (leitura do
conjunto) seguido de Conteudista, Revisor Teórico, Revisor de Fluidez e Revisor Pedagógico
por aula, com veredito final do Aprovador — e **todas fecham com veredito PRONTO**.

Pontos de maior risco definidos antes da geração (Blocos 2 e 4, escritos do zero sem curso
anterior para reaproveitar, e as 3 transições entre blocos) foram auditados com prioridade
pelo Revisor de Progressão e **confirmados sem nenhum ajuste obrigatório de progressão ou
conteúdo**. A transição de maior risco do curso — Sartre (fim do Bloco 3) → Husserl (início
do Bloco 4) — foi, na prática, a mais explicitamente resolvida das três, reconfirmada de
forma independente tanto pelo Revisor de Progressão quanto pelas revisões pontuais dos
lotes 3b e 4.

Todos os ajustes efetivamente aplicados nas 45 aulas foram de **fluidez de prosa** (o
padrão repetitivo "não é X — é Y" excedendo o limite de 1 por aula; clichês genéricos como
"vale notar"/"vale ressaltar"; e a abertura repetitiva da palavra "Compare" nas perguntas
de discussão das Fases 3-4) e **2 correções pontuais de precisão**: um erro factual sobre
a estrutura do curso no Checkpoint 1 (encontro-10-aula-03.html) e uma imprecisão teórica
na recapitulação de Scheler na síntese final (encontro-15-aula-03.html). Nenhum erro
conceitual filosófico, nenhuma ausência de conceito-chave esperado, nenhuma citação
inventada e nenhum jargão não explicado foram encontrados em nenhuma das 45 aulas.

---

## Mapa de Progressão do Curso (Passo 1, na íntegra)

**Corpus revisado:** 45 arquivos, `aulas/encontro-01-aula-01.html` a `encontro-15-aula-03.html`

### Leitura geral do arco

O arco de complexidade crescente descrito no Plano de Aulas está, de fato, implementado — e de forma mais disciplinada do que o esperado para um curso com dois blocos inteiramente inéditos (Bloco 2 e Bloco 4). Em praticamente todas as 45 aulas, o primeiro parágrafo do `.conteudo` (ou da seção equivalente, nos checkpoints) abre com uma frase de amarração explícita ao que veio antes — "Na aula anterior...", "Encerramos o Encontro X...", "Nas duas aulas anteriores deste encontro..." — e essa amarração quase nunca é decorativa: ela reintroduz o conceito específico da aula anterior e o usa como ponto de partida do argumento novo, não apenas como fórmula de transição vazia. Exemplos que confirmam isso: a aula de Descartes (encontro-10-aula-01.html) retoma explicitamente "a postura cética, que vimos no Encontro 3 como uma das três posições clássicas da teoria do conhecimento"; a aula de Marx (encontro-11-aula-01.html) abre situando-o "quase dois séculos depois de Descartes" e opondo diretamente os dois critérios de fundamentação do conhecimento.

Fase a fase:
- **Fase 1 (Encontros 1–3):** cumpre corretamente o papel de definir do zero. Mesmo assim, internamente ao bloco, as aulas 2 e 3 de cada encontro já retomam a aula 1 do mesmo encontro (ex.: encontro-01-aula-03.html abre com "Nas duas aulas anteriores, vimos como a atitude filosófica nasce do espanto..."), o que mostra que a disciplina de amarração não é um recurso introduzido só a partir do Bloco 2 — já está presente desde a primeira aula do curso.
- **Fase 2 (Encontros 4–6):** cumpre a expansão prevista e amarra de volta à Fase 1 logo na primeira aula (ver seção dedicada abaixo). É o bloco com a arquitetura interna mais rigorosa do curso inteiro.
- **Fase 3 (Encontros 7–11):** cumpre bem o papel de comparar e tensionar — o padrão lexical das perguntas de discussão (ver seção dedicada) confirma isso de forma quantitativa. Amarra de volta ao Bloco 1 de forma pontual e efetiva (Descartes/Encontro 3), mas praticamente não recupera o Bloco 2 (ver ressalva abaixo).
- **Fase 4 (Encontros 12–14):** cumpre a síntese prevista, mobilizando pelo menos um conceito de blocos anteriores no corpo do `.conteudo` de toda aula conceitual do bloco (confirmado por varredura textual, não apenas nas perguntas de debate) — majoritariamente conceitos do Bloco 3 (Marx, Adorno & Horkheimer, Sartre, Aristóteles). A recuperação do Bloco 2 (Scheler/Plessner/Gehlen/Cassirer) só acontece no fechamento do curso (encontro-15-aula-03.html), não distribuída ao longo do próprio Bloco 4.
- **Fase 5 (Encontro 15):** cumpre a regra de não introduzir conceito novo relevante — a exceção deliberada de Rancière está declarada no próprio objetivo da aula ("funciona como metáfora de fechamento pedagógico") — e encontro-15-aula-03.html executa exatamente o fechamento retrospectivo dos quatro blocos que o papel deste agente pede que se verifique.

Não foi encontrada nenhuma aula, das 36 aulas em Fases 2–5, que possa ser lida isoladamente sem prejuízo — o critério (a) de aula "ilhada" não se aplicou a nenhum arquivo nesta varredura. Isso é incomum e vale registrar como ponto forte explícito do curso, não apenas ausência de problema.

### Blocos escritos do zero — checagem prioritária

#### Bloco 2 (Encontros 4-6)

Progressividade interna confirmada de forma rigorosa, aula a aula:

- **Encontro 4 (4-1 → 4-2 → 4-3):** 4-1 (Cosmologias Antigas) já abre retomando explicitamente o Bloco 1 ("Encerramos o Bloco 1 perguntando como sabemos algo sobre o mundo... Cosmologia, tema deste encontro, é a mesma pergunta pelo conhecimento... voltada agora para uma questão específica", ver seção de transições). 4-2 (Casini) retoma 4-1 ("Na aula anterior vimos a passagem da explicação mítica do mundo para a busca por um princípio interno... Essa palavra, porém, não guardou um significado fixo ao longo dos séculos"). 4-3 fecha o encontro perguntando pelo humano e abre citando 4-2 ("Na aula anterior, acompanhamos com Casini a passagem histórica de uma natureza pensada como organismo vivo para uma natureza pensada como mecanismo... mas deixa, propositalmente, um ponto de interrogação em aberto: em qual lugar desse mapa fica o próprio ser humano").
- **Encontro 4 → Encontro 5:** funciona como amarração interna ao bloco, não apenas entre encontros — 5-1 (Scheler) abre com "Fechamos a aula anterior com uma pergunta em aberto e sem resposta óbvia: o que, se é que existe algo, distingue o ser humano dos demais seres vivos?", citando literalmente a pergunta que 4-3 havia deixado em aberto.
- **Encontro 5 (5-1 → 5-2 → 5-3):** é o trecho mais bem construído do bloco. 5-2 (Plessner) abre comparando explicitamente com Scheler: "Scheler perguntou o que distingue o ser humano dos outros seres vivos, e respondeu com a noção de espírito... Plessner parte exatamente da mesma pergunta, mas responde a partir de um ângulo diferente." 5-3 (Gehlen) faz o mesmo com os dois anteriores simultaneamente: "Scheler respondeu... Plessner respondeu... Arnold Gehlen parte da mesma pergunta que os dois anteriores, mas inverte o ponto de partida." Isso é exatamente o comportamento exigido pelo agente-definição: "a aula de Plessner deve retomar, não redefinir do zero, a pergunta... aberta por Scheler" — confirmado literalmente no texto.
- **Encontro 5 → Encontro 6:** 6-1 (Cassirer) cita a aula anterior por número — "Encerramos o Encontro 5 com Gehlen: o ser humano como ser carente (Mängelwesen)... Ernst Cassirer parte exatamente desse ponto — aceita a descrição de Gehlen sobre a carência biológica humana — mas desloca a pergunta." O objetivo da própria aula já anuncia isso: "retomando explicitamente a resposta de Gehlen (Encontro 5, Aula 3)".
- **Encontro 6 (6-1 → 6-2 → 6-3):** 6-2 retoma 6-1 (animal simbólico → historicidade). 6-3 (Síntese do Bloco 2) declara explicitamente sua função de fechamento retrospectivo — "É hora de olhar para trás e recompor o caminho percorrido por este bloco inteiro, do Encontro 4 até aqui" — e mobiliza os quatro autores do bloco no caso do calendário gregoriano de 1582.

Conclusão da checagem: o Bloco 2 **não** é uma sequência de três aulas de antropologia filosófica encaixadas lado a lado. É a parte do curso com a arquitetura de amarração mais explícita e mais granular (a ponto de citar "Encontro 5, Aula 3" pelo nome dentro do objetivo da aula seguinte). Nenhum ajuste é necessário aqui.

#### Bloco 4 (Encontros 12-14)

Progressividade interna igualmente confirmada, com o mesmo padrão de citação explícita:

- **Encontro 12 (12-1 → 12-2):** 12-2 (Lebenswelt) abre citando 12-1: "Na aula anterior vimos que, para Husserl, a consciência é sempre intencional... Essa exigência metodológica leva Husserl, já no fim de sua obra, a uma pergunta mais ampla."
- **Encontro 12 → Encontro 13:** 13-1 (Heidegger I) situa a relação Husserl-Heidegger em termos de filiação intelectual real, não apenas cronológica: "Martin Heidegger foi aluno e, por um tempo, assistente de Husserl, e herda dele essa desconfiança em relação a qualquer filosofia que trate o ser humano como um sujeito isolado... Mas Heidegger dá um passo além."
- **Encontro 13 (13-1 → 13-2 → 13-3):** é o trecho mais rigoroso do bloco. 13-3 (Espacialidade) cita as duas aulas anteriores do mesmo encontro pelo número: "Fechamos o Dasein como ser-no-mundo (Aula 13-01) e sua temporalidade como estrutura existencial... (Aula 13-02). Falta ainda um elemento para completar o quadro." Isso replica, no Bloco 4, exatamente o mesmo padrão de citação nominal que o Bloco 2 usou (Encontro 5, Aula 3).
- **Encontro 13 → Encontro 14:** 14-1 (Foucault) declara herança direta: "Michel Foucault herda essas duas intuições — tempo e espaço vividos, carregados de sentido, e não meros contêineres neutros — mas as desloca de uma análise da existência individual para uma análise histórica e política."
- **Encontro 14 (14-1 → 14-2):** 14-2 (Deleuze) situa Deleuze como interlocutor direto de Foucault, não como autor novo desconectado: "Gilles Deleuze foi contemporâneo e interlocutor próximo de Foucault — os dois trocaram influências diretas."

Além da amarração interna, o Bloco 4 mobiliza sistematicamente conceitos do Bloco 3 no corpo do `.conteudo` (não só nas perguntas de debate) — confirmado por varredura textual: 12-1 cita Sartre e Descartes; 12-2 cita Adorno e Horkheimer; 13-1 cita Descartes; 13-2 cita Marx; 13-3 cita Aristóteles; 14-1 cita Marx; 14-2 cita Adorno e Horkheimer. Isso cumpre à risca a exigência da Fase 4 de mobilizar "pelo menos 1 conceito de blocos anteriores" em cada aula.

Única ressalva (não gravidade de erro, mas oportunidade de reforço): o Bloco 4 recupera fartamente o Bloco 3, mas não recupera o Bloco 2 (Scheler/Plessner/Gehlen/Cassirer) em nenhuma de suas aulas — a recuperação do Bloco 2 só acontece no fechamento geral do curso (encontro-15-aula-03.html). Como o critério do agente-definição usa a palavra "idealmente" para essa recuperação de Fase 1/2 dentro da Fase 4, isso não configura falha, mas é um ponto que o Conteudista pode considerar ao revisar aula a aula do Bloco 4.

Conclusão da checagem: o Bloco 4 **não** é uma sequência de três fenomenologias desconectadas. A cadeia Husserl → Heidegger → Foucault/Deleuze está construída como aprofundamento progressivo de uma mesma questão (mundo percebido, ser-no-mundo, espacialidade/temporalidade), com o mesmo padrão de citação explícita observado no Bloco 2. Nenhum ajuste obrigatório é necessário aqui.

### As 3 transições entre blocos

| Transição | Aula de saída | Aula de chegada | Ponte existe? | Ajuste recomendado |
|---|---|---|---|---|
| Bloco 1 → 2 | encontro-03-aula-03.html | encontro-04-aula-01.html | **Sim** | Nenhum. 4-1 abre com "Encerramos o Bloco 1 perguntando como sabemos algo sobre o mundo — se pela razão, pela experiência, ou pela combinação das duas... Cosmologia, tema deste encontro, é a mesma pergunta pelo conhecimento... voltada agora para uma questão específica: o que é a realidade natural". O objetivo da aula reforça isso ("Retomar a pergunta pela teoria do conhecimento, fechada no Encontro 3"). Nota: 3-3 (Epicuro) em si não antecipa a virada para cosmologia — quem faz o trabalho de ponte é inteiramente 4-1, o que é aceitável, mas registra-se que a ponte é unidirecional (só a aula de chegada assume o trabalho de amarração). |
| Bloco 2 → 3 | encontro-06-aula-03.html | encontro-07-aula-01.html | **Sim** | Nenhum. 6-3 fecha anunciando literalmente "a virada do curso de volta à Grécia Antiga, onde os pensadores que a cosmologia panorâmica do Encontro 4 apenas mencionou de passagem serão retomados um a um" (ver seu próprio objetivo). 7-1 abre confirmando a promessa: "Como anunciamos ao fechar o bloco anterior, encerramos o Encontro 6 prometendo que o curso voltaria à Grécia Antiga para aprofundar, um a um, os pensadores que a cosmologia panorâmica do Encontro 4 apenas mencionara de passagem. É isso que fazemos a partir de hoje, abrindo o Bloco 3 da ementa." A aula ainda faz questão de diferenciar o aprofundamento do Encontro 7 do panorama do Encontro 4, evitando repetição de conteúdo — exatamente a distinção deliberada descrita nas Observações do Plano de Aulas. Esta é a transição mais explicitamente amarrada nas duas pontas do curso inteiro. |
| Bloco 3 → 4 | encontro-11-aula-03.html | encontro-12-aula-01.html | **Sim** | Nenhum. Esta era a transição de maior risco apontada no papel do agente (Sartre/Husserl são historicamente próximos, e a ausência de ponte seria falha grave) — e é, na prática, a mais bem resolvida das três. O objetivo de 11-3 já anuncia a ponte ("mostrar que essa filosofia nasce de uma leitura da fenomenologia de Husserl, ponto de partida que o curso retoma no encontro seguinte"), a pergunta 3 de 11-3 antecipa a questão ("Avalie por que a noção husserliana de intencionalidade da consciência... é necessária para Sartre sustentar que a existência precede a essência. O existencialismo se sustentaria sem essa base fenomenológica?"), e 12-1 confirma a promessa logo no primeiro parágrafo: "Encerramos o Encontro 11 com Sartre e o existencialismo, e fechamos aquela aula anunciando que Sartre não constrói sua filosofia da liberdade a partir do zero: ele é leitor atento de um filósofo alemão chamado Edmund Husserl." |

Achado geral sobre as três transições: nenhuma delas apresenta salto conceitual. Todas têm ponte de mão dupla (a aula de saída anuncia, a aula de chegada confirma), com exceção da transição 1→2, que tem ponte só do lado de chegada — diferença de grau, não de tipo, e que não chega a comprometer a leitura.

### Padrão das perguntas de discussão por fase

A variação de registro entre fases está corretamente implementada, e é possível demonstrá-la lexicalmente:

- **Fase 1 (Encontros 1–3, 9 aulas):** primeira pergunta de cada aula abre quase sempre com "Defina", "Identifique", "Classifique", "Descreva" ou "Reconheça" — puro registro de definição/identificação, como o esperado.
- **Fase 2 (Encontros 4–6, 9 aulas):** predomínio de "Descreva" + "Aplique" + "Proponha"/"Avalie", com "Compare" aparecendo pela primeira vez só em 05-02 (Plessner) e se consolidando em 06-03 (síntese, "Mobilize"). Isso mostra uma transição gradual e deliberada do registro de definição para o de comparação, acompanhando a curva interna do próprio bloco.
- **Fase 3 (Encontros 7–11, 15 aulas):** domínio quase total de "Compare", "Avalie", "Tensione", "Contraste", "Distinga", "Diferencie", "Confronte" — exatamente o registro de comparação/tensionamento entre posições esperado para esta fase.
- **Fase 4 (Encontros 12–14, 9 aulas):** aparecem verbos de síntese que não haviam sido usados antes no curso — "Sintetize" (13-01), "Mobilizando" (12-02), "Retomando" (13-02), "Reunindo" (13-03) — ao lado da continuidade de "Compare"/"Avalie". Esse vocabulário novo, específico da fase, é um acerto de desenho.
- **Fase 5 (Encontro 15, 3 aulas):** registro avaliativo-reflexivo de fechamento ("Avalie criticamente esse próprio percurso", "Qual dos quatro blocos... mais mudou sua forma de pensar").

**Achado sinalizado (redundância lexical, não de registro) e já corrigido no Passo 4:** dentro das Fases 3 e 4, a palavra "Compare" abria a primeira pergunta de discussão em pelo menos 18 das 24 aulas, chegando a se repetir duas vezes na mesma aula em três casos. O registro estava correto para a fase — o problema era a palavra escolhida para abri-la, repetida quase sem variação por oito encontros seguidos. Este achado foi tratado explicitamente pelos lotes de revisão do Passo 4 (ver tabela consolidada abaixo) — a saturação foi reduzida em todas as aulas onde havia duplicação literal na mesma aula, e parcialmente variada nas demais, preservando "Compare" como registro legítimo em parte das aulas.

### Conclusão do Mapa de Progressão

A arquitetura do curso como um todo está sólida. As duas checagens de maior risco definidas para esta revisão — a progressividade interna dos Blocos 2 e 4, e as três transições entre blocos — passaram sem nenhum ajuste obrigatório: os quatro autores do Bloco 2 (Scheler, Plessner, Gehlen, Cassirer) formam uma cadeia argumentativa real, com citação explícita e nominal entre aulas consecutivas; os três encontros do Bloco 4 (Husserl, Heidegger, Foucault/Deleuze) replicam esse mesmo padrão; e a transição de maior risco apontada no papel deste agente — Sartre (fim do Bloco 3) para Husserl (início do Bloco 4) — é, na prática, a mais explicitamente resolvida das três, com ponte anunciada no fim de uma aula e confirmada na abertura da seguinte.

Não foi encontrada nenhuma aula "ilhada" nem nenhum conceito filosófico introduzido "do zero" sem amarração nas Fases 2 a 5. O único achado de arquitetura com ajuste recomendado foi de natureza lexical, não estrutural, e já foi corrigido no Passo 4 (ver tabela abaixo).

---

## Veredito final das 45 aulas (Passo 3-4)

| Aula | Veredito final | Resumo do ajuste aplicado |
|---|---|---|
| encontro-01-aula-01.html | PRONTO | Reduzido excesso do padrão "não é X — é Y" (2→1) |
| encontro-01-aula-02.html | PRONTO | Reduzido excesso do padrão "não X, mas Y" (3→1) |
| encontro-01-aula-03.html | PRONTO | Reduzido excesso do padrão (3→1) |
| encontro-02-aula-01.html | PRONTO | Nenhum ajuste — já limpo |
| encontro-02-aula-02.html | PRONTO | Nenhum ajuste — já limpo |
| encontro-02-aula-03.html | PRONTO | Reduzido excesso do padrão (2→1) |
| encontro-03-aula-01.html | PRONTO | Nenhum ajuste — já limpo |
| encontro-03-aula-02.html | PRONTO | Nenhum ajuste — já limpo |
| encontro-03-aula-03.html | PRONTO | Removida repetição do contraste prazer/excesso entre `.conteudo` e `.caso` |
| encontro-04-aula-01.html | PRONTO | Reduzido excesso do padrão (2→1) |
| encontro-04-aula-02.html | PRONTO | Nenhum ajuste — já limpo |
| encontro-04-aula-03.html | PRONTO | Reduzido excesso do padrão (4→1) |
| encontro-05-aula-01.html | PRONTO | Reduzido excesso do padrão (3→1) |
| encontro-05-aula-02.html | PRONTO | Reduzido excesso do padrão (2→1) |
| encontro-05-aula-03.html | PRONTO | Nenhum ajuste — já limpo |
| encontro-06-aula-01.html | PRONTO | Reduzido excesso do padrão (6→1) |
| encontro-06-aula-02.html | PRONTO | Reduzido excesso do padrão (2→1) |
| encontro-06-aula-03.html | PRONTO | Reduzido excesso do padrão (4→1) |
| encontro-07-aula-01.html | PRONTO | Reescrito parágrafo com padrão duplicado |
| encontro-07-aula-02.html | PRONTO | Pergunta 1: "Compare" → "Contraste" |
| encontro-07-aula-03.html | PRONTO | Pergunta 1: "Compare" → "Distinga" |
| encontro-08-aula-01.html | PRONTO | Reescrita frase redundante + Pergunta 1: "Compare" → "Confronte" |
| encontro-08-aula-02.html | PRONTO | Pergunta 3: "Compare" → "Tensione" (duplicação com P1) |
| encontro-08-aula-03.html | PRONTO | Reescrita 2ª ocorrência do padrão + Pergunta 3: "Compare" → "Confronte" |
| encontro-09-aula-01.html | PRONTO | Consolidado padrão triplicado em 1 ocorrência |
| encontro-09-aula-02.html | PRONTO | Reescritas 2 ocorrências do padrão + Pergunta 1: "Compare" → "Diferencie" |
| encontro-09-aula-03.html | PRONTO | Reescrita ocorrência do padrão + Pergunta 3: "Compare" → "Contraste" |
| encontro-10-aula-01.html | PRONTO | Pergunta 1: "Compare" → "Confronte" |
| encontro-10-aula-02.html | PRONTO | Nenhum ajuste — já limpo |
| encontro-10-aula-03.html | PRONTO | Corrigido erro factual (Marx/Adorno&Horkheimer/Sartre rotulados como "mesmo encontro" do Checkpoint 1) |
| encontro-11-aula-01.html | PRONTO | Nenhum ajuste — já limpo |
| encontro-11-aula-02.html | PRONTO | Nenhum ajuste — já limpo |
| encontro-11-aula-03.html | PRONTO | Reduzido excesso do padrão (2→1) + Pergunta 1: "Compare" → "Contraste". Ponte Sartre→Husserl confirmada sólida |
| encontro-12-aula-01.html | PRONTO | Reduzido excesso do padrão (4→1) + Pergunta 1: "Compare" → "Contraste". Ponte de chegada Sartre→Husserl confirmada sólida |
| encontro-12-aula-02.html | PRONTO | Nenhum ajuste — já limpo |
| encontro-12-aula-03.html | PRONTO | Nenhum ajuste — checkpoint fiel ao Roteiro de Pesquisa |
| encontro-13-aula-01.html | PRONTO | Reduzido excesso do padrão (2→1) |
| encontro-13-aula-02.html | PRONTO | Substituído clichê "Vale comparar..." |
| encontro-13-aula-03.html | PRONTO | Reduzido excesso do padrão (3→1) |
| encontro-14-aula-01.html | PRONTO | Substituído clichê "Vale ainda notar..." |
| encontro-14-aula-02.html | PRONTO | Substituído clichê + reduzido padrão (2→1) + Pergunta 1: "Compare" → "Confronte" |
| encontro-14-aula-03.html | PRONTO | Nenhum ajuste — checkpoint fiel ao Roteiro de Pesquisa |
| encontro-15-aula-01.html | PRONTO | Reduzido excesso do padrão "não é X — é Y" (7→1) |
| encontro-15-aula-02.html | PRONTO | Nenhum ajuste — seminário fiel ao Roteiro de Pesquisa |
| encontro-15-aula-03.html | PRONTO | Corrigida imprecisão teórica sobre Scheler na síntese geral do curso |

**Total: 45/45 aulas PRONTO.** 30 das 45 aulas precisaram de pelo menos um ajuste; 15 já vieram limpas dos 4 critérios de revisão pontual. Nenhum ajuste alterou cobertura de conteúdo, correção conceitual (à exceção da imprecisão pontual sobre Scheler) ou adequação pedagógica — a esmagadora maioria foi fluidez de prosa.

---

## Observações não bloqueantes para referência futura

- **Extensão abaixo da faixa em Encontros 4-5:** o corpo expositivo de várias aulas dos Encontros 4 e 5 ficou entre ~633 e ~792 palavras, abaixo da faixa de referência de 800-1200. Nenhuma parte subdesenvolvida foi identificada, então não bloqueou nenhum veredito — fica como oportunidade de reforço se o docente quiser expandir esses trechos antes da publicação.
- **Recuperação do Bloco 2 dentro do Bloco 4:** o Bloco 4 recupera fartamente o Bloco 3, mas só recupera nominalmente os quatro autores do Bloco 2 no fechamento geral do curso (Encontro 15), não distribuído pelas próprias aulas do Bloco 4. O critério do agente usa a palavra "idealmente" para essa recuperação — não é falha, é reforço opcional.
- **Bonjour & Baker (Bibliografia, Bloco 1):** segue sem tradução brasileira confirmada — decisão de manter em inglês ou substituir por antologia nacional equivalente continua em aberto para o docente, conforme já registrado na Bibliografia.
