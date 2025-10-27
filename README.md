# 📝 Prompts - Gerenciador de Prompts

<div align="center">
  <img src="assets/logo.svg" alt="Logo Prompts" width="200"/>
  
  Um gerenciador inteligente de prompts desenvolvido durante o **NLW Pocket** da Rocketseat.
  
  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
</div>

## 📖 Sobre o Projeto

O **Prompts** é uma aplicação web moderna e intuitiva para gerenciar seus prompts de IA, textos reutilizáveis ou anotações. Desenvolvido durante as 3 aulas do evento **NLW Pocket** da Rocketseat, o projeto oferece uma interface elegante com tema dark e funcionalidades completas de CRUD.

### ✨ Funcionalidades

- ✅ **Criar novos prompts** com título e conteúdo
- 📝 **Editar prompts existentes** de forma intuitiva
- 🗑️ **Remover prompts** indesejados
- 🔍 **Buscar prompts** por título
- 📋 **Copiar conteúdo** para área de transferência
- 💾 **Persistência de dados** usando LocalStorage
- 📱 **Layout responsivo** - funciona perfeitamente em desktop e mobile
- 🎨 **Interface moderna** com tema dark

## 🚀 Tecnologias

Este projeto foi desenvolvido com as seguintes tecnologias:

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização e responsividade
  - CSS Variables
  - Flexbox
  - Media Queries
  - Transitions e Animations
- **JavaScript Vanilla** - Lógica e interatividade
  - LocalStorage API
  - DOM Manipulation
  - Event Listeners
  - ES6+ Features

## 📁 Estrutura do Projeto

```
prompts/
├── assets/
│   ├── collapse.svg      # Ícone de fechar menu
│   ├── copy.svg          # Ícone de copiar
│   ├── favicon.svg       # Favicon
│   ├── logo.svg          # Logo da aplicação
│   ├── open.svg          # Ícone de abrir menu
│   ├── remove.svg        # Ícone de remover
│   └── search.svg        # Ícone de busca
├── index.html            # Estrutura HTML
├── script.js             # Lógica da aplicação
├── style.css             # Estilização
└── README.md             # Documentação
```

## 🎯 Como Usar

### Pré-requisitos

- Um navegador web moderno (Chrome, Firefox, Safari, Edge)
- Nenhuma instalação adicional necessária!

### Instalação

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/prompts.git
```

2. Navegue até a pasta do projeto:
```bash
cd prompts
```

3. Abra o arquivo `index.html` no seu navegador:
```bash
# No macOS
open index.html

# No Windows
start index.html

# No Linux
xdg-open index.html
```

Ou simplesmente arraste o arquivo `index.html` para o navegador.

## 💡 Como Funciona

### Criando um Novo Prompt

1. Clique no botão **"Novo prompt"** na sidebar
2. Digite o título do prompt no campo superior
3. Escreva o conteúdo do prompt no editor
4. Clique em **"Salvar"** para armazenar

### Editando um Prompt

1. Clique em um prompt existente na lista lateral
2. Modifique o título ou conteúdo conforme necessário
3. Clique em **"Salvar"** para atualizar as alterações

### Copiando um Prompt

1. Selecione o prompt desejado
2. Clique no botão **"Copiar"** no canto superior direito
3. O conteúdo será copiado para sua área de transferência

### Buscando Prompts

1. Digite no campo de busca na sidebar
2. A lista será filtrada automaticamente
3. Os resultados aparecem em tempo real

### Removendo um Prompt

1. Localize o prompt na lista
2. Clique no ícone de **lixeira** (🗑️) ao lado do prompt
3. O prompt será removido permanentemente

## 🎨 Paleta de Cores

```css
--white: #ffffff
--accent-600: #4863f7      /* Azul principal */
--accent-500: #7878d7      /* Azul secundário */
--alert-600: #ff5c5c       /* Vermelho de alerta */
--gray-900: #0d0d0d        /* Fundo principal */
--gray-800: #111111        /* Fundo sidebar */
--gray-700: #1a1a1a        /* Bordas */
--gray-200: #424242        /* Elementos secundários */
--gray-100: #737373        /* Texto secundário */
```

## 📱 Responsividade

A aplicação é totalmente responsiva e se adapta a diferentes tamanhos de tela:

- **Desktop (> 950px)**: Sidebar fixa visível
- **Mobile (≤ 950px)**: Sidebar colapsável com menu hambúrguer

## 💾 Armazenamento

Os dados são salvos localmente no navegador usando a **LocalStorage API**, o que significa:

- ✅ Seus prompts permanecem salvos mesmo após fechar o navegador
- ✅ Não é necessário servidor ou banco de dados
- ⚠️ Os dados são específicos do navegador e dispositivo
- ⚠️ Limpar os dados do navegador apagará seus prompts

## 🎓 Aprendizados

Este projeto foi desenvolvido durante o **NLW Pocket** em 3 aulas, abordando:

- Manipulação do DOM com JavaScript
- Gerenciamento de estado da aplicação
- Persistência de dados com LocalStorage
- Event delegation e event handling
- CSS moderno com variáveis e responsividade
- Contenteditable para edição inline
- Implementação de busca em tempo real

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abrir um Pull Request

## 📝 Licença

Este projeto foi desenvolvido durante o NLW Pocket da Rocketseat para fins educacionais.

## 👨‍💻 Autor

Desenvolvido com 💜 durante o **NLW Pocket** da [Rocketseat](https://rocketseat.com.br)

---

<div align="center">
  Feito com ❤️ durante as 3 aulas do NLW Pocket
</div>

