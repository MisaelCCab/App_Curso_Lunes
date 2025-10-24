# Proyecto: App_Curso_Lunes

Este repositorio contiene el portal principal del proyecto **App_Curso_Lunes**.  
Cada integrante del equipo deberá agregar su propia aplicación Angular dentro de este repositorio siguiendo las instrucciones detalladas a continuación.


## Instrucciones para cada integrante

## Clonar el repositorio

Primero, clonen este repositorio en su computadora:

```bash
git clone https://github.com/TU-USUARIO/App_Curso_Lunes.git
cd App_Curso_Lunes


deberand de crear cada quien su branch 
git checkout -b tu-nombre

Generar el build de tu aplicación Angular

Entra a la carpeta de tu proyecto Angular local (no dentro del repositorio principal).

Ejecuta los siguientes comandos:
npm install
ng build --configuration production --base-href ./

Esto generará una carpeta llamada dist/ dentro de tu proyecto Angular.
dist/mi-proyecto-angular/
 ├── index.html
 ├── main.js
 ├── styles.css
 └── assets/

 deberas de entrar a la carpeta con tu nombre y luego copia el contenido de tu carpeta dist/tu-proyecto-angular/ dentro de tu carpeta personal

 No copies la carpeta dist completa, solo su contenido.

 y por ultimo deberas de 
 Editar el index.html principal

Abre el archivo index.html que está en la raíz del repositorio y agrega un enlace hacia tu aplicación.
