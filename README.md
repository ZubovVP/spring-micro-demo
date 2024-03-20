# Spring micro demo   
1) Eureka-server (там можно посмотреть зарегистрированные сервисы) - [http://localhost:8761/](http://localhost:8761/)  
2) Eureka-client (Тестовый сервис) - http://localhost:х/main/test (х - рандомный порт, который определяется на старте приложения)
3) Eureka-client(2) (Тестовый сервис) - http://localhost:х/new/name (х - рандомный порт, который определяется на старте приложения)
4) Api Gateway (настроен роутинг) :
   Eureka-client - [http://localhost:8765/main/test](http://localhost:8765/main/test) 
   Eureka-client(2) - [http://localhost:8765/new/name](http://localhost:8765/new/name) 
5) Config service :
   Eureka-client (настройки сервиса) - [http://localhost:8888/eclient/default](http://localhost:8888/eclient/default)   



