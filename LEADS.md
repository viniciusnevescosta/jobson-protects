# Controle de leads

**Base preparada em 2026-09-29. Nenhum lead foi pesquisado ou contatado nesta etapa.**

Cada lead terá uma ficha em `leads/`, criada a partir de [[MODELO_DE_LEAD]]. Este arquivo é o índice de acompanhamento; a ficha é a referência do histórico daquele lead. Ao mudar uma ficha, atualizar sua linha aqui e, quando aplicável, [[FOLLOWUPS]] e [[RESULTADOS]].

## Índice

| ID / ficha | Empresa/profissional | Segmento | Bairro / região do serviço | Potencial | Canal recomendado | Status | Último contato real | Próxima ação / data | Responsável |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

A tabela começa vazia de propósito. Primeiro ID disponível: **LEAD-0001**. Consultar os IDs existentes antes de criar novos registros; não reutilizar IDs descartados.

## Status padronizados

| Status | Quando usar |
| --- | --- |
| Novo | Candidato identificado, ainda sem análise |
| Em pesquisa | Verificando localização, oportunidade, fontes ou contato |
| Qualificado | Compatibilidade e potencial avaliados; abordagem ainda em preparação |
| Pronto para contato | Critérios de [[PERFIL_DE_CLIENTE]] cumpridos e mensagem revisada |
| Contatado | Envio real confirmado e registrado |
| Em conversa | Retorno recebido e conversa em andamento |
| Orçamento enviado | Proposta real enviada, com escopo e valor registrados |
| Fechado | Contratação confirmada; registrar evidência e condições |
| Perdido | Oportunidade encerrada após negociação ou negativa; registrar motivo |
| Sem resposta | Cadência encerrada sem retorno; não equivale a recusa |
| Descartado | Incompatibilidade ou duplicidade identificada; registrar motivo |
| Não contatar | Pedido explícito de não contato; suspender retomadas |

O status representa a etapa atual; “Resultado” na ficha registra o desfecho/retorno observado. Não mudar para “Contatado” ao apenas gerar uma mensagem.

## Deduplicação

Antes de criar uma ficha, comparar nome, domínio, perfil oficial e telefone com as fichas existentes. Reunir contatos alternativos da mesma empresa na ficha já existente. Se identificar duplicata depois, manter referência à ficha principal e marcar a duplicada como descartada por duplicidade, sem apagar seu histórico. Contar somente a principal nos indicadores.
