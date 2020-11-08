# Edfa3ly
This project is written in Java and use Chrome browser to simulate the following scenarios:

- Adding one of the automated products:launch the application then Enter automated Item url and select size then press Add Item button and validate the success message that the item is added to the cart successfully

- Adding one of the prohibited products:launch the application then Enter prohibted item url and all the fields disappear then validate warning message that this item is not available

How to run the scenarios?

- Download eclipse from https://www.eclipse.org/downloads/ then install it

- Download all jar files attached to the project(Selenium standalone server,Selenium Client & WebDriver language bindings,Google chrome driver and junit)

- Download Java <= 1.8 (Higher versions will not work)

- Add java 8 to eclipse following steps in this link https://dzone.com/articles/add-java-8-support-eclipse?fbclid=IwAR0T6ER8dgkgyLXOYIHjRDWd8YzSOG5tPIIuk4neLeesicD0z2qEHAP7i3k

- Open eclipse and create a new java project (Donot forget to select java version 1.8 when creating the project set use an execution enviroment JRE to JavaSE-1.8)

- Associate the downloaded jar files to the project: 

        - Right click on the project 
        
        - Select Build path then Configure build path
        
        - Select tab libraries then click on Add External Jars
        
        - Select all jar files (Selenium standalone server,Selenium Client & WebDriver language bindings,Google chrome driver and junit) need to add 
        
        - Press Apply and Close

- Create a folder in src then take chromedriver.exe copy and paste it in the folder

- Create a new package in src then add AddAutomatedProductItemScenario and AddProhibtedItemScenario classes that attached to the project to the package (Don't forget to change package name in the class to be the same as created package name)

