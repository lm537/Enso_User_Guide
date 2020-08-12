# 1.	Define Domain Objects

  
**Importance of Domain Object**   
 For a solution engineer, it is important to configure Domain Object to create a schema for the data to map the extracted text from ingested documents. Domain object is the representation of the universal data model that standardizes the flow of data through the sytem. To get the correct entity- attribute linking in the final output, it is essential to define entity and attributes correctly in domain object with appropriate synonym and NERs.  Domain object should be defined in such a manner that it can work for any file ingestion within our scope of work.

For example, to capture the patient information such as Name, Gender, SSN number from a patient medical form, the following schema can be followed.

Domain Object: medical form &lt;Can be any name&gt;

Entity: patient\_personal\_information &lt;can be any name&gt;

**Attribute1:**  Name &lt;can be any name, but possible synonyms to be given are: Patient Name, Patient or NER type must be defined such person, place, phone etc.&gt;

**Attribute2:** Gender &lt;can be any name but possible synonyms to be given are: Sex,gender&gt;

**Attribute3:** ssn\_number &lt;can be any name but possible synonyms to be given are:  ssn\#, ssn, ssn number &gt;

![](../../../.gitbook/assets/image%20%2846%29.png)



