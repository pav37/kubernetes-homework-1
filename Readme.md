# Развертывание
    kubectl apply -f k8s
Манифесты развертываются в namespace homework

# Проверка
После развертывания станут доступны следующие url:
    
http://arch.homework/health/    
http://arch.homework/health/liveness/   
http://arch.homework/health/readiness/  
http://arch.homework/hello/    
http://arch.homework/hello/man/

http://arch.homework/otusapp/andrey/health/  
http://arch.homework/otusapp/andrey/health/liveness/    
http://arch.homework/otusapp/andrey/health/readiness/   
http://arch.homework/otusapp/andrey/hello/      
http://arch.homework/otusapp/andrey/hello/man/  


Домашнее задание/проектная работа разработано(-на) для курса [Microservice Architecture](https://otus.ru/lessons/microservice-architecture)
    
    