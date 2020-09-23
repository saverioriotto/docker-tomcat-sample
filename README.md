# docker-tomcat-sample

Un semplice tutorial per avviare webapp su Tomcat utilizzando Docker

Passaggi da seguire considerando che l'installazione di Docker si già stata effettuata:

Clonare questo repository - $git clone https://github.com/saverioriotto/docker-tomcat-sample.git
cd 'docker-tomcat-sample'
$docker build -t sampleapp .
$docker run -p 80:8080 sampleapp
Verificare che l'app sia attiva all'indirizzo: http://localhost:80


saverioriotto.it
