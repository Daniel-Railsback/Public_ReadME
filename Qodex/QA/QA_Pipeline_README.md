# 📘 QA Pipelines README

### 📋 **Overview**

Welcome to the QA Pipeline Read me! 

Here you can find information about what pipelines are used to manage the QA dedicated sites. 

---

### 🚀 **Pipelines**

#### 📊 **QA Database**

- **Purpose:** Refreshes the data in the QA databases.
    - **Stages:**
        - 🔄 Refresh **QA1** with THS data
        - 🔄 Refresh **QA2** with Cooper data
	 **Schedule:** Release created @ 10 PM EST
	 **Execution:** Manual
	   **[Link](https://dev.azure.com/QodexSolutions/Atlas/_release?view=all&_a=releases&definitionId=47)**

#### 💻 **QA1 Front-End**

- **Purpose:** Deploys Atlas versions to `QA1.qodexsolutions.com`
- **Schedule:** Release created @ 5 AM EST
- **Execution:** Manual
- **[Link](https://dev.azure.com/QodexSolutions/Atlas/_release?view=all&_a=releases&definitionId=70)**
  
  

#### 💻 **QA2 Front-End**

- **Purpose:** Deploys Atlas versions to `QA2.qodexsolutions.com`
- **Schedule:** Release created @ 10 PM EST
- **Execution:** Manual
-   **[Link](https://dev.azure.com/QodexSolutions/Atlas/_release?view=all&_a=releases&definitionId=70)**
  
  
  
  
  
  #### Newest Changes: 
  QA-Front end has been separated out into individual pipelines.  This allows for more flexibility on what version or branch we want to deploy.