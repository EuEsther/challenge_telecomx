# 📞 TelecomX_BR - Challenge

Este projeto é um desafio de análise de dados focado em **Churn de clientes no setor de telecomunicações**. O objetivo é entender o comportamento dos clientes da operadora fictícia **TelecomX_BR**, identificando padrões que indicam a evasão de usuários.

---

## 💡 Sobre o Desafio

Este projeto foi desenvolvido como parte de um **challenge de análise de dados**, com foco em:

- Limpeza e tratamento de dados
- Exploração e visualização de dados
- Criação de variáveis derivadas
- Análise estatística
- Geração de insights de negócio

A base de dados contém informações contratuais e técnicas dos clientes da TelecomX_BR, além da variável alvo `churn`, que indica se o cliente saiu da operadora.

---

## 📂 Estrutura do Projeto

```bash
📁 challenge_telecomx/
├── 📁 graficos/          # Pasta com as imagens dos Gráficos 
├── TelecomX_BR.ipynb     # Notebook principal com todas as análises
├── README.md             # Documentação do projeto
````

---

## 🔧 Tecnologias Utilizadas

* 🐍 Python
* 📊 Pandas & NumPy
* 📈 Matplotlib, Seaborn & Plotly
* 📘 Jupyter Notebook

---

## 📌 Principais Análises

* Distribuição geral do churn
* Comparação de churn por tipo de contrato, pagamento e serviços extras
* Análise do tempo de permanência do cliente
* Correlações entre variáveis numéricas
* Criação de coluna `Contas_Diarias` para insights financeiros

---

## 🚀 Como Rodar o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/EuEsther/challenge_telecomx.git
```

2. Crie um ambiente virtual e ative:

```bash
python -m venv venv
source venv/bin/activate  # Ou venv\Scripts\activate no Windows
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Rode o notebook:

```bash
jupyter notebook TelecomX_BR.ipynb
```

---

## 📈 Resultados e Insights

* Clientes com **contratos mensais** têm taxas muito mais altas de evasão.
* Métodos de pagamento como **boleto bancário** estão fortemente associados ao churn.
* Serviços como **streaming** e **seguro** apresentam correlações com a permanência do cliente.
* A variável derivada `Contas_Diarias` oferece uma visão refinada sobre o impacto financeiro de cada cliente.

---

## 🤝 Contribuições

Sinta-se à vontade para abrir issues, sugerir melhorias ou clonar este repositório para seus próprios estudos.

---

## 📝 Licença

Este projeto está licenciado sob os termos da **MIT License**.
Veja o arquivo [LICENSE](./LICENSE) para mais informações.
