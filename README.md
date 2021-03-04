

SAP Bydesign Customized QC functionality
 
Parameter Master – This screen is being used to define all the quality parameters of all products. These parameters will further be tagged with Materials after creation of Inspection Plan. Parameter master can be accessed by going on to Parameter Master Work Center. 
Following are the screenshots 
 

 

In the above screenshot, we have defined three parameters. P0001, P0002 & P0003. 


![image](https://user-images.githubusercontent.com/79970797/109964717-0adcea00-7d14-11eb-8a9e-7a4ca1a34e4d.png)

![image](https://user-images.githubusercontent.com/79970797/109964820-2c3dd600-7d14-11eb-802e-870325033693.png)






Inspection Plan: Parameter earlier created will be linked with material in this document. We have created a new supplier delivery inspection plan for Raw Material RM001. We will edit this to define the parameters for QC check. 

 ![image](https://user-images.githubusercontent.com/79970797/109964856-39f35b80-7d14-11eb-98d5-a9e21919c0a1.png)

![image](https://user-images.githubusercontent.com/79970797/109964895-424b9680-7d14-11eb-860d-b6740caa4022.png)


 

Parameters has been linked with items and result of all parameters are different. Following screen shot will show the same 
P0001 – Visual Look & Result Type is defined as Alpha Numeric and accepted values are OK 
 
 ![image](https://user-images.githubusercontent.com/79970797/109964943-51324900-7d14-11eb-82e6-93cfa651f2a3.png)


P0002 – Length & Result Type is defined as Range and accepted values must be in range from 10-12
![image](https://user-images.githubusercontent.com/79970797/109964961-568f9380-7d14-11eb-8deb-4687bb218f0b.png)

 

P0003 – Diameter & Result Type is defined as Numeric and accepted values must be numeric with value 2
 ![image](https://user-images.githubusercontent.com/79970797/109964991-60b19200-7d14-11eb-8c60-3c657b32e0d1.png)

 
Inspection: After creation of Inbound Delivery, system will create the Inspection itself based on defined logistic model. Apart from standard fields, user will fill the below details 
Accepted Quantity & Accepted Logistics Area
Sample Quantity & Sample Logistics Area (If Applicable)
Rejected Quantity & Rejection Logistics Area (If Applicable)
Parameter wise results in observation field & Parameter wise accept / Reject. 

![image](https://user-images.githubusercontent.com/79970797/109965027-6ad39080-7d14-11eb-9d0c-30bc19eff1fc.png)


After clicking on ‘Create Goods Movement’, system will create a Goods Movement and that will transfer the quantity from Receiving Logistics Area to Different Logistics Area. 
 ![image](https://user-images.githubusercontent.com/79970797/109965065-78891600-7d14-11eb-8468-3db70bc5b167.png)

 
Goods Movement document can be opened by clicking on ‘Link’ button defined. 
 ![image](https://user-images.githubusercontent.com/79970797/109965095-80e15100-7d14-11eb-83f8-124f12ad2569.png)


Following is the Goods Movement which is created 
 ![image](https://user-images.githubusercontent.com/79970797/109965118-876fc880-7d14-11eb-8c90-a833dbb1f05b.png)


