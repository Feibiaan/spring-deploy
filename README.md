
## Despliegue de apps Spring bBoot en Heroku

Crear archivo `system.properties` en el proyecto con el contenido:

```
java.runtime.version=19
```

1. Crear cuenta en heroku.com y github.com
2. Tener configurado git en el ordenador
   1. `git config --global useer.name "fabianruiz"`
   2. `git config --global user.email ...`
3. Subir el proyecto a Github desde Intellij IDEA desde la opción: VCS > Share project on Github
4. Desde Heroku, crear app y elegir método GitHub y buscar el repositorio subido
5. Habilitar deploy automático y ejecutar el Deploy