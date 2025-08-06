# 📊 Relatório Final: Análise de Churn de Clientes

### Desafio TelecomX - Escola de Dados Alura (Parte 1)

---

## 🎯 Sobre o Projeto
O objetivo deste desafio foi analisar uma base de dados de uma empresa de telecomunicações para entender os motivos que levam os clientes a cancelarem seus serviços (fenômeno conhecido como **Churn**). A partir da análise, buscamos identificar padrões e perfis de clientes para, então, propor ações que ajudem a reduzir essa taxa de evasão.

---

## 🛠️ O Que Foi Feito? (Passo a Passo)

De forma simples, o trabalho seguiu um roteiro claro de análise de dados:

1.  **Organização da Bagunça:** Os dados iniciais estavam em um formato `JSON` complexo. A primeira etapa foi "arrumar a casa", limpando, organizando e corrigindo colunas que não estavam em formato numérico.

2.  **Padronização:** As colunas foram renomeadas para o português e valores como "Sim" e "Não" foram transformados em `1` e `0` para facilitar os cálculos.

3.  **Investigação com Gráficos:** Com os dados limpos, foram criados diversos gráficos para encontrar pistas. Buscamos responder perguntas como: "Clientes com contrato mensal cancelam mais?" ou "O valor da fatura influencia no cancelamento?".

4.  **Geração de Conclusões:** As respostas encontradas nos gráficos foram resumidas em conclusões claras sobre o que leva um cliente a deixar a empresa.

---

## 💡 Principais Descobertas

A análise visual dos dados revelou três fatores principais que influenciam o churn:

* 契約書 **Tipo de Contrato:** Clientes com **contratos mensais** são, de longe, os que mais cancelam. A falta de um compromisso de longo prazo aumenta o risco.

* ⏳ **Tempo de Casa:** Clientes **novos (com poucos meses de contrato)** têm uma probabilidade muito maior de sair. O início da jornada do cliente é um momento crítico.

* 💰 **Valor da Fatura:** Contas com **faturamento mensal mais alto** estão mais associadas ao churn, o que pode indicar que os clientes não estão vendo valor suficiente para justificar o custo.

---

## 🚀 Recomendações Estratégicas

Baseado nas descobertas, algumas ações podem ser tomadas pela empresa:

1.  **Incentivar Contratos Longos:** Oferecer descontos ou benefícios para clientes de planos mensais migrarem para contratos de 1 ou 2 anos.
2.  **Cuidar dos Novos Clientes:** Criar um programa de boas-vindas e acompanhamento nos primeiros 3 meses para garantir que o cliente entenda e use os benefícios do seu plano.
3.  **Agregar Valor aos Planos Caros:** Para os clientes com faturas mais altas, oferecer serviços extras ou um atendimento diferenciado para justificar o investimento e aumentar a satisfação.

---

_Relatório elaborado por: **Lucas Frigato**_
