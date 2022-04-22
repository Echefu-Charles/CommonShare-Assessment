# CommonShare-Assessment

CommonShare acquires, normalizes and consolidates information for a variety of data resources. In order to do so, we often utilize information from publicly available sources. In this test, we would like to better understand the way you 
* 1.) Think about data scraping and scripting and 
* 2.) Your actual skills in doing so. Here we will work on scrapping a marketplace directory outside of the domain where CommonShare works. 

The final submission for this test should be:

* An explanation of how you performed the scrape, challenges you faced and how you overcame them. If you used specific tools, please mention them 
* A CSV file with all of the data you were able to acquire 

### Overview:

This platform lists 77,000+ organizations on its website. We would like you to acquire the data against all of these organizations. The search page for the directory is available here: ( https://www.devex.com/organizations/search ). When you select into any organization, the internal page will present information such as the below: (https://www.devex.com/organizations/environmental-resources-management-erm-21485). Please generate a scrape that captures at least the following information from the internal tabs 

#### 1st Tab - Organizational Information 

* Company Name
* Company Logo
* Company Description 
* Organization Type
* Staff
* Development Budget
* Headquarters
* Founded
* website link 
* Sectors, comma separated in one column
* Funded, comma separated in one column
* Countries, comma separated in one column 
* Skills, comma separated in one column 

#### 2nd Tab - Contracts

* Use the Company Name as the unique identifier
* Contract Name, 
* Contract Fundier, e.g. Bill and Melinda Gates Foundation  
