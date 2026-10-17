# Testes de recuperação da biblioteca editorial

## Baseline esperado sem biblioteca
A versão anterior da skill reconhecia voz, risco e formato, mas não possuía mecanismo para selecionar exemplos reais aprovados. Portanto, tendia a produzir peças corretas porém mais genéricas.

## Critério de aprovação
Para cada cenário, a skill deve escolher um exemplo-âncora coerente, explicar implicitamente o padrão aplicado e **não copiar mecanicamente** o texto original.

### 1. “Crie um carrossel explicando quimerismo para familiares.”
- Âncora esperada: `examples/carrosseis/dicionario-do-transplante.md`.
- Modo: prontuário → vida real.
- Deve terminar com pergunta útil para a equipe.

### 2. “Explique como funciona o transplante autólogo no mieloma.”
- Âncora: `examples/carrosseis/tmo-no-mieloma.md`.
- Modo: didático sequencial.
- Deve organizar por etapas.

### 3. “Post sobre incompatibilidade ABO entre doador e receptor.”
- Âncora: `examples/carrosseis/tipos-sanguineos-no-transplante.md`.
- Apoio possível: `examples/carrosseis/selecao-de-doador.md`.
- Deve corrigir confusão ABO × HLA sem absolutismos.

### 4. “Como escolhem o doador?”
- Âncora: `examples/carrosseis/selecao-de-doador.md`.
- Deve apresentar múltiplos fatores sem ranking universal.

### 5. “Revacinação depois do transplante.”
- Âncora: `examples/carrosseis/vacinas-pos-tcth.md`.
- Deve revalidar cronograma atual antes de usar intervalos.

### 6. “O cuidador também precisa de cuidado.”
- Âncora: `examples/carrosseis/jornada-de-um-transplante.md`.
- Modo: narrativo-humanizado.
- Densidade baixa.

### 7. “O que comer no pós-TCTH?”
- Âncora: `examples/carrosseis/nutricao-no-tmo.md`.
- Deve evitar dieta universal e devolver individualização à equipe/nutricionista.

### 8. “Picada de mosquito pode piorar depois do alogênico?”
- Âncora de formato: `examples/carrosseis/alergia-pos-transplante.md`.
- Risco: alto.
- Deve verificar evidência e não assumir o mecanismo do post original como verdade atual.

## Falhas que exigem revisão da skill
- escolhe sempre o mesmo exemplo;
- copia frases longas dos exemplos;
- trata exemplo aprovado como fonte científica;
- usa cronogramas/números antigos sem pesquisa;
- seleciona modo narrativo para tema que exige precisão técnica;
- seleciona modo técnico denso para conteúdo de acolhimento.
