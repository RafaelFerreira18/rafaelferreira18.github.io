Site feito em HTML/CSS e Django para me apresentar, mostrando imagem, contatos, minha educação e um formulário Django para mandar mensagens e elas são guardadas no banco de dados e podem ser vistas no Admin do Django, os arquivos foram organizados com base no modelo Django, a parte HTML está armazenada na pasta templates do app portfolioPage criado usando python manage.py startapp e a parte CSS está armazenado na pasta static do app portfolioPage também, para começar o projeto primeiro foi necessário criar um ambiente virtual python e apartir dele instalar o Django e o python-decouple para poder esconder a SECRET-KEY do Django, depois de tudo instalado eu conectei o projeto ao meu github utilizando a chave SSH e criei o arquivo .gitignore para não enviar a pasta venv e o arquivo .env que está sendo utilizado para guardar a SECRET-KEY, além disso utilizei o comando pip freeze > requirements.txt para criar um arquivo de todos os módulos necessários para o projeto. Para hospedar o site utilizei o Railway, assim podendo fazer deploy com base no repositório do github, para conseguir hospedar o site nessa plataforma foi necessário ter que enviar o arquivo .env com a SECRET-KEY. Para acessar o admin do Django criei um superuser cujo nome é rafab e senha é 0q9w8e7r.