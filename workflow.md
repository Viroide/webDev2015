Workflow
===

Instalar gulp
---
1. mcd prueba101 
1. mpn init (--force)
1. npm install --save-dev gulp
1. crear gulpfile.js
2. crear carpetas dist y src
1. copiar la plantilla
1. editar las task para que se adecuen al proyecto
1. configurar el archivo config.json
1. Instalar TODOS los modulos gulp
         ```npm install gulp-rename gulp-uglify gulp-concat gulp-sourcemaps gulp-stylus gulp-jshint gulp-livereload gulp-watch gulp-header gulp-replace nib gulp-jade gulp-coffee gulp-token-replace --save-dev```


Instalar bower y dependencias
---
1. bower init
1. copiarte el .bowerrc
1. bower install bootstrap --save-dev
1. poner bien rutas

Pruebas de compilar dev o ops
---
1. minificar o no
2. links a CDNs
3. importancia del config.json

Llega la hora de compartir el esqueleto:
---
1. git init 
1. git add *.json 
1. git commit -am "Primer commit"
1. git remote add origin git@github.com:Viroide/prueba101.git
1. git push -u origin master

Toca que se lo baje un compi:
---
1. Crear, entrar en la carpeta
1. git clone https://github.com/Viroide/prueba101.git ./
1. npm install
1. bower install

Ahora... hay que hacer algo para abrir todo facilmente cada mañana
---
* O tmux con detach
* O terminator
* alias alias alias
