
![image](https://user-images.githubusercontent.com/79970797/109964566-d832f180-7d13-11eb-93bc-b071ea7cfb89.png)


SAP Bydesign Customized QC functionality
 
Parameter Master – This screen is being used to define all the quality parameters of all products. These parameters will further be tagged with Materials after creation of Inspection Plan. Parameter master can be accessed by going on to Parameter Master Work Center. 
Following are the screenshots 
 

 

In the above screenshot, we have defined three parameters. P0001, P0002 & P0003. 







Inspection Plan: Parameter earlier created will be linked with material in this document. We have created a new supplier delivery inspection plan for Raw Material RM001. We will edit this to define the parameters for QC check. 

 

 

Parameters has been linked with items and result of all parameters are different. Following screen shot will show the same 
P0001 – Visual Look & Result Type is defined as Alpha Numeric and accepted values are OK 
 

P0002 – Length & Result Type is defined as Range and accepted values must be in range from 10-12
 

P0003 – Diameter & Result Type is defined as Numeric and accepted values must be numeric with value 2
 
Inspection: After creation of Inbound Delivery, system will create the Inspection itself based on defined logistic model. Apart from standard fields, user will fill the below details 
Accepted Quantity & Accepted Logistics Area
Sample Quantity & Sample Logistics Area (If Applicable)
Rejected Quantity & Rejection Logistics Area (If Applicable)
Parameter wise results in observation field & Parameter wise accept / Reject. 
 

After clicking on ‘Create Goods Movement’, system will create a Goods Movement and that will transfer the quantity from Receiving Logistics Area to Different Logistics Area. 
 
Goods Movement document can be opened by clicking on ‘Link’ button defined. 
 

Following is the Goods Movement which is created 
 

