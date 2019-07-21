# IBMHackChallenge-MethodTracer

This desktop app is used to trace method in a java program.it is a program which help developer to find the problematic method and also find the count and time taken by methods. 

========================
# BUILD OUTPUT DESCRIPTION
========================

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "TraceMethod.jar" 

OR 

You can run it manully also from repo

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.

* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.

* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.

* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.


prerequisite:the java program should be compiled.

Step1: Open the TraceMethod.jar file by double click.

Step2: Choose the ".class" file you have to analyze or compare.

Step3: Click from the below two options if "Compare" clicked then go to Step 4 or else go to step 5.

Step4: 

	Step4.1: Run all 4 commands on cmd from anywhere and click  and click proceed.
	
	Step4.2: The output is the two tables with 2 trace data.


Step5: 
	
	Step5.1: Run the 2 commands on cmd from anywhere and click  and click proceed.
	
	Step5.2: The output is the two table trace data.
	
	Step5.3: Click on Barchart to get the bar chart of the frequency of the methods.


NOTE : You can run the cmd command from anywhere.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

The code is in TraceMethod.rar file named as TraceMethod-CODE.rar you have to extract it to see whole code and work in java.

Please delete a.trc, b.trc, a.log, b.log from your class file locations.

