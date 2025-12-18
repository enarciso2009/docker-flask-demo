# 🚀 Flask + Docker Demo

Projeto simples que demonstra como rodar uma aplicação **Flask** dentro de um **container Docker**.  
Ideal para estudos iniciais de Docker e para compor portfólio de desenvolvedor Python.

---

## 📝 Visão Geral

Este projeto demonstra como containerizar uma aplicação web Python utilizando Docker, garantindo que a aplicação rode da mesma forma em qualquer ambiente, sem depender de configurações locais complexas.

O foco é aprendizado prático e apresentação de boas práticas para projetos Flask.

---

## 🛠️ Tecnologias Utilizadas

- 🐍 **Python 3.12**
- 🌐 **Flask**
- 🐳 **Docker**

---

## 📁 Estrutura do Projeto

<img width="158" height="284" alt="image" src="https://github.com/user-attachments/assets/af2e7971-191b-4bc6-bd21-5f12fa89b27e" />


## 🚀 Como Rodar o Projeto

### 1️⃣ Clonar o repositório
git clone https://github.com/enarciso2009/docker-flask-demo.git
cd docker-flask-demo

### 2️⃣ Build da imagem Docker
docker build -t flask-docker .

### 3️⃣ Rodar o container
docker run -p 5000:5000 flask-docker

### 4️⃣ Acessar no navegador
Abra o navegador e acesse:
http://localhost:5000

Você deverá ver a aplicação Flask rodando dentro do container Docker 🎉

🎯 Objetivo do Projeto
Este projeto foi criado com foco em aprendizado e portfólio, demonstrando:

 * Criação de imagens Docker com Dockerfile

 * Execução de aplicações Flask em containers
  
 * Organização profissional de projetos Python
  
 * Estruturação correta de templates no Flask
  
 * Versionamento de código com Git e GitHub

📚 Possíveis Evoluções

Algumas melhorias que podem ser implementadas futuramente:
 
  * Uso de docker-compose
  
  * Separação de ambientes (dev/prod)
  
  * Variáveis de ambiente com .env
  
  * Testes automatizados
  
  * CI/CD com GitHub Actions
  
  * Versão Django do projeto

👤 Autor
  
  Everton Narciso
  
  Desenvolvedor Python
  
  GitHub: https://github.com/enarciso2009


