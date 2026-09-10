# Decisões do projeto

Registro extraído dos documentos existentes, com atualização posterior fornecida pelo docente. As fontes originais não informam as datas das decisões nem um histórico de alternativas deliberadas; por isso, esses dados só são registrados quando explicitamente disponíveis. Regras do protocolo, resultados da revisão e decisões resolvidas estão separados abaixo.

## Regras adotadas

### Revisar o conjunto antes de revisar cada aula
- Contexto: o corpus contém 45 aulas, distribuídas em 15 encontros de 3 aulas, com um arco de complexidade crescente.
- Decisão: o Revisor de Progressão lê todo o conjunto primeiro. Seu Mapa de Progressão é insumo obrigatório dos quatro revisores pontuais e do Aprovador.
- Fonte: [Workflow, Passos 1–3](../workflows/revisar-aulas.md); [Revisor de Progressão, Papel](../agentes/revisor-progressao.md).

### Separar os pareceres e consolidar o veredito
- Contexto: cobertura, correção teórica, fluidez e adequação pedagógica são dimensões distintas da revisão.
- Decisão: Conteudista, Revisor Teórico, Revisor de Fluidez e Revisor Pedagógico produzem pareceres independentes, com dependência comum do mapa. O Aprovador consolida esses pareceres e os apontamentos de progressão, sem reavaliar o conteúdo por conta própria.
- Fonte: [Workflow, Passos 2–3](../workflows/revisar-aulas.md); [Aprovador, Papel](../agentes/aprovador.md).

### Dar prioridade explícita aos Blocos 2 e 4 e às transições
- Contexto: os Blocos 2 (Encontros 4–6) e 4 (Encontros 12–14) foram escritos do zero, sem material equivalente de curso anterior para adaptar.
- Decisão: avaliar a progressividade interna desses blocos e as transições 1→2, 2→3 e 3→4 em seções próprias, mesmo quando não houver problemas. O Aprovador deve consultar essas verificações antes de aprovar as aulas correspondentes.
- Fonte: [Revisor de Progressão, checagens prioritárias](../agentes/revisor-progressao.md); [Aprovador, Nota sobre Blocos 2, 4 e as 3 aulas de transição](../agentes/aprovador.md).

### Preservar o arco de cinco fases e a exceção de Rancière
- Contexto: o curso avança de definição para expansão, comparação, síntese e avaliação crítica.
- Decisão: o Encontro 15 fecha o percurso sem introduzir conceito filosófico novo relevante. Rancière é a exceção deliberada: funciona como metáfora de fechamento pedagógico, sem constituir novo conteúdo teórico a dominar.
- Fonte: [Revisor de Progressão, O Arco de Complexidade Esperado](../agentes/revisor-progressao.md); [Mapa, Leitura geral do arco](../mapa-progressao.md).

### Aplicar limites de fluidez preservando a voz autoral
- Contexto: o protocolo de fluidez surgiu de padrões identificados em uma aula de curso anterior revisada à mão pelo professor.
- Decisão: admitir no máximo uma ocorrência do padrão definidor “não é X — é Y” e uma caixa de destaque por aula; integrar a leitura filosófica ao caso; remover clichês genéricos. Preservar perguntas metodológicas e ressalvas específicas que evitam simplificações, inclusive quando contêm negação.
- Fonte: [Revisor de Fluidez, Padrões a Corrigir e O que Preservar sem Alterar](../agentes/revisor-fluidez.md).

### Adequar a linguagem à graduação em História
- Contexto: o público não tem necessariamente formação prévia em Filosofia, mas possui repertório de processos e periodização históricos.
- Decisão: explicar termos técnicos em linguagem comum na primeira aparição na aula, ancorar conceitos historicamente e evitar simplificações que esvaziem seu significado.
- Fonte: [Revisor Pedagógico, Papel e Critérios de Avaliação](../agentes/revisor-pedagogico.md).

### Fechar o ciclo após aplicar os ajustes obrigatórios
- Contexto: o Aprovador emite PRONTO ou PRECISA REVISAR, com ajustes rastreáveis aos pareceres.
- Decisão: aplicar os ajustes obrigatórios diretamente no HTML. Não repetir automaticamente o Passo 2 após a aplicação, salvo indicação de quem executa o workflow. Consolidar mapa, vereditos e resumos de correções em `relatorio_final.md`.
- Fonte: [Workflow, Passos 3–5](../workflows/revisar-aulas.md).

## Tratamentos e resultados registrados na revisão

### Variar “Compare” sem eliminar o registro de comparação
- Contexto: o mapa identificou repetição de “Compare” nas perguntas das Fases 3 e 4, embora a exigência cognitiva estivesse adequada.
- Tratamento registrado: variar aberturas com “Contraste”, “Confronte”, “Distinga”, “Tensione” e “Diferencie”, preservando “Compare” em parte das aulas. O relatório registra a correção das duplicações na mesma aula e variação parcial nas demais.
- Fontes: [Mapa, Padrão das perguntas de discussão por fase](../mapa-progressao.md); [Relatório final, mesma seção e tabela de vereditos](../../relatorio_final.md).

### Aceitar ressalvas sem transformá-las em bloqueios
- Contexto: várias aulas dos Encontros 4–5 tinham aproximadamente 633–792 palavras, abaixo da referência de 800–1200; o Bloco 4 não recuperava nominalmente os quatro autores do Bloco 2, retomados no fechamento geral.
- Tratamento registrado: a extensão não bloqueou a aprovação porque não foram identificadas partes subdesenvolvidas. A recuperação do Bloco 2 dentro do Bloco 4 foi mantida como reforço opcional, pois o protocolo a qualifica como ideal.
- Fonte: [Relatório final, Observações não bloqueantes para referência futura](../../relatorio_final.md).

### Estado registrado do corpus
- O relatório declara 45/45 aulas PRONTO: 30 receberam ajustes e 15 já estavam sem problemas nos quatro critérios pontuais.
- Além dos ajustes de fluidez, registra a correção da referência a autores como pertencentes ao “mesmo encontro” no Checkpoint 1 (`encontro-10-aula-03.html`) e uma imprecisão sobre Scheler na síntese (`encontro-15-aula-03.html`).
- Este é o resultado da revisão documentada, não uma nova auditoria nem uma aprovação automática de futuras alterações.
- Fonte: [Relatório final, Resumo executivo e Veredito final das 45 aulas](../../relatorio_final.md).

## Decisões resolvidas

### Bibliografia de Bonjour & Baker

- Contexto original: o relatório informava que não havia tradução brasileira confirmada e deixava ao docente a decisão entre manter a obra em inglês ou substituí-la por antologia nacional equivalente.
- Resolução (2026-09-10): o docente confirmou a existência de tradução brasileira — Artmed/Penso, 2ª ed., 2010, ISBN 9788536321196 — e forneceu a referência completa para atualização da bibliografia.
- Decisão: manter a obra original via edição em português, *Filosofia: textos fundamentais comentados*, tradução de Roberto Hofmeister Pich et al., Porto Alegre: Artmed, 2010, 776 p. Não há necessidade de substituição por outra antologia nem de manter a leitura em inglês para contornar a ausência de tradução.
- Fontes: [Relatório final, Observações não bloqueantes para referência futura](../../relatorio_final.md), preservado como contexto histórico; confirmação e orientação do docente em 2026-09-10; [Bibliografia atualizada, Bloco 1](../../Bibliografia_Fundamentos_Pensamento_Filosofico.md).
