# 📍 BuscaCEP

Projeto desenvolvido como desafio final da formação **Learn Java with Object Oriented Programming** da [Alura](https://www.alura.com.br).  
O objetivo é realizar a **busca de informações de endereço a partir de um CEP**, consumindo a API pública **ViaCEP**.

---

## 🚀 Funcionalidades

- Consulta de endereço pelo CEP informado  
- Consumo de API REST com `HttpClient`  
- Manipulação de dados em **JSON** com a biblioteca **Gson**  
- Estruturação do código utilizando **Programação Orientada a Objetos (POO)**  

---

## 🛠️ Tecnologias utilizadas

- **Java 17**  
- **HttpClient (java.net.http)**  
- **Gson** (Google)  
- **API ViaCEP** → [https://viacep.com.br/](https://viacep.com.br/)  

---

## 📂 Estrutura do projeto

- `Main.java` → ponto de entrada da aplicação  
- `ConsultaCep.java` → responsável pela chamada da API  
- `Endereco.java` → classe modelo para mapear os dados do CEP  
- `GeradorDeArquivo.java` → cria arquivos `.json` com os dados consultados  

---

## ▶️ Como executar

1. Clone este repositório:  
   ```bash
   git clone https://github.com/CaioXys/BuscaCEP.git
