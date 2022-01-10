# A Short Exercise to Explore Object-Oriented Programming - Encapsulation

---
## Overview

This repository is a short exercise designed for you to explore **Encapsulation** which is one of the
four pillars of Object-Oriented Programming (OOP).

---
## 📖 Instructions

- Fork this repository
  

- To run the program, go to the [Main](src/main/java/com/techreturners/encapsulation/bankaccount/app/Main.java) class which 
  is the entry point and run it using IntelliJ
  

- There are two models `DodgyBankAccount` and `SecureBankAccount`, these are located in the 
  [model](src/main/java/com/techreturners/encapsulation/bankaccount/model) directory.

---
## 🤓 Study Prompts

Use the following questions to guide your exploration and learning! 🗺

- Run the `main` method on the `Main` class, what is it doing? What is being outputted to the console?


- Look at the `DodgyBankAccount`, this class is not well-encapsulated.
  Can you note down the problems with how the class is designed, and the ways it is being misused?
  
  
  -The addreward() function is set to public and is therefore easily accesible to anyone and is being misused
  -Class variables should be set to private so no one is able to make changes to any of the details.
  -The reward amount should be a constant
  -The account number should be constant
  

- Compare and contrast the `DodgyBankAccount` and the `SecureBankAccount`, how is the `SecureBankAccount` different to 
the `DodgyBankAccount`? How is it designed to prevent it from being misused? Are there instances of better method names
  for clearer abstraction?
  
  
-This is much better and secure as its attributes and reward function are set to private
  
---
## 🐸 Extension Challenge

- Now that you've had the chance to explore a well-encapsulated vs. poorly-encapsulated class,
your next challenge is to put your newly minted skills into practice 💪!
  
- Refactor the `WeatherReporter` class located in the [model](src/main/java/com/techreturners/encapsulation/bankaccount/model) directory.
  
- You may want to think about Encapsulation here. Do the methods follow the Single Responsibility Principle (SRP)? Are the method names suitable?
  Are there any magic numbers / hardcoded numbers in the code that needs to be represented by a constant?
  Are there better ways to write the code?
  
- Changes have been made to the code
  
- As an added challenge, could you write some unit tests to test the class' methods?
