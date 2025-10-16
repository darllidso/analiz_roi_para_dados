# Analiz — ROI em Dados

Site estático do estúdio **Analiz**, com foco em **ROI em Ciência de Dados**.  
Inclui conceitos baseados em estudo próprio (com base DataCamp), um **simulador simples de ROI**, e acesso a um **agente de IA** para dúvidas sobre ROI.

---

## 🌐 Deploy

- **GitHub Pages**: ative em `Settings → Pages → Deploy from a branch (main /root)`.
- A página inicial é `index.html`.  
- A página de conhecimento é `conhecimento.html`.

---

## ✨ Funcionalidades

- **Home** com apresentação da Analiz e CTA.
- **Página de Conhecimento** com:
  - Conceitos (origem, história, fórmula, exemplo).
  - Link para **NotebookLM** com materiais do estúdio.
  - **Simulador de ROI** (modo simples) com KPIs e faixas de interpretação.
  - **IA (Agente)**: chat externo com a Analiz (ChatGPT).

---

## 📁 Estrutura

```
/ (raiz)
├─ index.html               # Página inicial
├─ conhecimento.html        # Conteúdo de ROI, simulador e IA
├─ assets/                  # Imagens e mídias (ex.: analiz.png)
└─ README.md
```

> Dica: mantenha os caminhos relativos (`assets/...`) para funcionar no GitHub Pages.

---

## 🧪 Simulador de ROI

Preencha:
- **Custos** (dev, treinamento, infra, outros)  
- **Benefício líquido** (receita adicional + custos evitados + economia de tempo − custos operacionais)

O painel mostra:
- **Custo total**, **Benefício líquido** e **ROI (%)**
- Selo: `Negativo`, `Baixo`, `Bom`, `Excelente`

> Valores são interpretativos e servem para **exploração**.

---

## 🤖 Agente de IA (ROI)

- Botão “**Abrir Chat com Analiz**” abre um modal com link para o agente no ChatGPT:
  - `https://chatgpt.com/g/g-68f1401d11748191bc3bd0512a15f29d-data-science-roi`
- Sugestões de perguntas:
  - “Meu projeto é X, custo Y, benefício Z. Qual o ROI?”
  - “Como transformar economia de tempo em valor financeiro?”

---

## 📓 NotebookLM

- Link na aba “NotebookLM” (abre em nova aba).

---

## 🖌️ Cores e Fonte

- Paleta principal: `#EC0000`, `#333333`, `#6D6D6D`, `#C2C2C2`, `#F0F0F0`  
- Fonte: **Poppins** (Google Fonts)  
> Para ajustar, edite as variáveis CSS em `:root` nos arquivos HTML.

---

## 📚 Fontes & Créditos

- Base de estudo: [Data Science ROI — DataCamp](https://www.datacamp.com/pt/blog/data-science-roi)  
- Conteúdo estudado e desenvolvido por **Darlliane**.  
- Personagem **Analiz**: mascote do estúdio.

---
