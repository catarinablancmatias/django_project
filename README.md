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

8. Após a instalação correta, deve criar o projeto, seguindo este tutorial: https://docs.djangoproject.com/en/2.2/intro/tutorial01/.

9. De seguida, instalar o crispy forms acedendo à linha comando e executar:
    pip install django-crispy-forms

10. Após intalar o tema do form, deve instalar uma coleção de armazenamento personalizado de django, para isso utiliza a linha comando, executando;
    pip install django-storages
    
11. Para aramazenar as imagens contidas no blog, deve instalar uma biblioteca de imagens, para isso execute na linha de comando:
    pip install Pillow
        
12. De seguida, deve verificar o código do manage.py, e na linha de código executar:
    python manage.py 
    makemigrations
    python manage.py migrate
    
13. Agora será necessário executar:
    winpty python (Pacote que permite a comunicação com o Windows)
    manage.py
    
14. Após a comunicação estar estabelecida, utilizamos uma funcionalidade do Django (createsuperuser), que nos permite criar um user que pode aceder ao painel do administrador do site, com conteúdo editável. Para isso, deve verificar se o django.contrib.auth está instalado em settings.py (por defeito, ao instalar a app é automaticamente instalado) e de seguida executar:

    python manage.py createsuperuser
        Username: (inserir utilizador desejado)
    Password: (Inserir password desejada)
    Password (again): (Inserir password desejada novamente)
    
    Deve aparecer a seguinte mensagem:
Superuser created successfully.

15. Agora temos de executar o servidor e ver se está funcional. Para isso, na linha comando execute:
    python manage.py runserver

16. Se tudo correr bem, vai retornar uma mensagem dizendo que não contém erros.

17. Para aceder ao Painel de administrador, abra uma página WEB e vá para a página admin do seu domínio local, por exemplo: http://127.0.0.1:8000/admin/. 

Esperamos que esta explicação tenha sido perceptível. 

Em caso de dúvida, contacte-nos através de: Naminhacozinha@gmail.com
  
Documentação Suplementar:
  Código do BLOG: https://github.com/catarinablancmatias/django_project/tree/master/blog;
