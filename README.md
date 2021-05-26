

SAP Bydesign Customized QC functionality
 


Parameter Master – This screen is being used to define all the quality parameters of all products. These parameters will further be tagged with Materials after creation of Inspection Plan. Parameter master can be accessed by going on to Parameter Master Work Center. 
Following are the screenshots 
 
![image](https://user-images.githubusercontent.com/79970797/109966632-817ae700-7d16-11eb-9447-8bf68b987459.png)


![image](https://user-images.githubusercontent.com/79970797/109964820-2c3dd600-7d14-11eb-802e-870325033693.png)
 

In the above screenshot, we have defined three parameters. P0001, P0002 & P0003. 




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
 
 Steps for Solution Replication into another tenant
 1.	Click on Administrationswitch customer
 
   ![image](https://user-images.githubusercontent.com/79970797/119613594-e415e780-be1a-11eb-8116-8a643ba45567.png)
   
 2.	Click on Create Customer and assign Customer name and Customer ID.
 
  ![image](https://user-images.githubusercontent.com/79970797/119613720-0a3b8780-be1b-11eb-9eb7-c514a8cb5427.png)

3.	To moving a solution into another tenant, click on viewImplementation manager

   ![image](https://user-images.githubusercontent.com/79970797/119613765-17587680-be1b-11eb-9933-d2b26f1292da.png)

4.	Select Assemble and Download option from Implementation manager. This will download and assembled a Zip file for complete solution in your local PC.

   ![image](https://user-images.githubusercontent.com/79970797/119613806-28a18300-be1b-11eb-941b-28b4bcc4c383.png)

5.	Now, Logoff from local tenant and re-login into another tenant.
6.	Click on ViewImplementation managerclick on Upload.
7.	Upload the same zip file which you have downloaded on the local tenant.
8.	Once it’s been uploaded, you need to activate the solution in implementation manager

   ![image](https://user-images.githubusercontent.com/79970797/119614062-76b68680-be1b-11eb-8a9d-f316f7828389.png)
   Implementation manager screen will show exact status of solution upload after processing of Activate.


