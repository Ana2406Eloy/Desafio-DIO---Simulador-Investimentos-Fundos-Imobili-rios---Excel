# 📊 Simulador de Investimentos em Fundos Imobiliários (FIIs)

## 📌 Descrição do Projeto
Este projeto consiste no desenvolvimento de uma planilha em Excel para **simulação de investimentos em Fundos Imobiliários (FIIs)**.  
A ferramenta permite que o usuário simule aportes mensais, defina um período de investimento e uma taxa de rendimento, obtendo como resultado o **patrimônio acumulado** e os **dividendos mensais estimados**.

O objetivo principal é apoiar investidores iniciantes na tomada de decisão, oferecendo uma visão clara e automatizada do potencial de retorno ao longo do tempo.

---

## 🎯 Objetivos de Aprendizagem
Com este projeto, foi possível:

- Criar uma ferramenta prática de simulação financeira no Excel;
- Aplicar conceitos de **juros compostos** e **valor futuro**;
- Automatizar cálculos de patrimônio e dividendos;
- Documentar tecnicamente uma solução;
- Utilizar o **GitHub** como repositório de versionamento e entrega.

---

## 🛠️ Tecnologias Utilizadas
- Microsoft Excel  
- Funções financeiras:  
  - `FV()` (Valor Futuro)  
  - Operações matemáticas básicas  
- GitHub para versionamento e documentação

---

## 📂 Estrutura do Projeto
O arquivo principal do projeto é:

- `Simulador_Investimentos_Fundos_Imobiliarios.xlsx`

Ele contém:
- Aba **APP**: interface principal do simulador;  
- Aba **DOCUMENTAÇÃO**: explicação interna de uso e fórmulas.

---

## 🧭 Como Utilizar a Planilha

### 1. Configurações iniciais
Na aba **APP**, o usuário deve preencher:

- Salário  
- Quanto investir por mês  
- Por quantos anos  
- Taxa de rendimento mensal  

### 2. Resultados automáticos
A planilha calcula automaticamente:

- Patrimônio acumulado;  
- Dividendos mensais;  
- Simulações para:  
  - 2 anos  
  - 5 anos  
  - 10 anos  
  - 20 anos  
  - 30 anos  

### 3. Perfil de Investimento
É possível selecionar um perfil (ex: Moderado), e a planilha sugere a distribuição entre:

- FIIs de Papel  
- FIIs de Tijolo  
- Híbridos  
- FOFs  
- Desenvolvimento  

---

## 📐 Fórmulas Utilizadas

### Valor Futuro:
```excel
=FV(taxa_mensal; anos*12; aporte*-1)
=patrimonio * rendimento_mensal 

```

## 💡 Exemplo de Aplicação
Um usuário que investe **R$ 200 por mês durante 5 anos**, com rendimento médio de **1% ao mês**, consegue visualizar:

- Total investido;  
- Patrimônio final estimado;  
- Valor médio de dividendos mensais.  

Tudo de forma automática e visual.

---

## 🚀 Possíveis Melhorias Futuras
- Inclusão de gráficos dinâmicos;  
- Simulação com inflação;  
- Comparação entre diferentes taxas;  
- Dashboard interativo;  
- Versão web (Power BI ou Google Sheets).

---

## 👩‍💻 Autora
Projeto desenvolvido por **Ana Júlia Eloy**.

