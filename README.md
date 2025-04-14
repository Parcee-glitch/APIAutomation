**API Automation for Assurity Consulting**

This repository contains a Postman-based test automation script for validating the Assurity Consulting API.

**📌 Project Overview**

We are testing the following API endpoint: [https://api.tmsandbox.co.nz/v1/Categories/6327/Details.json?catalogue=false](https://api.tmsandbox.co.nz/v1/Categories/6327/Details.json?catalogue=false)

The script checks whether the response meets the specified acceptance criteria.

**✅ Acceptance Criteria**

The test validates the following:

\- **Status Code**: Response status is "200" (Optional).

\- **Name Field**: The \`Name\` field in the response is “Carbon credits”.

\- **CanRelist**: The value of "CanRelist=true".

\- **Promotions Array**:

\- There is a promotion with "Name = Gallery”.

\- That promotion has a “Description = Good position in category”.

**🚀 How to Run the Test**

Option 1: Use Postman GUI

1\. Open Postman.

2\. Import the collection file:

\- Assurity Consulting.postman\_collection.json

3\. Run the collection manually or using the built-in Collection Runner.
