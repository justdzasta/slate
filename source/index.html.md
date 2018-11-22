---
title: API Reference

language_tabs: # must be one of https://git.io/vQNgJ
  - shell
  - ruby
  - python
  - javascript

toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true
---
# Kompilowanie CSS na SCSS używając npm

```shell
# Instalacja modułu node-sass
npm install node-sass
```

[Instrukcja na WebDesign Tutsplus](https://webdesign.tutsplus.com/pl/tutorials/watch-and-compile-sass-in-five-quick-steps--cms-28275)

1. Instalacja Node.js.
2. Zainicjowanie npm (`npm init`).
3. Zainstalowanie **node-sass** (`npm install node-sass`).

```shell
# Dodanie linijki po "script:". 
# Zmiana spowodowana nowszą wersją Node'a
node-sass . --watch --recursive --output css
```

4. Dodanie do pliku .JSON po `"script"` następującej linijki: `node-sass . --watch --recursive --output css`

```shell
# Moja konstrukcja folderów:
node-sass . --watch src/sass --recursive --output src/css
```

<aside class="notice">
Ja z racji konstrukcji projektu użyłam następującej linijki: <br>
<strong>node-sass --watch src/sass --recursive --output src/css</strong>
<br><br>
Ważne: <i>recursive</i> znaczy <i>rekurencyjnie!</i>
</aside>

5. Uruchomić kompilator `npm run scss`.

# Stawianie lokalnego serwera na NodeJS

[Instrukcja na jsdn.pl](http://jsdn.pl/ustawic-serwer-node-js/)

1. Instalacja Node.js.
2. Instalacja modułu Node'a o nazwie `http-server`. (`npm install http-server -g`).

```shell
# Instalacja modułu http-server globalnie:
npm install http-server -g
```

3. Uruchomienie modułu przy pomocy `http-server`.
4. Na porcie 8080 powinna wyświetlać nam się zawartość folderu, w którym uruchomiliśmy serwer.

# Livereload

Instrukcja na [LiveJS](http://livejs.com/) oraz [npmJS.com](https://www.npmjs.com/package/lr-http-server).

1. Załączyć kod ze strony LiveJS jako skrypt do swojego pliku HTML.
2. Zainstalować globalnie moduł `lr-http-server`.

```shell
# Instalacja modułu lr-http-server globalnie:
npm install -g lr-http-server
```

3. Odpalić `lr-http-server`.





