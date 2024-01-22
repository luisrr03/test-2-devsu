# Prueba E2E api demoblaze
## Instalacion
```bash
npm install
```

## Iniciar cypress
```bash
npm run test
```

## Iniciar pruebas
seleccione el archivo spec.cy y automaticamente correran los test

## Nota adicional
Para poder crear un usuario que no exista dentro de la base de datos, se implemento un usuario estatico `luisrodriguez` mas un codigo random con digito 1000000000 para que sea unico. Hay posibilidad que se repita el usuario en una probabilidad de 1 a 1000000000
ejemplo: `luisrodriguez013927371727`