# dark

1. Добавьте на панель браузера закладку с названием "Темная тема"
2. Вместо URL в этой закладке напишите

```
javascript: {
  var st = document.createElement('link'); 
  st.rel = 'stylesheet'; 
  st.href = 'https://kvisaz.github.io/dark/style.css';
  document.head.appendChild(st);}
```

3. Зайдя на сайт - нажмите закладку. Она подключит css из урла [https://kvisaz.github.io/dark/style.css](https://kvisaz.github.io/dark/style.css)


Недостаток этого метода в том, что нажимать кнопку придется каждый раз при заходе сайта.

Этот репозиторий, этот код можно свободно копировать, менять и распространять, используя под все необходимые случаи
