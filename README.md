# shop-soa

## Requerimientos

- Docker

## Configuración e Instalación
Clonar repositorio 
```
git clone --recurse-submodules https://github.com/Pabloitl/shop-soa.git 
```
Para poder instalar y correr por medio de docker ejecutar
```
docker-compose build
```
```
docker-compose up
```

## Notas importantes de desarrollo

- No realizar commits directamente en las branches de develop y master ya que estas serán administradas por el RM (Release Manager).
- Se debe usar el modelo de branching de [git-flow](http://danielkummer.github.io/git-flow-cheatsheet/).
- Cada vez que se trabaje en algo se debe crear una branch a partir de develop y posteriormente al finalizar los cambios en vez de hacer un ```git flow feature finish nombre``` se subirá la branch al repo y de esa branch enviar el Pull Request (PR) a develop para que a su momento y después de que alguien más revise el código haga el merge a develop.
- El nombre de los commits debe ser en inglés empezando con letra mayúscula, sin punto final y explicando bien de lo que se trata el commit.
- Las feature branchs deben ser creadas usando [git-flow](http://danielkummer.github.io/git-flow-cheatsheet/) ejemplo: ```git flow feature start profile-api```
- El nombre de las feature branch debe ser en inglés y al estilo [kebab-case](http://wiki.c2.com/?KebabCase) ```english-name-using-kebab-case```.


## Autor
* **Pablo Vargas** - *Tech Lead*
* **Daniel Escobar** - *Tech Lead*
