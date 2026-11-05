# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


# Práctica: Integración de Efectos y Escena 3D en React

## Respuesta a la pregunta teórica:

**Si la carpeta `node_modules/` está excluida, ¿borrar una dependencia hace alguna acción sobre el repositorio? ¿Cuál?**

No afecta directamente a los archivos de código guardados o indexados en el repositorio de Git, ya que la carpeta `node_modules/` está excluida a través del archivo `.gitignore`. Sin embargo, **sí realiza una acción directa sobre el repositorio porque modifica los archivos `package.json` y `package-lock.json`** (los cuales sí están bajo el control de versiones). Al desinstalar una dependencia (por ejemplo, con `npm uninstall`), Git registrará una modificación en estos archivos de configuración reflejando que dicha librería ya no forma parte del proyecto para futuras instalaciones.

## Capturas de pantalla del proyecto:
* (Añade aquí tus capturas arrastrando las imágenes directamente al README en GitHub o vinculando las rutas locales de tus imágenes guardadas).
