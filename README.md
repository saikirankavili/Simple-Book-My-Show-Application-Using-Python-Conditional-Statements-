# Simple-Book-My-Show-Application-Using-Python-Conditional-Statements
This is a simple book my show movie ticket booking application for PVR and INOX theaters using python conditional statements.
This code is a professional console-based movie ticket booking application where users select a theater (PVR or INOX), choose a movie, and confirm or cancel their booking, with details like ticket price, booking ID, and show timings displayed.

###### CODE ######

print("Welcome to Book My Show Application✨!")
print("Theaters Available \n1.PVR \n2.INOX")
a=input("Enter the name of the theater( PVR or INOX):")
l=["PVR","INOX"]
if a in l:
    if a==l[0]:
        print("Movies available at PVR :\n 1.THE PARADISE - Rs. 500 \n 2.SALAAR - Rs. 600")
        b=int(input("Enter number to choose a movie(1 or 2):"))
        if b==1:
            print("You have selected THE PARADISE movie\nTicket Price is Rs. 500")
            b1=input("DO you want to confirm the booking (yes/no):")
            if b1=="yes":
                print("Your Booking to the THE PARADISE movie is Confirmed✅\nYour Booking Id: 35689 \n Amount paid : Rs. 500 \nShow Timings 11:00 am")
            if b1=="no":
                print("Your Booking to the THE PARADISE movie is Cancelled❌\nPlease Try Again ")
        if b==2:
            print("You have selected SALAAR movie\nTicket price is Rs. 600")
            b2=input("Do you want to confirm the booking (yes/no):")
            if b2=="yes":
                print("Your Booking to the SALAAR movie is confirmed✅ \nYour Booking Id:53689 \nAmount paid : Rs. 600 \nShow Timings : 3:00 pm")
            if b2=="no":
                print("Your Booking for the SALAAR movie is Cancelled❌\nPlease Try Again")
    elif a==l[1]:
        print("Movies available at INOX : \n 1.BLOODY ROMEO - Rs. 350 \n 2.KGF CHAPTER-3 - Rs. 300")
        c=int(input("Enter number to choose a movie(1 or 2):"))
        if c==1:
            print("You have selected the BLOODY ROMEO movie\nTicket Price is Rs. 350")
            c1=input("Do you wan to confirm booking (yes/no):")
            if c1=="yes":
                print("Your Booking to the BLOODY ROMEO movie is confirmed✅\nYour Booking Id:68359 \nAmount paid : Rs. 350 \n Show Timings : 11:00 am")
            if c1=="no":
                print("Your Booking to the BLODDY ROMEO movie is cancelled❌\nPlease Try Again")
        if c==2:
            print("You have selected the KGF CHAPTER-3 movie\nTicket Price is Rs. 300")
            c2=input("Do you want to confirm booking (yes/no):")
            if c2=="yes":
                print("Your Booking to the KGF CHAPTER-3 movie is confirmed✅\nYour Booking Id:86593\nAmount paid : Rs. 300 \nShow Timings : 3:00 pm")
            if c2=="no":
                print("Your Booking to the KGF CHAPTER-3 movie is cancelled❌\nPlease Try Again")
else:
    print("❌Theater Name is not Available❌ \nPlease choose Correct Theater")
    
