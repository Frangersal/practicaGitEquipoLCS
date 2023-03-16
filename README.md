# CH25_colaborar

## Ejercicio para colaborar con varias personas en Git y Github

### Pasos a seguir para colaborar en Github.com desde git bash

1. Crear Repositorio en Github.com
2. Agregar colaboradores en Github.com
3. Aceptar solicitud por todos los colaboradores
4. Crear la rama `develop` desde la rama `main` en Github.com
5. Clonar el repositorio de manera local `git clone [url-ssh]` (por todos los colaboradores)
   > Estos pasos sólo se deben ejecutar 1 vez

---

6. Cambiar de Directorio con `cd [nombreDelRepo]`
7. Cambiar a la rama develop `git checkout develop`
8. Crear archivos/directorios base para trabajar  
   8.1 `git add .`  
   8.2 `git commit -m "Mensaje"`  
9. Subir los cambios a `develop` con `git push origin develop`  
   > Estos pasos se deben ejecutar cuando sea necesario

---

10. Crear la rama de la característica desde develop. Por ejemplo: `git branch [formContactoJCVL]`
11. Entrar a la rama previamente creada. Por ejemplo: `git checkout [formContactoJCVL]`
12. Trabajar sobre las características deseadas en los archivos.
13. Agregar cambios al área de preparación `git add .`
14. Confirmar los cambios `git commit -m "Mensaje"`
15. Subir los cambios de la rama actual `git push origin [formContactoJCVL]`
16. Cambiar a la rama `develop` con `git checkout develop`
17. Descargar los cambios de `develop` con `git pull origin develop`
18. Fusionar la rama deseada con `develop` con `git merge [formContactoJCVL]`
19. Subir los cambios de develop `git push origin develop`
20. **El resto de los colaboradores** deben actualizar `develop`  
    20.1 Cambiarse a la rama `develop` con `git checkout develop`  
    20.2 Descargar los cambios con `git pull origin develop`  
