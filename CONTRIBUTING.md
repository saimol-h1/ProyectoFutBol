# 🛠️ Guía de Contribución

¡Gracias por tu interés en contribuir a nuestro proyecto de **Sitio Web de Gestión para Ligas Deportivas Parroquiales**! 🎉 Tu contribución es muy valiosa para nosotros.

Para mantener un flujo de trabajo limpio y ordenado, establecimos las siguientes normas:

## 📂 Estructura de Ramas (GitFlow)
Nuestro flujo de trabajo se basa en **GitFlow**, lo que nos permite organizar el desarrollo y facilitar las contribuciones. A continuación, se detallan las ramas principales que utilizamos:
- `main`: Rama principal con el código estable y listo para producción.
- `develop`: Rama para integrar nuevas funcionalidades.
- `feature/*`: Ramas para el desarrollo de nuevas características.
- `release/*`: Ramas para preparar versiones estables de lanzamiento.
- `hotfix/*`: Ramas para la corrección urgente de errores en producción.

## 🚀 Cómo colaborar

1. **Sincroniza tu repositorio local** con la rama `develop` del repositorio remoto para asegurarte de que estás trabajando con la última versión:
   ```bash
   git pull origin develop
   ```

2. **Crea una nueva rama** para tu funcionalidad o corrección:
   ```bash
   git flow feature start nombre-de-la-feature
   ```

3. **Realiza tus cambios** localmente, siguiendo las buenas prácticas de codificación y asegurándote de que no haya errores.

4. **Agrega y commitea** tus cambios de forma clara y estructurada.
   ```bash
   git add .
   git commit -m "Descripción clara de los cambios"
   ```

5. **Finaliza tu rama de feature** una vez que hayas completado los cambios:
   ```bash
   git flow feature finish nombre-de-la-feature
   ```

6. **Haz push de la rama develop** al repositorio remoto para actualizar los cambios:
   ```bash
   git push origin develop
   ```

7. **Crea un Pull Request (PR)** en GitHub para fusionar tus cambios con la rama `develop`. Asegúrate de describir los cambios realizados en el PR de manera clara.

## ✅ Reglas generales
Para asegurar que el proyecto se mantenga limpio y bien organizado, por favor sigue estas reglas:

 - **Mensajes de commit claros:** Escribe mensajes descriptivos y concisos que expliquen el propósito de los cambios.

   - *Ejemplo:* `Se ha agregado la funcionalidad para mostrar noticias en la página de inicio`.

 - **Nombres de ramas precisos:** Utiliza nombres cortos y significativos para las ramas. Por ejemplo: `feature/header`, `feature/noticias`.

 - **Pruebas locales:** Antes de finalizar tu trabajo, asegúrate de que todo funcione correctamente ejecutando el proyecto localmente con:

```bash
npm run dev
```
Verifica que no haya errores y que la funcionalidad esté completa.

 - **Pruebas en el navegador:** Toda nueva funcionalidad debe ser probada en el navegador para garantizar su correcta visualización y funcionamiento.

## 📜 Proceso de Pull Request
1. Haz un fork del proyecto en GitHub y clónalo en tu máquina local.
2. Realiza los cambios en tu repositorio fork.
3. Asegúrate de utilizar el versionado semántico [SemVer](http://semver.org/) para realizar tus cambios.
4. Crea un Pull Request desde tu rama ``feature/*`` hacia la rama ``develop`` en el repositorio principal. Describe detalladamente los cambios realizados en el PR.
5. Espera la aceptación de tu Pull Request. Al menos dos compañeros del equipo deben revisar y aprobar los cambios antes de fusionarlos.


## 👀 Revisión de Código

El proceso de revisión de código es crucial para mantener la calidad y coherencia del proyecto. Aquí te dejamos algunas pautas:

 - **Revisión de Pull Requests:** Si eres un revisor, asegúrate de examinar el código cuidadosamente y deja comentarios constructivos.

   - Asegúrate de que los cambios sean claros, correctos y sigan las convenciones de codificación establecidas.

 - **Mínimo dos revisores:** Cada Pull Request debe ser revisado por al menos dos compañeros antes de fusionarlo.

 - **Sugiere mejoras:** Si notas posibles mejoras en la estructura, el estilo o la funcionalidad, haz sugerencias para mejorar la calidad del código.

 - **No mezcles cambios:** No combines cambios de múltiples funcionalidades en un solo Pull Request. Cada PR debe enfocarse en una sola tarea o característica.

---

Siguiendo estas pautas, garantizamos que nuestro proyecto se mantenga bien organizado y exitoso para todos los colaboradores. 🚀⚽

¡Gracias por ser parte de este proyecto! Tu contribución es fundamental para hacer crecer nuestra plataforma. 🙌
