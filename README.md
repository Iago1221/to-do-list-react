# ✅ ToDo App

Uma aplicação de lista de tarefas desenvolvida com **React +
Typescript**, usando **Vite**, **TailwindCSS**, **React Router** e
armazenamento no **localStorage**.\
O design foi baseado no layout da **Rocketseat**:
[📁 Acessar layout no Figma](https://www.figma.com/community/file/1507067269388806436/lista-de-tarefas)

------------------------------------------------------------------------

## 🚀 Tecnologias utilizadas

| Tecnologia                   | Descrição                                            |
|------------------------------|------------------------------------------------------|
| **React 19**                 | Biblioteca para criação de interfaces                |
| **Typescript**               | Superset do JavaScript com tipagem estática          |
| **Vite**                     | Ferramenta de build e servidor de desenvolvimento    |
| **TailwindCSS 4**            | Estilização baseada em utility-first                 |
| **React Router**             | Navegação entre páginas                              |
| **use-local-storage**        | Hook para salvar dados no localStorage               |
| **class-variance-authority** | Padronização de estilos por variantes                |
| **SVGR**                     | Importação de SVG como componentes React             |

------------------------------------------------------------------------

## 📁 Estrutura do projeto

    📦 src/
     ├── assets/          # Imagens e ícones
     ├── components/      # Componentes reutilizáveis
     ├── core-components/ # Componentes da aplicação
     ├── helpers/         # Utils auxiliares
     ├── hooks/           # Hooks personalizados
     ├── models/          # Modelos da aplicação
     ├── pages/           # Páginas da aplicação
     ├── App.tsx
     ├── main.tsx
     ├── index.css

------------------------------------------------------------------------

## ⚙️ Como executar o projeto

### 📌 1. Clonar o repositório

``` bash
git clone https://github.com/iago1221/to-do-list-react.git
cd to-do-list-react
```

### 📌 2. Instalar as dependências

``` bash
npm install
```

### 📌 3. Iniciar o servidor de desenvolvimento

``` bash
npm run dev
```

### 📌 4. Gerar build de produção

``` bash
npm run build
```

------------------------------------------------------------------------

## 🌐 Deploy no GitHub Pages (opcional)

### 📁 1. Instalar pacote de deploy

``` bash
npm install gh-pages --save-dev
```

### 📁 2. Configurar `vite.config.ts`

``` js
export default defineConfig({
  base: "/to-do-list-react/",
  plugins: [react(), tailwindcss(), svgr()],
})
```

### 📁 3. Adicionar scripts no `package.json`

``` json
"predeploy": "npm run build",
"deploy": "gh-pages -d dist"
```

### 📁 4. Publicar

``` bash
npm run deploy
```

------------------------------------------------------------------------

## ✅ Funcionalidades

✔ Adicionar tarefas\
✔ Alterar tarefas\
✔ Marcar como concluída / pendente\
✔ Excluir tarefas\
✔ Armazenamento automático no localStorage\
✔ Interface responsiva\
✔ Navegação com React Router

------------------------------------------------------------------------

## 👨‍💻 Autor

-   **Iago Oliveira**
-   GitHub: https://github.com/iago1221
-   LinkedIn: https://linkedin.com/in/in-iago-oliveira