# Exercício CEIA — Case Nivaldo (Scale IA)

> Documento de organização das informações do exercício.
> **Entrega:** nossa *sugestão de pipelines*. (Não é resolver o problema — é propor as pipelines.)

---

## 1. O negócio do Nivaldo

Mini hortifrúti de esquina.

- **Abastecimento:** vai ao CEASA às **4h da manhã**, **3x por semana — segunda, quarta e sexta**.
- **Precificação:** usa o **preço de compra do CEASA como base** e ajusta o **preço de venda** em cima disso (repassa a variação do custo).
- **Controle financeiro:** faz **tudo no olho** — calcula o total de grana do dia e o caixa (gaveta de dinheiro) de cabeça, sem sistema/registro.

### Clientes — 2 tipos
1. **Transeuntes** — quem passa na rua e compra na hora.
2. **Grupo de WhatsApp (~200 pessoas)** — recebe fotos das frutas e ofertas.

### Rotina diária — "religiosamente todo dia às 08:30" (slide `slides/01-rotina-diaria-0830.jpeg`)
1. Tira da prateleira as frutas que **passaram do ponto** e coloca num **caixote descartável**.
2. Tira **foto das prateleiras** e manda no **grupo do WhatsApp**.

### Gestão de perecível / oferta de urgência (slide)
Quando percebe que a fruta **vai perder** mas **NÃO** irá ao CEASA no dia seguinte,
ele manda uma **oferta** pra quem **normalmente compra aquela fruta**.
- Exemplo real do slide: *"🍌 URGENTE! Banana nanica R$2,99 o KG. Tá barato, em, madurinha 😋"* (editada 03:33)

---

## 2. O desafio (o que os varejistas pagariam por)

> "Não só o Nivaldo, mas outros pequenos varejistas estão dispostos a pagar vocês se entregarem essas 2 coisas:"

**Entregável 1 — Atendimento automático no WhatsApp**
Responder o cliente automaticamente (**do jeitinho que o varejista responde**) sobre a
**disponibilidade** de uma fruta TAL, sempre que o cliente perguntar no WhatsApp sobre aquela fruta.

**Entregável 2 — Previsão de "passar do ponto"**
Saber a **probabilidade de uma fruta passar do ponto ANTES da próxima ida ao CEASA**,
para automaticamente mandar **oferta** pra clientes do varejista **sempre que for o caso**.

*(Obs. do calendário D-S-T-Q-Q-S-S no slide: a janela de risco depende de quando é a próxima ida ao CEASA.)*

---

## 2b. Regras do exercício (mecânica da atividade)

- 1 pessoa por startup; juntam-se em **trios de startups**.
- Em **3 horas**, discutem juntos como resolver as **2 dores** da MPE do Seu Nivaldo (podem trocar conhecimento sobre técnicas).
- **Cada um** do trio cria um **diagrama INDIVIDUAL** da solução.
- O diagrama deve representar a **pipeline de processamento de dados, realista e de alto nível**, que **viabilize** a automação que o Nivaldo tá disposto a pagar.
- **Cada etapa do diagrama deve ser o nome de uma técnica** de análise / pré-processamento de dados, antes de chegar nas etapas dos módulos "inteligentes".
- Nos últimos **20 minutos**, elegem o **melhor** do trio (não pode votar em si mesmo).
- **Entrega/submissão via:** `appscaleia.sebraestartups.com.br`
- **Fonte oficial (Google Doc):** https://docs.google.com/document/d/1UTiYbSXEWyT5WVDT5wioosyg3FLM780lygn15xJaeu0

## 2c. ⚠️ Restrições da Casa (constraints duras — filtro do desenho)

1. O Nivaldo **não quer PDV (Ponto de Vendas) nem planilha** — ele não sabe mexer.
2. Você **perde a venda** se disser *"primeiro vamos coletar dados por X meses"* → ou você **coleta ENQUANTO soluciona** alguma dor, ou **NEM COLETE**.
3. O Nivaldo **proibiu** que adicionem pra ele qualquer obrigação que exija **> +3 min do dia dele**.

---

## 3. Nossa entrega: 3 pipelines principais

> A entrega do exercício é a **sugestão dessas pipelines**.

### Pipeline 1 — Coleta de informação
*(a detalhar)*

### Pipeline 2 — Treinamento do modelo
*(a detalhar)*

### Pipeline 3 — Inferência do modelo
*(a detalhar)*

---

## Pendências / a preencher
- Detalhar cada uma das 3 pipelines.
- (adicionar conforme o exercício avança)
