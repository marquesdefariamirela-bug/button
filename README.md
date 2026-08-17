# 📱 Button — Aplicação Flutter

Aplicação mobile desenvolvida com **Flutter e Dart**, criada com o objetivo de praticar a construção de interfaces, navegação entre telas, utilização de widgets e gerenciamento básico de estado.

O projeto apresenta uma estrutura simples e didática, permitindo compreender conceitos fundamentais do desenvolvimento de aplicações Flutter, como `StatelessWidget`, `StatefulWidget`, `Scaffold`, `AppBar`, `Column`, `ElevatedButton`, `FloatingActionButton` e `setState()`.

---

## 🚀 Sobre o projeto

O **Button** é um projeto desenvolvido para estudos de desenvolvimento mobile utilizando o framework **Flutter**.

A aplicação possui uma tela principal com um contador interativo e uma tela adicional de boas-vindas. A interação com os botões permite praticar eventos de clique e navegação entre telas.

O projeto foi desenvolvido de forma simples e objetiva, servindo como base para a evolução de aplicações Flutter mais completas.

---

## ✨ Funcionalidades

* 🔢 **Contador interativo**

  * Incrementa o valor exibido na tela através de um botão.
  * Utiliza `setState()` para atualizar a interface.

* 🏠 **Tela Home**

  * Apresenta uma mensagem de boas-vindas.
  * Possui botão para retornar à tela anterior.

* 🎨 **Interface utilizando Material Design**

  * Utilização de `Scaffold`.
  * Barra superior com `AppBar`.
  * Botões e componentes nativos do Flutter.

* 🧭 **Navegação**

  * Utilização do `Navigator` para controlar o retorno entre telas.

---

## 🛠️ Tecnologias utilizadas

| Tecnologia          | Utilização                           |
| ------------------- | ------------------------------------ |
| **Flutter**         | Desenvolvimento da aplicação mobile  |
| **Dart**            | Linguagem de programação             |
| **Material Design** | Construção da interface              |
| **Flutter Widgets** | Estrutura e componentes da aplicação |

---

## 📂 Estrutura do projeto

```text
button/
│
├── README.md
├── main.dart
├── home.dart
└── principal.dart
```

### `main.dart`

Arquivo responsável pela inicialização da aplicação.

Nele são definidos:

* `main()`;
* `MaterialApp`;
* tema da aplicação;
* tela inicial;
* contador;
* evento de incremento;
* estrutura visual principal.

A aplicação utiliza um `StatefulWidget` para controlar o valor do contador e atualizar a interface através do `setState()`.

### `home.dart`

Contém a tela **Home**, construída utilizando `StatelessWidget`.

A tela apresenta uma mensagem de boas-vindas e um `ElevatedButton` responsável por retornar à tela anterior utilizando `Navigator.pop(context)`.

### `principal.dart`

Arquivo atualmente reservado para futuras implementações. No estado atual do repositório, ele ainda não possui código implementado.

---

## 🧠 Conceitos praticados

Este projeto permite praticar conceitos fundamentais do Flutter:

### Widgets

O Flutter utiliza widgets como elementos básicos da interface. Neste projeto são utilizados componentes como:

```dart
Scaffold()
AppBar()
Column()
Text()
ElevatedButton()
FloatingActionButton()
```

### Gerenciamento de estado

O contador utiliza um `StatefulWidget` e o método `setState()` para atualizar o valor exibido na tela.

```dart
setState(() {
  _counter++;
});
```

Dessa forma, quando o botão é pressionado, o Flutter reconstrói a parte necessária da interface para apresentar o novo valor.

### Navegação

A tela `Home` utiliza:

```dart
Navigator.pop(context);
```

para retornar à tela anterior da pilha de navegação.

---

## ⚙️ Pré-requisitos

Antes de executar o projeto, certifique-se de possuir:

* [Flutter](https://flutter.dev/) instalado;
* Dart SDK configurado;
* Android Studio ou Visual Studio Code;
* Emulador Android/iOS ou dispositivo físico;
* Git instalado.

---

## 📥 Instalação

Clone o repositório:

```bash
git clone https://github.com/marquesdefariamirela-bug/button.git
```

Entre na pasta:

```bash
cd button
```

Instale as dependências:

```bash
flutter pub get
```

Execute a aplicação:

```bash
flutter run
```

---

## ▶️ Executando no Visual Studio Code

1. Abra o projeto no **Visual Studio Code**.
2. Certifique-se de que a extensão **Flutter** está instalada.
3. Conecte um dispositivo ou inicialize um emulador.
4. Execute:

```bash
flutter run
```

ou pressione **F5** para iniciar o modo de execução e depuração.

---

## 🎯 Objetivo acadêmico

O projeto foi desenvolvido com finalidade **educacional**, proporcionando prática com os principais conceitos iniciais do desenvolvimento de aplicações mobile utilizando Flutter.

Entre os conhecimentos trabalhados estão:

* criação de interfaces;
* organização de widgets;
* interação com botões;
* gerenciamento básico de estado;
* navegação entre telas;
* utilização da linguagem Dart;
* estruturação de uma aplicação Flutter.

---

## 🔮 Possíveis melhorias

O projeto pode ser expandido futuramente com:

* [ ] Implementação completa da tela de login;
* [ ] Sistema de navegação entre múltiplas páginas;
* [ ] Melhorias no design da interface;
* [ ] Adição de validação de campos;
* [ ] Persistência de dados;
* [ ] Integração com banco de dados;
* [ ] Implementação de autenticação;
* [ ] Criação de componentes reutilizáveis;
* [ ] Responsividade para diferentes tamanhos de tela;
* [ ] Adição de testes automatizados.

---

## 📌 Status

**Em desenvolvimento** 🚧

O projeto encontra-se em fase de estudos e pode receber novas funcionalidades e melhorias de interface ao longo do desenvolvimento.

---

## 👩‍💻 Desenvolvedora

**Mirela Marques de Faria**

Projeto desenvolvido para fins acadêmicos e de aprendizado em **Desenvolvimento de Aplicações Mobile**.

---

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais. Caso seja reutilizado ou modificado, recomenda-se manter os créditos da autora original.
