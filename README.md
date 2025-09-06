
#Task1
report_card={'Ankit': 75, 'Ankur':80, "Bhaskar": 70, "Bhimar": 85, "Sahitya":60 }
print(report_card)
name=input("Enter your name: ")
if name in report_card.keys():
    print("{}'s marks are: {}".format(name,report_card[name]))
    print(f"{name}'s marks are: {report_card[name]}")
else:
    print("{} is not present in report card ".format(name))


#Task2
l1=list(range(11))
print(l1)
first5=l1[:5]
print(first5)
rev_first5=list(reversed(first5))
print(rev_first5)
print("The extracted list is :{} and reversed is :{}".format(first5,rev_first5))
