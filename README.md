# 4cGold-Performance-tests


![pngjoy com_load-new-gatling-io-wp-gatling-logo-bat_5086430](https://user-images.githubusercontent.com/79532994/117981296-c598f200-b32c-11eb-839f-dba407381100.png)

 ## Technology Used:
 ```
 Gatling,Scala
 
 ```
 ## Built With
 
 1. [Gatling](https://gatling.io/) - Performance Testing Tool
 2. [Scala](https://www.scala-lang.org/)- Language used to built the Code.

Gatling is a highly capable load testing tool. It is designed for ease of use, maintainability and high performance.
Gatling comes with excellent support of the HTTP and JMS protocols. The core engine is protocol agnostic, 
it is perfectly possible to implement support for other protocols,an open-source load testing framework based on Scala, Akka and Netty that features High performance, Ready-to-present HTML reports.

## Installation of Gatling 

1. Make sure that you have the JDK8 (or newer installed).
2. The simplest way to install Gatling is to download the open-source Gatling version from the Gatling.io website. Click Download, and a ZIP file will be downloaded.
3. Unzip the file anywhere on your computer. Open up the new folder, and browse to the bin directory. From here, run either:

 > **gatling.bat** - If you are on Windows
	
 >  **gatling.sh** - If you are on a Mac or Unix machine

4. Gatling will load, and you will be asked to choose a simulation to run
5. Download the Simulation files from the project and copy to the simulation folder
6. Choose the Simulation Script you wish to run. You will be asked to enter a run description, but this optional and can be left blank
7. Gatling will go ahead and run the script that you choose - which executes a load test 

## Gatling Results Analysis

At the end of each execution of a Gatling script, a Gatling Results Report is automatically created.

You will see a message in the console about where the report is located, i.e.
```
Please open the following file: /Users/jw/Desktop/myGatlingTest/target/gatling/runtimeparameters-20200207112322164/index.html
```
## Overall Simulation charts
1. Global Section-This report shows global or aggregate level information with the total number of requests/responses and the total failed requests/responses at a scenario or simulation level
2. This chart shows how response times are distributed among standard ranges. The right panel show number of OK/KO requests.
3. The top panel shows some standard statistics such as min, max, average, standard deviation and percentiles globally and per request.
4. Response time distribution-displays the distribution of the response times.
5. Response time percentiles over time-displays a variety of response time percentiles over time, but only for successful requests. As failed requests can end prematurely or be caused by timeouts, they would have a drastic effect on the percentiles computation.
6. Requests per second over time-displays the number of requests sent per second over time
7. Responses per second over time-displays the number of responses received per second over time : total, successes and failures.
