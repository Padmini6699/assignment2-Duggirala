# assignment2-Duggirala
# Padmini Duggirala
###### Chicken biryani
>Biryani is a mixed rice dish originating from the Indian subcontinent. It is made with **Indian spices**, rice, and meat, and sometimes, in addition, eggs and/or vegetables such as potatoes in certain regional varieties. I like it  because it tatses too yum!

***
***How to create Twitter account?***
1. Go to twitter homepage and click on the "Sign up now" button.
2. Begin the sign-up information by providing your username, date of birth, and your choice of an email account or phone number.
3. Choose how you want to view ads. Click on the button that says "Next."
4. Click on the button that says "Create Account."
  1. A verification code will be sent to your email address or phone number.
  2. Enter the verification code once you receive it.
5. Create a password and that should be atleast six characters.
6. At the top of the settings page, you will see a "photo" tab. Click this and add a photo of you.
7. Complete the rest of your profile information.And your twitter account is craeted.
8. Next time you can just click login option by providing your username and password and that directly opens your home page.

- Laptop
- Date of birth
- email ID
- Phone number

**[my picture](Padmini.JPG)**

---
## My favourite tourist places
These are some of my favourite places which I recommend for others to visit

|location     |Spending Hours |Amount to be spent|
|:---:| :---: | :---: |
|California   |      48       |      $200        |
|New York     |      24       |      $300        |
|Alleppey     |      72       |      $100        |
|Mumbai       |      24       |      $100        |

![picture](images/california.jpg)
![picture](images/newyork.jpg)
![picture](images/alleppey.jpg)
![picture](images/mumbai.jpg)
![picture](images/chickenbiriyani.jpg)



---
## Life Quotes

> "Reality is that which, when you stop believing in it, doesn't go away."

> "Words are free.It's how you use them.That may cost you."

---
## Code fencing
> Transact-SQL (T-SQL) is Microsoft's and Sybase's proprietary extension to the SQL (Structured Query Language) used to interact with relational databases. T-SQL expands on the SQL standard to include procedural programming, local variables, various support functions for string processing, date processing, mathematics, etc. and changes to the DELETE and UPDATE statements.

Source Link <https://en.wikipedia.org/wiki/Transact-SQL>

```
SELECT emp.BusinessEntityID AS EmpID,
    psn.FirstName, 
    psn.LastName,
    emp.NationalIDNumber AS NatID
  FROM HumanResources.Employee emp, 
    Person.Person psn
  WHERE emp.BusinessEntityID = psn.BusinessEntityID
    AND emp.JobTitle = 'Production Technician - WC60';
```

Source Link <https://www.red-gate.com/simple-talk/sql/t-sql-programming/basics-good-t-sql-coding-style/>