# 💡 ¿Qué es Git y qué es GitHub?
Es muy común confundirlos, pero no son lo mismo. La forma más fácil de entenderlo es con una analogía del mundo de los videojuegos:

**Git es la consola y el juego:** Es el software que instalas en tu computadora. Su función principal es ser un **Sistema de Control de Versiones**. Imagínalo como el botón de "Guardar partida". Te permite tomar "fotos" de tu código en un momento específico. Si metes la pata y tu código deja de funcionar, puedes "cargar la partida" anterior y salvar el día. Todo esto ocurre de forma local en tu máquina.

**GitHub es la nube donde subes tus partidas:** Es una plataforma web (una red social para programadores). Sirve para alojar tus proyectos (llamados repositorios) en internet. Así, no solo tienes un respaldo si a tu computadora le pasa algo, sino que también te permite compartir tu trabajo con el mundo y colaborar con otras personas.

## 🏗️ Los Conceptos Clave que debes conocer
Antes de tocar la terminal, necesitas entender el vocabulario básico:
- **Repositorio (Repo):** Es la carpeta de tu proyecto que Git está vigilando.
- **Commit:** Es el acto de "guardar partida". Es una foto instantánea de tus archivos en ese preciso momento. Cada commit lleva un mensaje descriptivo (ej: "Agregado botón de borrar").
- **Rama (Branch):** Imagina el tronco de un árbol (la rama principal o main). Si quieres probar una función nueva y peligrosa sin romper lo que ya funciona, creas una "rama" hacia el costado. Si sale bien, la unes al tronco; si sale mal, la borras y el juego sigue intacto.
- **Push:** Es la acción de "empujar" o subir tus commits locales (de tu PC) hacia GitHub.
- **Pull:** Es lo contrario; bajar los cambios más recientes desde GitHub a tu computadora.

## 🚀 El Flujo de Trabajo Diario (Tus herramientas del oficio)
Este es el ciclo que vas a repetir absolutamente todos los días de tu ruta de aprendizaje:

1. [Modificas tu código] 
2. `git add .` o  `git add README.md`   -> Seleccionas los cambios (Puedes seleccionar todos los cambios o algo en específico).
3. `git commit -m "Texto descriptivo"` -> Guardas tu cambio.
4. `git push` -> Subes el cambio a la nube de Github.

### **Los Comandos Esenciales (Tu caja de herramientas)**
Para moverte en este flujo, usarás la terminal con estos comandos básicos:
1. **git init:** Se usa una sola vez al inicio. Le dice a Git: "Empieza a vigilar esta carpeta".
2. **git status:** Tu mejor amigo. Te dice qué archivos cambiaste, cuáles agregaste y qué está listo para guardarse.
3. **git add .:** Selecciona todos los archivos que modificaste y los prepara para la foto.
4. **git commit -m "Tu mensaje aquí":** Toma la foto y le pone una etiqueta explicativa.
5. **git push origin main:** Sube tus cambios a la nube de GitHub.
Pueden haber mas comando que utilizaras cuando trabajes en equipo. 

## 🛠️ Tu primer reto: Preparar el terreno
Para arrancar mañana mismo con tu plan de cuadritos verdes en GitHub, necesitamos dejar tu entorno listo:
- [✔️] Paso 1: Descarga e instala Git desde su página oficial (git-scm.com).
- [✔️] Paso 2: Regístrate en GitHub si aún no tienes cuenta.
- [✔️] Paso 3 (Configuración inicial): Abre la terminal de tu PC y escribe estos dos comandos (cambiando los datos por los tuyos) para que Git sepa quién eres:
```
    git config --global user.name "Tu Nombre"
    git config --global user.email "tu-correo@email.com"
```