

## Step 1: Access the Azure Portal
Go to the Azure Portal.
Navigate to your storage account.
## Step 2: Open Your Storage Account
In the left-hand menu, click on "Storage accounts."
Select the storage account where you want to apply the lifecycle management policy.
## Step 3: Navigate to Lifecycle Management
In the storage account menu, scroll down and click on "Lifecycle Management" under the "Blob service" section.
## Step 4: Add a New Rule
Click on "+ Add rule" to create a new lifecycle management rule.
## Step 5: Define Rule Conditions
* Rule name: Give your rule a name, such as "ArchiveAndDeleteRule".
* Prefix filter: Optionally, you can specify a prefix if you want to apply the rule to a specific subset of blobs. Leave it blank to apply the rule to all blobs.
* Blob type: Select "Block blob" as the blob type.
## Step 6: Add Rule Actions
Base blob actions:

* Click on "+ Add a rule action".
Select "Move to archive storage" and set the number of days after modification to 30.
* Click on "Save".
Base blob actions (continued):

* Click on "+ Add a rule action" again.
Select "Delete blob" and set the number of days after modification to 365.
* Click on "Save".
Step 7: Review and Save the Rule
Review the conditions and actions you have defined.
* Click on "Add" to save the rule.

