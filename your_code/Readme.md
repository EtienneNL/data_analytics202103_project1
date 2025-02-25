<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Building a (modified) solitaire game, using Python (lessons learned in week 1)
### **Thinh Nguyen**
### _Cohort: DAPTAMS0321_
### _Amsterdam, March - 2021_

## Content
- [Project Description](#project-description)
- [Rules](#rules)
- [Workflow](#workflow)
- [Links](#links)

## Project Description
This is the first small project in my journey with Iron Hack data analytics bootcamp. It is about building a game, for which the intention is to apply all the basic python skills we learned in the first week of the progam. 
I have chosen the game **Solitaire**, which is at a moderate level of difficulty. There is no specific reason why I have selected it, except for that I perhaps like a bit of a challenge.

## Rules
Most of the rules are retained from the original game, which are captured illustratively in the image below. For more detailed info on that, refer to the following [link](https://www.solitr.com). 
![Alt Text](quick_reminder.png) 


Due to time constraint, I have made the following adaptations to the rules, to make the project more achievable:
1. The cards range from 1 to 13; thus:
    * 1 = Ace
    * 11 = J 
    * 12 = Q
    * 13 = K
2. The stock pile:
    * only one card is visible at a time
    * upon starting the game, one card will already be made visible
    * it cannot be moved directly from the stock pile to any of the foundations
3. The tableaus:
    * When moving cards from one tableau to another, it is possible only to move the whole of all the visible cards on the move-from tableau
4. The foundations:
    * Foundations are numbered 1-2-3-4 from left to right
    * The foundations are designated for specific card types as follows:
        * Foundation 1 =  ❤️
        * Foundation 2 = ♦️
        * Foundation 3 = ♠️
        * Foundation 4 = ♣️

All the above-mentioned changes are captured illustratively in the following image:
![Alt Text](game_rule_changes.png)

## Workflow
Outline of the project workflow can be found on my kanban board on Trello. Refer to section [Links](#links)

## Links
Include links to your repository, slides and kanban board. Feel free to include any other links associated with your project.

[Repository](https://github.com/EtienneNL/data_analytics202103_project1/tree/main/your_code) 

[Presentation](https://github.com/EtienneNL/data_analytics202103_project1/blob/main/your_code/210327_Presentation.pptx)

[Trello](https://trello.com/b/Bn9EjlNz/thinhs-build-your-own-game-project-board)  
