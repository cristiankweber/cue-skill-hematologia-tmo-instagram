# Hematologia e TMO no Instagram — pacote de skill

Pacote editorial para o perfil profissional @hematoweber, com biblioteca de exemplos reais aprovados.

## Estrutura

- `SKILL.md` — regras de disparo, fluxo e contrato de saída.
- `references/perfil_editorial.md` — identidade, credenciais e posicionamento.
- `references/linguagem_e_voz.md` — padrões linguísticos derivados do corpus aprovado.
- `references/biblioteca_editorial.md` — roteamento para exemplos reais conforme intenção, risco e formato.
- `references/guardrails_clinicos_e_eticos.md` — segurança clínica, privacidade e publicidade.
- `references/fontes_preferenciais.md` — hierarquia de evidências.
- `references/pilares_e_formatos.md` — pilares, risco e escolha de formato.
- `examples/carrosseis/` — fichas estruturadas de 8 carrosséis aprovados.
- `examples/visual/` — contact sheets dos materiais originais para calibração visual.
- `templates/` — carrossel, Reel, Stories, post estático, comentários/DM e calendário.
- `tests/pressure-scenarios.md` — guardrails gerais.
- `tests/library-retrieval-scenarios.md` — testes de seleção e uso da biblioteca.

## Corpus inicial

1. A Jornada de um Transplante
2. O Dicionário do Transplante
3. Tipos Sanguíneos no Transplante
4. Vacinas pós-TCTH
5. TMO no Mieloma
6. Nutrição no TMO
7. Seleção de Doador
8. Alergia nova no pós-transplante

## Como a biblioteca funciona

Para uma nova pauta, a skill escolhe 1 exemplo-âncora com base em público, objetivo, risco, densidade e função narrativa. O exemplo calibra **como comunicar**; fontes atuais definem **o que pode ser afirmado**.

Essa separação é deliberada: um post antigo pode continuar excelente como referência de linguagem e design mesmo que algum detalhe clínico precise ser atualizado.

## Manutenção

Quando um novo conteúdo for considerado representativo da marca:
1. adicionar uma ficha em `examples/carrosseis/` (ou diretório do formato correspondente);
2. registrar quando usar em `references/biblioteca_editorial.md`;
3. acrescentar um cenário em `tests/library-retrieval-scenarios.md` se ele trouxer um modo editorial novo;
4. nunca usar o exemplo como substituto de guideline.


## Versão instalável

Este pacote omite os arquivos de vídeo brutos para permanecer abaixo do limite de tamanho de instalação. As referências audiovisuais são preservadas por fichas editoriais e contact sheets, suficientes para roteamento de estilo e formato. Os vídeos originais permanecem fora da skill como arquivos-fonte do usuário.
