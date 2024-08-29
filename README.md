<div style="display: flex; justify-content: space-between;">
  <p align="center">
    <a href="https://react.dev/" target="blank"><img src="public/react.svg" width="200" alt="React Logo"/></a>
  </p>
  
  <p align="center">
    <a href="https://vitejs.dev/" target="blank"><img src="public/vite.svg" width="200" alt="Vite Logo"/></a>
  </p>

  <p align="center">
    <a href="https://www.typescriptlang.org/" target="blank"><img src="public/typescript.svg" width="200" alt="TypeScript Logo"/></a>
  </p>
</div>

# FrontEnd del Proyecto Administrador de Productos - PERN Stack

Aplicación creada con [React](https://react.dev/), [Vite](https://vitejs.dev/), [TypeScript](https://www.typescriptlang.org/), [TailwindCSS](https://tailwindcss.com/), [React Router DOM](https://www.npmjs.com/package/react-router-dom), [Axios](https://axios-http.com/) y [Valibot](https://valibot.dev/), la Aplicación es un Administrador de PRroductos (en este caso de productos computacionales) que se conecta a una API externa, puedes crear nuevos productos, editarlos, cambiar su disponibilidad, o incluso eliminarlos. La APP se conecta a una [API](https://github.com/ElNetoAguirre/Administrador-de-Productos-BackEnd-Node-Express-Sequelize-TS-PostgreSQL.git) creada para éste ejercicio. Cuenta con validación de campos y mensajes de error y/o confirmación.

Algunos de los conceptos utilizados para la generación de ésta App, son:

1. API's.
2. Formularios.
3. Validaciones.
4. useNavigate.
5. useFetcher.
6. Types.
7. Outlet.
8. [React Router DOM](https://www.npmjs.com/package/react-router-dom).
9. [Axios](https://www.npmjs.com/package/axios).
10. [Valibot](https://valibot.dev/).
11. [TailwindCSS](https://tailwindcss.com/).
12. Y más.


## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
  },
}
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
