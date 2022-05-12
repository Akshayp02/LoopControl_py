# LoopControl_py
"""
Loop control Statements = change a loop execution from its normal sequence

# break = used to terminate the loop entirly

# Contintine = skips to the next itration of the loop

#pass = does nothing , acts as a placeholder 

"""

while True:
    name=input("enter your name ")
    if name!="":
        break

phonenum = "123-6547-9876"_
for i in phonenum:
    if i == "-":
        continue
    print(i,end="")


# pass

for i in range(1,21):
    if i==13:
        pass
    else:
        print(i)
