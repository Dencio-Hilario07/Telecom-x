# Telecom-x
# 📊 Análise de Churn — Telecom X

## 🧾 Introdução

A evasão de clientes (churn) é um dos principais desafios enfrentados por empresas de telecomunicações. Em um mercado altamente competitivo, reter clientes é mais estratégico — e econômico — do que adquirir novos.

Este relatório apresenta uma análise exploratória (EDA) detalhada sobre os principais fatores que impactam o churn na Telecom X. Com base nos dados, são propostas ações práticas e direcionadas para reduzir a saída de clientes e melhorar os indicadores de fidelização.

---

## 1️⃣ Panorama Geral do Churn

![Rotatividade dos clientes](./imagens/Rotatividade dos clirentes.png)

> ❗ A cada 4 clientes, 1 deixa a empresa — um sinal crítico para a área de gestão de clientes.

---

## 2️⃣ Impacto do Tipo de Contrato
### Distribuição e Análise por Gênero

A imagem à esquerda mostra a distribuição percentual de churn, enquanto a da direita detalha a taxa por gênero:

<p align="center">
  <img src="https://github.com/user-attachments/assets/55ac115e-cca3-47d0-83db-5c50310cc366" width="45%" alt="Distribuição de Churn" />
  <img src="https://github.com/user-attachments/assets/39b5dfac-cbb3-4bac-88f9-61b8833fe2b7" width="50%" alt="Análise por Gênero" />
</p>



| Tipo de Contrato   | % da Base | Churn (%) |
|--------------------|-----------|-----------|
| Month-to-Month     | 55,1%     | 42,7%     |
| Anual              | 20,9%     | 11,3%     |
| Bienal             | 24,0%     | 2,8%      |

**📌 Insights:**
- Contratos mensais concentram a maioria da base e têm a maior taxa de churn.
- Contratos anuais e bienais retêm melhor os clientes, especialmente o bienal.

**✅ Recomendações:**
- Criar promoções agressivas para migração para contratos mais longos.
- Incluir benefícios reais: descontos progressivos, upgrades, bônus exclusivos.

---

## 3️⃣ Análise por Método de Pagamento
<img width="989" height="590" alt="Image" src="https://github.com/user-attachments/assets/322baf5b-e914-421b-bfb2-8ff06e75f40b" />

**📌 Insights:**
- Cheque eletrônico está associado às maiores taxas de churn.
- Métodos automáticos são mais seguros e promovem maior retenção.

**✅ Recomendações:**
- Incentivar a troca para métodos automáticos com descontos ou bônus.
- Melhorar a comunicação sobre as vantagens práticas (menos falhas e atrasos).

---

## 4️⃣ Distribuição de Cobranças (`account.Charges.Total`)

<img width="715" height="402" alt="Image" src="https://github.com/user-attachments/assets/563aae15-36e9-4853-9fd9-feb8860c4b72" />

- Clientes churners possuem **padrões distintos** de cobrança.
- Há presença de **outliers**, indicando possíveis erros, cobranças excessivas ou disputas mal resolvidas.

**✅ Ações:**
- Investigar casos fora do padrão e atuar nos pontos críticos de insatisfação.
- Ajustar o processo de cobrança para evitar surpresas ao cliente.

---

## 5️⃣ Ações Prioritárias

### 🎯 1. Contratos Longos
- Ofertas exclusivas para contratos anuais e bienais.
- Programa de fidelidade com recompensas claras.

### 💳 2. Migração para Pagamentos Automáticos
- Lembretes automáticos e onboarding simples para migrar métodos.
- Descontos na primeira fatura automática.

### 🔍 3. Monitoramento Proativo
- Sistema de alerta para perfis de alto risco (ex.: contratos mensais com uso intenso de suporte).
- Intervenções antecipadas com ofertas personalizadas.

---

## ✅ Conclusão

O churn da Telecom X é altamente concentrado entre clientes com:
- Contratos mensais (`month-to-month`)
- Pagamentos manuais (`electronic check`)

Ações segmentadas nesses públicos, com campanhas de migração e fidelização bem estruturadas, têm **alto potencial de impacto** na redução do churn e no aumento do valor do ciclo de vida do cliente.

---

## 🚀 Próximos Passos (Sugeridos)

- [ ] Criar dashboard interativo com KPIs de churn em tempo real.
- [ ] Desenvolver modelo preditivo de churn (machine learning).
- [ ] Automatizar campanhas de retenção com base em perfis de risco.

---
