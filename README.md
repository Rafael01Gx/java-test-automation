<div align="center">

# 🧪 Automatização de Testes em Java  
### _Testes Unitários, Integração, Mocks e Boas Práticas com JUnit 5, Mockito e Spring Boot_

[![Java](https://img.shields.io/badge/Java-25+-orange?logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen?logo=spring&logoColor=white)](https://spring.io/projects/spring-boot)
[![JUnit5](https://img.shields.io/badge/JUnit-5-red?logo=junit5&logoColor=white)](https://junit.org/junit5/)
[![Mockito](https://img.shields.io/badge/Mockito-4.x-yellow?logo=mockito&logoColor=white)](https://site.mockito.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](#-como-contribuir)

</div>

---

## 🧭 Sobre o Projeto

Este repositório foi criado para estudos do curso **“Automatização de Testes em Java”**, dando **continuidade ao projeto [java-clean-code](https://github.com/Rafael01Gx/java-clean-code)**, onde foram aplicadas boas práticas, Design Patterns e refatorações em uma API REST.

Agora, o foco é elevar a qualidade do código por meio de **testes automatizados**, cobrindo desde testes unitários até testes de integração com **Spring Boot**, sempre aplicando os princípios de **Clean Code e SOLID**.

> “Testes não garantem a ausência de bugs.  
> Eles apenas tornam os bugs visíveis mais rapidamente.”  
> — *Gerard Meszaros*

---

## 🧩 Conteúdos Abordados

### ✅ Testes Unitários
- Escrita e estruturação de testes com **JUnit 5**  
- Aplicação de boas práticas e convenções de nomeação  
- Validação de regras de negócio isoladas  

### 🤖 Mocks e Stubs
- Simulação de dependências com **Mockito**  
- Uso de `@Mock`, `@InjectMocks` e `@ExtendWith(MockitoExtension.class)`  
- Estratégias para reduzir acoplamento entre classes  

### 🌐 Testes de Integração
- Testes com **Spring Boot Test**  
- Utilização de **@SpringBootTest**, **@DataJpaTest** e contextos reais  
- Testes em endpoints REST e persistência com **JPA/Hibernate**  

### 🧠 Boas Práticas e Clean Tests
- Testes legíveis e de fácil manutenção  
- Organização por camadas e contextos de domínio  
- Cobertura de código e refatoração contínua  

---

## 🧰 Tecnologias Utilizadas

| Categoria | Ferramenta |
|------------|-------------|
| Linguagem | ![Java](https://img.shields.io/badge/Java-25+-orange?logo=openjdk&logoColor=white) |
| Framework | ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen?logo=spring&logoColor=white) |
| Testes | ![JUnit5](https://img.shields.io/badge/JUnit-5-red?logo=junit5&logoColor=white) |
| Mocks | ![Mockito](https://img.shields.io/badge/Mockito-4.x-yellow?logo=mockito&logoColor=white) |
| Build | ![Maven](https://img.shields.io/badge/Maven-3.x-C71A36?logo=apachemaven&logoColor=white) |
| Persistência | ![JPA](https://img.shields.io/badge/JPA%2FHibernate-blue?logo=hibernate&logoColor=white) |

---

## ⚙️ Requisitos

Antes de começar, certifique-se de ter:

- ☕ **Java 25+** instalado  
- 🧱 Conhecimento em **Spring Boot**  
- 🌐 Familiaridade com **APIs REST**  
- 🗄️ Noções de **JPA/Hibernate**

---

## 🚀 Como Executar o Projeto

```bash
# Clone este repositório
git clone https://github.com/seu-usuario/java-test-automation.git

# Acesse a pasta do projeto
cd java-test-automation

# Compile e rode os testes
./mvnw test

# Ou execute com Spring Boot (para testes de integração)
./mvnw spring-boot:run
