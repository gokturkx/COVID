# COVID
COVID RISK ANALYSIS

age = input("Are you a cigarette addict older than 75 years old? Y/N ")
if age == "Y":
   print(True)
else:
   print(False)
chronic = input("Do you have a severe chronic disease? Y/N ")
if chronic == "Y":
   print(True)
else:
   print(False)
immune = input("Is your immune system too weak?  Y/N ")
if immune == "Y":
   print(True)
else:
   print(False)
print("High Covid Risk: " + str(age or chronic or immune))
