# 🚗 Sistema de Estacionamento - Desafio DIO .NET

Projeto desenvolvido como parte do desafio proposto pela [DIO](https://www.dio.me/).

---

## 📘 Sobre o Projeto / proposta

Este sistema simula a gestão de um estacionamento, permitindo que o usuário adicione veículos, remova veículos calculando o valor da permanência, e visualize os veículos atualmente estacionados.

### 📐 Diagrama da classe desenvolvida
![Diagrama de classe estacionamento](diagrama_classe_estacionamento.png)
---

## ✍️ O que eu desenvolvi

Este projeto foi implementado por mim, Lucas Gabriel Lima Silva, com foco em boas práticas e código limpo, como forma de revisar meus conhecimentos em C#. As implementações incluem:

✅ Criação completa da classe `Estacionamento` com:

- Declaração das variáveis `precoInicial`, `precoPorHora` e `veiculos`  
- Métodos:
  - `AdicionarVeiculo()` → adiciona a placa à lista de veículos
  - `RemoverVeiculo()` → solicita a placa e a quantidade de horas, calcula o valor a pagar e remove o veículo
  - `ListarVeiculos()` → lista todos os veículos presentes no estacionamento  

✅ Criação do **menu interativo**, com as opções:
- `1 - Cadastrar veículo`
- `2 - Remover veículo`
- `3 - Listar veículos`
- `4 - Encerrar`

✅ Validações importantes como:
- Conferência se o veículo está na lista antes de remover
- Cálculo correto do valor a pagar: `precoInicial + precoPorHora * horas`
- Mensagens claras para orientar o usuário em cada etapa

✅ Estilo de código com boas práticas (Clean Code)

---

## 🧪 Tecnologias Utilizadas

- C#
- .NET 9.0
- IDE: Visual Studio Code 

---

## 💡 Como usar

Clone o repositório, abra o projeto em sua IDE e execute:

```bash
dotnet run
