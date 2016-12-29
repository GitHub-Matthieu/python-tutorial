# --coding:Utf-8 -

year = input("input a year: ")
try:
	year = int(year)
except:
	print("Year is not integer")

is_bisextile = False

def print_bisextile(is_bisextile, year):
	if(is_bisextile):
		print(str(year) + " is bisextile")
	else:
		print(str(year) + " is not bisextile")


if(year % 4 != 0):
	print_bisextile(False, year)
elif(year % 100 == 0):
	if(year % 400):
		print_bisextile(True, year)
	else:
		print_bisextile(False, year)
else:
	print_bisextile(True, year)



