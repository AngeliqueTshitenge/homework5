Description

The EarthquakeQueryApp program is a Java application that allows you to read earthquake data from a CSV file named all_month.csv. It analyzes the data to extract information about the date, magnitude, and place of each earthquake. The program then provides a summary of the information in the console.

Features

Reads a CSV file containing earthquake data.

Counts the total number of earthquake records.

Stores extracted data in tables for easy handling.

 Displays the total number of earthquakes.
 
 Prints the details (date, magnitude, place) of each earthquake in the console.

Prerequisites

 Java Development Kit (JDK): Version 8 or later must be installed on your system.CSV file: The all_month.csv file containing the data must be placed in the same directory as the Java file.

Expected structure of the CSV file

The CSV file must contain at least three columns:
 Date: ISO format (ex. 2024-12-01T00:00:00Z).

Magnitude: Decimal number representing the magnitude (e.g. 5.3).

 Location: Textual description of the location (e.g. "Near the coast of Chile").

Example of file content:

Date,Magnitude,Place

2024-12-01T00:00:00Z,5.3,"Near the coast of Chile"

2024-12-02T12:45:10Z,4.8,"California, USA"

Installation Steps

 Download the EarthquakeQueryApp.java file.
 
 Place the all_month.csv file in the same directory as the Java file.

 Make sure the JDK is installed and configured.

Instructions for running the program

Compilation of the code:

Open a terminal or command prompt.

Navigate to the directory where EarthquakeQueryApp.java is located.

 Run the following command to compile the program:

Java EarthquakeQueryApp.java

Program execution:

Once the program is compiled, run it with the command:

Java EarthquakeQueryApp

The program will analyze the CSV file and display the information in the console.