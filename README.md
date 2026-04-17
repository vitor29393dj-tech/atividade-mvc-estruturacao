# Atividade: Estruturação MVC e UX

## 🗺️ Mapeamento da Jornada do Usuário (UX)
Este projeto simula a estrutura de um sistema web organizado sob o padrão MVC.

### 📋 Menu Principal
- **Início:** Tela de boas-vindas com o resumo do sistema.
- **Cadastro:** Página para inserção de novos registros.
- **Relatórios:** Listagem e consulta de dados salvos.

### 🚀 Fluxo de Ação (Função Principal)
1. O usuário acessa a tela de "Cadastro".
2. Preenche todos os campos obrigatórios do formulário.
3. Clica no botão "Enviar/Salvar".
4. O sistema processa os dados e exibe uma mensagem de "Sucesso".

### ♿ Acessibilidade e Usabilidade
- **Melhoria aplicada:** Botões com textos claros e cores de alto contraste para facilitar a leitura.
- **Navegação:** Menu simplificado para que o usuário encontre qualquer função em menos de 3 cliques.

---
## 🚀 Progresso do Desenvolvimento - Parte 2

### Status das Rotas
- O arquivo `NavigationController.php` atua como o intermediário. Ao receber um comando da View, ele simula a validação e o redirecionamento para a tela correta.

### Feedback ao Usuário
- **Visual (CSS):** Botões configurados com alto contraste e efeito `:hover` no `style.css`.
- **Interativo (JS):** Função no `main.js` que dispara um alerta e muda a cor da página para confirmar que a ação foi realizada.

### Dificuldades Técnicas
- O maior desafio foi garantir que cada arquivo estivesse na pasta correta seguindo o padrão MVC, especialmente ao criar subpastas (`css/`, `js/`) diretamente pelo site do GitHub.

