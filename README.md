class Bank_Account:
    def __init__(self):
        self.balance=100
        print("Hello!!! Welcome to your Bank Account", self.balance)

    def accountNumber(self):
        accountnumber=2393473410
        print("Account Number:", accountnumber)

    def deposit(self):
        amount=float(input("Enter amount to be Deposited: "))
        self.balance += amount
        print("\n Amount Deposited:",amount)

    def withdraw(self):
        amount = float(input("Enter amount to be Withdrawn: "))
        if self.balance>=amount:
            self.balance-=amount
            print("\n You Withdrew:", amount)
        else:
            print("\n Insufficient balance  ")
    def balance(self) :
        amount=self.balance
        print(amount)

    def display(self):
        print("\n Net Available Balance=",self.balance)
class Savings_Account:
    def __init__(self):
        self.balance=25
        print("Hello!!! Welcome to your Savings Account")

    def interestRate(self):
        amount=float(input("Enter Interest Amount: "))
        self.balance *= amount
        print("\n Interest Added.",amount)
class Checking_Account:
    def __init__(self):
        minimum.balance=50
        print("Minimum Balance required is $50.")
    def withdrawfees(self):
        amount = float(input("Amount of Fees Withdrawn: "))
        minimum.balance=45
        print("\n $5 Withdrawn in Fees.", minimum.balance)
