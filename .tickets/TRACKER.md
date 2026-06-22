# Tracker — Tickets de plane

Índice de uma linha por ticket **aberto**. A pasta de cada ticket é a fonte da verdade;
este arquivo é só o mapa rápido. Atualize no mesmo passo em que move uma pasta de status.

> **Método:** sessão é descartável, o contexto mora nos arquivos. Cada ticket é uma
> *pasta* (`ACTIVE/<ID>/TICKET.md`) com um bloco `▶ RESUME HERE` no topo, para qualquer
> sessão nova retomar lendo a pasta — sem depender de manter conversa aberta.
>
> **Prefixo de ID deste repo:** `PLANE`  ·  **Projeto LGPD:** (vincular projeto em https://lgpd.liteti.com.br/projetos)

---

## 🧹 Regra de limpeza (mantém este arquivo curto)

**Este tracker lista APENAS o que está em progresso ou pendente** — tickets em
`ACTIVE/`, `BLOCKED/` e `BACKLOG/`.

- Quando um ticket vai para **`DONE/`** ou **`CLOSED/`**, **remova a linha dele daqui.**
  A pasta continua existindo como registro histórico — nada se perde.
- Não acumule "concluídos" no tracker: o histórico é o conteúdo das pastas + o git log.
- Para revisitar tickets fechados (estudos de caso), abra as pastas `DONE/` e `CLOSED/`.

> Em resumo: o tracker responde "o que está aberto agora?", não "o que já fiz?".

---

## 🟡 ACTIVE (em andamento)
<!-- Uma linha: `- [<ID>](ACTIVE/<ID>/TICKET.md) — descrição curta · próximo passo` -->
- _(vazio)_

## 🔴 BLOCKED (esperando dependência/decisão)
<!-- Inclua o que/quem está bloqueando. -->
- _(vazio)_

## ⚪ BACKLOG (pendente, ainda não iniciado)
- _(vazio)_

---

## Convenções
- **ID:** `PLANE-NNN` (sequencial).
- **Status = pasta:** mover entre `ACTIVE/ BLOCKED/ DONE/ CLOSED/ BACKLOG/` reflete o estado.
- **Um commit** move a pasta **e** atualiza este arquivo, juntos.
- Tickets de trabalho real espelham num **WorkItem no projeto LGPD** correspondente.
