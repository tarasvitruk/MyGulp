// --> Install node.js <-- //

// сначало нужно установить node.js (если он не установлен на ПК)
https://nodejs.org/en/


// --> Install Global Gulp <-- //

// установить глобально gulp
npm install -g gulp


// --> Create "package.json" <-- //

// создать файл "package.json"
npm init


// --> Create "gulpfile.js" <-- //

// создать файл "gulpfile.js" (вручную)
или вставить свой файл "gulpfile.js" с своими найстройками


// --> Install Local Gulp <-- // 

// создать папку с плагинами
npm i gulp --save-dev


// --> Upload plugins (Gulp) <-- //

// добавить плагины ...
npm i gulp gulp-sass browser-sync del gulp-autoprefixer gulp-cache gulp-concat gulp-cssnano gulp-imagemin gulp-rename gulp-uglifyjs imagemin-pngquant --save-dev


// --> Update plugins (Gulp) <-- //

1. npm i -g npm-check-updates     // установить плагин
2. ncu                            // проверить какие плагины нужно обновить
3. ncu -u (или "ncu -a")          // обновить файл "package.json"
4. npm update                     // обновить все плагины
