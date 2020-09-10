# password-generator
Generate a strong password satisfying the password criteria

""" 
Password Generator
Condition used 
8 charater minmum
1 upper case
1 lower case 
1 number 
1 special charater 
"""

import random
Lower_case=['a','b','c','d','e','f','g','h','i']
Upper_case=['A','B','C','D','E','F','G','H','I']
Numbers=['0','1','2','3','4','5','6','7','8','9']
Special_charater=['!','@','#','$','%','^','&','/']

con1=random.choice(Lower_case)
con2= random.choice(Upper_case)
con3=random.choice(Numbers)
con4=random.choice(Special_charater)
con7=random.choice(Special_charater)
fifthchar=int(random.choice(Numbers))
fifthchar<<2

con8=random.choice(Numbers)

con5=random.choice(Lower_case)


password_Sting1= (con1+con2+con3+con4+con5+str(fifthchar)+con7+con8)
password_Sting2=(con2+con1+con4+con3+password_Sting1)


print(password_Sting2)
