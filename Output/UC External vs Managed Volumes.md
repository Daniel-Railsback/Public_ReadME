
# Here is a quick write up for Unity Catalog.  Here we are looking more into External & Managed Volumes. 

---

## Useful Links
 [Azure Volumes](https://learn.microsoft.com/en-us/azure/databricks/sql/language-manual/sql-ref-volumes)
[Reddit Article](https://www.reddit.com/r/databricks/comments/16tninv/managed_vs_external_tables/)
[Stack Overflow](https://stackoverflow.com/questions/78652707/databricks-managed-tables-vs-external-**tables**)
[Blog](https://medium.com/@tsiciliani/experimenting-with-databricks-volumes-5666cecb166)


# What is a Volume in Databricks

Volumes are a feature of Databricks similar to tables.  You get all the same benefit of security within Databricks, except volumes contain all sort of files not just data tables(Non-Tabluar). 


# What’s the difference between Managed & External Volumes


## Managed 
Host on the same storage blob as UC
100% managed on UC dashboard
When dropped it is deleted from Azure(Requires owner permissions)
Less Maintenance 
Harder to assign costs


## External 
Creation of blob storage required in Azure portal
Blob recovery options managed by IT
Delete only from Azure portal
Can read DLT pipeline but CAN NOT write

#databricks 




