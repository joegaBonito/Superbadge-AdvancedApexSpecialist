# Superbadge-AdvancedApexSpecialist


Pre work

1. Create a new Trailhead Playground for this Superbadge
2. Instal this pkg - https://login.salesforce.com/packaging/installPackage.apexp?p0=04tf4000001O5si
3. Update the Product Family field on the Product2 sObject to only have the following values: Entree, Side, Dessert, Beverage
4. Update the Product page layout to include the Initial Inventory, Quantity Ordered, and Quantity Remaining fields
5. Update the Account page layout to display the Orders related list.
6. Remove the Contract Number field from the Order page layout if it is currently there
7. Use the methods provided in the unmanaged package without changing their name or signature.

Challange
Step 1. Create two custom labels with the following attributes:

Short Description	    Name	                  Categories	    Value	                Protected Component
Select One	          Select_One	            constants	      Select one	          Unchecked
Inventory Level Low	  Inventory_Level_Low	    constants	      Has a low inventory	  Unchecked


Step 2. Create a custom metadata type with the following attributes.

Field	              Value
Singular Label	    Inventory Setting
Plural Label	      Inventory Settings
Object Name	        Inventory_Setting

Next, create a new field on the new metadata type.

Field	              Value
Type	              Number
Field Label	        Low Quantity Alert
Length	            18
Decimal Places	    0
Field Name	        Low_Quantity_Alert

Manage Inventory Settings to create the following custom metadata records.

Master Label	  Low Quantity Alert
Entree	        20
Side	          10
Dessert	        15
Beverage	      5

Step 3. Delete packagetest class

Step 4. Create chatter group named "Inventory Announcements"

Step 5. Copy all code from below link [git repo link]  
https://github.com/amitjpr/Superbadge-AdvancedApexSpecialist

Step 6. Overwrite the NEW and ADD button of product2 object with VF page

Step 7. Check chalanges one by one. 

#DONE Yahoo!!!


