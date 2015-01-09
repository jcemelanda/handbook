# PyLadies Brasil Website

Repositorio: https://github.com/pyladies-brazil/br-pyladies

###PyLadies website uses:

[Jekyll]() with Notepad theme made by @hmfaysal  
[SnapCI]() for continuous integration and deploy  
[Heroku]() for hosting  

###Running PyLadies Website:
``git clone https://github.com/pyladies-brazil/br-pyladies.git``  
``cd br-pyladies``  
``LC_ALL="en_US.UTF-8" jekyll serve -w``


Now you can access http://localhost:4000/

### Como adicionar dados do seu evento ao PyLadies Brasil?

1. Clone o projeto
``git clone https://github.com/pyladies-brazil/br-pyladies.git``

2. Edite o arquivo *br-pyladies/_data/locations.yml* e adicione o seu evento, como no exemplo:  
``- city: Recife - PE``  
``   url: https://www.facebook.com/pages/PyLadies-Recife/950001281692844 `` 
``  image: /images/locais/recife.png``

3. Adicione sua imagem na pasta *br-pyladies/images/locais/*

4. Verifique se está tudo ok localmente

5. Tudo pronto! Agora é hora de fazer um **push** e um **pull request**

<br>

PS: Estamos trabalhando para que seja possível criar o site dentro do proprio PyLadies usando o _categories do proprio Jekyll. Assim que estiver disponível nós informaremos.

<br>

Qualquer dúvida ou sugestão não deixe de nos procurar. Fique a vontade para contribuir com o projeto resolvendo as issues no Github (:
  




