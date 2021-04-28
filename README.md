def isleapyear(n):
    if (n%400 == 0):
        print("Year {0} was a leap year".format(n))
        return True
    if (n%100 == 0):
        print("Year {0} was not a leap year".format(n))
        return False
    if (n%4 == 0):
        print("Year {0} was a leap year".format(n))
        return True
    else:
        print("Year {0} was not a leap year".format(n))
    return False

n = input("mybirthyear = ")

if (isleapyear(n)):
    print("Year {0} was a leap year".format(n))
else:
    print("Year {0} was not a leap year".format(n)
