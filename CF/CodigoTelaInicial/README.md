A **Tela Inicial** é a porta de entrada do sistema desenvolvido pela equipe FutureX. Com design intuitivo e botões de navegação simples, ela conecta o usuário às funcionalidades principais do sistema: **Login**, **Calculadora** e **Jogo da Velha**.

---

## 🎯 Objetivo

- Criar uma tela de boas-vindas funcional e elegante
- Facilitar o acesso às funcionalidades do sistema
- Demonstrar organização e fluidez no projeto

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Descrição |
|------------|-----------|
| Java       | Linguagem de programação principal |
| Swing      | Biblioteca para interface gráfica (GUI) |
| IntelliJ IDEA / NetBeans | IDEs usadas no desenvolvimento |
| Git & GitHub | Controle de versão e colaboração em equipe |

---

## 📌 Funcionalidades da Tela

- Layout centralizado na tela
- Botões com direcionamento para:
  - **Tela de Login**
  - **Calculadora**
  - **Jogo da Velha**
- Mensagem de boas-vindas com o nome da aplicação
- Estrutura modular que permite fácil expansão

---

## 🧱 Estrutura do Código

```java
btnCalculadora.addActionListener(evt -> {
    new Calculadora().setVisible(true);
    dispose();
});
````

* Cada botão instância a respectiva funcionalidade
* A tela atual é encerrada ao abrir a nova

---

## 📸 Prévia Visual

> *(Adicione aqui uma imagem da tela inicial)*

---

## 👨‍💻 Desenvolvedores

* **João Pedro** – Estrutura da navegação e integração entre telas

---

## 🧠 Possibilidades Futuras

* Adição de ícones visuais nos botões
* Implementação de modo escuro
* Animações de entrada para cada botão
* Menu com atalhos de teclado

---

## ▶️ Como Executar

1. Clone o projeto:

   ```bash
   git clone https://github.com/futurex/tela-inicial-java.git
   ```

2. Abra na sua IDE (IntelliJ ou NetBeans)

3. Execute a classe principal:

   ```java
   TelaInicial.java
   ```

---

## 📄 Licença

Distribuído sob a licença **MIT**. Consulte o arquivo `LICENSE` para mais informações.

---

## 🌐 Contato

* Instagram: [@futurexnetx](https://instagram.com/futurexnetx)
* GitHub: [github.com/futurex](https://github.com/futurex)

---

> Projeto educacional desenvolvido no **IFCE – Campus Maranguape** como parte da disciplina de Programação Orientada a Objetos.


