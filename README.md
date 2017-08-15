# superstockmarket
Super Simple Stock Market for JPMorgan

#Requirements

* Provide working source code that will:-
  * For a given stock, 
    * Given any price as input, calculate the dividend yield
    * Given any price as input, calculate the P/E Ratio
    * Record a trade, with timestamp, quantity of shares, buy or sell indicator and 
    * Calculate Volume Weighted Stock Price based on trades in past 15 minutes
  * Calculate the GBCE All Share Index using the geometric mean of prices for all stocks traded price


#How to use:
This is a maven project, so you can run these 2 goals:
* mvn test -> to execute the unit tests.
* mvn package -> to generate the executable jar.

To run the program just run:
* java -jar target/superstockmarket-0.0.1-SNAPSHOT.jar

#Classes
* com.jpmorgan.superstockmarket.App -> Just a sample app using the main classes Stock and GBCE
* com.jpmorgan.superstockmarket.GBCE -> Class used to calculate the All Share Index
* com.jpmorgan.superstockmarket.Stock -> Class used to manage the operations against the stocks
* com.jpmorgan.esuperstockmarket.Trade -> Just a bean representing each trade

#Packages
* com.jpmorgan.superstockmarket -> The main project package
* com.jpmorgan.superstockmarket.enums -> Package containing some enums needed 
