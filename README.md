# El Tiempo — España

Web sencilla y **sin anuncios** para ver el tiempo en cualquier municipio de España. Por eso me decidí a hacerla.

👉 **Úsala aquí:** https://detomas.net/uploads/urls/ndt-tiempo-app.html

## De dónde salen los datos

- **AEMET OpenData**: la predicción oficial por municipio de la Agencia Estatal de Meteorología. Se pide a través de un pequeño intermediario (un Worker de Cloudflare) que guarda la clave de acceso, para que no esté a la vista en la web.
- **Open-Meteo**: se usa para buscar lugares y como respaldo si AEMET no responde, para que la web nunca se quede en blanco.

## Qué muestra

Tiempo actual, previsión de 7 días, previsión hora a hora y lugares favoritos (se guardan solo en tu navegador).

Todo está en un único fichero, `index.html`: HTML, CSS y JavaScript, sin frameworks.

---
Hecho por [detomas.net](https://detomas.net)
