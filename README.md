# Scala seed project for Spark-ML

## Running on the command line with SBT:

This is a seed project to get you started with Apache Spark quickly. It contains HelloWorld and TextClassification apps.

Download the project and in the command line:

    sbt run

Then it will provide two options: HelloWorld and TextClassification. Choose 1 or 2 and see the results.


## Running on IntelliJ

Make sure you have installed Scala and SBT plugins for IntelliJ.

In IntelliJ, click File->Open and choose the spark-seed folder. A dialog will appear. Choose all checkboxes except for Auto-Import. When the editor opens up, open build.sbt and click "Refresh project"  on the top right to install the SBT requirements. After installing dependencies, IntelliJ will show you the source folders on the left.

Now navigate to src/main/scala/HelloWorld.scala. Right click and Run 'Hello World'. See the outputs. Do the same thing for TextClassification.

Enjoy it!
