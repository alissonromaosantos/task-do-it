<div align="center">

  # ✔️ Task: Do It

  ### 📝 Organize suas tarefas. Simplifique seu dia.

  Uma aplicação de gerenciamento de tarefas **leve, interativa e responsiva**, desenvolvida com **HTML5, CSS3 e JavaScript Vanilla**, utilizando uma interface moderna inspirada no conceito de **Glassmorphism**.

  <br />

  <a href="https://romaosantosalisson.github.io/task-do-it/">
    <img
      src="https://img.shields.io/badge/🌐%20Acessar%20Aplicação-Task%3A%20Do%20It-2ea44f?style=for-the-badge"
      alt="Acessar Task: Do It"
    />
  </a>

  <br /><br />

  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=yellow)
  ![LocalStorage](https://img.shields.io/badge/Web%20Storage-LocalStorage-6A5ACD?style=for-the-badge)

</div>

---

## 📖 Sobre o Projeto

O **Task: Do It** é uma aplicação web de gerenciamento de tarefas criada para demonstrar, na prática, conceitos fundamentais do desenvolvimento frontend utilizando **JavaScript puro**.

A aplicação permite **criar, concluir, editar e excluir tarefas**, mantendo os dados salvos no navegador através do `localStorage`.

O projeto também explora conceitos importantes como:

- 🌐 Manipulação do **DOM**
- 🖱️ Gerenciamento de eventos
- 💾 Persistência de dados no navegador
- 🎨 Estilização dinâmica com CSS
- 📱 Desenvolvimento **Mobile-First**
- 🪟 Interface com efeito **Glassmorphism**
- ✨ Microinterações e animações
- 🧩 Organização do código

> 💡 **Sem frameworks. Sem bibliotecas externas. Apenas HTML, CSS e JavaScript.**

---

## ✨ Funcionalidades

### ➕ Adicionar tarefas

Adicione novas tarefas rapidamente através do campo de entrada.

A nova tarefa é criada inicialmente como **pendente**.

### ✔️ Concluir tarefas

Alterne o status de uma tarefa entre:

- ⚪ Pendente
- ✔️ Concluída

Ao concluir uma tarefa, seu texto recebe o efeito de **tachado** e uma alteração visual para indicar seu novo estado.

### ✏️ Editar tarefas

Edite suas tarefas diretamente no cartão, sem abrir caixas de diálogo.

A edição pode ser iniciada através de:

- 🖱️ **Duplo clique** sobre o texto
- ✏️ **Botão de edição**

Durante a edição:

- `Enter` → 💾 Salvar
- `Escape` → ❌ Cancelar

### 🗑️ Excluir tarefas

Remova permanentemente qualquer tarefa da lista através do botão de exclusão.

### 💾 Persistência com LocalStorage

As tarefas são armazenadas no `localStorage` do navegador.

Isso permite que os dados permaneçam disponíveis mesmo depois de:

- 🔄 Recarregar a página
- 🚪 Fechar o navegador
- 💻 Retornar posteriormente à aplicação

### 📜 Rolagem automática

Ao adicionar uma nova tarefa, a lista realiza uma rolagem suave para manter a nova tarefa visível.

### ✨ Estado vazio

Quando não existem tarefas na lista, a aplicação apresenta uma mensagem amigável incentivando o usuário a adicionar uma nova tarefa.

### 🎯 Microinterações

A interface possui pequenas animações para tornar a interação mais agradável:

- 🔄 Rotação de ícones
- 📈 Efeito de escala nos botões
- 🆙 Elevação dos cartões ao passar o mouse
- 🎨 Transições suaves
- ✨ Feedback visual durante as ações

---

## 📱 Design Responsivo & Mobile-First

O **Task: Do It** foi desenvolvido seguindo uma abordagem **Mobile-First**.

A experiência começa sendo projetada para telas pequenas e, posteriormente, é adaptada para dispositivos maiores.

### 📐 Breakpoints

A interface utiliza breakpoints progressivos:

| Breakpoint | Largura mínima | Dispositivo |
|:---:|:---:|:---|
| 📱 Base | `< 640px` | Smartphones |
| 📲 `sm` | `640px` | Smartphones maiores / Tablets |
| 💻 `md` | `768px` | Tablets |
| 🖥️ `lg` | `1024px` | Notebooks / Desktops |
| 🖥️ `xl` | `1280px` | Monitores maiores |

### 🎯 Princípios utilizados

- 📱 Layout pensado primeiro para dispositivos móveis
- 🖥️ Expansão progressiva para telas maiores
- 🧩 Layout flexível
- 📐 Media Queries
- 📦 Componentes adaptáveis
- 👆🏻 Controles adequados para interação por toque
- 📖 Tipografia e espaçamentos responsivos

---

## 🪟 Interface & Glassmorphism

O design da aplicação utiliza uma estética moderna inspirada no **Glassmorphism**.

O cartão principal combina:

- 🌫️ Transparência
- 🪟 Efeito de vidro
- 🌁 `backdrop-filter`
- 🎨 Gradientes
- 🌑 Sombras suaves
- ✨ Transições e microinterações

O resultado é uma interface minimalista e visualmente agradável, sem comprometer a usabilidade.

---

## 🎨 Tipografia

A aplicação utiliza a família tipográfica **Poppins**, carregada através do Google Fonts.

São utilizados diferentes pesos para estabelecer uma hierarquia visual:

- `400` — Regular
- `500` — Medium
- `600` — Semi Bold
- `700` — Bold

As tarefas pendentes e concluídas também utilizam diferentes pesos para reforçar visualmente seus estados.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Utilização |
|:---|:---|
| 🧱 **HTML5** | Estrutura semântica da aplicação |
| 🎨 **CSS3** | Layout, responsividade, animações e Glassmorphism |
| ⚡ **JavaScript ES6+** | Lógica da aplicação e manipulação do DOM |
| 💾 **LocalStorage** | Persistência das tarefas |
| 🔤 **Google Fonts** | Tipografia Poppins |
| 🖼️ **SVG** | Favicon e elementos gráficos |

### 🚫 Sem frameworks

O projeto foi desenvolvido utilizando **JavaScript Vanilla**, sem frameworks frontend como:

- React
- Vue
- Angular

Também não depende de bibliotecas externas para executar sua lógica principal.

> **HTML + CSS + JavaScript. Simples, leve e direto ao ponto.** 🚀

---

## 📋 Requisitos do Projeto

O projeto foi desenvolvido considerando requisitos funcionais e não funcionais.

### ⚙️ Requisitos Não Funcionais

| ID | Requisito | Implementação |
|:---:|:---|:---|
| **NFR001** | Tipografia e identidade visual consistentes | Favicon personalizado e fonte Poppins |
| **NFR002** | Fundo com aparência moderna | Gradiente linear em tons de cinza |
| **NFR003** | Hierarquia visual de títulos | `h1` e `h2` com pesos tipográficos distintos |
| **NFR004** | Tarefas exibidas em cartões | Cards individuais com hover e transições |
| **NFR005** | Estrutura padronizada de tarefas | Objetos contendo informações da tarefa e seu status |
| **NFR006** | Campo para adicionar tarefas | Input acompanhado de botão de ação |
| **NFR007** | Ícones e emojis nas ações | Feedback visual através de ícones e microinterações |
| **NFR008** | Design responsivo | Desenvolvimento utilizando abordagem Mobile-First |

### ⚡ Requisitos Funcionais

| ID | Requisito | Implementação |
|:---:|:---|:---|
| **FR001** | Adicionar tarefas | Nova tarefa criada com status pendente |
| **FR002** | Alterar status | Alternância entre pendente e concluída |
| **FR003** | Excluir tarefas | Remoção da tarefa selecionada |
| **FR004** | Editar tarefas | Edição diretamente no cartão |
| **FR005** | Persistir dados | Tarefas armazenadas no `localStorage` |

---

## 🧠 Conceitos Técnicos

### 🌐 Manipulação do DOM

A interface é construída e atualizada dinamicamente através da API do DOM.

As alterações no estado das tarefas refletem imediatamente na interface sem necessidade de recarregar a página.

---

### 💾 Ciclo de Persistência

O array de tarefas funciona como a fonte de dados em memória.

Sempre que ocorre uma alteração, os dados são sincronizados com o `localStorage`.

Fluxo simplificado:

```text
📦 Estado em memória
       ↓
✏️ Alteração
       ↓
💾 LocalStorage
       ↓
🔄 Renderização
       ↓
🖥️ Interface atualizada
````

Exemplo:

```javascript
function saveTasks() {
  localStorage.setItem(
    'task_do_it_tasks',
    JSON.stringify(tasks)
  );
}
```

---

### ✏️ Editor Inline

A edição acontece diretamente dentro do cartão da tarefa.

Ao entrar no modo de edição, os elementos relacionados ao estado e às ações normais são temporariamente ocultados, dando espaço ao campo de edição.

```css
.task-card.editing .task-text,
.task-card.editing .status-btn,
.task-card.editing .standard-actions {
  display: none;
}

.task-card.editing .edit-input {
  display: block;
}

.task-card.editing .edit-actions {
  display: flex;
}
```

Isso proporciona uma experiência de edição mais fluida, sem a necessidade de abrir `prompt()` ou outra janela externa.

---

### ✨ Microinterações

Os elementos interativos utilizam transições suaves com curvas `cubic-bezier()` para criar uma sensação mais natural durante as interações.

Exemplo:

```css
.task-card {
  transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

.task-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.08);
}
```

---

## 📂 Arquitetura do Projeto

```text
task-do-it/
│
├── assets/
│   └── docs/
│       └── requirements.md
│
├── index.html
├── script.js
├── styles.css
└── README.md
```

### 📄 Principais arquivos

**`index.html`**
Estrutura principal da aplicação, incluindo cabeçalho, formulário e lista de tarefas.

**`script.js`**
Contém a lógica da aplicação, gerenciamento das tarefas, eventos, persistência e renderização do DOM.

**`styles.css`**
Responsável pelo layout, responsividade, tipografia, animações e efeitos de interação.

**`requirements.md`**
Documentação dos requisitos funcionais e não funcionais utilizados como base para o desenvolvimento.

---

## 🚀 Como Executar

O projeto é totalmente estático e **não requer instalação de dependências, compilação ou servidor backend**.

### 📋 Pré-requisitos

Você precisa apenas de:

* 🌐 Um navegador moderno
* 📁 Os arquivos do projeto

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/romaosantosalisson/task-do-it.git
```

### 2️⃣ Acesse o diretório

```bash
cd task-do-it
```

### 3️⃣ Abra a aplicação

Você pode abrir diretamente:

```text
index.html
```

no navegador.

---

## 💻 Executando com VS Code

Se estiver utilizando o **Visual Studio Code**, também é possível utilizar a extensão **Live Server**.

### Passos

1. 📂 Abra o projeto no VS Code.
2. 🔌 Instale a extensão Live Server.
3. ▶️ Clique em **Go Live**.
4. 🌐 A aplicação será aberta automaticamente no navegador.

---

## 🧑‍💻 Como Usar

### ➕ Adicionar uma tarefa

Digite uma tarefa no campo de entrada e:

* Pressione `Enter`
* Ou clique em `➕ Add`

---

### ✔️ Concluir uma tarefa

Clique no ícone de status:

```text
⚪ → ✔️
```

A tarefa será marcada como concluída.

Clique novamente para retornar ao estado pendente.

---

### ✏️ Editar uma tarefa

Você pode:

* 🖱️ Dar **duplo clique** sobre o texto
* ✏️ Clicar no botão de edição

Depois:

```text
Enter  → 💾 Salvar
Escape → ❌ Cancelar
```

---

### 🗑️ Excluir uma tarefa

Clique no botão:

```text
🗑️
```

A tarefa será removida permanentemente.

---

## 🎯 Objetivos do Projeto

O **Task: Do It** foi desenvolvido para consolidar conhecimentos fundamentais de desenvolvimento frontend, especialmente:

* 🧱 HTML5 semântico
* 🎨 CSS3
* 📱 Desenvolvimento Mobile-First
* 📐 Design responsivo
* ⚡ JavaScript ES6+
* 🌐 Manipulação do DOM
* 🖱️ Event Handling
* 💾 LocalStorage
* 🔄 Renderização dinâmica
* ✨ Animações e microinterações
* 🧩 Organização de código

---

## 🌐 Aplicação

<div align="center">

### 🚀 Experimente o Task: Do It

  <br />

  <a href="https://romaosantosalisson.github.io/task-do-it/">
    <img
      src="https://img.shields.io/badge/🌐%20Abrir%20Task%3A%20Do%20It-Visitar%20Aplicação-2ea44f?style=for-the-badge"
      alt="Abrir Task: Do It"
    />
  </a>

<br /><br />

👉🏻 **[Acessar o Task: Do It](https://romaosantosalisson.github.io/task-do-it/)**

</div>

---

## 🤝🏻 Contribuição

Contribuições, sugestões e melhorias são bem-vindas! 🚀

Para contribuir:

1. 🍴 Faça um **Fork** do projeto.
2. 🌿 Crie uma nova branch.
3. ✏️ Faça suas alterações.
4. 💾 Realize um commit.
5. 🚀 Abra um **Pull Request**.

---

## 👨🏻‍💻 Autor

<div align="center">

### Álisson Romão Santos

Desenvolvido com ❤️, ☕ e JavaScript puro.

  <br />

  <a href="https://github.com/romaosantosalisson">
    <img
      src="https://img.shields.io/badge/GitHub-Álisson%20Romão%20Santos-181717?style=for-the-badge&logo=github&logoColor=white"
      alt="GitHub - Álisson Romão Santos"
    />
  </a>

</div>

---

<div align="center">

### ⭐ Gostou do projeto?

Se o **Task: Do It** foi útil ou interessante para você, considere deixar uma ⭐ no repositório!

  <br />

✔️ **Task: Do It**

  <br />

*Feito com ❤️, ☕ e JavaScript puro.*

  <br />

**© 2026 — Álisson Romão Santos**

</div>
