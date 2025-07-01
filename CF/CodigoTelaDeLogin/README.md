
# 🔐 Tela de Login em Java – Projeto FutureX

Este é um projeto de **tela de login com interface gráfica** desenvolvido em Java, usando a biblioteca **Swing**. A tela é funcional e pode ser integrada a sistemas maiores. É parte do sistema educacional criado pela equipe **FutureX**, com foco em autenticação básica para usuários.

---


## 🎯 Objetivos do Projeto

- Criar uma tela de login funcional com **validação de usuário e senha**
- Aplicar conceitos de **interface gráfica (GUI)** com Swing
- Simular autenticação local (padrão educacional)
- Servir como base para futuras integrações com banco de dados

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Descrição |
|------------|-----------|
| Java       | Linguagem de programação |
| Swing      | Criação da interface gráfica |
| IntelliJ IDEA / NetBeans | IDEs utilizadas |
| Git & GitHub | Controle de versão e colaboração |

---

## 👨‍💻 Desenvolvedor Responsável

- **João Pedro** – Criação da tela, estrutura de validação e integração com repositórios

**Colaboração:**
- Ana Karine – Feedback visual e testes
- Humberto – Organização do fluxo geral
- Hayana – Apoio na apresentação

---

## ✅ Funcionalidades

- Campo para **usuário** e **senha**
- Botão **Login** com ação validada
- Mensagens de sucesso ou erro
- Integração com **outras telas** (ex: Calculadora, Jogo da Velha)
- Centralização automática na tela

---

## 🧠 Como Funciona

- A validação é feita diretamente no código:
  ```java
  if (usuario.equals("admin") && senha.equals("123")) {
      // login válido
  } else {
      // erro de autenticação
  }
````

* Após o login correto, a tela atual é fechada e uma nova tela (por exemplo, o sistema principal) é aberta.

---

## ▶️ Como Executar

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/futurex/tela-de-login-java.git
   ```

2. **Abra na sua IDE favorita** (IntelliJ ou NetBeans)

3. **Execute a classe principal**:

   ```java
   TelaLogin.java
   ```

---

## 📌 Melhorias Futuras

* Conexão com banco de dados (MySQL, SQLite)
* Hash de senha para maior segurança
* Sistema de cadastro e redefinição de senha
* Responsividade para diferentes resoluções

---

## 📄 Licença

Este projeto é distribuído sob a licença **MIT**. Consulte o arquivo `LICENSE` para mais detalhes.

---

## 🌐 Contato e Redes

* Instagram: [@futurexnetx](https://instagram.com/futurexnetx)
* GitHub: [github.com/futurex](https://github.com/futurex)

---

> Projeto educacional desenvolvido por alunos do **IFCE – Campus Maranguape**


