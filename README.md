# **AdvancedProgramming_Lab01_Problem 02**
## **Description**  
Defining class
### **Problem 02** -  _Bank Account Method_  
To solve this problem, we followed these following step, contain:  
> **NOTE :** We using the _**BankAccount** class_ of the _**Problem 1**_. The source code that presented as the following figure.    
> ![Imgur](https://i.imgur.com/V7lQYue.png)  
> ![Imgur](https://i.imgur.com/wiHjAwA.png)  
1. With using the _**BankAccount** class_ that we created before, we also added some properties that required, include:  
* Deposit (decimal amount): void
* Withdrawl (decimal amout): void  
  According the source code that shown as the below figure.  
  ![Imgur](https://i.imgur.com/lUFzv4k.png)
  > _**Note:**_  
  > In this source code we declare _**amount**_ variable is decimal. In _**Deposit**_ if the value of a mount is greater then 0, the balance will plus amount. Otherwise, in _**Withdrawl**_, if the value of amount is smaller or equal the value of balance, the value of balance equal the value of amount, else the value of balance equal the value of balance minus the value of amount.  

2. We overrided the method ToString() to display the information of an account, include _**id**_ and _**balance**_. 
   ![Imgur](https://i.imgur.com/OLwLKrF.png)   
3. Then, we created new object that inherit the properties from _**BankAccount**_ class.  
   ![Imgur](https://i.imgur.com/aQSxR1x.png)  
4. Next, we set the value for objects, follwing the source code shown in the following figure.  
   ![Imgur](https://i.imgur.com/g1JRUbT.png)
5. Finally, we call ToSting() method to display the information of a account that we created in step 3 and 4.  
   ![Imgur](https://i.imgur.com/u8x1ING.png)
### **The result of source code**  
![Imgur](https://i.imgur.com/9IZKt9g.png)
