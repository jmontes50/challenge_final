# Proyecto React con Vite: Temática Abierta

Este proyecto es un desafío para construir una aplicación de lista de tareas interactiva en React utilizando Vite como boilerplate.

## Desarrollo del proyecto

El proyecto esta plantado para ser desarrollado entre 1 a 3 Personas.

## Temática del proyecto

La temática del proyecto queda a elección del desarrollador o equipo de trabajo. Se sugiere considerar la incorporación de características adicionales o proponer una temática de interés personal para enriquecer la propuesta.

## Características Principales

- **Rutas**: Implementación de **mínimo de dos vistas**, una principal con renderizado de listas y otra de detalle, [usa React Router Dom 6](https://reactrouter.com/en/main/start/tutorial) para esto
- **Manejo de Estado**: Utiliza al menos `useState` y `useEffect` para gestionar el estado y los efectos dentro de los componentes de tu aplicación.
- **Consumo y persistencia de Datos**: Puede utilizar [mock API](https://mockapi.io/) (recomendado) o cualquier API de tu preferencia, en [Rapid API](https://rapidapi.com/) puedes encontrar diferentes API. Se recomienda usar métodos POST y PUT para interactuar con la API, en caso que la API no tenga métodos GET o POST disponibles limitate a usar GET.
- **Componentes Funcionales**: Desarrolla la aplicación utilizando componentes funcionales en JSX.
- **CSS**: Usa CSS puro, Bootstrap o algún framework/librería de CSS de tu elección.
- **Usabilidad**: El proyecto debe ser responsive.

> [!IMPORTANT]
> Al utilizar una API externa, como las de Rapid API, es importante entender su funcionamiento rápidamente y realizar pruebas para verificar la comprensión. Invierte tiempo eficientemente para no obstaculizar el desarrollo del proyecto.

## Opciones Adicionales

- **Manejo de Estado Avanzado**: Puedes incorporar herramientas como [useContext](https://www.telerik.com/blogs/react-usecontext-hook), [Zustand](https://github.com/pmndrs/zustand) o [Redux-Toolkit](https://redux-toolkit.js.org/) para un manejo más avanzado del estado de la aplicación.
- **Firebase**: Considera integrar Firebase para funciones como la autenticación o el almacenamiento de datos.
- **Pruebas con Jest y React Testing Library**: Agrega tests utilizando Jest y React Testing Library para garantizar la robustez de tu aplicación.

## Estructura del Proyecto

- **src/**: Directorio principal del código fuente.
  - **components/**: Almacena los componentes de React.
  - **views/**: Contiene las vistas de React utilizando React Router Dom.
  - **utils/**: Puede incluir utilidades, como funciones para el manejo de estado avanzado o la interacción con la API.

## Cómo iniciar el Proyecto

1. Crea un proyecto con Vite:

   ```bash
   npm create vite@latest nombreproyecto
   ```

2. Selecciona `React` como framework y `Javascript` como lenguaje.

3. Entra a la carpeta del proyecto recién creado.

    ```bash
    cd nombreproyecto
    ```

4. Instala las dependencias

    ```bash
    npm install
    ```

5. Levanta el servidor de desarrollo del proyecto

    ```bash
    npm run dev
    ```

## Links recomendados

- [Ejemplo con Zustand](https://dev.to/shubhamtiwari909/zustand-state-management-library-react-20p2)
- [Documentación Firebase](https://firebase.google.com/docs/build?hl=es-419)
- [Documentación Jest](https://jestjs.io/docs/getting-started)
- [Documentación React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
- [Ejemplo de Rapid API con Deezer](https://rapidapi.com/blog/deezer-api-with-java-python-php-ruby-javascript-examples/)
- [Guía Sencilla React Router DOM](https://dev.to/jeetvora331/react-router-dom-6-for-beginners-20ob)
- [useState y useEffect](https://www.shecodes.io/athena/125174-difference-between-usestate-and-useeffect-in-react#:~:text=In%20summary%2C%20useState%20is%20used,data%2C%20or%20subscribing%20to%20events.)
- [Guía Sencilla Axios](https://dev.to/lindaojo/beginner-s-introduction-to-axios-hie)
- [Callbacks, Promises y AsyncAwait](https://www.freecodecamp.org/news/javascript-promises-async-await-and-promise-methods/)
