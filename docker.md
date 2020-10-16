###rabbitmq  
docker run --name rebbitmq-management -d --restart always -p 5671:5671 -p 5672:5672  -p 15672:15672 -p 15671:15671  -p 25672:25672  -v /home/dlsrm/data/rabbitmq-data/:/var/rabbitmq/lib  macintoshplus/rabbitmq-management  
http://localhost:15672/   guest/guest  
