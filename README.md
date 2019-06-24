===================================
Django Blog Na minha cozinha |Última versão|
===================================

Um blog simples e intuitivo, permitindo a inscrição de utilizadores e que cada inscrito possa partilhar a sua receita adicionando uma foto.
Podem ainda pesquisar por qualquer palavra que pretendam e todos os conteúdos no blog com essa chave vão aparecer.


Funcionalidades
========

Lista de funcionalidades importantes:

* Ferramenta de pesquisa avançada
* Inscrição de utilizador
* Login de utilizador
* Visualização de quem interage
* Publicar, atualizar e remover publicação
* Painel de Administrador
* `Bit.ly`_ support
* `Django-CMS`_ plugins
* Utilização de base de dados

Recursos online
================

Mais informações e ajuda nestes links:

* Repositório de Código: https://github.com/catarinablancmatias/django_project/tree/master/blog
* Para reportar um bug ou fazer alguma questão contacte: Naminhacozinha@gmail.com

Instalação (Passos a seguir)
========

1. Sendo o Django uma framework web python, requer que o python seja instalado no computador. A ultima versão do python é a 3.7.3.
Para instalar o python deve aceder a: https://www.python.org/.
Baixe o ficheiro do instalador e execute-o. Selecione a próxima checkbox e clique em Install Now.

2. Depois da instalação, abra a linha comando e verifique se a versão do Python é a mesma que a versão instalada executando:

    python --version

3. Para facilitar as instalações seguintes, deve utilizar o pip (gerenciador de pacotes do python), instalando pacotes através da linha de comando.
Para instalar o pip, deve aceder a https://pip.pypa.io/en/latest/installing/, e seguir todas as instruções.

4. Apesar de não ser obrigatório, para economizar tempo, precisa de um ambiente dedicado (virtual environment) para este projeto, para instalá-lo, deve executar a seguinte linha de código (linha comando):
    
    pip install virtualenvwrapper-win

5. Para criar um ambiente virtual para o projeto, execute: 

    mkvirtualenv django_project

6. Agora que já tem o ambiente virtual, deve verificar que o mesmo está ativo, e para instalar o django abra a linha de comando e execute: 

    pip install django

7. Verifique se o Django foi corretamente instalado (última versão), na linha de comando execute:

    django-admin --version

8. Após a instalação correta, antes de aceder ao código do blog deve proceder a mais alguns passos:
  1. Criar o projeto, seguindo este tutorial: https://docs.djangoproject.com/en/2.2/intro/tutorial01/
  2. Seguir os seguintes tutoriais, fazendo as instalações necessárias e as migrações, consoante o código exposto na documentação suplementar (github) a baixo:
  
    2.1 https://docs.djangoproject.com/en/2.2/intro/tutorial01/
    2.2 https://docs.djangoproject.com/en/2.2/intro/tutorial03/
    2.3 https://docs.djangoproject.com/en/2.2/intro/tutorial04/
    2.4 https://docs.djangoproject.com/en/2.2/intro/tutorial06/
    2.5 https://docs.djangoproject.com/en/2.2/intro/tutorial05/
    2.6 https://docs.djangoproject.com/en/2.2/intro/tutorial07/

Documentação Suplementar:
  *BLOG: https://github.com/catarinablancmatias/django_project/tree/master/blog; 
  *ADMIN: https://github.com/catarinablancmatias/django_project/blob/master/blog/admin.py;
  *APPS: https://github.com/catarinablancmatias/django_project/blob/master/blog/apps.py;
  *MODELS: https://github.com/catarinablancmatias/django_project/blob/master/blog/models.py;
  *TESTS: https://github.com/catarinablancmatias/django_project/blob/master/blog/tests.py;
  *URLS: https://github.com/catarinablancmatias/django_project/blob/master/blog/urls.py;
  *VIEWS: https://github.com/catarinablancmatias/django_project/blob/master/blog/views.py.
