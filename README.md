# Test Automation com Selenium e Java

Projeto de automação de testes desenvolvido utilizando Java, Selenium WebDriver e TestNG.

O projeto demonstra a utilização do padrão Page Object Model (POM) para organização dos testes e dos elementos utilizados durante as interações com as páginas.

## Cenários automatizados

O projeto contém cenários relacionados a:

- Abertura do navegador e navegação para uma URL
- Teste de login
- Pré-cadastro
- Preenchimento de formulário de cadastro
- Interações com formulários utilizando Page Object Model

## Tecnologias utilizadas

- Java
- Selenium WebDriver
- TestNG
- Maven
- Page Object Model (POM)

## Estrutura do projeto

```text
- selenium-java/
├── demo/
│   ├── src/
│   │   ├── main/
│   │   │   └── java/
│   │   ├── test/
│   │   │   └── java/
│   │   └── test/
│   │       └── resources/
└── README.md
```

## Pré-requisitos

- Java JDK 8 ou superior
- Maven
- ChromeDriver ou WebDriver compatível com o navegador utilizado

## Como executar

Clone o repositório:

```bash
git clone https://github.com/alan-almeida-dev/-selenium-java.git
```

Entre no diretório do projeto:

```bash
cd -selenium-java
```

Execute os testes com Maven:

```bash
mvn test
```

## Organização dos testes

O projeto utiliza o padrão Page Object Model (POM) para separar a estrutura das páginas dos casos de teste.

Essa abordagem facilita a organização e manutenção dos testes automatizados.

## Objetivo

O projeto foi desenvolvido como prática de automação de testes web utilizando Java, Selenium WebDriver e TestNG.

## Autor

Alan Almeida

GitHub: https://github.com/alan-almeida-dev
