# 🏭 Guia de Preparação da Bancada — Agentes S.A.
**Por Leonardo Nóbrega | Aula Ao Vivo**

Este guia resume a arquitetura completa apresentada na aula ao vivo para você montar, personalizar e operar seu time de **6 agentes de IA** na sua empresa ou agência — sem precisar programar.

---

## 🧰 A Fórmula dos Agentes (Slide 04)
> **`LLM (Motor de Raciocínio)` + `Skills (.md)` + `Tools & Conexões (MCP/OpenBot)` = Agente de IA Pronto para Trabalhar**

1. **Google Antigravity (Criação & Arquitetura):** Lê as pastas da marca, aplica o aprendizado de estilo e configura os agentes já com o Brand DNA embarcado.
2. **OpenBot (Operação & Execução):** O QG onde os **6 agentes** ficam ativos no canal `🏢 QG Agentes S.A. — Geral`, conversam entre si e executam entregas reais.

---

## 🧱 A Arquitetura das 2 Camadas (Slide 08)

* **Camada 1 — DNA da Marca (Permanente):** Pasta local com tom de voz, lista negra de palavras, paleta HEX, tipografia, logos e referências aprovadas. Você preenche **uma única vez**.
  * *Empresa própria (In-House):* 1 pasta fixa da marca.
  * *Agência:* 1 pasta por cliente dentro de `/Clientes/[Nome_do_Cliente]/`.
* **Camada 2 — Briefing Tático do Dia:** No dia a dia, você não sobe manual de marca no chat. Envia apenas a oferta, conceito e peças da campanha para o **Gerente Geral**.

---

## 🚀 Passo a Passo da Bancada (3 Passos)

### Passo 1: Baixe e Preencha a Pasta Modelo (`01_Pasta_Modelo_Brand_DNA`)
Substitua os campos `[PREENCHER: ...]` com os dados da sua marca (e adicione seu logo em `04_Logos_e_Assets/`).

### Passo 2: Importe os 6 Agentes no OpenBot (ou use as Skills `.md` no Antigravity)
No OpenBot:
1. Acesse **Server Settings → Import → Grok Bot**.
2. Selecione `openbot_agentes_sa_import_grokbot.zip`.
3. Os 6 agentes (**Gerente Geral, Redator, Designer, Web Designer, Videomaker e Publicador**) e o canal **`🏢 QG Agentes S.A. — Geral`** ficarão ativos na barra lateral.

### Passo 3: Rode sua Primeira Campanha com os 2 Gates HITL
1. Cole o **Prompt 01 (Onboarding)** para conectar os agentes à pasta da sua marca.
2. Cole o **Prompt 02 (Briefing Tático)** no chat do **Gerente Geral**.
3. Aprove o plano estratégico no **Gate 1**, acompanhe as **3 Ondas Fast-First** e dê o OK final no **Gate 2** antes de publicar!
