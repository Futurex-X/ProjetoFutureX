# 🧮 Calculadora Java com Interface Gráfica – Projeto FutureX

Este é um projeto de **calculadora com interface gráfica (GUI)** desenvolvido em Java utilizando **Swing**, como parte do sistema educacional da equipe **FutureX**. A calculadora realiza operações básicas (adição, subtração, multiplicação e divisão), possui centralização de layout e um botão de retorno à tela inicial.

## 🚀 Funcionalidades

- ✅ Interface gráfica amigável e responsiva
- ✅ Operações matemáticas básicas: `+`, `-`, `×`, `÷`
- ✅ Teclas numéricas de 0 a 9
- ✅ Botão de limpar (`CE`)
- ✅ Botão `OFF` que retorna para a **Tela Inicial**
- ✅ Exibição de resultados com tratamento para inteiros e decimais
- ✅ Interface centralizada na tela

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Descrição |
|------------|-----------|
| 💻 Java     | Linguagem de programação principal |
| 🖼️ Swing     | Biblioteca para construção da interface gráfica |
| 🧱 Java Swing Layout | Responsável pela organização dos componentes |
| 🛠️ IntelliJ / NetBeans | IDEs utilizadas durante o desenvolvimento |

---

## 🎯 Objetivo

Criar uma aplicação simples, funcional e de fácil uso que sirva como base para o aprendizado de **interfaces gráficas com Java** e **eventos de botões**. Também estimula boas práticas como organização de código e separação por pacotes.

---

## 🧑‍💻 Equipe FutureX

- **João Pedro** – Tela de login, Tela inicial, Design e integração com GitHub
- **Ana Karine** – Design e lógica da calculadora
- **Humberto** – Lógica do jogo da velha
- **Hayana** – Documentação e testes

---

## 🔄 Como Executar

1. **Clone este repositório**:
   ```bash
   git clone https://github.com/futurex/calculadora-java.git
````

2. **Abra no NetBeans ou IntelliJ**

3. **Execute a classe principal**:

   ```
   Calculadora.java
   ```

---

## 🧠 Lógica de Funcionamento

* O valor digitado é armazenado em `valor1`.
* A operação é definida (`+`, `-`, `*`, `/`).
* Ao pressionar `=`, o segundo valor é capturado (`valor2`).
* O cálculo é feito por meio de `switch-case`.
* O resultado é exibido no campo `txtResult`.

---

## 🔙 Voltar para Tela Inicial

O botão `OFF` executa o seguinte:

```java
TelaInicial telaInicial = new TelaInicial();
telaInicial.setVisible(true);
this.dispose();
```

---

## 📌 Possíveis Melhorias Futuras

* ☑️ Adição de teclas de ponto flutuante (ex: `1.5`)
* ☑️ Teclas com atalhos do teclado (keydown)
* ☑️ Suporte a operações mais avançadas (exponenciação, raiz quadrada)
* ☑️ Dark Mode
* ☑️ Integração com banco de dados para salvar histórico

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

## 📲 Contato

* Instagram: [@futurexnetx](https://instagram.com/futurexnetx)
* GitHub: [github.com/futurex](https://github.com/futurex)

> Desenvolvido com 💙 por alunos do IFCE – Campus Maranguape

