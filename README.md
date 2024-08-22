# ContactTrigger
This trigger calculates Contact objects on Account object, and store this value to a custom number field (Count_Contact__c) on Account object. It handles insert, update, delete, and undelete events. 
# When you create an account: Count_Contact__c field is NULL, should be handled
Steps to Set Default Value:
•	Go to Setup > Object Manager > Account > Fields & Relationships.
•	Find the Count_Contact__c field and click Edit.
•	Set the Default Value to 0.
•	Save the changes.
