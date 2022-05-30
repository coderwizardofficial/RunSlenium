5 Step by Step Instructions to run first basic Selenium Program



1.	Install Java and Set Java Home Path in System variables
2.	Install Eclipse and Create new Maven Project with Selenium Dependencies
3.	Understand creation of WebDriver object and its related classes
4.	Run the First Selenium WebDriver Program with Browser Invocation
5.	Different ways of setting Browser Driver executable files.



What can Kind of Interview Questions I can expect from above Concepts?























1.  What is Interface in Java?
        An interface is a group of related methods with empty bodies.
        Its class responsibility to implement the methods declared in the Interface
        When class agreed to implement the interface, they must need to provide implementation/bodies to all the defined methods in Interface

    In simple terms, Interface enforces the Contract to class to follow. 
        
  2. WebDriver is an Interface which provides Set of Browser Automation methods with empty bodies (Abstract methods)

      Classes like ChromeDriver, FirefoxDriver, MicrosoftEdgeDriver , SafariDriver etc implement the WebDriver Interface
      and provide their own implementation to the WebDriver methods 

   3. We need to create the object of the class to access the methods present in the class.

      ChromeDriver driver = new ChromeDriver ();
      driver object here has access to all the methods of Chrome driver 

      WebDriver driver = new ChromeDriver ();
      driver object here has access to the methods of Chrome driver which are defined in web Driver Interface













Selenium Web Driver Locators

•	As part of Automation, Selenium Performs actions (such as click, typing) on the Page HTML Elements.

•	The Locators are the way to identify an HTML element on a web page. 
Selenium WebDriver uses any of the below locators to identify the element on the page and performs the Action 


ID
Xpath
CSS Selector
name
Class Name
Tag Name
Link Text
Partial Link Text


<input type="text" placeholder="Username" id= “inputUsername”  value=" ">




Input -> tag name
Red-> attribute 
Green-> attribute associated value. 





Css Selector-

•	Class name -> tagname.classname ->  Button.signInBtn -> .error

•	Id -> tagname#id      ->   input#inputUsername

•	Tagname[attribute=’value’]

<input type="text" placeholder="Username” value=" ">

Input [placeholder=’ Username’]

•	//Tagname[@attribute=’value’]:nth-child(index). -  Child items
•	Parenttagname childtagname
•	input[type*='pass'] – CSS
•	tagname




Xpath –

•	//Tagname[@attribute=’value’]
//input[@placeholder=’ Username’’]

<input type="text" placeholder="Name">
//input[@placeholder=’ Name’]

•	//Tagname[@attribute=’value’][index]
•	//parentTagname/childTagname
•	//button[contains(@class,'submit')].  – Regular expression 
•	//tagname
•	//header/div/button[1]/following-sibling::button[1]
•	//header/div/button[1]/parent::div








Interview Question -

Core Java Basics needed to Get started with Automation –

•	Variables & Data types in Java
•	Working with Arrays
•	Loops & Conditions
•	Strings and its functions
•	Importance of Array Lists 
•	Array list operations and conversion of Array to List
•	Declaring Methods 
•	Accessing Methods in class & Static keyword









Note: Rest all topics are present in the last 2 sections of this course. 


![image](https://user-images.githubusercontent.com/104607577/170909560-66e650c9-c877-4ffa-8e7d-92a68f8f6ff5.png)
