# 🏭 Painel de Produção Industrial — Monitoramento de Máquinas CNC

> **Status do Projeto:** 🚀 Versão 1.0 (Concluído/Produção)
> **Desenvolvido por:** José Cleison de Lima

Este repositório contém o desenvolvimento de um **Dashboard de Business Intelligence** focado no monitoramento em tempo real de uma linha de produção industrial automatizada por máquinas CNC. O objetivo principal do projeto é centralizar indicadores de **Produtividade, Consumo Energético e Controle de Qualidade** para apoiar tomadas de decisão rápidas e eficazes no chão de fábrica.

---

## 📊 Visualização do Dashboard

![Painel de Produção Industrial](https://github.com/cleisonlima/industrial-powerbi-dashboard/blob/main/projeto_power_bi_2/dashboard.png?raw=true)
*(Substitua o link acima pelo link da imagem do seu painel após subir no GitHub!)*

---

## 📈 Indicadores Principais (KPIs)

O painel foi estruturado seguindo as melhores práticas de hierarquia visual, destacando os seguintes macro-indicadores no topo da página:

*   **Produção Total:** Volume acumulado de peças produzidas pelas máquinas.
*   **Consumo Total:** Monitoramento de gastos energéticos globais.
*   **Total de Defeitos:** Quantidade absoluta de peças fora do padrão de qualidade.
*   **Taxa de Defeitos:** Indicador percentual crítico de eficiência de qualidade (ajustado com alertas visuais rápidos).
*   **Horas de Uso:** Tempo de atividade acumulado do parque de máquinas CNC.

---

## 🧠 Arquitetura do Projeto & Funcionalidades

O projeto foi construído utilizando um ecossistema otimizado dentro do Power BI:

### ⚙️ Engenharia de Dados & Modelagem
*   **DataModel Otimizado:** Modelagem de dados estruturada para garantir performance mesmo com grandes volumes de registros de sensores industriais.
*   **Inteligência de Tempo (Time Intelligence):** Análise evolutiva de consumo de energia e incidência de defeitos ao longo dos dias do mês.
*   **Granularidade por Ativo:** Filtros e detalhamentos específicos por máquina (`CNC-01` a `CNC-05`), permitindo identificar gargalos de manutenção ou baixa performance individual.

### 🎨 Design & Experiência do Usuário (UX/UI)
*   **Tema Escuro de Alta Performance:** Desenvolvido sob um esquema de cores moderno no estilo *Operations Center* (Sala de Controle), utilizando cores vibrantes e contrastantes para evitar a fadiga visual dos operadores.
*   **Layout Customizado:** Utilização de um plano de fundo exclusivo (`Fundo_Dashboard_PowerBI.png`) para delimitar perfeitamente os quadrantes de dados.
*   **Acessibilidade Visual:** Implementação de regras estritas de contraste (baseado no padrão `AccessibleTidal`), garantindo a leitura fluida de tabelas de sensores e gráficos de barras.

---

## 🛠️ Tecnologias e Recursos Utilizados

*   **Power BI Desktop:** Construção, tratamento e visualização de dados.
*   **Linguagem DAX:** Criação de medidas calculadas dinâmicas e taxas percentuais de eficiência.
*   **Power Query (M):** Extração, transformação e limpeza dos dados brutos dos sensores.
*   **JSON Custom Themes:** Configuração de paleta de cores global (`CY26SU05.json`).

---

## 📂 Como Replicar ou Abrir o Projeto

1. Faça o clone deste repositório em sua máquina local:
   ```bash
   git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
