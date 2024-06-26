# calc -- Beautiful Calculator on the F# WebSharper-SPA
<img src="https://user-images.githubusercontent.com/16160120/164889033-ddc76ec5-9a32-4855-9cbb-3631b1d563cf.png" width="300px" />  
https://fujiwat.github.io/calc-FSharp/wwwroot/

## Overview
This is a simple calculator with a decimal point. using F# WebSharper-SPA.

## Requirement
Modern Web Browser
Visual Studio 2022
For the development environment, following commands are needed:  
```
> dotnet new -i WebSharper.Templates
> dotnet tool install -g dotnet-ws
> cd c:\<parent-folder-of-the-projects>
> dotnet new websharper-spa -lang f# -n <project-name>
> cd <project-name>
> dotnet add package WebSharper.UI
> dotnet tool install -g dotnet-ws
```

## Usage
Just Click the buttons as same as the physical regular calculator.  If you want to get the result of 1 + 2 * 3 then that means 1 + (2 * 3) = 7 therefore you need to click following order:  
  \[2\] \[\*\] \[3\] \[+\] \[1\] \[=\]  
When you click the buttons for * / - + then the calculation is immediately occurred.  Therefore, if you click buttons by the following order then the result is ( 1 + 2 ) \* 3 = 9:  
  \[1\] \[+\] \[2\] \[*\] \[3\] \[=\]

## Features
![image](https://user-images.githubusercontent.com/16160120/164895452-15531965-ddb3-4dd3-ae0c-0d34eb77e571.png)
![image](https://user-images.githubusercontent.com/16160120/164895464-c47cfca0-e001-455c-a1c6-15ad61f47c6f.png)
![image](https://user-images.githubusercontent.com/16160120/164895855-3b630f61-d066-438a-9362-df34ea7f774e.png)
![image](https://user-images.githubusercontent.com/16160120/164895492-19b24c0b-1a4d-4c36-abaf-34efbf0eed3e.png)
![image](https://user-images.githubusercontent.com/16160120/164895811-c3c98953-99e0-4266-a442-963bac998c08.png)
![image](https://user-images.githubusercontent.com/16160120/164895750-5cc835bb-5972-4294-a7f8-a01c648e903b.png)
![image](https://user-images.githubusercontent.com/16160120/164895519-84f1c1d2-9a63-4e92-9e80-7774792ccbfb.png)
![image](https://user-images.githubusercontent.com/16160120/164895528-0e1c61ea-8903-4bca-80db-f47655df8322.png)
![image](https://user-images.githubusercontent.com/16160120/164895532-d1ef6afc-e6ed-448e-a7a8-8aed658e9381.png)
![image](https://user-images.githubusercontent.com/16160120/164895790-ef2c6257-15c4-4ec8-98d6-a8295569dc31.png)
Corresponds to each digit in the number.  
![image](https://user-images.githubusercontent.com/16160120/164895282-2e333bc8-89b7-470b-966a-1afcef462130.png) Input the decimal point.  
![image](https://user-images.githubusercontent.com/16160120/164894253-a5faa34c-968b-44e8-b12c-3c35828f30a5.png) Get Pi 3.14.....  
![image](https://user-images.githubusercontent.com/16160120/164894284-bc006a59-a772-49cb-a25f-aafc84b5d30b.png) Get Sin for the displaying value.  Value is radian only.  
![image](https://user-images.githubusercontent.com/16160120/164894292-a8899c46-cbfe-4208-9581-771c5251fe5d.png) Get Cosin for the displaying value.  Value is radian only.  
![image](https://user-images.githubusercontent.com/16160120/164894303-abd08d00-4095-4ee0-b767-c36961218556.png) Get tangent for the displaying value.  Value is radian only.  
![image](https://user-images.githubusercontent.com/16160120/164894317-4f0db86d-a036-4c36-a07e-a881d74c0a21.png) Backspace without decimap point ".".  
![image](https://user-images.githubusercontent.com/16160120/164895007-57c29ab1-04aa-47fc-8c1f-25885b156e4d.png) Calculate immediately.  
![image](https://user-images.githubusercontent.com/16160120/164894399-dababace-ee12-4de6-874b-25d4c1515c6a.png) Clear the input value to zero.  
![image](https://user-images.githubusercontent.com/16160120/164894424-29822b4d-f291-48a6-82a7-3921ea34fd16.png) All Clear the first operand and 2nd operand.  
![image](https://user-images.githubusercontent.com/16160120/164895383-6369befa-6e7c-4508-a546-2683b22ccfbd.png) Get negative number for the displaying value.  
![image](https://user-images.githubusercontent.com/16160120/164895427-91708476-0263-45dd-bac9-4125d2efe298.png) Get the inverse number for the displaying value.  
![image](https://user-images.githubusercontent.com/16160120/164895028-1b82f163-c264-4391-9216-de5f6c0bdd82.png) Calculate immediately and set the next operation as division.  
![image](https://user-images.githubusercontent.com/16160120/164895035-b37a5f38-2001-40f3-a001-a1323d8db188.png) Calculate immediately and set the next operation as multiplication.  
![image](https://user-images.githubusercontent.com/16160120/164895044-973ff213-3275-4204-8b3b-a111124200bb.png) Calculate immediately and set the next operation as subtraction.  
![image](https://user-images.githubusercontent.com/16160120/164895054-a542281c-5233-4ca4-b20c-22649f64274a.png) Calculate immediately and set the next operation as an addition.  

## Restrictions
The calculation values are using `double` which means 64bit IEEE floating-point number type.  Sometimes it causes a margin of error therefore this program round to the 10th decimal place.

## Reference
This program is derived from the following source code and modified the color and added functions "1/x", "Sin", "Cos", "Tan", and decimal point.  
https://try.websharper.com/snippet/adam.granicz/00002I  
Web-font 'Quantico' is used from the following google font.  
https://fonts.google.com/specimen/Quantico

## Author
Takahiro FUJIWARA
https://www.linkedin.com/in/fujiwat/
