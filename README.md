# Blog Pessoal com Flask

## Descrição
Um blog completo desenvolvido com Flask, com sistema de autenticação, criação/edição/exclusão de posts, e comentários. O design utiliza Bootstrap 5 e CSS customizado com efeitos hover e gradientes.

## Funcionalidades
- Registro e login de usuários (senhas criptografadas)
- Usuários autenticados podem criar posts
- Usuários podem editar e excluir apenas seus próprios posts
- Qualquer usuário logado pode comentar em posts
- Exclusão de comentários pelo autor
- Interface responsiva e moderna
- Mensagens flash para feedback de ações
- Persistência em SQLite (banco de dados local)

## Como executar

1. **Clone ou crie a estrutura de pastas** conforme acima.

2. **Crie um ambiente virtual e instale as dependências:**
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
   pip install -r requirements.txt