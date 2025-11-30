# GEN-AI
Code Related to GEN AI
Instruction
Generate test data for Credit card Application
[Mandatory] create positive and negative test data with proper error message in the response
[Critical] while creating test data apply filters for credit check in order to eligible for credit card 
[Mandatory] validate the customer profile whether he involved in any risk related factor or bank corrupcy 
[Critical] 

Context
You are expertise in banking domain specifically with respect to credit card features  and eligibility criteria 

Example

Here are examples of test data for a credit card application in Excel and JSON formats:

Excel Format:
| Field Name | Data Type | Example Value |
| FirstName | String | John |
| LastName | String | Doe |
| Email | String | johndoe@example.com |
| PhoneNumber | String | 123-456-7890 |
| Address | String | 123 Main St, Anytown, USA 12345 |
| City | String | Anytown |
| State | String | CA |
| ZipCode | String | 12345 |
| Country | String | USA |
| DateOfBirth | Date | 1990-01-01 |
| Income | Number | 50000.00 |
| EmploymentStatus | String | Employed |
| CreditScore | Number | 700 |
| CardType | String | Visa |
| CardLimit | Number | 1000.00 |
JSON Format:
{
  "firstName": "John",
  "lastName": "Doe",
  "email": "johndoe@example.com",
  "phoneNumber": "123-456-7890",
  "address": {
    "street": "123 Main St",
    "city": "Anytown",
    "state": "CA",
    "zipCode": "12345",
    "country": "USA"
  },
  "dateOfBirth": "1990-01-01",
  "income": 50000.00,
  "employmentStatus": "Employed",
  "creditScore": 700,
  "cardDetails": {
    "cardType": "Visa",
    "cardLimit": 1000.00
  }
}


Persona
Review the test data generated like a Testing Architect

Output
Generate an output in json and excel format which is downloadable 

Tone
Provide the test data with respect to realtime scenario credit card application
