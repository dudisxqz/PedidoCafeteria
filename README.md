# ☕ Café do Java

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=java&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

Um programa simples em **Java** que simula um pedido em uma cafeteria.  
O usuário escolhe o **tamanho** e o **tipo de café**, e o programa calcula o valor total do pedido.  

---

## 📝 Como funciona

1. O programa exibe as opções de tamanho:
   - **P** → Pequeno (R$ 2,50)  
   - **M** → Médio (R$ 3,00)  
   - **G** → Grande (R$ 3,50)  

2. Depois, exibe as opções de tipo de café:
   - **E** → Expresso (+ R$ 1,50)  
   - **C** → Capuccino (+ R$ 2,00)  
   - **L** → Latte (+ R$ 2,50)  

3. O preço final é calculado com base no tamanho + tipo.  
4. O pedido é exibido na tela com o valor total.  

---

## 🚀 Funcionalidades

- Sistema de menu interativo via console.
- Uso de **`Scanner`** para leitura do usuário.
- Estrutura **`switch-case`** para calcular os preços.
- Validação para entradas inválidas.

---

## 📦 Como executar

```bash
# Clone este repositório
git clone https://github.com/seu-usuario/cafe-do-java.git

# Entre na pasta do projeto
cd cafe-do-java

# Compile o código
javac PedidoCafeteriaCardapio.java

# Execute o programa
java PedidoCafeteriaCardapio
