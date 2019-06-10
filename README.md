 
i=18
number_of_guesses=1
while(number_of_guesses <=5):
    i=int(input("your no.pls"))
    if(i>18):
        print("decrease your no.")
    elif(i<18):
        print("increase your no.pls")
    elif(i==18):
        print("winner winner chicken dinner!!!!!!!!!!!!!!!!!!!!!!!!")
        break
    print(5 - number_of_guesses, "no. of guesses left")
    number_of_guesses = number_of_guesses + 1

if (number_of_guesses > 5):
    print("Game Over")
