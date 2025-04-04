# Todo App com Vue.js

![Vue.js](https://img.shields.io/badge/Vue.js-3.x-brightgreen) ![Bootstrap](https://img.shields.io/badge/Bootstrap-5.x-blue) ![Vite](https://img.shields.io/badge/Vite-6.x-purple)

Este é um aplicativo de lista de tarefas (Todo App) desenvolvido com **Vue.js 3**, utilizando **Vite** como ferramenta de build e **Bootstrap 5** para estilização. O objetivo do projeto é oferecer uma interface simples e funcional para gerenciar tarefas, com suporte a filtros e persistência de dados no navegador.

---

## 🎯 Funcionalidades

- ✅ **Adicionar tarefas**: Insira uma nova tarefa com descrição.
- ✅ **Marcar como concluída**: Marque tarefas como finalizadas.
- ✅ **Filtrar tarefas**: Visualize tarefas pendentes, concluídas ou todas.
- ✅ **Persistência de dados**: As tarefas são armazenadas no Local Storage, garantindo que não sejam perdidas ao recarregar a página.
- ✅ **Interface responsiva**: Estilização com Bootstrap para uma experiência agradável em dispositivos móveis e desktops.

---

## 🛠️ Tecnologias Utilizadas

- **[Vue.js 3](https://vuejs.org/)**: Framework JavaScript progressivo para construção de interfaces de usuário.
- **[Vite](https://vitejs.dev/)**: Ferramenta de build rápida e moderna.
- **[Bootstrap 5](https://getbootstrap.com/)**: Framework CSS para estilização responsiva.
- **Local Storage**: Para armazenamento persistente de dados no navegador.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos

- **Node.js** (versão 16 ou superior)
- **npm** (gerenciador de pacotes do Node.js)

### Passos para rodar o projeto

1. **Clone o repositório**:
   ```sh
   git clone https://github.com/seu-usuario/todo-vue.git
   cd todo-vue
   ```

2. **Instale as dependências**:
   ```sh
   npm install
   ```

3. **Inicie o servidor de desenvolvimento**:
   ```sh
   npm run dev
   ```

4. **Acesse o aplicativo**:
   Abra o navegador e acesse: [http://localhost:5173](http://localhost:5173)

---

## 📂 Estrutura do Projeto

```plaintext
todo-vue/
├── public/               # Arquivos públicos (favicon, etc.)
├── src/                  # Código-fonte do projeto
│   ├── components/       # Componentes Vue
│   │   ├── Cabecalho.vue # Cabeçalho do aplicativo
│   │   ├── Formulario.vue # Formulário para adicionar tarefas
│   │   ├── ListaDeTarefas.vue # Lista de tarefas
│   ├── App.vue           # Componente principal
│   ├── main.js           # Arquivo de entrada
├── .gitignore            # Arquivos ignorados pelo Git
├── package.json          # Configurações do projeto e dependências
├── vite.config.js        # Configuração do Vite
└── README.md             # Documentação do projeto
```

---

## 📸 Capturas de Tela

![image](https://github.com/user-attachments/assets/c05a25a3-079e-4f24-89d5-b7f5d6902762)



## 📖 Como Funciona

1. **Adicionar Tarefa**:
   - Digite a descrição da tarefa no campo de texto e clique em "Cadastrar".
   - A tarefa será exibida na lista.

2. **Marcar como Concluída**:
   - Clique na caixa de seleção ao lado da tarefa para marcá-la como finalizada.
   - Tarefas concluídas serão riscadas.

3. **Filtrar Tarefas**:
   - Use o menu suspenso para alternar entre "Todas tarefas", "Pendentes" e "Finalizadas".

4. **Persistência de Dados**:
   - As tarefas são salvas automaticamente no Local Storage do navegador.

---

## 📚 Aprendizados

Este projeto foi desenvolvido com o objetivo de praticar:
- Componentização no Vue.js.
- Gerenciamento de estado reativo com `reactive`.
- Estilização responsiva com Bootstrap.

---

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

1. Faça um fork do projeto.
2. Crie uma branch para sua feature:
   ```sh
   git checkout -b minha-feature
   ```
3. Commit suas alterações:
   ```sh
   git commit -m 'Adiciona minha nova feature'
   ```
4. Envie para o repositório remoto:
   ```sh
   git push origin minha-feature
   ```
5. Abra um Pull Request.

---


## 🌟 Agradecimentos

- [Vue.js](https://vuejs.org/)
- [Bootstrap](https://getbootstrap.com/)
- [Vite](https://vitejs.dev/)
