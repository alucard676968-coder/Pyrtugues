<div align="center">

<img src="./assets/logo-pyrtugues.png" alt="Logo do Pyrtugues" width="160">

# Pyrtugues

### Python em português, feito para aprender programação.

**Programação em português • lógica de Python • aprendizado progressivo**

Uma ferramenta educacional criada para facilitar o primeiro contato com programação, usando uma sintaxe em português e mantendo a lógica do Python como base.

[🌐 **Site oficial**](https://pyrtugues.netlify.app/) · [🧪 **Editor Web**](https://pyrtugues-editor.netlify.app/) · [📦 **Downloads**](https://github.com/pyrtugues/Pyrtugues/releases/latest) · [▶️ **YouTube**](https://www.youtube.com/@pyrtugues)

[![Versão](https://img.shields.io/badge/vers%C3%A3o-1.2.0-10B981?style=for-the-badge)](https://github.com/pyrtugues/Pyrtugues/releases)
[![Base](https://img.shields.io/badge/base-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Editor](https://img.shields.io/badge/editor-Web-111827?style=for-the-badge&logo=googlechrome&logoColor=white)](https://pyrtugues-editor.netlify.app/)
[![GitHub](https://img.shields.io/badge/GitHub-Pyrtugues-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pyrtugues/Pyrtugues)

</div>

---

## 📚 O que é o Pyrtugues?

**Pyrtugues** é um projeto educacional de programação em português criado para facilitar o primeiro contato com **lógica de programação e Python**.

A ideia é reduzir a barreira inicial causada pelos comandos em inglês sem trocar programação textual por blocos. O estudante aprende variáveis, condições, repetições, funções e expressões usando uma sintaxe em português e, ao mesmo tempo, consegue enxergar a relação com o Python tradicional.

O Pyrtugues funciona como uma **ponte para o Python**: o código em Pyrtugues é processado por um motor de tradução para uma sintaxe correspondente em Python antes da execução.

> **Programar em português → entender a lógica → enxergar o Python → aprender Python.**

---

## 🚀 Comece agora

### 🧪 Teste no navegador

**[Abrir o Editor Web do Pyrtugues](https://pyrtugues-editor.netlify.app/)**

Você pode experimentar o Pyrtugues diretamente no navegador usando a versão Web do projeto.

### 🖥️ Baixe para Windows

**[Baixar a versão mais recente](https://github.com/pyrtugues/Pyrtugues/releases/latest)**

A versão Desktop reúne editor e execução em uma aplicação gráfica para Windows.

### 🌐 Conheça o projeto

**[Visitar o site oficial](https://pyrtugues.netlify.app/)**

---

## 💡 Pyrtugues → Python

A proposta pode ser entendida com um exemplo simples.

### Pyrtugues

```pyrtugues
idade = 12

se idade maior que 10:
    mostrar("Olá! Você pode programar!")
```

### Python equivalente

```python
idade = 12

if idade > 10:
    print("Olá! Você pode programar!")
```

A sintaxe muda, mas a lógica de programação continua reconhecível.

---

## 🧠 Como funciona?

```text
┌─────────────────────────────┐
│       Código Pyrtugues      │
│                             │
│  se idade maior que 10:     │
│      mostrar("Olá!")       │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│      Motor de tradução      │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│       Código em Python      │
│                             │
│  if idade > 10:             │
│      print("Olá!")         │
└──────────────┬──────────────┘
               │
               ▼
           EXECUÇÃO
```

Na versão Web, a arquitetura usa **Pyrtugues → tradutor → Python → Pyodide → execução no navegador**.

---

## ✨ Recursos

| Recurso | Descrição |
|---|---|
| 🇧🇷 **Sintaxe em português** | Estruturas e comandos em português para o primeiro contato com programação |
| 🐍 **Base Python** | Conceitos e organização próximos da lógica do Python |
| 🔄 **Pyrtugues → Python** | Permite visualizar a relação entre as duas sintaxes |
| 🖥️ **Desktop** | Aplicação gráfica para Windows |
| 🌐 **Editor Web** | Experiência de programação diretamente no navegador |
| 📚 **Exemplos** | Programas para estudar e experimentar |
| ⌨️ **Editor de código** | Recursos de edição voltados para escrever e testar programas |
| 🧪 **Projeto em evolução** | Novas correções, recursos e exemplos podem chegar em versões futuras |

---

## 🔤 Pyrtugues ↔ Python

O vocabulário do projeto continua em desenvolvimento. Alguns exemplos de correspondência são:

| Pyrtugues | Python |
|---|---|
| `mostrar()` | `print()` |
| `pergunte()` | `input()` |
| `se` | `if` |
| `senão` | `else` |
| `senão se` | `elif` |
| `enquanto` | `while` |
| `para` | `for` |
| `em` | `in` |
| `função` | `def` |
| `retornar` | `return` |
| `importar` | `import` |
| `tentar` | `try` |
| `excepto` | `except` |
| `inteiro()` | `int()` |
| `decimal()` | `float()` |
| `texto()` | `str()` |
| `lista()` | `list()` |
| `dicionário()` | `dict()` |
| `tupla()` | `tuple()` |
| `conjunto()` | `set()` |
| `intervalo()` | `range()` |
| `tamanho()` | `len()` |
| `verdadeiro` | `True` |
| `falso` | `False` |
| `nulo` | `None` |

> O conjunto de comandos e a compatibilidade podem mudar conforme o desenvolvimento. Consulte o código e os exemplos da versão utilizada.

---

## 🧪 Exemplos práticos

### 👋 Olá, mundo

```pyrtugues
mostrar("Olá, mundo!")
```

### 📦 Variáveis

```pyrtugues
nome = "Vinicius"
idade = 12

mostrar(f"Meu nome é {nome} e tenho {idade} anos.")
```

### 🔀 Condição

```pyrtugues
idade = 12

se idade maior que 10:
    mostrar("Você passou da primeira etapa!")
senão:
    mostrar("Continue estudando!")
```

### 🔁 Repetição

```pyrtugues
para numero em intervalo(1, 6):
    mostrar(numero)
```

### 🧩 Função

```pyrtugues
função saudacao(nome):
    retornar f"Olá, {nome}!"

mostrar(saudacao("Pyrtugues"))
```

### 🧮 Calculadora

```pyrtugues
n1 = decimal(pergunte("Primeiro número: "))
op = pergunte("Operação (+, -, *, /): ")
n2 = decimal(pergunte("Segundo número: "))

se op == "+":
    mostrar(n1 + n2)
senão se op == "-":
    mostrar(n1 - n2)
senão se op == "*":
    mostrar(n1 * n2)
senão:
    mostrar(n1 / n2)
```

> Os exemplos mostram a proposta sintática. A compatibilidade exata de cada recurso depende da versão atual do motor de tradução.

---

## 🖥️ Versão Desktop

A versão Desktop foi desenvolvida com **Python + CustomTkinter** e reúne a edição e execução do Pyrtugues em uma interface gráfica.

**[📦 Baixar a versão mais recente](https://github.com/pyrtugues/Pyrtugues/releases/latest)**

O código principal da aplicação está no arquivo:

```text
Pyrtugues_code.py
```

---

## 🌐 Editor Web — Pyrtugues Online

O projeto possui um editor para experimentar **programação em português baseada em Python** diretamente no navegador.

**👉 https://pyrtugues-editor.netlify.app/**

A versão Web utiliza tecnologias de navegador e **Pyodide** para executar Python no ambiente do browser.

Entre os recursos disponíveis na versão Web estão:

- editor de código;
- tradução Pyrtugues → Python;
- execução no navegador;
- entrada interativa;
- exemplos;
- saída no terminal;
- visualização/cópia do Python gerado;
- download do código Python;
- execução do motor em Web Worker.

---

## 🌐 Site oficial

O site reúne a apresentação do projeto, informações sobre o Pyrtugues e links para as versões disponíveis.

**👉 https://pyrtugues.netlify.app/**

---

## 📂 Estrutura do repositório

```text
Pyrtugues/
├── assets/
│   └── logo-pyrtugues.png
├── LICENSE
├── README.md
├── Pyrtugues_code.py
├── index.html
├── Pyrtugues_Documentacao
└── ...
```

| Arquivo / pasta | Função |
|---|---|
| `assets/` | Recursos visuais do projeto |
| `LICENSE` | Termos de uso e distribuição |
| `README.md` | Documentação principal |
| `Pyrtugues_code.py` | Código principal da versão Desktop |
| `index.html` | Parte Web do projeto |
| `Pyrtugues_Documentacao`| Documentação do projeto |
---

## 🛠️ Tecnologias

### Desktop

- **Python**
- **CustomTkinter**
- **Tkinter**

### Web

- **HTML**
- **CSS**
- **JavaScript**
- **Tailwind CSS**
- **Pyodide**
- **Web Worker**

---

## 🚀 Começando pelo código-fonte

Clone o repositório:

```bash
git clone https://github.com/pyrtugues/Pyrtugues.git
```

Entre na pasta:

```bash
cd Pyrtugues
```

Depois, consulte os arquivos da parte Desktop ou Web que deseja estudar. O procedimento de execução pode variar conforme a parte do projeto utilizada.

---

## ❓ Perguntas frequentes

### O Pyrtugues é Python?

Não. O Pyrtugues é uma proposta de sintaxe em português baseada na lógica do Python, com um motor de tradução para Python.

### O Pyrtugues substitui o Python?

Não. O objetivo é funcionar como uma **ponte para o aprendizado de Python**.

### Preciso saber inglês para começar?

A proposta do Pyrtugues é reduzir a barreira inicial dos comandos em inglês para quem está começando.

### Onde posso testar?

No **[Editor Web do Pyrtugues](https://pyrtugues-editor.netlify.app/)**.

### O Pyrtugues está pronto?

O projeto está em desenvolvimento e pode receber novos recursos, correções e mudanças de compatibilidade.

---

## 🔎 Pyrtugues na internet

Para facilitar a identificação do projeto, os canais oficiais usam o mesmo nome e identidade:

| Canal | Endereço |
|---|---|
| 🌐 Site | [pyrtugues.netlify.app](https://pyrtugues.netlify.app/) |
| 🧪 Editor Web | [pyrtugues-editor.netlify.app](https://pyrtugues-editor.netlify.app/) |
| 💻 GitHub | [github.com/pyrtugues/Pyrtugues](https://github.com/pyrtugues/Pyrtugues) |
| 👤 Perfil | [github.com/pyrtugues](https://github.com/pyrtugues) |
| 📦 Releases | [Versão mais recente](https://github.com/pyrtugues/Pyrtugues/releases/latest) |
| ▶️ YouTube | [@pyrtugues](https://www.youtube.com/@pyrtugues) |

O projeto pode aparecer em pesquisas relacionadas a **Pyrtugues**, **programação em português**, **Python em português**, **programação baseada em Python** e **editor de Python em português**. A posição de cada página depende da indexação de cada buscador.

---

## 🌱 Estado do projeto

**Versão atual: 1.2.0**

O Pyrtugues continua em desenvolvimento. Entre as áreas que podem evoluir estão:

- novos comandos;
- melhorias no tradutor;
- tratamento de erros;
- novos exemplos e exercícios;
- documentação;
- experiência do editor;
- materiais educacionais;
- novas plataformas.

---

## 🤝 Contribuições

Sugestões, testes e contribuições podem ajudar o projeto a evoluir.

Você pode contribuir com:

- 🧪 testes;
- 🐛 identificação de bugs;
- 💡 sugestões de comandos;
- 📖 documentação;
- 🧩 exemplos educacionais;
- 💻 código.

Ao modificar o tradutor, é importante testar alterações que possam afetar nomes de variáveis, strings, comentários, f-strings, expressões e código já suportado.

**👉 [Abrir uma Issue](https://github.com/pyrtugues/Pyrtugues/issues)**

---

## 📜 Licença

O Pyrtugues **não utiliza a licença MIT atualmente**.

O projeto possui uma **licença própria**, com regras específicas para uso pessoal, educacional individual, institucional, comercial, redistribuição e modificações.

Antes de copiar, modificar, distribuir ou utilizar o Pyrtugues, consulte o arquivo **[`LICENSE`](./LICENSE)**.

A publicação do código no GitHub não deve ser interpretada como autorização para usos que a licença não permita.

---

## 👨‍💻 Criador

**Vinicius Caracciolo**

O Pyrtugues nasceu como um projeto pessoal voltado para **programação e educação**, com a ideia de tornar o primeiro contato com código mais acessível para falantes de português.

O projeto começou quando seu criador tinha **12 anos** e evoluiu para incluir uma aplicação Desktop, uma versão Web, documentação, exemplos e uma identidade própria.

---

## ⭐ Como apoiar o Pyrtugues

Você pode ajudar de formas simples:

- ⭐ dar uma estrela no GitHub;
- 🧪 testar o editor Web;
- 🐛 reportar bugs;
- 💡 sugerir melhorias;
- 📖 ajudar com documentação e exemplos;
- 🔗 compartilhar o projeto.

**👉 [Dar uma estrela no GitHub](https://github.com/pyrtugues/Pyrtugues)**

---

<div align="center">

# 💚 Pyrtugues

### Programação em português.
### Lógica de Python.
### Uma ponte para aprender.

**Pyrtugues — Python em português, feito para aprender programação.**

[🌐 Site](https://pyrtugues.netlify.app/) · [🧪 Editor Web](https://pyrtugues-editor.netlify.app/) · [💻 GitHub](https://github.com/pyrtugues/Pyrtugues) · [📦 Releases](https://github.com/pyrtugues/Pyrtugues/releases/latest) · [▶️ YouTube](https://www.youtube.com/@pyrtugues)

</div>
