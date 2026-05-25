# Gerador de CPF em Python

Projeto simples desenvolvido em Python para gerar CPFs válidos utilizando o cálculo oficial dos dígitos verificadores.

---

## 📌 Sobre o projeto

O script:

- Gera CPFs aleatórios
- Calcula automaticamente os dois dígitos verificadores
- Permite escolher quantos CPFs serão gerados
- Explica o cálculo do CPF através de comentários no código

---

## 🛠️ Tecnologias utilizadas

- Python 3
- Biblioteca padrão `random`

---

## ▶️ Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

### 2. Acesse a pasta do projeto

```bash
cd seu-repositorio
```

### 3. Execute o script

```bash
python main.py
```

---

## 💻 Exemplo de execução

Entrada:

```bash
Digite quantos CPF você deseja gerar: 3
```

Saída:

```bash
74682489070
12345678909
98765432100
```

---

## 🧠 Como funciona o cálculo

O programa:

1. Gera os 9 primeiros dígitos aleatórios
2. Calcula o primeiro dígito verificador
3. Calcula o segundo dígito verificador
4. Exibe o CPF completo e válido

O cálculo segue a regra oficial da Receita Federal utilizando multiplicação por contagem regressiva e operação módulo 11.

---

## 📂 Estrutura do projeto

```bash
📦 gerador-cpf
 ┣ 📄 main.py
 ┗ 📄 README.md
```

---

## 🚀 Possíveis melhorias

- Formatação automática do CPF (`000.000.000-00`)
- Exportação para arquivo `.txt`
- Interface gráfica
- Validação de CPF
- Geração sem números repetidos

---

## 📄 Licença

Este projeto é livre para estudos e aprendizado.
