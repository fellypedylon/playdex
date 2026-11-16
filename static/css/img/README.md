<div align="center">
🎮 Playdex
Sua biblioteca de jogos, organizada do seu jeito.

Catálogo web para cadastrar, visualizar e gerenciar a sua coleção de games, construído com Python + Flask.

Mostrar imagem Mostrar imagem Mostrar imagem Mostrar imagem Mostrar imagem Mostrar imagem

🚀 Demo ao vivo · 📸 Screenshots · ⚙️ Como rodar

</div>
📸 Screenshots

Substitua pelas suas capturas de tela (salve em docs/ ou static/img/).

Home / Lista de jogos	Cadastro de jogo
Lista	Cadastro
<!-- Dica: um GIF curto mostrando o uso do app chama MUITO mais atenção. --> <!-- ![Demo](docs/demo.gif) -->
💡 Sobre o projeto

O Playdex nasceu como meu primeiro projeto com Flask e evoluiu para um catálogo de jogos completo. A ideia é simples: ter um lugar bonito e rápido para registrar tudo o que você joga, quer jogar ou já zerou.

Mais do que uma lista, o projeto foi pensado para praticar boas práticas de backend: rotas, templates dinâmicos, separação de responsabilidades e, nas próximas etapas, persistência em banco de dados e autenticação.

✨ Funcionalidades
📋 Listagem dinâmica de jogos renderizada com Jinja2 (nada de conteúdo fixo no HTML)
➕ Cadastro de novos jogos (nome, categoria e console)
🎨 Interface responsiva com tema dark e cards interativos
🧩 Templates reutilizáveis com herança (base.html)
🔔 Mensagens de feedback para o usuário (flash messages)
🛣️ Roadmap
[x] Estrutura base com Flask e ambiente virtual
[x] Conteúdo dinâmico com Jinja2
[x ] Formulário de cadastro (POST)
[ ] Banco de dados com SQLAlchemy
[ ] Editar e excluir jogos (CRUD completo)
[ ] Login e sessão de usuário
[ ] Busca e filtro por console/categoria
[ ] Upload de capa do jogo
[ ] Deploy online
🛠️ Tecnologias
Camada	Tecnologia
Linguagem	Python
Framework	Flask
Templates	Jinja2
Front-end	HTML5, CSS3
Ambiente	venv
⚙️ Como rodar localmente
bash
# 1. Clone o repositório
git clone https://github.com/fellypedylon/playdex.git
cd playdex

# 2. Crie e ative o ambiente virtual
python -m venv venv

# Windows
venv\Scripts\activate
# Linux/macOS
source venv/bin/activate

# 3. Instale as dependências
pip install -r requirements.txt

# 4. Rode a aplicação
python jogoteca.py

Depois, acesse http://localhost:5000 no navegador.

📁 Estrutura do projeto
playdex/
├── jogoteca.py          # Aplicação Flask (rotas e lógica)
├── templates/
│   ├── base.html        # Layout base (navbar, rodapé)
│   └── lista.html       # Página de listagem de jogos
├── static/
│   ├── css/             # Estilos
│   └── img/             # Imagens e capas
├── requirements.txt
└── README.md
🧠 O que aprendi
Como o Flask recebe requisições e devolve páginas com render_template
Como enviar dados do Python para o HTML e exibi-los com Jinja2 ({{ }} e {% %})
Organização de um projeto web com ambiente virtual e estrutura de pastas
Como pensar em um projeto de portfólio além do passo a passo da aula
👨‍💻 Autor

Fellype Dylon Estudante de Engenharia de Software · Foco em backend com Python

GitHub LinkedIn

<div align="center">

⭐ Se gostou do projeto, deixe uma estrela no repositório!

</div>