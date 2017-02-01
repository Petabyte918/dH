dH
==

[https://relatur.tk/](https://relatur.tk/)  
Браузерная игра с использованием Socket.IO

![alt tag](https://raw.githubusercontent.com/latur/dH/master/client/img/demo-3.jpg) 

Идея заключается в том, что каждый игрок находится в своём собственном измерении и не может перебраться в любое другое.
Для уничтожения соперников в вашем распоряжении есть два инструмента:

**Проекция** (межпространственное зрение). Нажав клавишу Q вы можете увидеть проекцию игроков из всех измерений в ваши два.

**Гиперпространственный лазер**, поражающий всех во всех измерениях. Активируется кликом мыши в нужное место экрана. Место соприкосновения лазера с поверхностью сопровождается взрывом.


### Как ставить:

 • Скопировать игрулю к себе и положить на сервер с php.  
 • Вписать настройки тут `app/config.php` и тут `node/dh.js` (там прокомментировано)  
 • Запустить ноду из папки `node` (например, через `forever`)
 
~~~
cd /home/www/relatur.tk/node
npm install
forever start ./dh.js
~~~
