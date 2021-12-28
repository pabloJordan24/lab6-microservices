## The two services are running and registered.
* Prove they´re running...
<br/> Fire up the web service using `./gradlew :web:bootrun` and the account service using: `./gradlew :accounts:bootrun`.
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/tarea1.png)


* Ensure that both of them are accesible from browser:
1. web...
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/3333.png)

2. accounts...
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/2222.png)


## The service registration service has the two services registered.
* Prove it´s running...
<br/> Fire it up using `./gradlew :registration:bootrun`.
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/t2.png)

* See if the above two services are registered...
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/tarea2.1.png)

## A second account service is running in the port 4444 and it is registered.
* Change port configuration in account´s application.yaml file to 4444:
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/port.png)

* Launch the second account service...
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/launch.png)

* Ensure it is accessible from the browser...
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/browser4444.png)

* Prove this newly created service is registered...
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/twoServices.png)

## What happens when you kill the service with port 2222? Can the web service provide information about the accounts? Why?
* Fetch account after killing account service running on port 2222...
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/fetchaccDspsKill.png)

**It is not available just after killing the process. Error with code 500 is shown. Nevertheless, we just need to wait a few seconds after the service registration realizes and redirects to the other...**
<br/> <br/> ![alt text](https://github.com/pabloJordan24/lab6-microservices/blob/test/PrimaryGoal/fetchEsperandoTiempo.png)

