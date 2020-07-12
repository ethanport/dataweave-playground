# DataWeave Playground
### First Open Source DataWeave Playground

### What is the DataWeave Playground?

Is a tool for quick and easy development of DataWeave scripts

![DataWeave Playground](./images/playground.png)

### Features

* Save and Open DataWeave Playground projects (**.dwp** files), to not loose the progress of your transformations.
* Able to quickly modify your input data selecting the correspondent mimeType and see instantly the result of your transformation.

### Missing Features
* Code areas with highlighting
* Auto formatting for DataWeave scripts
* Add multiple inputs
* Export application as a native one
* DataWeave script validation

## How to run the application

To build the DataWeave Playground, navigate to the outer GitHub repo folder (where this README file is located along with the pom.xml file) and execute
```mvn clean package```

To run the DataWeave Playground using maven, execute the following command:

```mvn exec:java -Dexec.mainClass="com.github.estebanwasinger.DWPlayground"```
