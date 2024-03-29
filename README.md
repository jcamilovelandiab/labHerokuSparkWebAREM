# AREM Laboratory 2 - Spark web

In this laboratory a web application was designed with Spark Web and Maven.

The user enters the data on the website, and the program calculates the mean and standard deviation of the entered data.

The following formulas were used to calculate the mean and standard deviation of the linked list.

![](https://github.com/jcamilovelandiab/TareaMVNGIT/blob/master/images/formulas.PNG)

## Heroku

The web application is deployed in heroku. To visit the website go to the following link. [SparkWeb Calculator](https://sparklab2.herokuapp.com/inputdata "Heroku Page")

## Prerrequisites

If you want to download and run the source code, it is necessary to have installed java 1.8 and Apache Maven 3.6.0  on the computer where the program will run.

## Running the project

To download the project dependencies the following line must be executed.
```
mvn package
```

To execute the project
```
mvn exec:java -Dexec.mainClass="edu.escuelaing.arem.SparkWebApp"
```

To open the website locally go to
```
http://localhost:4567/inputdata
```

Execute this line to see the java documentation.
```
mvn javadoc:jar
```


## Testing

Table 1 shows the data used to test the program.

![](https://github.com/jcamilovelandiab/labHerokuAREM/blob/master/images/testingData.PNG)

Table 2 shows the results.

![](https://github.com/jcamilovelandiab/labHerokuAREM/blob/master/images/testingResults.PNG)

## Author

Juan Camilo Velandia Botello - Escuela Colombiana de Ingeniería Julio Garavito, Colombia.

## License

This project is under the Apache license - see [LICENSE](LICENSE.md) for more details.
