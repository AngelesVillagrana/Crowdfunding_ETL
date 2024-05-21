Crowdfunding ETL Project: A Summary
What We Did
This project was all about transforming and organizing data from a crowdfunding platform. We took raw data from some Excel files, cleaned it up, organized it, and then loaded it into a database. Here’s a step-by-step breakdown of what we accomplished:

1. Organizing Categories and Subcategories
First, we looked at the raw data about the different categories and subcategories of crowdfunding campaigns. We needed to make this data easy to work with, so we:

Created a List of Categories: We identified all the unique categories and assigned each one a unique ID.
Created a List of Subcategories: Similarly, we listed all the unique subcategories, giving each one its own unique ID.
Saved These Lists: We saved these organized lists as CSV files, which are simple text files that store data in a structured way.
2. Structuring Campaign Data
Next, we focused on the main data about the crowdfunding campaigns. We needed to create a clear and organized table, so we:

Extracted Key Information: We took important details like campaign ID, company name, description, funding goal, amount pledged, and more.
Formatted the Data: We made sure all the data was in the right format. For example, we converted dates into a standard format and ensured numerical data was consistent.
Linked Categories and Subcategories: We matched each campaign with the correct category and subcategory using the IDs we created earlier.
Saved the Table: This organized table was also saved as a CSV file.
3. Cleaning Up Contact Information
We then worked on the contact details of people involved in the campaigns. To make this data useful, we:

Extracted the Data: We pulled out contact information like contact ID, full name, and email.
Split Names: We separated the full names into first and last names.
Formatted and Cleaned the Data: We made sure all the contact details were clean and consistent.
Saved the Contacts: This cleaned-up contact data was saved as another CSV file.
4. Building the Database
Finally, we put all this organized data into a database to make it easy to manage and analyze. Here’s how we did it:

Designed a Visual Diagram: We created a visual map (called an ERD) to show how all the different pieces of data are related.
Defined the Database Structure: Using this diagram, we created a database schema, which is like a blueprint for the database, detailing what each table should look like and how they connect.
Set Up the Database: We used the schema to create the actual database in Postgres, a type of database management system.
Loaded the Data: We imported all our CSV files into the corresponding tables in the database.
Checked the Data: We ran some checks to make sure all the data was correctly loaded and organized in the database.
Collaboration and Workflow
Throughout this project, we worked closely with a partner. We regularly communicated to divide tasks and support each other, ensuring that we stayed on track and completed the project efficiently.

Final Outcome
The end result of this project is a well-organized Postgres database containing clean, structured data about crowdfunding campaigns, categories, subcategories, and contacts. This database is now ready to be used for analysis or further development.


