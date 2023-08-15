# React + Vite + Material UI

### INSTALANDO REACT Y MUI
Creamos el proyecto con vite y seleccionamos react
```bash
npm create vite@latest
```

[Link para el sitio de Material UI](https://mui.com/material-ui/getting-started/installation/)

Instalamos la libreria
```bash
npm install @mui/material @emotion/react @emotion/styled
```
Instalamos la fuente roboto
```
npm install @fontsource/roboto
```
Importamos esto en main.jsx
```js
import '@fontsource/roboto/300.css';
import '@fontsource/roboto/400.css';
import '@fontsource/roboto/500.css';
import '@fontsource/roboto/700.css';
```

Importamos los iconos de material UI desde ya
```bash
npm install @mui/icons-material
```

Vamos instalar este ultimo, para que no haya problemas con posteriores actualizaciones
```bash
npm install @mui/lab
```

## LIMPIEZA DE ARCHIVOS DEL PROYECTO
1. Eliminamos App.css
2. Vaciamos el contenido de App.jsx
3. Vaciamos el contenido de index.css


[SEGUIMOS ESTA GUIA](https://bluuweb.dev/05-react/material-ui.html)