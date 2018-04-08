// --> Install node.js <-- //
<br>
// сначало нужно установить node.js (если он не установлен на ПК)
<br>
https://nodejs.org/en/
<br>
<br>
// --> Install Global Gulp <-- //
<br>
// установить глобально gulp
npm install -g gulp
<br>
<br>
// --> Create "package.json" <-- //
<br>
// создать файл "package.json"
npm init
<br>
<br>
// --> Create "gulpfile.js" <-- //
<br>
// создать файл "gulpfile.js" (вручную)
<br>
или вставить свой файл "gulpfile.js" с своими найстройками
<br>
<br>
// --> Install Local Gulp <-- // 
<br>
// создать папку с плагинами
npm i gulp --save-dev
<br>
<br>
// --> Upload plugins (Gulp) <-- //
<br>
// добавить плагины ...
<br>
npm i gulp gulp-sass browser-sync del gulp-autoprefixer gulp-cache gulp-concat gulp-cssnano gulp-imagemin gulp-rename gulp-uglifyjs imagemin-pngquant --save-dev
<br>
<br>
// --> Update plugins (Gulp) <-- //
<br>
1. npm i -g npm-check-updates     // установить плагин
2. ncu                            // проверить какие плагины нужно обновить
3. ncu -u (или "ncu -a")          // обновить файл "package.json"
4. npm update                     // обновить все плагины
