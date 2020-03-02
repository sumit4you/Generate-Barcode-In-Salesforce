# Salesforce-2D-Barcode

This article is for 2D-128B (Code Set B) Barcode, In this article we have used www.bcgen.com serviceds to generate our barcodes.

Steps 1: Create formula field

        Field             API Name              Type             Return Type                      
        Barcode           Barcode__c            Formula          Text

Field Value:
IMAGE("https://www.bcgen.com/demo/linear-dbgs.aspx?S=13&D="+Name+"&CC=F&CT=F&ST=T&X=0.03&O=0&BBV=0&BBH=0&CG=0&BH=1&LM=0.2&EM=0&CS=0&PT=T&TA=F&CA=7-Eleven","Barcode")

You can modifay this above Barcode accroding to your requirement.

For more information or question, you can reach out me, through my email address.

Email:- sumitchoubey247@gmail.com
