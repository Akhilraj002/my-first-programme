# my-first-programme----<br>
next program

class Atm:
   def __init__(self):
       self.pin = ""
       self.balance = 0
       self.menu()

   def menu(self):
       print(''' 
       enter 1. generate pin
       enter 2. deposit
       enter 3. withdraw
       enter 4. balance
       enter 5. exit
       ''')
       user_input =input("enter you")
       if user_input = "1":
          self.pin()
       eif user_input = "2":
          self.deposit()
       elif user_input = "3":
          self.withdraw()
       elif user_input == "4":
          self.balance()
       elif user_input =="5":
          self.exit()

          
  def pin(self):
      self.pin = int(input("enter pin "))
      print("your password set ")
       
  def deposit(self):    
      temp = int(input("enter pin:"))
          if temp == self.pin:
             amount = float(input("rnter amount"))
             self.balnce = self.balance + amount
          else:
             print("invalid password")
  def withdraw(self):
      temp = int(input("enter the password"))
        if temp == self.pin:
        amount = float(input(enter the amount:"))
          if amount > 500:
              amount = slf.balance - amount
           else:
                print("insufficient balance")
        else:
              print("invalid pin")

  def check(sel):
      temp == self.pin
      print(self.balance)

 def exit(self):
     Exit()
           
         
         
             
