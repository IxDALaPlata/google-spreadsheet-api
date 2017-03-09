# google-spreadsheet-api

[![Greenkeeper badge](https://badges.greenkeeper.io/durancristhian/google-spreadsheet-api.svg)](https://greenkeeper.io/)

Microservicio que devuelve un JSON con los datos de la primer hoja de una Google Spreadsheet
Usa `memory-cache` para storear los resultados durante el tiempo indicado por configuración

## Motivación

Usar una Google Spreadsheet como DB. Para lograrlo, [es necesario seguir estos pasos](https://support.google.com/docs/answer/37579)

## Desarrollo

Duplicar el archivo `.env-template`, nombrarlo como `.env` y reemplazar por los valores que se necesiten

```bash
# npm install
yarn install
npm run start-dev
```

## License

MIT
