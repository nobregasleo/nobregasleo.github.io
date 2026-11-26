# ⚡ Roteiro OpenBot: Operação no QG & Automação Web
**Por Leonardo Nóbrega | Aula Ao Vivo Agentes S.A.**

---

## 1. O Papel do OpenBot na Esteira
Enquanto o **Google Antigravity** cria e estrutura os arquivos locais (`.md`, tokens CSS, HTML, peças visuais), o **OpenBot** atua como o **QG operacional** do time:
- Reúne os **6 agentes** em um único canal (`🏢 QG Agentes S.A. — Geral`).
- Mantém o **Gerente Geral** como líder (`leadAgentId`), delegando tarefas reais aos 5 especialistas.
- Executa ações externas via ferramentas locais ou navegador (publicação no LinkedIn, disparo de e-mail via API/SMTP, notificações no WhatsApp).

---

## 2. Boas Práticas de Segurança e Governança
1. **Escopo Fechado por Agente:** Nunca peça para um único agente escrever copy, desenhar layout, programar página e publicar. Cada especialista tem um único manual (`.md`).
2. **Credenciais Fora dos Prompts:** Chaves de API (Brevo, LinkedIn, etc.) devem ficar em variáveis de ambiente locais (`.env`), nunca dentro do texto da skill.
3. **Trava Inviolável no Gate 2 (HITL):** O **Agente Publicador** é programado para recusar qualquer disparo ou agendamento sem a frase explícita `"Gate 2 Aprovado"` do humano responsável.

---

## 3. Comandos Rápidos no Canal QG
- **Iniciar campanha:** Cole o `Prompt_02_Briefing_Tatico_Campanha.md` preenchido com sua oferta.
- **Destravar produção:** Responda com o `Prompt_03_Aprovacao_Gate1_e_Ondas.md`.
- **Autorizar publicação real:** Responda com o `Prompt_04_Aprovacao_Gate2_e_Disparo.md`.
- **Corrigir estilo permanentemente:** Use o `Prompt_06_Aprendizado_Delta_Diff.md` e salve a regra em `06_Historico_Delta_Diff_Regras_Aprendidas.md`.
