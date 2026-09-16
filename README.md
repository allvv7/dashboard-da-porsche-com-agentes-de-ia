# Dashboard da Porsche com Agentes de IA

[![DIO Challenge](https://img.shields.io/badge/DIO-Desafio%20Conclu%C3%ADdo-00d2df?style=for-the-badge&logo=rocket)](https://dio.me)
[![Tech Stack](https://img.shields.io/badge/AI%20Agents-Gemini%20Spark%20%7C%20Antigravity-d5001c?style=for-the-badge)](https://deepmind.google)
[![Design](https://img.shields.io/badge/Design-Porsche%20Luxury%20Glass-c5a059?style=for-the-badge)](https://porsche.com)
[![Security](https://img.shields.io/badge/Security-Audit%20Passed%20%26%20CSP%20Active-10b981?style=for-the-badge)](docs/SECURITY_AUDIT.md)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-success?style=for-the-badge&logo=github)](https://allvv7.github.io/dashboard-da-porsche-com-agentes-de-ia/)

> 🌐 **Acesse a Demonstração Online no GitHub Pages:** [https://allvv7.github.io/dashboard-da-porsche-com-agentes-de-ia/](https://allvv7.github.io/dashboard-da-porsche-com-agentes-de-ia/)  
> 🔗 **Repositório Oficial no GitHub:** [https://github.com/allvv7/dashboard-da-porsche-com-agentes-de-ia](https://github.com/allvv7/dashboard-da-porsche-com-agentes-de-ia)

Este projeto foi desenvolvido como entrega de excelência para a formação da **DIO (Digital Innovation One)** no desafio **"Criando uma Dashboard da Porsche com Agentes de IA"**, com foco na construção de aplicações analíticas interativas de alta fidelidade fora dos limites convencionais de softwares de BI (*out-of-bounds*).

Utilizando o poder combinado do **Google Gemini Spark** (para raciocínio analítico, sanitização de dados e engenharia de software) e do **Google Antigravity** (como harness de execução, automação de testes e deploy), foi concebido um **Cockpit Executivo de Alto Luxo** inspirado no padrão estético oficial da Porsche.

---

## ✨ Destaques & Recursos da Experiência

1. **Estética de Alto Luxo (Porsche Design Language)**:
   - Paleta exclusiva: *Preto Ônix Profundo*, *Titânio Escovado*, *Vermelho Carmine Porsche* e detalhes em *Ouro Champanhe*.
   - Efeitos de *glassmorphism* com reflexos de luz e profundidade (*backdrop-filter*).
   - Tipografia nobre: Harmonização entre *Cinzel* (elegância clássica) e *Plus Jakarta Sans* (legibilidade técnica).
2. **Hero Cinematográfico com Vídeo HD**:
   - Vídeo em alta definição capturando dois Porsche 911 Targa em condução esportiva por drone FPV, com controles de reprodução e transições fluidas.
3. **Sonorização Ambiente com Web Audio API**:
   - Sintetizador de áudio ambiente simulando o ronco clássico do motor boxer de 6 cilindros Porsche (100% nativo, sem arquivos externos ou latência de rede).
4. **Vitrine Interativa de Modelos (*Showcase Gallery*)**:
   - Destaque para ícones como *911 Turbo S*, *911 GT3 RS*, *Taycan Turbo S*, *Cayenne Turbo GT* e *Macan Electric*, com especificações técnicas e filtro com 1 clique.
5. **Auditoria de Segurança Rigorosa**:
   - Proteção completa contra XSS via `escapeHTML()`, meta tag de Content Security Policy (CSP) ativa e exportadores seguros para CSV, JSON e PDF.

---

## 📊 Principais Indicadores Auditados (Base Oficial DIO)

A base de dados oficial sanitizada contém **100 transações comerciais** de veículos Porsche:

- **Faturamento Total:** `$12,827,800.50` (USD 12.82 milhões)
- **Volume Comercial:** `100 veículos`
- **Ticket Médio:** `$128,278.00`
- **Modelos com Maior Volume:** *Cayenne Coupe*, *Taycan 4S*, *Cayenne E-Hybrid*, *Panamera* e *Macan Electric*.
- **Ano-Modelo Dominante:** *2024* (29% das vendas), seguido por 2023 (19%) e 2022/2025 (16% cada).
- **Meios de Pagamento Líderes:** *Wire Transfer* (26%) e *Credit Card* (15%).
- **Taxa de Sucesso Logístico:** Mais de 41% já entregues (*Delivered*) e menos de 7% de cancelamentos.

---

## 🎯 Respostas Estratégicas às Perguntas Centrais (DIO)

### 📌 1. Quais os principais modelos vendidos por cidade e região?
Grandes centros executivos como **Atlanta, Seattle, Boston e Los Angeles** concentram a maior fatia financeira, impulsionando modelos topo de linha como **Cayenne Coupe**, **911 Turbo S** e **Taycan 4S**.

### 📌 2. Qual o ano de modelo (Model Year) com maior demanda?
O ano-modelo **2024 lidera amplamente** (~29% da base), demonstrando alta preferência dos clientes por veículos de lançamento e frotas recém-atualizadas.

### 📌 3. Qual a concentração por estado e meios de pagamento?
A praça do **Texas (TX)**, **Califórnia (CA)** e **Flórida (FL)** lideram o volume geográfico. Nas formas de liquidação, **Wire Transfer** e **Credit Card** somam mais de 41% de todas as vendas.

---

## 📁 Estrutura de Arquivos do Projeto

```
dio-porsche-sales-intelligence/
├── index.html                     # Dashboard de Alto Luxo (All-in-One, GitHub Pages Ready)
├── README.md                      # Documentação executiva completa do projeto
├── .gitignore                     # Configuração de arquivos ignorados no Git
├── data/
│   ├── porsche_sales_original.xlsx # Planilha original fornecida no desafio DIO
│   └── porsche_sales_sanitized.json # Base de 100 transações sanitizadas em JSON
└── docs/
    ├── ARCHITECTURE.md            # Arquitetura dos Agentes (Gemini Spark + Antigravity)
    └── SECURITY_AUDIT.md          # Relatório de auditoria de segurança e testes
```

---

## 🛠️ Como Executar e Publicar

### Opção 1: Execução Local Imediata
1. Dê um duplo clique no arquivo `index.html` para abri-lo em qualquer navegador moderno (Chrome, Edge, Firefox, Safari).
2. O dashboard é 100% funcional offline para visualização, filtros, gráficos e exportações!

### Opção 2: Publicação no GitHub Pages
1. Crie um repositório no seu GitHub chamado `dashboard-porsche-sales`.
2. Execute no terminal da pasta do projeto:
   ```bash
   git init
   git add .
   git commit -m "feat: dashboard executivo porsche de alto luxo com agentes de IA"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/dashboard-porsche-sales.git
   git push -u origin main
   ```
3. No GitHub, acesse **Settings** > **Pages**.
4. Em **Branch**, selecione `main` e pasta `/ (root)`, clicando em **Save**.
5. Em instantes o link estará público: `https://SEU_USUARIO.github.io/dashboard-porsche-sales/`

---

## 👨‍💻 Autor & Créditos

- **Projeto:** Desafio da Formação DIO — *Criando um Dashboard da Porsche com Agentes de IA*.
- **Aluno / Desenvolvedor:** Desenvolvido em parceria com agentes inteligentes.
- **Ecossistema:** Google Gemini Spark & Google Antigravity.
- **Licença:** MIT.
