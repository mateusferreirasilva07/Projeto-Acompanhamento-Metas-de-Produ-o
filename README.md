# 📊 Dashboard de Acompanhamento de Metas de Produção 

Solução de Business Intelligence desenvolvida para unificar o acompanhamento estratégico da diretoria com a supervisão operacional do chão de fábrica, permitindo a gestão industrial baseada em dados em tempo real.

<br>

## 🎯 Sobre o Projeto
Este painel foi estruturado para resolver o desafio de acompanhar o atingimento de metas operacionais tanto em uma visão macro acumulada do ano quanto no detalhamento diário do mês. 

### 🌟 Principais Destaques:
- **Visão Anual (YTD) & Mensal (MTD):** Alternância rápida de contexto para avaliar tendências anuais ou o ritmo diário das operações.
- **Formatação Condicional Inteligente:** Identificação visual instantânea (Verde = Meta superada / Vermelho = Abaixo da meta).
- **Segmentação Multi-nível:** Filtros dinâmicos por *Máquina*, *Produto* e *Turno* que recalculam instantaneamente todos os indicadores.
- **UX & Interface Dark:** Tema focado em contraste, legibilidade rápida e navegação intuitiva.

<br>

---

## 1️⃣ Visão Anual de Metas (YTD)
Monitoramento macro do ritmo de produção anual contra metas projetadas.
- **KGauge Dinâmico (% Atingimento):** KPI em formato de medidor calculando o atingimento geral da meta.
- **Curva de Tendência YTD:** Gráfico de linha acumulada que compara em tempo real se a produção realizada está acompanhando o ritmo das metas mês a mês.
- **Análise Mensal (Produção vs Meta):** Barras com formatação condicional automática (Verde = Meta superada / Vermelho = Abaixo da meta).

<p align="center">
  <img src="https://raw.githubusercontent.com/mateusferreirasilva07/Projeto-Acompanhamento-Metas-de-Produ-o/0d4e62f0aebdef020a4469daadcab2a0b55dd9fc/Captura%20de%20tela%202026-08-06%20075205.png" alt="Visão Anual de Metas" width="100%">
</p>

<br>

---

## 2️⃣ Segmentação Dinâmica e Navegação Fluida
Detalhamento operacional direto na ponta para dar autonomia aos gestores e supervisores de turno.
- **Filtros Multi-Nível:** Segmentação rápida por máquina específica, tipo de produto fabricado e turno de trabalho (T1, T2, T3).
- **Recálculo Instantâneo:** Todos os KPIs reagem automaticamente à seleção dos filtros[cite: 5].
- **UX / Tooltip Guiado:** Botão com indicação direta (*"Clique para Visão Mensal"*) para mudar o contexto sem poluir a interface.

<p align="center">
  <img src="https://raw.githubusercontent.com/mateusferreirasilva07/Projeto-Acompanhamento-Metas-de-Produ-o/0d4e62f0aebdef020a4469daadcab2a0b55dd9fc/Captura%20de%20tela%202026-08-06%20075302.png" alt="Visão Anual de Metas" width="100%">
</p>
<br>

---

## 3️⃣ Visão Mensal e Acompanhamento Diário (MTD)
Monitoramento de chão de fábrica para identificação ágil de desvios e gargalos diários no mês vigente.
- **Visão Diária MTD:** Alternância do gráfico para analisar o volume fabricado dia a dia dentro do mês selecionado.
- **Identificação de Gargalos:** Destaca visualmente os dias em que a produção ficou abaixo da meta diária, permitindo rápida ação corretiva.

<p align="center">
  <img src="https://raw.githubusercontent.com/mateusferreirasilva07/Projeto-Acompanhamento-Metas-de-Produ-o/0d4e62f0aebdef020a4469daadcab2a0b55dd9fc/Captura%20de%20tela%202026-08-06%20075429.png" alt="Demonstração do Projeto - Parte 1" width="100%">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/mateusferreirasilva07/Projeto-Acompanhamento-Metas-de-Produ-o/0d4e62f0aebdef020a4469daadcab2a0b55dd9fc/Captura%20de%20tela%202026-08-06%20075503.png" alt="Demonstração do Projeto - Parte 2" width="100%">
</p>

<br>

---

## 🛠️ Tecnologias, Engenharia e DAX
- **Ferramenta:** Microsoft Power BI.
- **Modelagem de Dados:** Estruturação em *Star Schema* (Tabelas Fato e Dimensão) para garantir alta performance nos filtros.
- **Métricas e Regras:** Fórmulas avançadas em **DAX** para cálculos acumulados (YTD/MTD) e regras condicionais automatizadas.

<br>

## 👨‍💻 Autor
Desenvolvido por **Mateus Ferreira**. 
Se este projeto te inspirou, sinta-se à vontade para se conectar comigo no LinkedIn! <p>
  <a href="https://www.linkedin.com/in/mateus-ferreira-data-analytics" target="_blank">
    <img align="center" alt="LinkedIn" height="40" width="40" src="https://github.com/BruceFonseca/Portfolio/blob/main/social%20icons/linkedin.png?raw=true">
  </a>
