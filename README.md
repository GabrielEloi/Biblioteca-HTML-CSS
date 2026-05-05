#  Biblioteca HTML + CSS

Uma coleção de componentes reutilizáveis para construção de interfaces web.

---

# Componentes

* Header (Cabeçalho)
* Footer (Rodapé)
* Sidebar (Menu lateral)
* Login Flutuante
* Botões
* Card
* Modal
* Tabela

---

# 🔷 Header (Cabeçalho)

## 📖 Descrição

Componente de navegação superior com ícone, busca e links.

---

## ⚙️ Como utilizar

1. Faça o link do CSS (`style.css`)
2. Adicione a biblioteca de ícones:

```html
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet" />
```

3. Utilize a estrutura:

```html
<header class="header">
    <div class="round">
        <span class="icon material-symbols-outlined">face_2</span>
        <div class="search">
            <input type="search" placeholder="Search...">
        </div>
        <div class="links">
            <a class="link" href="#">Home</a>
            <a class="link" href="#">About</a>
            <a class="link" href="#">Footer</a>
        </div>
    </div>
</header>
```

---

# Footer (Rodapé)

## 📖 Descrição

Rodapé com ícones, links e informações de copyright.

---

## ⚙️ Como utilizar

1. Faça o link do CSS (`style.css`)
2. Adicione a biblioteca de ícones:

```html
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet" />
```

3. Utilize a estrutura:

```html
<footer class="footer">
    <div class="empty">
        <hr>
    </div>
    <div class="content-footer">
        <span class="material-symbols-outlined">face_2</span>
        <p>©Copyright 2026 </p>
        <div class="icons-footer">
            <a href="#"><span class="material-symbols-outlined">chat</span></a>
            <a href="#"><span class="material-symbols-outlined">contacts</span></a>
        </div>
    </div>
</footer>
```

4. O `body` deve ocupar toda a altura da tela (`100vh`)

---

# Sidebar (Menu Lateral)

## 📖 Descrição

Menu de navegação vertical com links e ações auxiliares.

---

## ⚙️ Como utilizar

1. Faça o link do CSS (`style.css`)
2. Adicione a biblioteca de ícones:

```html
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet" />
```

3. Utilize a estrutura:

```html
<main class="main-sidebar">
    <section class="sidebar">
        <span class="material-symbols-outlined">face_2  </span>
        <div class="div-sidebar">
            <a href="#"><span class="material-symbols-outlined">home</span>Home</a>
            <a href="#"><span class="material-symbols-outlined">task_alt</span>Task</a>
            <a href="#"><span class="material-symbols-outlined">shelves</span>Catalog</a>
            <a href="#"><span class="material-symbols-outlined">route</span>Route</a>
            <a href="#"><span class="material-symbols-outlined">help</span>About</a>
        </div>
        <div class="footer-sidebar">
            <a href="#">LogOut</a>
            <a href="#">HelpDesk</a>
        </div>
    </section>
</main>
```

---

# Login Flutuante

## 📖 Descrição

Formulário de autenticação centralizado/flutuante.

---

## ⚙️ Como utilizar

1. Faça o link do CSS (`style.css`)
2. Adicione a biblioteca de ícones:

```html
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet" />
```

3. Utilize a estrutura:

```html
<section class="floating">
    <h1>Tela de login</h1>
    <form action="" class="floating-form">
        <div class="user">
            <label for="usuario">Usuario:</label>
            <input type="text" name="usuario">
        </div>
        <div class="pass">
            <label for="senha">Senha:</label>
            <input type="text">
        </div>    
        <input type="submit" value="Entrar" class="enter">
    </form>
</section>
```

---

# Botões 

## 📖 Descrição

Elementos de ação com diferentes estilos visuais.

---

## ⚙️ Como utilizar

1. Faça o link do CSS (`style.css`)

---

### 🎨 Variações

#### Botão preenchido

```html
<button class="button-filled">Filled Button</button>
```

#### Botão vazio

```html
<button class="button-empty">Empty Button</button>
```

#### Botão com borda animada

```html
<button class="button-borderchange">Border Change Button</button>
```

---

# 🧱 Card

## 📖 Descrição

Container para exibir conteúdo estruturado.

---

## ⚙️ Como utilizar

1. Faça o link do CSS (`style.css`)

```html
<div class="card">
    <h2 class="card__titulo">Título</h2>
    <p class="card__conteudo">Conteúdo do card</p>
</div>
```

---

# 🪟 Modal

## 📖 Descrição

Janela sobreposta para exibir informações ou ações.

---

## ⚙️ Como utilizar

1. Faça o link do CSS (`style.css`)
2. Adicione a biblioteca de ícones:

```html
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined" rel="stylesheet" />
```

```html
<div class="modal">
    <div class="modal-title">
        <a href=""><span class="material-symbols-outlined">close</span></a>
        <h1>Modal Example</h1>
    </div>
    <div class="modal-content">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit...</p>
        <button class="button-filled">Ok!</button>
    </div>
</div>
```

---

# 📊 Tabela 

## 📖 Descrição

Estrutura para exibição de dados tabulares.

---

## ⚙️ Como utilizar

1. Faça o link do CSS (`style.css`)

```html
<div class="table-title">
    <h1>Tabela bonita</h1>
    <div class="table">
        <table>
            <tr>
                <th>Coluna 1</th>
                <th>Coluna 2</th>
                <th>Coluna 3</th>
            </tr>
            <tr>
                <td>Ex 1 Coluna 1</td>
                <td>Ex 1 Coluna 2</td>
                <td>Ex 1 Coluna 3</td>
            </tr>
            <tr>
                <td>Ex 2 Coluna 1</td>
                <td>Ex 2 Coluna 2</td>
                <td>Ex 2 Coluna 3</td>
            </tr>
            <tr>
                <td>Ex 3 Coluna 1</td>
                <td>Ex 3 Coluna 2</td>
                <td>Ex 3 Coluna 3</td>
            </tr>
        </table>
    </div>
</div>
```


# 📊 Grid Layout 

## 📖 Descrição

Estrutura para exibição de texto e imagens.

---

## ⚙️ Como utilizar
1. Faça o link do CSS (`style.css`)
```html
<section class="flex-grid">
    <div class="main-grid">
        <div class="img-grid">
            <h1>Example</h1>
            <img src="img.png" alt="img">
        </div>
        <div class="description-grid">
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Laudantium ut quis numquam neque inventore reiciendis incidunt sapiente voluptas itaque eum! Nam minus modi aliquid vero at, molestiae libero illo! Dignissimos.
            </p>
        </div>
    </div>
    <div class="side-grid">
        <h1>Title</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora vitae facere perspiciatis voluptatum, assumenda aliquid nam qui minima quidem nisi similique iste fugiat corrupti quam quas dolorum provident, cumque repellendus. Lorem ipsum dolor sit amet consectetur adipisicing elit. Aut molestias quaerat dicta rerum debitis similique repudiandae distinctio nostrum, earum esse veniam est eos officiis minus dignissimos repellat aliquam blanditiis. Quam. Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias vitae dolor nihil accusamus. Voluptatem id neque inventore vitae, asperiores dolore distinctio similique est alias exercitationem consectetur eum, facere, itaque voluptas.
        </p>
    </div>
</section>
```
