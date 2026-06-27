# Gerenciador de Tarefas (React + Vite)

Este é um projeto de **Gerenciador de Tarefas (Todo List)** moderno, responsivo e interativo, construído com React, Vite, TailwindCSS e React Router. O projeto foi desenvolvido para demonstrar conceitos fundamentais do React, como gerenciamento de estados, propriedades (props), hooks (`useState`, `useEffect`), roteamento dinâmico e persistência de dados.

## 🚀 Funcionalidades

- **Adicionar Tarefas:** Adicione novas tarefas com título e descrição detalhada.
- **Listar e Concluir Tarefas:** Veja a lista de tarefas pendentes e conclua-as com um simples clique.
- **Detalhes da Tarefa:** Navegue para uma página de detalhes exclusiva para visualizar o título e a descrição de uma tarefa selecionada.
- **Remover Tarefas:** Exclua facilmente qualquer tarefa da sua lista.
- **Persistência Local (LocalStorage):** Seus dados não são perdidos ao recarregar a página; as tarefas ficam salvas localmente no navegador.
- **Design Responsivo:** Interface limpa, elegante e moderna estilizada com TailwindCSS.

---

## 🛠️ Tecnologias Utilizadas

- **[React](https://react.dev/):** Biblioteca JavaScript para construção de interfaces.
- **[Vite](https://vitejs.dev/):** Ferramenta de build rápida e leve para projetos web.
- **[TailwindCSS](https://tailwindcss.com/):** Framework CSS utilitário para design rápido e moderno.
- **[React Router DOM](https://reactrouter.com/):** Gerenciamento de rotas e navegação na aplicação.
- **[Lucide React](https://lucide.dev/):** Biblioteca de ícones bonitos e minimalistas.
- **[UUID](https://github.com/uuidjs/uuid):** Geração de identificadores únicos para as tarefas.

---

## 📂 Estrutura de Arquivos

```text
src/
├── assets/             # Arquivos de mídia estáticos
├── components/         # Componentes reutilizáveis
│   ├── AddTask.jsx     # Formulário para inserção de novas tarefas
│   ├── Button.jsx      # Componente de botão customizado
│   ├── Input.jsx       # Componente de input padrão estilizado
│   ├── Tasks.jsx       # Lista que renderiza os itens de tarefas
│   └── Title.jsx       # Título estilizado da aplicação
├── pages/              # Páginas da aplicação (Roteamento)
│   └── TaskPage.jsx    # Tela com detalhes específicos da tarefa
├── App.css             # Estilos CSS específicos do App
├── App.jsx             # Componente raiz da aplicação com a lógica de estado
├── index.css           # Configurações globais e diretivas do Tailwind CSS
└── main.jsx            # Ponto de entrada do React com o Router Provider
```

---

## ⚙️ Instalação e Execução

Para rodar o projeto localmente em sua máquina, siga os passos abaixo:

### Pré-requisitos
Certifique-se de ter o **Node.js** instalado em seu computador.

### Passo a Passo

1. **Clone o repositório ou navegue até a pasta do projeto:**
   ```bash
   cd c:/aulao/react
   ```

2. **Instale as dependências:**
   Você pode usar o gerenciador de pacotes de sua preferência (`pnpm`, `npm` ou `yarn`):
   ```bash
   pnpm install
   # ou
   npm install
   # ou
   yarn install
   ```

3. **Inicie o servidor de desenvolvimento:**
   ```bash
   pnpm dev
   # ou
   npm run dev
   # ou
   yarn dev
   ```

4. **Acesse a aplicação:**
   Abra o navegador e acesse a URL indicada no terminal (geralmente [http://localhost:5173](http://localhost:5173)).

---

## 📝 Scripts Disponíveis

No arquivo `package.json`, estão disponíveis os seguintes comandos:

- `npm run dev`: Inicia o servidor de desenvolvimento local.
- `npm run build`: Compila a aplicação para produção (otimizada para implantação).
- `npm run lint`: Executa o ESLint para encontrar e corrigir problemas no código.
- `npm run preview`: Visualiza localmente o build de produção gerado.
