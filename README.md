# About Project
This Project is Patika-Norma Spring Bootcamp assignment.
You can test it from this >>>>> [LINK](https://emir-bank-frontend.herokuapp.com/login) <<<<<
# Project features
- Role based authorization (For ex : Admin and Customer have different authorities )
- Basic authentication
- JWT
- Used cron jobs to do things that can be triggered at certain times. ( For ex : Automatically blocking the cards of customers who do not pay their credit card debt. )
- Exchange Rate Api of apilayer.com is used
- Basic Unit Test
- Basic validation
# Project business rules
- A customer can only have one credit card.
- A customer can have an unlimited number of savings or drawing accounts.
- A customer can make payments to the corporate accounts in the system by entering the card information.
- Our customers who want to create a corporate account should contact our bank. Companies that work with us (KOTON)
- Money cannot be transferred to savings account. Only money can be deposited. If you want to withdraw your money from your savings account, you have to go to our branches. (We have branches in BURSA, ANKARA, IZMIR )
- Money transfer can be made between drawing accounts.
- You can deposit money in your savings account. Once the maturity period has expired, your money will be credited to your account at 9 a.m. the next business day.
- Credit card is given according to your monthly income. (A credit card with a limit of 10000 is given to someone with a salary of 10000 TRY)
- You can open current and time deposit accounts with USD EUR TRY currency . If you transfer between accounts with different currency, we calculate the current exchange rate and perform your transaction.
- Admin account is created by the system.
# Test Users
You can log in to these users and test the application or create a user for yourself.

| E-mail  | Password  | User Type |
| :------------ |:---------------:| -----:|
| emirhan@gmail.com     | 123456789e | ADMIN |
| testuser@gmail.com      | 123456789e| CUSTOMER  |

