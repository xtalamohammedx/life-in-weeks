# life-in-weeks
##to count how many days, weeks ,months left
###python 

age = input("what is your current age?")
age_as_int=int(age)                   #to convert the type 
years_remainig=90-age_as_int          #90-your age
days_remainig=years_remainig*365 
weeks_remainig=years_remainig*52
months_remainig=years_remainig*12
message= f"you have{days_remainig}days,{weeks_remainig}week,{months_remainig}months left" #F-STRIG. so you do nedd to convert every var
print(message)
