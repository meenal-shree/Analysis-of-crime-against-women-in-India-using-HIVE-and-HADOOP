# Analyzing the crimes against women in India using Apache Hive

## Project Description

The aim of this project was to analyze the data of crimes that were done against the women in India during the period 2001-2012. I have tried to find the major crimes that were done against the women in each state, based on the data collected. The analysis was done so the we can shine some light on the problems that are being faced by women in the society. This analysis helped us to find the states that has the most cases, the percentage of average change in crime against women in India and also see the states where the cases went down during the time period of 2001 to 2012.

## Technologies Used

* HDP 2.6.5
* Hive 2.1.0
* Hadoop 2.7.3
* Sqoop 1.4.6
* MySQL 10.5
* Git/GitHub  

## Problem Statement

* What are the crimes done against women in India between 2001 to 2012?
* What is the percentage increased between years?
* What are the major crime against women per state?
* What is the total average change in crimes between 2001 and 2012?

## Getting Started

> All the operations below are for Windows OS.
   
* Make sure that the virtualization is enabled for your system from the BIOS.
* Install VMware Workshation Player.
* Download and insatll Hortonworks HDP 2.6.5.
* Get everything up and runninng.
* Connect to the system either through the webshell/OpenSSH/PuTTY.
* Upload all the required files into the local system or clone this repo using the following command:-
```
git clone https://github.com/meenal-shree/Analysis-of-crime-against-women-in-India-using-HIVE-and-HADOOP
```
> For linux, install all the dependencies and then run the project from the command-line.

## Usage

All the queries used in thge project can be fount [here](./Queries/queries.txt)

To run the hive queries, use the Hive shell

Use the Sqoop commands to load the data into MySQL
`sqoop export --connect jdbc:mysql://localhost:3306/<DB Name> -username <user> -password <pass> -table <table_name> -m 1 --export-dir /path/to/dir --input-fields-terminated-by ',';`

To run the MySQL queries, use the MySQL shell 
`mysql -u<username> -p<password>`

# License

 This project uses the [MIT](./LICENSE) license.

# References
 [Dataset](https://www.kaggle.com/navinch/crime-against-women-in-india)
