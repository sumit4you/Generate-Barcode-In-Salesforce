# Generate Barcode In Salesforce

In this article, we have used 2D-128B modal Barcode, with the help of www.bcgen.com.

For generating the barcode we have to create below components in your Salesforce instance.

Steps 1: Create formula field

        Field             API Name              Type             Return Type                      
        Barcode           Barcode__c            Formula          Text

Field Value:
IMAGE("https://www.bcgen.com/demo/linear-dbgs.aspx?S=13&D="+Name+"&CC=F&CT=F&ST=T&X=0.03&O=0&BBV=0&BBH=0&CG=0&BH=1&LM=0.2&EM=0&CS=0&PT=T&TA=F&CA=7-Eleven","Barcode")

In a place of "Name", you can use any field to convert the value into the Barcode.

You can also modifay this above Barcode accroding to your requirement.

For more information or question, you can reach out me, through my email address.

Email:- sumitchoubey247@gmail.com
