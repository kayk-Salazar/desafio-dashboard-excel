# Dashboard de Vendas – Xbox Game Pass

## Descrição do Projeto

Este projeto consiste no desenvolvimento de um dashboard interativo no Microsoft Excel com o objetivo de transformar dados brutos em informações visuais claras e úteis para análise do desempenho financeiro das assinaturas do Xbox Game Pass.

Por meio de tabelas dinâmicas, gráficos e segmentações de dados, foi possível criar um painel que permite analisar a arrecadação gerada pelas diferentes modalidades de assinatura e pelos serviços adicionais oferecidos aos usuários.

---

## Objetivo

O principal objetivo deste dashboard é facilitar a análise da receita proveniente das assinaturas do Xbox Game Pass, permitindo identificar padrões de consumo, comparar modalidades de assinatura e avaliar o impacto dos serviços complementares na arrecadação total.

---

## Base de Dados

A base utilizada contém informações relacionadas às assinaturas do Xbox Game Pass, incluindo:

* Nome do assinante;
* Plano contratado;
* Data de início da assinatura;
* Renovação automática;
* Tipo de assinatura;
* Contratação do EA Play Season Pass;
* Contratação do Minecraft Season Pass;
* Cupons de desconto;
* Valores pagos pelos assinantes.

---

## Funcionalidades do Dashboard

### Análise da Receita do Xbox Game Pass

O dashboard apresenta um gráfico que demonstra a arrecadação total do Xbox Game Pass, separando os resultados entre:

* Assinantes com renovação automática ativada ("Yes");
* Assinantes sem renovação automática ("No").

Os valores são atualizados automaticamente conforme os filtros selecionados pelo usuário.

---

### Filtros Interativos

O painel possui segmentações de dados que permitem analisar os resultados de acordo com a modalidade de assinatura contratada:

* Annual;
* Monthly;
* Quarterly.

Ao selecionar uma das opções, todos os gráficos e indicadores do dashboard são recalculados automaticamente.

---

### Indicadores de Receita dos Serviços Adicionais

Além da análise principal do Xbox Game Pass, foram desenvolvidos indicadores do tipo Big Number para demonstrar a arrecadação proveniente dos serviços complementares disponíveis na plataforma.

#### EA Play Season Pass

Apresenta o valor total arrecadado com a contratação do EA Play Season Pass, considerando os filtros aplicados no dashboard.

#### Minecraft Season Pass

Apresenta o valor total arrecadado com a contratação do Minecraft Season Pass, também atualizado dinamicamente conforme os filtros selecionados.

---

## Informações Importantes sobre a Interpretação dos Dados

Os filtros "Annual", "Monthly" e "Quarterly" representam os tipos de assinatura contratados pelos usuários e não períodos cronológicos do calendário.

Dessa forma, uma modalidade mensal pode apresentar uma arrecadação superior à modalidade anual, dependendo de fatores como:

* Quantidade de assinantes em cada modalidade;
* Plano contratado pelo usuário;
* Utilização da renovação automática;
* Contratação dos serviços adicionais.

---

## Planos Disponíveis

A base de dados contempla três tipos de planos do Xbox Game Pass:

| Plano    | Valor da Assinatura |
| -------- | ------------------- |
| Core     | R$ 5,00             |
| Standard | R$ 10,00            |
| Ultimate | R$ 15,00            |

Esses valores influenciam diretamente nos resultados apresentados pelo dashboard.

---

## Recursos Utilizados

* Microsoft Excel;
* Tabelas Dinâmicas;
* Gráficos Dinâmicos;
* Segmentação de Dados (Slicers);
* Indicadores do tipo Big Number;
* Formatação condicional e visual para apresentação dos resultados.

---

## Estrutura do Arquivo

O arquivo disponibilizado contém as seguintes abas:

* Dashboard: painel principal para análise e interação com os dados;
* Base de Dados: conjunto de informações utilizado para a construção das análises.

As demais abas auxiliares utilizadas durante o desenvolvimento foram ocultadas com o objetivo de proporcionar uma apresentação mais organizada.

---

## Como Utilizar

1. Faça o download do arquivo `dashboard.xlsx`;
2. Abra o arquivo utilizando o Microsoft Excel;
3. Utilize os filtros disponíveis para explorar os diferentes tipos de assinatura;
4. Analise os gráficos e indicadores apresentados no painel para compreender o comportamento da arrecadação.

---

## Considerações Finais

Este projeto demonstra como ferramentas do Excel podem ser utilizadas para transformar dados em informações estratégicas, permitindo análises rápidas, dinâmicas e orientadas à tomada de decisão.

A utilização de dashboards interativos facilita a identificação de padrões de consumo e contribui para uma melhor compreensão do desempenho financeiro dos serviços oferecidos.
