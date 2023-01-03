# link del projecto

[https://anthonyx159.github.io/maker-landing-page/]
## Proyecto con Mix (webpack wrapper)

Lee la documentación aqui: https://laravel-mix.com/docs/5.0

1. Correr en consola: `npm install`

1. Segun lo que necesites, puedes correr lo siguiente:

    - Si deseas compilar para desarrollo:
    
        - Para compilar una vez, correr en consola: `npm run dev`
        
        - Para escuchar los cambios y compilar, correr en consola: `npm run watch`
        
        - Para crear un servidor local, escuchar los cambios y compilar, correr en consola: `npm run hot`  
    
    - Si deseas compilar para produccion, correr en consola: `npm run prod`
    
1. Puedes cambiar la configuración del mix en [webpack.mix.js](webpack.mix.js)

1. Puedes cambiar las dependencias en el [package.json](package.json)
    
    * Es recomendable siempre usar las dependencias de JS o CSS desde package.json para manejar librerias, de este modo podemos mantenerlas actualizadas y mantener la compatibilidad entre versiones.
    
    * En el package.json tambien podemos usar la entrada `browserslist` para manejar las versiones de browsers compatibles. Aumentar o disminuir nuestro rango de compatibilidad hara crecer el css o js resultante por el polyfills, prefixer y otros factores.