# EDI X12 Standard Transaction JSON Converte Snowflake Native App


Business Need:

In healthcare industry we have X12 data format that’s been used for various financial transactions such as purchase orders, invoices, healthcare claims which are not easy to read and complex as well.

X12 is a standard for EDI developed and maintained by the ANSI may have complex data structures. Transforming data from X12 format to JSON or even save them in a database tables may look challenging. Concord identify these data enrichment issues and provide UDFs built using Snowflake capabilities.


Description

This App is built up of various user-defined functions which solving different problems in ingesting the healthcare datasets. These functions provide capabilities to ingest the complex datasets, convert into readable formats, validate the datasets and many other functionalities that easing the ingestion process for these datasets.


This listing gives you access to one of the functions in our library which helps in converting X12 data into JSON format.
This listing provides you an access to a sample text file contains X12 data and an UDF called “x12Tojson” which provide a functionality to convert X12 data into JSON format along with description of the elements used in data. It takes an input of the X12 text file which needs to be present inside Snowflake staging area. In return it emits the JSON data which can be saved directly into the Snowflake tables and can be further parse using the Snowflake capabilities for reading the JSON data.

Expected Workflow in Snowflake:
1. Customer requests access to x12Tojson app through Marketplace listing
2. Customer shares provider / account information with Concord to join the private preview waitlist
3. Concord receives approval for customer, and adds them to the Private Listing
4. Once added, the app will be discoverable for the customer to implement


Conctact us at https://concordusa.com/contactus to learn more about EDI X12 Standard Transaction JSON Converter SaaS and what its capabilities can do for your business.



