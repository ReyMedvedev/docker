удалить все остановленные контейнеры<br>
<code>docker rm -v $(docker ps -aq -f status=exited)</code>

чистим всё<br>
<code>docker system prune -a</code>
