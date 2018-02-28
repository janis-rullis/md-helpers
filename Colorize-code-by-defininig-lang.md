# Colorize the code by defining the language

## Source
* [Code and Syntax Highlighting](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code-and-syntax-highlighting).
* [Creating and highlighting code blocks](https://help.github.com/articles/creating-and-highlighting-code-blocks/).
* [Supported languages by Linguist](https://github.com/github/linguist/blob/master/lib/linguist/languages.yml)

## Without lang

```
function shout(str){
  alert(str);
}

shout('Hey');
```

## JS

```javascript
function shout(str){
  alert(str);
}

shout('Hey');
```

```

## PHP

```php
<?php die('Hi');?>
```

## CSS
```css
color: red;
```

## NGINX
```nginx
user www-data;
pid /run/nginx.pid;

worker_rlimit_nofile 65536; # ulimit
worker_processes auto; #some last versions calculate it automatically

events {
    worker_connections 65536; # ulimit
}
```
