# ☕ Rota do Grão - High Performance Landing Page

> Projeto de Landing Page focado em alta conversão e performance extrema (Core Web Vitals), desenvolvido com HTML5 Semântico e CSS Puro (No-Framework).

<p align="center">
  <a href="https://landing-page-nine-opal-10.vercel.app/">
    <img src="https://img.shields.io/badge/Ver_Projeto_Online-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Ver na Vercel" />
  </a>
</p>

---

## 🚀 Status do Projeto

| Ambiente | URL Pública | Status |
| :--- | :--- | :--- |
| **Produção** | [**Acessar Landing Page**](https://landing-page-nine-opal-10.vercel.app/) | ✅ Online (Vercel) |

---


## ⚡ Relatório de Performance (Lighthouse / PageSpeed)

O projeto atingiu pontuação máxima em desempenho graças à estratégia de *Critical Rendering Path* otimizado.

| Métrica | Mobile 📱 | Desktop 💻 |
| :--- | :---: | :---: |
| **Desempenho** | **100** 🟢 | **100** 🟢 |
| **Acessibilidade** | **100** 🟢 | **100** 🟢 |
| **Práticas Rec.** | **100** 🟢 | **100** 🟢 |
| **SEO** | **90** 🟢 | **90** 🟢 |

---

## 🛠️ Estratégia de Desenvolvimento

### O Segredo do "100/100": CSS Drawing
Para esta Landing Page, evitamos o carregamento de imagens pesadas (LCP alto) na primeira dobra. Utilizamos uma estratégia de **CSS Drawing** para o elemento Hero.
* **A "Máquina de Café" não é uma imagem (PNG/JPG).**
* Ela é desenhada inteiramente via código (DIVs, Gradients e CSS Shadows).
* Isso garantiu um **LCP (Largest Contentful Paint) instantâneo**, eliminando o tempo de download de assets visuais críticos.

---

## 📈 Oportunidades de Otimização (Roadmap)

Embora a performance técnica esteja maximizada, identificamos pontos de melhoria para UX e Negócio:

### 1. Acessibilidade e SEO (Semântica)
As imagens de apoio (seções de benefícios e prova social) foram implementadas como `background-image` em DIVs para agilidade na prototipagem.
* **Ação Futura:** Converter para tags `<img>` ou `<picture>`.
* **Benefício:** Permitir o uso de atributos `alt` descritivos (leitura de tela para deficientes visuais) e indexação de imagens pelo Google Images.
* **Formato:** Utilizar WebP ou AVIF.

### 2. Conversão (Backend)
O formulário atual utiliza um JavaScript simples (`alert`) para simulação.
* **Ação Futura:** Integração com APIs como **Formspree** ou **ConvertKit**.
* **Benefício:** Captura real de leads e início de automação de e-mail marketing (Welcome Drip).

---

## 🧰 Stack & Ferramentas

* **HTML5 / CSS3:** Estrutura e Estilização (Vanilla).
* **Git / GitHub:** Versionamento e Hospedagem do código.
* **Vercel:** Deploy e Hospedagem (CDN Global).
* **PageSpeed Insights:** Validação de métricas Core Web Vitals.
* **Lightshot:** Documentação visual.

---
*Desenvolvido como parte da entrega acadêmica de Front-end & CRO.*

## 📂 Estrutura do Repositório

A organização dos arquivos neste projeto segue a estrutura abaixo:

```text
.
├── index.html               # Código fonte principal (Landing Page em arquivo único)
├── PageSpeed Insights/      # Pasta contendo os prints dos resultados de performance
└── README.md                # Este arquivo de documentação