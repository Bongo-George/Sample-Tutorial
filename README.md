# Sample-Tutorial
A code that tells and control the day temperature


weather = int(input(" ENTER THE TEMPERATURE OF THE DAY? "))

if weather >= 0 and weather <= 37 :

    print("Temperature is normal at " + str(weather) + "degree(s) ")

    print("you can go out ")

elif weather <= 0 :

    print("The day is so cold at " + str(weather)+"degree(s)" )

    print("Stay at home and use the blanket pls ")

else:

    print("The weather is so hot at " + str(weather)+"degree(s)")

    print("Stay at home and use the air condition ")
