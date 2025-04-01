# Consulta de Preços de Veículos - API Tabela FIPE

Este é um projeto desenvolvido em **Java** utilizando **Spring Boot**, que consome a API da **Tabela FIPE** para consultar os preços de veículos com base na marca, modelo e ano.

## 📌 Funcionalidades
- Escolher o tipo de veículo (Carro, Moto, Caminhão).
- Selecionar a marca (ex: Fiat, Ford, Honda, etc.).
- Escolher o modelo do veículo.
- Consultar os anos disponíveis e seus valores de mercado segundo a Tabela FIPE.

## 🚀 Tecnologias Utilizadas
- **Java 17**
- **Spring Boot**
- **Spring Web**
- **RestTemplate** (para consumo da API externa)
- **CommandLineRunner** (para execução da lógica no start da aplicação)
- **Jackson** (para manipulação de JSON)

## 📦 Como Executar o Projeto

### ✅ Pré-requisitos
Certifique-se de ter instalado:
- **Java 17+**
- **Maven**

### 🔧 Passos para execução
1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/tabela-fipe.git
   ```
2. Acesse a pasta do projeto:
   ```sh
   cd tabela-fipe
   ```
3. Compile e execute o projeto:
   ```sh
   mvn spring-boot:run
   ```
4. Interaja com a aplicação via terminal, escolhendo o tipo de veículo, marca e modelo para obter os preços.

## 🔗 API da Tabela FIPE
Este projeto consome a API da **Tabela FIPE** para obter informações de preço de mercado de veículos. Para mais detalhes, consulte a documentação oficial da API.

## 📜 Licença
Este projeto é de uso livre para aprendizado e melhorias. Contribuições são bem-vindas!
