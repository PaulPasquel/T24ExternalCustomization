# T24ExternalCustomization

One of the hardest functionality as T24, is to use another programming language to manage customization. 
I want to implement a connection library that allows to interact with T24 operations (VERSION, ENQUIRY), 
using a local DSL. Usign this new DSL a new business logic can be built, wihtout using internal elements.

Example:
- Recieve payment information
- Read Debit Account information
- Check and validate local conditions, with respect Debit Account
- Calculate local taxes and commissions
- Apply Payment


