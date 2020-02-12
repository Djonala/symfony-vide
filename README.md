# symfony-vide

## Modèle template prêt à être dupliqué pour créer de nouveaux projets. 

## Comment participer au projet ?

### Recupération du projet : 
en SSH : 
        git clone git@github.com:symfony/demo.git

en HTTPS : 
        git clone https://github.com/symfony/demo.git

### Placez vous sur develop : 

        git checkout develop

### Creez votre branche : 

        git checkout -b <Nom de votre branche>

### Enfin, effectuez vos modifications. 

### Une fois vos modifications effectuées : 

        git add <nom des fichiers>

        git commit -m "<votre commantaire>"

### créez votre pull request :

        git push


## Comment lancer le projet : 


There's no need to configure anything to run the application. If you have
[installed Symfony][4], run this command and access the application in your
browser at the given URL (<https://localhost:8000> by default):

```bash
$ cd my_project/
$ symfony serve
```

If you don't have the Symfony binary installed, run `php -S localhost:8000 -t public/`
to use the built-in PHP web server or [configure a web server][3] like Nginx or
Apache to run the application.


### Comment lancer les tests : 



Execute this command to run tests:

```bash
$ cd my_project/
$ ./bin/phpunit
```