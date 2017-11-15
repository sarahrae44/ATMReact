# Lab: React ATM application

--------

Let's practice modifying an existing codebase. This repository contains the code for existing ATM application using React. In it, you can currently deposit money into a checking account.

You'll be adding a few features to this:
- The ability to withdraw money
- Having a savings account as well as a checking account

In the end, your solution will look like this:

<img width="992" alt="atm" src="https://cloud.githubusercontent.com/assets/4304660/24376818/18c39a82-12f2-11e7-81e7-af618c22b3ed.png">

--------

## Setting up:

- Clone this repo, and run `npm install`. To launch the app, run `npm start`.

- The code that's running is in the `/src` directory - that's what you need to change!

- The `/solution_src` directory is just that - the solution - don't look before giving this your best shot!

You can do the below tasks in any order you'd like.

---------

## Task:

Currently, you can see that there is a Checking account where a user can deposit money. Try it out - it works!
- Create a "Withdraw" button next to the "Deposit" button.
  - You should not be able to withdraw more than the current balance.
- Create a Savings account - another component of the same class.
  - It will have the same deposit (and eventual withdraw) functionality.
- You cannot type negative numbers in to either withdraw or deposit.

-------

### Hints:
<details>
<summary>Stuck on making a Savings account? Here's a hint:</summary>
The `name` prop being passed into `Account` is "Checking" - perhaps you can just call the component again for "Savings".   
</details>

<details>
<summary>Stuck on making a Withdraw button? Here's a hint:</summary>
Functionality to withdraw money is quite similar to functionality for depositing money, except with subtraction instead of addition.
</details>

<details>
<summary>Stuck on limiting negative numbers? Here's a hint:</summary>
When a function checks if the input is a number (with `isNaN`), an `||` condition could be added to be sure the input is not less than 0.
</details>

--------

## Solution

Solution code is provided in the `solution_src` folder of this repository. Please give this your best go before looking!

Testing
