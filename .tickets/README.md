# .tickets — método "sessão descartável, contexto no arquivo"

Cada tarefa é uma **pasta** com um `TICKET.md`, não uma conversa. O contexto
durável vive aqui (versionado no git), então qualquer sessão nova retoma lendo a
pasta — economiza token e preserva aprendizado.

## Fluxo
1. `ticket new "título"`  → cria `ACTIVE/PLANE-NNN/TICKET.md`
2. Trabalhe escrevendo no `TICKET.md` (não só no chat). Mantenha o `▶ RESUME HERE` no topo atualizado.
3. `ticket move PLANE-NNN DONE`  → move a pasta. Atualize o `TRACKER.md` no mesmo passo.

## Arquivos
- `TRACKER.md` — índice de uma linha do que está **aberto** (some quando vai p/ DONE/CLOSED).
- `TICKET-TEMPLATE.md` — modelo copiado pelo `ticket new`.
- `PREFIX` / `LGPD_URL` — metadados lidos pelo CLI.

CLI: `~/.claude/ticket-system/ticket` (tenha no PATH como `ticket`).
