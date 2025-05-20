# Automação de Testes Web - Projeto Selenium Web

Este projeto contém scripts de automação de testes para aplicações web, desenvolvidos em **Java** utilizando o framework **Selenium WebDriver**.

## Descrição

O objetivo deste repositório é oferecer uma base robusta para criação, organização e execução de testes automatizados de interface web, aplicando boas práticas de automação e design de código, como o padrão **Page Object Model (POM)**.

## Tecnologias Utilizadas

- **Java** (linguagem de programação principal)
- **Selenium WebDriver** (automação de testes web)
- **Maven** (gerenciamento de dependências e build)
- **JUnit/TestNG** (frameworks de testes)
- **Page Object Model (POM)** (padrão para organização de código)
- **GeckoDriver** (driver para Firefox)

## Estrutura do Projeto

- `src/main/java/org/exemplo` – código fonte dos testes e das páginas (POM)
- `pom.xml` – arquivo de configuração do Maven
- `geckodriver.exe` – driver para execução dos testes no navegador Firefox
- `.idea` – configurações do projeto para IntelliJ IDEA

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Chaygois/AutomacaoDeTestesWeb.git

Execute os testes usando o Maven:
   ```bash

mvn test
