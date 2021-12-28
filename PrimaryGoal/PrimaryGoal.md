## The two services are running and registered.
First of all, fire up the services using:
* `./gradlew :registration:bootrun`
* `./gradlew :web:bootrun`
* `./gradlew :accounts:bootrun`

Prove they´re running...
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/tarea1.png)


Ensure that both of them are accesible from browser:
1. web...
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/3333.png)

2. accounts...
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/2222.png)


## The service registration service has the two services registered.
Prove it´s running...
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/t2.png)

See if the above two services are registered...
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/tarea2.1.png)

## A second account service is running in the port 4444 and it is registered
Change port configuration in account´s application.yaml file to 4444:
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/port.png)

Launch the second account service...
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/launch.png)

Ensure it is accessible from the browser...
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/browser4444.png)

Prove this newly created service is registered...
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/twoServices.png)


