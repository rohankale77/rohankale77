    print("4. Number of students who play cricket and football but not badminton")
    print("5. Exit\n")
    ch=int(input("Enter your Choice (from 1 to 5) :"))

    if ch==1:
        print("Number of students who play both cricket and badminton : ", CB(Cricket,Badminton))
        a = input("\n\nDo you want to continue (yes/no) :")
        if a == "yes":
            flag = 1
        else:
            flag = 0
            print("Thanks for using this program!")

    elif ch==2:
        print("Number of students who play either cricket or badminton but not both : ", eCeB(Cricket, Badminton))
        a = input("\n\nDo you want to continue (yes/no) :")
        if a == "yes":
            flag = 1
        else:
            flag = 0
            print("Thanks for using this program!")

    elif ch==3:
        print("Number of students who play neither cricket nor badminton : ", nCnB(SEComp,Cricket,Badminton))
        a = input("\n\nDo you want to continue (yes/no) :")
        if a == "yes":
            flag = 1
        else:
            flag = 0
            print("Thanks for using this program!")

    elif ch==4:
        print("Number of students who play cricket and football but not badminton : ", CBnF(Cricket,Football,Badminton))
        a = input("\n\nDo you want to continue (yes/no) :")
        if a == "yes":
            flag = 1
        else:
            flag = 0
            print("Thanks for using this program!")

    elif ch==5:
        flag=0
        print("Thanks for using this program!")

    else:
        print("!!Wrong Choice!! ")
        a=input("\n\nDo you want to continue (yes/no) :")
        if a=="yes":
            flag=1
        else:
            flag=0
            print("Thanks for using this program!")


output:

 C:\Users\dell5\PycharmProjects\ArjuShaikh\venv\Scripts\python.exe C:/Users/dell5/PycharmProjects/ArjuShaikh/operationonset.py

Enter number of students in SE COMP: 3
Enter the names of 3 students (Please press ENTER after entering each students name) :
gaurav
karan
preet
Original list of students in SEComp : ['gaurav', 'karan', 'preet']


Enter number of students who play cricket : 1
Enter the names of 1 students who play cricket (Please press ENTER after entering each students name) :
gaurav
Original list of students playing cricket is :['gaurav']
The list of students playing cricket after removing duplicates : ['gaurav']


Enter number of students who play football : 2
Enter the name of 2 students who play football (Please press ENTER after entering each students name) :
karan
preet
Original list of students playing football :['karan', 'preet']
The list of students playing football after removing duplicates : ['karan', 'preet']


Enter number of students who play badminton : 1
Enter the name of 1 students who play badminton (Please press ENTER after entering each students name) :
karan
Original list of students playing badminton :['karan']
The list of students playing badminton after removing duplicates : ['karan']


--------------------MENU--------------------

1. List of students who play both cricket and badminton
2. List of students who play either cricket or badminton but not both
3. List of students who play neither cricket nor badminton
4. Number of students who play cricket and football but not badminton
5. Exit

Enter your Choice (from 1 to 5) :1


List of students who play both cricket and badminton is :  []
Number of students who play both cricket and badminton :  0


Do you want to continue (yes/no) :yes


--------------------MENU--------------------

1. List of students who play both cricket and badminton
2. List of students who play either cricket or badminton but not both
3. List of students who play neither cricket nor badminton
4. Number of students who play cricket and football but not badminton
5. Exit

Enter your Choice (from 1 to 5) :2
Difference between Cricket and Badminton (C-B) is :  ['gaurav']
Difference between Badminton and Cricket (B-C) is :  ['karan']

List of students who play either cricket or badminton but not both is :  ['gaurav', 'karan']
Number of students who play either cricket or badminton but not both :  2


Do you want to continue (yes/no) :yes


--------------------MENU--------------------

1. List of students who play both cricket and badminton
2. List of students who play either cricket or badminton but not both
3. List of students who play neither cricket nor badminton
4. Number of students who play cricket and football but not badminton
5. Exit

Enter your Choice (from 1 to 5) :3


List of students who play neither cricket nor badminton is :  ['preet']
Number of students who play neither cricket nor badminton :  1


Do you want to continue (yes/no) :yes


--------------------MENU--------------------

1. List of students who play both cricket and badminton
2. List of students who play either cricket or badminton but not both
3. List of students who play neither cricket nor badminton
4. Number of students who play cricket and football but not badminton
5. Exit

Enter your Choice (from 1 to 5) :4


List of students who play cricket and football but not badminton is :  []
Number of students who play cricket and football but not badminton :  0


Do you want to continue (yes/no) :5
Thanks for using this program!

Process finished with exit code 0
