# Gulp v4 \ Relict-Web \ Assembly of gulp for website

Build is designed to create sites using `Html`, `Css(Scss)`, `JavaScript`.

## Inside (auto):
(dev - developmend mode, build - production mode)

- **Live server & Watch files** - open "New Tab" and content update, file change tracking;
- **Html** - include repeating elements, versioning "css & js", minifier(build);
- **Libs** - simple connection(local download & build one file) of Css(Scss) & JS libraries;
- **Css(Scss)** - sourcemap(dev), compiler Scss to Css in 1 file, prefixer last 5 (chrome, firefox, safari) version (without cascade), grouping media queries, minifier(build);
- **JavaScript** - sourcemap(dev), grouping in 1 file, minifier(build);
- **Fonts** - convert ttf to woff2;
- **Images** - optimizating (png, jpeg, jpg) & converting to WebP, svg sprite.

## Start work:
Skip 1 - 4 if you've done it before.

1) Install Git - [Official site](https://git-scm.com/downloads);
2) Add Git terminal in VSCode - [Stackoverflow](https://stackoverflow.com/questions/42606837/how-do-i-use-bash-on-windows-from-the-visual-studio-code-integrated-terminal);
3) Install NodeJs - [Official site](https://nodejs.org/);
4) Install Gulp - run command in terminal `npm install --global gulp-cli`;

5) Download repository or run command in terminal `git clone https://github.com/DazzleFun/gulp-relict-web`;
6) Installing dependences - `npm i`;

## Work process (all in terminal):
1) Run dev - `gulp`;
2) Stop dev - `Ctrl + C`;
3) Production - `gulp build`.

**Note**: Production mode does not require stopping, it creates 2 archives inside the build (working version assembled and minimized).

>Also in the future I will make blanks `html`, `scss`, `js`.
>I just started and this is not the end. Improvements will come as needs grow.