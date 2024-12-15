**Jungle Game**


Welcome to the Jungle Game!

In this game, you will embark on an adventurous journey through a mysterious jungle filled with challenges and forks in the road. Your choices will determine the outcome of the game.

Game Story
text
Copy code
Alex, an avid gamer, entered the Jungle Game, a cutting-edge VR experience that promised to blur reality. He appeared in a dense jungle, filled with strange sounds and towering trees. His mission was clear: find the glowing stone marker in the distance. But the path ahead was not simple.

Soon, Alex reached a fork in the road—one path led right, the other left. A voice crackled in his ear: “Choose wisely, Alex. The wrong choice leads to failure.” He chose the right. As he ventured deeper, the jungle grew darker and eerier. He came to another fork, and once again, the voice urged him to decide: right or left. Alex chose right again, his gut telling him to press forward.

The ground trembled, and massive vines erupted from the earth, nearly trapping him. Heart racing, Alex dodged the vines and pushed on. After a long trek, he finally reached an ancient temple. The stone door opened as he stepped forward, revealing a treasure chest inside. 

“You’ve won, Alex,” the voice said. “But remember—every choice matters.” As Alex opened the chest, he wondered: What would have happened if he had chosen the other path? The jungle’s secrets remained, but for now, he had triumphed.
How to Play
Initial Decision
When you start, you are given the option to take help from an unknown entity or proceed without help.
Choose wisely!

Fork in the Road
After making the initial choice, you will encounter a fork in the road with two options: left or right. Your choice will lead to different outcomes.

Subsequent Choices
If you choose right or left, you will be presented with more decisions. Keep making choices to navigate through the jungle and reach your goal.

Winning or Losing
Depending on your choices, you may win or lose the game. Remember, every choice matters!

Game Code
python
Copy code
print('                                                          Lets start the Game')

print('''Alex, an avid gamer, entered the Jungle Game, a cutting-edge VR experience that promised to blur reality. He appeared in a dense jungle, filled with strange sounds and towering trees. His mission was clear: find the glowing stone marker in the distance. But the path ahead was not simple. Soon, Alex reached a fork in the road—one path led right, the other left. A voice crackled in his ear: “Choose wisely, Alex. The wrong choice leads to failure.” He chose the right. As he ventured deeper, the jungle grew darker and eerier. He came to another fork, and once again, the voice urged him to decide: right or left. Alex chose right again, his gut telling him to press forward. The ground trembled, and massive vines erupted from the earth, nearly trapping him. Heart racing, Alex dodged the vines and pushed on. After a long trek, he finally reached an ancient temple. The stone door opened as he stepped forward, revealing a treasure chest inside. “You’ve won, Alex,” the voice said. “But remember—every choice matters.” As Alex opened the chest, he wondered: What would have happened if he had chosen the other path? The jungle’s secrets remained, but for now, he had triumphed.''')

# Asking the player for their choice
unknown = int(input("Press 1 to take help from an Unknown or Press 2 to not take help from the unknown"))
print("############################################===================================================############################################")

# First fork in the road
Number = int(input('Press 1 to go left or 2 to go right'))

if Number == 1:
    print("You are going left")
    number = int(input("Again press 1 to go left or 2 to go right"))
    print(number)
    if number == 1:
        print('You Lost. Oops!')
    elif number == 2:
        print('Try Again')
    else:
        print('No other number Please')

elif Number == 2:
    number = int(input("Again press 1 to go left or 2 to go right"))
    print(number)
    print("You are going left")

    if number == 1:
        help = int(input('\nPress 1 to take help from an Unknown or Press 2 to not take help from the unknown'))
        print(help)
        if help == 1:
            print("YOU WIN")
        elif help == 2:
            print("Better Luck Next time")
        else:
            print('No other number Please')

    elif number == 2:
        print("Now as you chose right")
        print("You Lose the Game")
    else:
        print("NO OTHER NUMBER PLEASE")
else:
    print("NO OTHER NUMBER PLEASE")
Game Instructions
Choose either to go left or right at every fork.
You may choose to seek help from an unknown entity.
Every decision impacts the outcome of the game, so choose wisely!
Future Enhancements
Add more paths and forks to expand the storyline.
Introduce more complex challenges and puzzles.
Add visual graphics or VR elements to enhance the experience.
Enjoy your journey through the jungle! Choose wisely and may luck be with you!
