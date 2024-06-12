<h1>Сила воли 2</h1>

<h2>Задание:</h2>
Вы действительно сильны, если смогли дойти сюда после первого задания. Но теперь предлагаю решить задачу по другому, как программист.<br>

<h2>Решение:</h2>
Для решения необходимо написать скрипт, который сможет автоматизировать запросы, отсылаемые на сервер по нажатию кнопки:

<pre lang="python">
<code>
import requests

for i in range(9999):
  r = requests.post("http://fatal_error2.alexavr.ru:5555/click/RandomNameTeam")
 
r = requests.post("http://fatal_error2.alexavr.ru:5555/click/RandomNameTeam")
print(r.json())

</code>
</pre>
