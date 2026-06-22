<!--
=============================================================================
 TEMPLATE DE TICKET — método "sessão descartável, contexto no arquivo"
 Inspirado no fluxo de tickets do Caio (laudite/iqpay). Adaptado para LiteTI.
=============================================================================

COMO USAR (passo a passo)

 1. Para cada tarefa, crie uma PASTA (não uma conversa):
        .tickets/ACTIVE/<ID>/        ex: .tickets/ACTIVE/LGPD-001/
    e copie este arquivo para dentro dela como TICKET.md.
    (Atalho: `ticket new "título"` — ver .tickets/README.md)

 2. Trabalhe SEMPRE escrevendo no arquivo, não só no chat.
    O chat é rascunho; este arquivo é a verdade que sobrevive à sessão.

 3. Antes de fechar o Claude (ou quando travar), ATUALIZE o bloco
    "▶ RESUME HERE" no topo. Ele é a carta que esta sessão escreve para a
    PRÓXIMA — que pode ser amanhã, ou uma sessão nova qualquer.
    Numa nova sessão é só apontar: "continue o <ID>, leia o TICKET.md".

 4. Mova a pasta entre os status conforme avança e atualize o TRACKER.md:
        ACTIVE/ -> BLOCKED/ -> DONE/ -> CLOSED/   (e BACKLOG/ pro que não começou)

 5. Regra de ouro: se você não conseguiria recomeçar do zero lendo só este
    arquivo, então falta contexto nele. Escreva mais.

 Por que isso funciona: o contexto durável vive em arquivos versionados, não na
 sessão. Ninguém precisa "achar aquela conversa" — qualquer sessão reconstrói
 tudo lendo a pasta. Economiza token e preserva aprendizado.
=============================================================================
-->

# <ID> — <título curto da tarefa>

**Status:** ACTIVE · **Aberto em:** <AAAA-MM-DD> · **Tipo:** tarefa / aprendizado / bug
**Projeto LGPD:** <https://lgpd.liteti.com.br/projetos/NN  ·  WorkItem #__ — preencher quando criado>
**Mentoria:** pontos para discutir com o Caio marcados com 🎓

---

## ▶ RESUME HERE (próxima sessão)
<!--
 A PARTE MAIS IMPORTANTE. Mantenha sempre atualizada e no TOPO.
 Em 30 segundos, uma sessão nova tem que saber: onde estou, o que já fiz,
 qual é o PRÓXIMO passo concreto, e qualquer armadilha pra não repetir.
-->

- **Onde estou:** <ex: fase 2 de 4 — testando localmente, nada em produção>
- **Estado seguro?** <ex: sim, nada destrutivo feito; serviço só na porta de teste>
- **Próximo passo concreto (faça isto primeiro):**
  1. <passo 1>
  2. <passo 2>
- **Não esqueça / armadilhas:** <ex: precisa de VPN; rodar só de madrugada; X já falhou por causa de Y>

---

## 1. Objetivo
<!-- O que se quer ao final, em 1-3 linhas. Qual o "pronto"? -->



## 2. Contexto
<!-- Onde isso roda, quais sistemas/pastas/repos envolvidos, links úteis.
     Anote IDs, IPs, nomes de recurso — tudo que você não quer re-descobrir. -->



## 3. Investigação / o que fui descobrindo
<!-- Diário do trabalho: escreva enquanto faz, não depois.
     Comandos que rodou, o que retornaram, hipóteses, becos sem saída.
     Beco sem saída documentado também é aprendizado — não apague. -->

- [<AAAA-MM-DD HH:MM>] <descoberta / comando / resultado>



## 4. Plano (fases)
<!-- Quebre em fases pequenas e marque o progresso. Facilita o RESUME HERE. -->

- [ ] Fase 1 — <...>
- [ ] Fase 2 — <...>
- [ ] Fase 3 — <...>



## 5. Causa-raiz / Resolução
<!-- Preencher quando concluir. POR QUE acontecia (não só o sintoma) e
     COMO foi resolvido. É isto que vira estudo de caso / memória depois. -->



## 6. Critérios de aceite (como sei que terminou)
<!-- Lista verificável. Marque cada item testado de fato. -->

- [ ] <ex: serviço responde no endpoint X>
- [ ] <ex: caso de erro Y é tratado>



## 7. Follow-ups / dúvidas para a mentoria
<!-- O que ficou pra depois e o que levar pro Caio. -->

- 🎓 <dúvida ou tema para discutir>
- [ ] <follow-up técnico tracked>


<!--
 LEMBRETES DO MÉTODO (não apague — servem de checklist):
 • Sessão é descartável; o arquivo é a memória.
 • Atualizou algo importante? -> atualize o "▶ RESUME HERE".
 • Pediram um relatório? -> escreva em REPORT.md nesta pasta, não no chat.
 • Mudou de status? -> mova a pasta E atualize o TRACKER.md no mesmo passo.
 • Concluiu com causa-raiz? -> sincronize o WorkItem no projeto LGPD.
 • Travou +30 min? -> documente o que tentou aqui e pergunte ao Caio.
-->
