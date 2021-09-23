# Oluwatimileyin Soyege
# Computer Science 30
# September 22, 2021
# Creating my menu for my adventure game


#1 we first label the loop

# we next put the while True statement to create a loop



loop = 0
while loop == 0:
      

      print("welcome to the vengance of the father")    
      print ("you meet the man who killed your entire family, you point a gun at him")
      print("your options are")
      print()
      print("1 shoot ")
      print("2 stay")
      print("3 call the police")
      print("4 exit")
      print()
      break




while True:
      
      
      choice = input("please choose option:  ")
      choice = int(choice)     
      # the first option is to shoot, trying to avenge family death
      if choice == 1:
       print("you have successfully avenged your family's death, game over!")
        
      # the second option is to stay, falling for the trick as he shoots you but you survive
      elif choice == 2:
        print("he begs for mercy, for forgiveness, and you decide to spare his life, but big mistake, he grabs the gun and points it at you! hitting your head twice, and in the chest 3 times, leg once, you miraculously survived but took months to recover, and he walks away freely, game over!")
          
      # the third option is to call the police, as you end up in a fight and beat the hell out of him as you walk away
      elif choice == 3: 
          print("he tries to reach for the gun and you beat the living hell out of him and knock him out, you call the police immediately")
          print("you report him to the police and he gets arrested, with his face swollen and bruised by your punches, he says to you that he'll be back coming for you, as you give him a middle finger,once the cop car drives away, game over")
      
      # the last choice leaves you to exit the program
      elif choice == 4:
            print("you have exited the program") 
      loop = 0
      break
      #if you pick any other option than 1-4, your option is invalid
else:
  print("please choose valid option")
  
       
      
