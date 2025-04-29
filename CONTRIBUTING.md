# 🛠️ Guía de Contribución

¡Gracias por tu interés en contribuir a nuestro proyecto de sitio web de fútbol con Astro!

Para mantener un flujo de trabajo limpio y ordenado, seguimos las siguientes normas:

## 📂 Estructura de Ramas (GitFlow)

- `main`: Rama de producción, siempre contiene código estable.
- `develop`: Rama de integración donde se juntan todas las nuevas funcionalidades.
- `feature/*`: Para trabajar nuevas características.
- `release/*`: Para preparar versiones estables.
- `hotfix/*`: Para solucionar errores críticos en producción.

## 🚀 Cómo colaborar

1. **Sincroniza tu repositorio local** con el repositorio remoto:
   ```bash
   git pull origin develop
   ```

2. **Crea una nueva rama** para tu funcionalidad o cambio:
   ```bash
   git flow feature start nombre-descriptivo
   ```

3. **Realiza tus cambios** localmente, siguiendo las buenas prácticas de codificación.

4. **Agrega y commitea** tus cambios de manera ordenada:
   ```bash
   git add .
   git commit -m "Descripción clara de los cambios"
   ```

5. **Finaliza tu feature**:
   ```bash
   git flow feature finish nombre-descriptivo
   ```

6. **Haz push de la rama develop** al repositorio remoto:
   ```bash
   git push origin develop
   ```

7. **Crea un Pull Request** hacia la rama `develop` en GitHub para revisión de tu compañero o líder de proyecto.

## ✅ Reglas generales

- Los commits deben tener mensajes claros y descriptivos.
- Las ramas deben tener nombres cortos y precisos (por ejemplo: `feature/header`, `feature/noticias`).
- Antes de finalizar tu trabajo, asegúrate de que el proyecto funcione correctamente (`npm run dev` sin errores).
- Toda nueva funcionalidad debe ser probada en el navegador.

## 👀 Revisión de Código

- Comenta y aprueba los Pull Requests de tus compañeros si todo está correcto.
- Sugiere mejoras en la estructura, estilo o funcionalidad cuando sea necesario.
- No mezcles cambios de varias funcionalidades diferentes en un solo Pull Request.

---

¡Siguiendo estas reglas aseguramos un proyecto ordenado y exitoso para todos! 🚀⚽
