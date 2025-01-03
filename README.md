# creditflow

All the Architecture was design using draw.io. Please open using it. 

- * CreditMap: * contains the general idea behind credit evalution.
- * Level 1: * contains the flow for onboard with data loading abd integration.
- * On board: * contains the details and knock out rules for the credit risk.


## Next steps:
1.  Version 1 of the Architecture is shared with client.
2.  Questions and refinements will be incorporated in the flow
3.  External providers APIs must be encapsulated and connected to Taktile
4.  Implementation the mock system.
5.  Flow should be tested using mock data.
6.  Pre-piloting using selected clients.
7.  Piloting and pos-production follow-up
8.  Roll out gradually.
 

## Question for the interview:
- will the customer only be evaluated during the onboard or there will be other situations ( application, behaviour)?
- I couldn't find the details of the SEON API. What is the focus of KYC? only biometrics? will documents be validated?
- Address, phone number age and other information will be validated besides biometrics?
- Are Letigation and international lists (interpol) not being consumed? 
- Is the credit score developed internally or it will be retrieved from Experian?
- Credit card limit are usully defined base on risk and number of incomes. Eg. 2 * income.... are other formulas possible?
