#Started: September 29, 2020
#Finished: October 27, 2020
#Created by: Bailey Williams
#Purpose: RGB Chatbot
print("Hello! Welcome to my chatbot all about Ruth Bader Ginsberg")
n = 1
while n != 0:
  answer = input("Would you like to hear about her influence on opera, fashion, rap, or her tenure? Type 'exit' to end.")
  answer = answer.lower()
  if (answer == "opera"):
    answer = answer.lower()
    answer = input("Did you know that there was an opera inspired by RBG?")
    answer = answer.lower()
    if (answer == "yes"):
      print ("Her relationship with former Justice Scalia inspired the opera Scalia/Ginsberg.")
    elif (answer == "no"):
      print ("Her relationship with former Justice Scalia inspired the opera Scalia/Ginsberg.")
    else:
      print ("Hmm.. try typing yes or no.") 
  
  elif (answer == "fashion"):
    answer = answer.lower()
    answer = input("Have you heard about RBG’s different collars?")
    answer = answer.lower()
    if (answer == "yes"):
      print ("Her collar choice was determined by whether she dissented or voted with the majority. If she voted with the majority, she wore a collar with gold embellishments, but she was most famous for her “dissent collar”, which was black with gold embellishments.")
    elif (answer == "no"):
      print (" Her collar choice was determined by whether she dissented or voted with the majority. If she voted with the majority, she wore a collar with gold embellishments, but she was most famous for her “dissent collar”, which was black with gold embellishments.")
    else:
      print ("Hmm.. try typing yes or no.")
  elif (answer == "rap"):
    answer = answer.lower()
    answer = input("Have you heard of her rap-inspired nickname?")
    answer = answer.lower()
    if (answer == "yes"):
      print ("RBG became a pop-culture icon by the name of the Notorious RBG. She once said that she had multiple things in common with the Notorious BIG, including the fact that they were both born and raised in Brooklyn, New York, and that he released his debut album in 1993, the same year RBG joined the Supreme Court.")
    elif (answer == "no"):
      print ("RBG became a pop-culture icon by the name of the Notorious RBG. She once said that she had multiple things in common with the Notorious BIG, including the fact that they were both born and raised in Brooklyn, New York, and that he released his debut album in 1993, the same year RBG joined the Supreme Court.")
    else:
      print ("Hmm.. try typing yes or no.")
  elif (answer == "tenure"):
    answer = answer.lower()
    answer1 = int(input("Do you know how long RBG served on the Supreme Court? (type number)"))
    number = 27
    if (answer1 == 27):
      print ("Good job! RBG served on the Supreme Court for 27 years!")
    else:
      wrong = abs(int(answer1) - number)
      print ("Close! RBG served on the Supreme Court for 27 years! You were " +str(wrong)+ " years off!")
  elif (answer == "exit"):
    print ("I hope you learned more about Ruth Bader Ginsberg! Bye!")
    n=0
  else:
      print("Hmm.. try typing opera, fashion, rap, or tenure. Type 'exit' to end")


