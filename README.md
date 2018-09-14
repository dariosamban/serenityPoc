# serenityPoc

Asegurarse de tener mvn configurado con tls 1.2
mvn -Dhttps.protocols=TLSv1.2 install

Luego parar correr los tests te serenity
mvn clean verify serenity:aggregate
