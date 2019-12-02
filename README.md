# Bootcamp FIWARE Machine Learning - Málaga 2019

* Clone this project
```shell
git clone https://github.com/ging/BootCamp-FIWARE-ML
cd BootCamp-FIWARE-ML
```

* Run the whole scenario
```shell
docker-compose up
```

* Create entites
```shell
sh entities/createPredictionEntities.sh
```

* Train prediction model
```
TODO: Right now run in IntelliJ TrainingJob.scala
```

* Submit job to Spark
```shell
TODO: Right now run in IntelliJ PredictionJob.scala
Once it's done change the notify url in entities/subscribeReqPredictionTicket.sh to the spark container name
Also, add packaging instructions and submit using spark-submit
```

* Subscribe to predictions 
```shell
sh entities/subscribeResPredictionTicket.sh
```

* Subscribe to prediction requests
```shell
sh entities/subscribeReqPredictionTicket.sh
```
* Open browser in http://localhost:8080

* Select a date and time range

* Predict!
