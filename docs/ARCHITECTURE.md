# Arquitetura de Agentes de IA: Gemini Spark + Google Antigravity

Este documento detalha os princípios arquiteturais, o fluxo de raciocínio analítico e a divisão de papéis no desenvolvimento do **Porsche Sales Intelligence**, superando as limitações de ferramentas tradicionais de Business Intelligence (Power BI, Tableau e Excel).

---

## 🏛️ Visão Geral da Arquitetura (*Agent-First*)

A abordagem *Out-of-Bounds* substitui dependências de softwares proprietários ou licenças corporativas pesadas por um ecossistema autônomo baseado em Inteligência Artificial, gerando aplicações web puras, ultra-rápidas e auto-contidas.

```
+-------------------------------------------------------------------------+
|                        1. GOOGLE GEMINI SPARK                           |
|   - Leitura direta da base original (XLSX com ruídos e anomalias)       |
|   - Raciocínio analítico e formulação das respostas de negócio DIO      |
|   - Sanitização de campos inconsistentes (Datas, Preços, Tipos)         |
|   - Síntese de código com padrões defensivos e design de alto luxo      |
+------------------------------------+------------------------------------+
                                     |
                                     v
+------------------------------------+------------------------------------+
|                      2. GOOGLE ANTIGRAVITY                              |
|   - Harness e Ambiente de Execução Local Multi-Ferramentas              |
|   - Execução de scripts de auditoria de segurança (XSS, CSP, DOM)       |
|   - Automação de versionamento Git e publicação no GitHub Pages         |
|   - Garantia de integridade determinística e testes de renderização     |
+------------------------------------+------------------------------------+
                                     |
                                     v
+-------------------------------------------------------------------------+
|                        3. PORSCHE LUXURY COCKPIT                        |
|   - index.html (Artefato auto-contido: HTML5, CSS3 Glassmorphic, JS)   |
|   - Vídeo cinematográfico de alta definição (Porsche 911 Targa FPV)    |
|   - Síntese de áudio ambiente via Web Audio API (ronco Boxer)          |
|   - Gráficos reativos Chart.js com gradientes metálicos e glow         |
|   - Terminal de transações com busca em tempo real, ordenação e CSV/JSON|
+-------------------------------------------------------------------------+
```

---

## 🧠 1. O Papel do Gemini Spark

### A. Sanitização e Higienização de Dados
A base de dados original de concessionárias costuma conter ruídos operacionais:
- **Datas inconsistentes**: Registros com marcações fora do calendário gregoriano tratados com regras de sanitização defensiva.
- **Tipagem de Preço**: Tratamento rigoroso de valores numéricos para cálculo exato de faturamento ($12.827.800,50) e ticket médio ($128.278,00).
- **Padronização de Modelos**: Unificação de nomenclaturas como *Cayenne Coupe*, *Taycan 4S*, *911 Turbo S*, etc.

O **Gemini Spark** analisou a planilha, aplicou regras de higienização e extraiu a base sanitizada (`data/porsche_sales_sanitized.json`) com 100% de consistência.

### B. Resolução das Perguntas Centrais de Negócio (DIO)
1. **Quais os principais modelos vendidos por praça geográfica?** Identificação de cidades polo como Atlanta, Seattle, Boston e San Diego com concentração de modelos topo de linha (*Cayenne Coupe*, *911 Turbo S* e *Taycan 4S*).
2. **Qual o ano de modelo (Model Year) dominante?** Constatação de que 2024 lidera com 29% das aquisições, demonstrando forte apetite por veículos de lançamento.
3. **Qual a distribuição de pagamentos e eficiência logística?** Mapeamento de Wire Transfer (26%) e Credit Card (15%) como líderes de liquidação, com mais de 41% dos veículos já entregues e menos de 7% de cancelamentos.

---

## ⚡ 2. O Papel do Google Antigravity

O **Google Antigravity** atua como o ambiente de orquestração avançada:
- **Execução e Testes**: Valida o código em tempo real via comandos de terminal (Node.js, PowerShell), verificando se não há erros de sintaxe ou vazamento de memória nos gráficos.
- **Auditoria de Segurança Automatizada**: Varre o código em busca de vulnerabilidades (XSS em manipulações de DOM, injeções em buscas e ausência de headers).
- **Deploy & Publicação**: Gerencia a criação do repositório Git, commits estruturados e suporte imediato ao GitHub Pages.

---

## 💎 3. Princípios de Design de Alto Luxo (Porsche Experience)

- **Dark Mode Profundo**: Preto Ônix (`#060709`), Titânio Escovado (`#12151f`) e reflexos de Ouro Champanhe (`#c5a059`).
- **Glassmorphism Specular**: Bordas translúcidas ultrafinas com `backdrop-filter: blur(20px)`.
- **Tipografia Nobre**: Harmonização de *Cinzel* (elegância clássica e numerais monumentais) com *Plus Jakarta Sans* (legibilidade técnica).
- **Multimídia Imersiva**: Vídeo de drone FPV em alta definição e sonorização ambiente gerada via osciladores puros da Web Audio API (zero dependências externas).
