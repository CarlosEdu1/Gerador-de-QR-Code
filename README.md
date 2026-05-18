# Gerador de QR Code

Um projeto Java para gerar códigos QR de forma simples e eficiente, com suporte para containerização via Docker.

## 🎯 Sobre o Projeto

Este projeto é um gerador de QR Code desenvolvido em **Java** que permite criar códigos QR a partir de textos, URLs ou outros dados. O projeto está pronto para ser executado em containers Docker, facilitando o deployment em diferentes ambientes.

## 📋 Requisitos

- **Java 8+** ou superior
- **Maven** (para build e gerenciamento de dependências)
- **Docker** (opcional, para containerização)

## 🚀 Como Usar

### Localmente

1. Clone o repositório:
```bash
git clone https://github.com/CarlosEdu1/Gerador-de-QR-Code.git
cd Gerador-de-QR-Code
```

2. Compile o projeto:
```bash
mvn clean install
```

3. Execute a aplicação:
```bash
mvn exec:java
```

### Com Docker

1. Build da imagem Docker:
```bash
docker build -t gerador-qr-code .
```

2. Execute o container:
```bash
docker run -it gerador-qr-code
```

## 📦 Composição do Projeto

- **Java**: 93.2% - Linguagem principal do projeto
- **Dockerfile**: 6.8% - Containerização da aplicação

## 🛠️ Tecnologias

- Java
- Maven
- Docker
- Bibliotecas de geração de QR Code (ZXing ou similar)

## 📝 Funcionalidades

- ✅ Gerar QR Codes a partir de texto
- ✅ Suporte para URLs
- ✅ Containerização com Docker
- ✅ Fácil de integrar em outros projetos

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se livre para:
- Reportar bugs
- Sugerir melhorias
- Enviar pull requests

## 📄 Licença

Este projeto está disponível sob a licença MIT.

## 👨‍💻 Autor

**CarlosEdu1**

---

**Última atualização**: 18 de maio de 2026
