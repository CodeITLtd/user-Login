# user-Login
username = ''
password = ''
counter = 0
flag = 0
while counter != 3:
  username = input('Please enter your username:')
  if username == "Faisal":
    password = input("Please enter your password:")
    if password == "Polycom":
      print ("Welcome back!" , username)
      flag = 1
      break
    else:
      counter += 1
      if counter == 3:
        print("Account locked! contact your Administrator.")
if flag == 1:
  print("Welcome", username) 
