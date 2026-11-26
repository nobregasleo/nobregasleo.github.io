# 📋 Checklist dos 5 Passos & Diagramas Oficiais — Agentes S.A.

> **Material de Apoio Pós-Aula | Por Leonardo Nóbrega**  
> Resumo executivo completo da metodologia, organograma dos 6 agentes e esteira Fast-First apresentados na aula ao vivo.

---

## ✅ OS 5 PASSOS PARA MONTAR E OPERAR SEU TIME DE AGENTES

### Passo 1 · Preparar a Bancada Gratuita (Antigravity + OpenBot)
- [ ] Instalar o **Google Antigravity** (cérebro que lê pastas locais, cria skills e treina agentes).
- [ ] Instalar o **OpenBot** (QG operacional onde os 6 agentes conversam e executam em grupo).
- [ ] Definir onde ficará a pasta raiz da operação no computador.

### Passo 2 · Montar a Camada 1 (Brand DNA Permanente da Marca)
- [ ] Baixar e duplicar a pasta `01_Pasta_Modelo_Brand_DNA/` (se for agência, criar `/Clientes/[Nome_do_Cliente]/`).
- [ ] Preencher `01_Brand_DNA_e_Tom_de_Voz.md` (tese central, traços de voz e **Lista Negra** de palavras proibidas).
- [ ] Preencher `02_Identidade_Visual_e_Design.md` + `04_Logos_e_Assets/tokens_marca.css` (HEX, fontes e logos `.svg`/`.png`).
- [ ] Preencher `03_Catalogo_e_Oferta_Campanha.md` (produtos reais, preços `de/por`, cupom e links para zero alucinação).

### Passo 3 · Calibrar com Machine Learning (Sem Código)
- [ ] **Aprendizado por Exemplos (Few-Shot):** Colocar prints de peças, páginas e textos reais aprovados em `05_Referencias_Conteudo/` (ou rodar o **Prompt 07**).
- [ ] **Aprendizado por Reforço (Delta-Diff):** Sempre que editar um rascunho da IA, rodar o **Prompt 06** comparando V1 vs. Versão Aprovada e salvar a regra em `06_Historico_Delta_Diff_Regras_Aprendidas.md`.

### Passo 4 · Ativar os 6 Agentes Especialistas (Onboarding com DNA Embarcado)
- [ ] Importar `openbot_agentes_sa_import_grokbot.zip` no OpenBot (*Server Settings → Import → Grok Bot*) ou carregar as 6 skills `.md` no Antigravity.
- [ ] Rodar o **Prompt 01 (Onboarding)** apontando a pasta da marca para injetar a Camada 1 na memória permanente dos 6 agentes.

### Passo 5 · Operar em 3 Ondas com os 2 Gates HITL (Você como Diretor)
- [ ] Enviar o **Prompt 02 (Briefing Tático — Camada 2)** ao **Gerente Geral**.
- [ ] **🛑 GATE 1:** Revisar o conceito, ângulos e entregáveis. Responder *"Aprovado"* para liberar a produção.
- [ ] Acompanhar as **3 Ondas Fast-First**:
  - **Onda 1:** Copywriting (3 Posts + 2 E-mails + Roteiro Reels)
  - **Onda 2:** Web & Ads (1 Landing Page + 3 Google Ads)
  - **Onda 3:** Feed & Vídeo (3 Criativos `1080×1350` + 1 Reels `9:16`)
- [ ] **🛑 GATE 2:** Revisar todas as 10 peças prontas e enviar o **Prompt 04** para liberar o **Publicador**.

---

## 🏛️ DIAGRAMA 1 · ORGANOGRAMA DO TIME (6 AGENTES)

```text
                    ┌───────────────────────────────────┐
                    │       👤 VOCÊ (DIRETOR / CEO)     │
                    │  Define o briefing e aprova Gates │
                    └─────────────────┬─────────────────┘
                                      │
                                      ▼
                    ┌───────────────────────────────────┐
                    │   👔 AGENTE 00 · GERENTE GERAL    │
                    │  Orquestrador & Guardião HITL     │
                    │  (Interface única no Canal QG)    │
                    └─────────────────┬─────────────────┘
                                      │
        ┌──────────────┬──────────────┼──────────────┬──────────────┐
        ▼              ▼              ▼              ▼              ▼
 ┌─────────────┐┌─────────────┐┌─────────────┐┌─────────────┐┌─────────────┐
 │ ✍️ Redator  ││ 🎨 Designer ││🌐 Web Des.  ││🎬 Videomaker││🚀 Publicador│
 │ Copywriting ││ Feed + Ads  ││Landing Page ││ Reels 9:16  ││Social+E-mail│
 └─────────────┘└─────────────┘└─────────────┘└─────────────┘└─────────────┘
```

---

## 🧱 DIAGRAMA 2 · ARQUITETURA DAS 2 CAMADAS

```text
  CAMADA 1 · MEMÓRIA FIXA (Preenche 1x)          CAMADA 2 · OPERAÇÃO DIÁRIA
 ┌──────────────────────────────────────┐       ┌───────────────────────────┐
 │ 📂 Pasta da Marca / Cliente          │       │ 🎯 Briefing Tático (5 min)│
 │ • Brand DNA & Lista Negra            │  ───▶ │ • Objetivo da campanha    │
 │ • Design Tokens & Logos SVG          │       │ • Oferta / Cupom / Prazo  │
 │ • Catálogo Real & Referências        │       │ • 10 peças solicitadas    │
 │ • Regras Delta-Diff Aprendidas       │       └───────────────────────────┘
 └──────────────────────────────────────┘
```

---

## ⚡ DIAGRAMA 3 · ESTEIRA FAST-FIRST (3 ONDAS + 2 GATES HITL)

```text
  [Briefing Camada 2]
          │
          ▼
  ┌────────────────────────────────────────────────────────┐
  │ 🛑 GATE 1 (HITL) — Você aprova Estratégia e Ângulos    │
  └───────────────────────────┬────────────────────────────┘
                              │ "Aprovado"
          ┌───────────────────┼───────────────────┐
          ▼                   ▼                   ▼
  [🌊 ONDA 1]         [🌊 ONDA 2]         [🌊 ONDA 3]
  Redator             Web Designer        Designer Social
  • 3 Posts           • 1 Landing Page    • 3 Feed 1080×1350
  • 2 E-mails         Designer Ads        Videomaker
  • 1 Roteiro Reels   • 3 Google Ads      • 1 Reels 9:16 MP4
          │                   │                   │
          └───────────────────┼───────────────────┘
                              ▼
  ┌────────────────────────────────────────────────────────┐
  │ 🛑 GATE 2 (HITL) — Revisão Final das 10 Peças Prontas  │
  └───────────────────────────┬────────────────────────────┘
                              │ "Gate 2 Aprovado"
                              ▼
  [🚀 PUBLICADOR] ➔ Publica na Rede Social + Dispara E-mail + Avisa CEO
```
