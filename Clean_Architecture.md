# Clean Architecture
- Goal of software architect is to minimize the use of humans to build and maintain the system.

## Use case approach
![picture 1](images/74fac79f2abc981287152f3ac0fe61eb8f2ea3ed5ac6da2f323f8cdc4661dc2b.png)  
- No details are specified.
![picture 2](images/5f57eeb57c47cfdcc266ff3938ad5a4fa56f808e60eb274452e30bcddf3a3e83.png)  
- It's better to have design which can work with any io (without web), because it makes testing a lot easier.
## Model View Controller
- *Model* just knows about data.
- *Controller* just knows about input.
- *View* just knows about output.
- This was supposed to used for each individual element in system.

## Making Decisions
![picture 3](images/82b689b703c82c5359a79634d5dd60c1797cb05d6eb224d468c523c792a8109f.png)  
- Most of the times you don't a separate database (simple filesystem may work good).
## Agile
- Purpose of agile is to have these two charts on wall so everyone can see the status of project.
![picture 5](images/87396741ab8bc5aa270abe8b886cb26a3f70923367debdcba6f0b7bf6dea4ec6.png)  
![picture 6](images/6751bdd5f520e26ba8d39dc23e595080c0fd9b061c2dd2660a941191706c7a27.png)  
- The vertical bars below are time-blocks (1 week long usually) called sprints.
![picture 7](images/0d1031db1567f468808d0882e7683e1a132fb4002b1b090c01346764cfffa046.png)  
- Usually first iteration (sprint 0) involves just analysis (planning design, features etc).
- In first iteration, stories are planned (small implementations of code) according to features specified.
- Then next we try to do what planned and at the end of week we calculate whats done.
- Then in upcoming weeks, we observe the rate of completing stories and estimate the completion time accordingly.


### Iron Cross of project management
- ![picture 4](images/7b3f4099e31f69766a1ee8605f57b09ff02578b1fdd804751ff3b62f74295326.png)
- Pick any three and fourth cannot be done.
### THE ONLY WAY TO GO FAST IS TO GO WELL !!!

### Principles of agile programming
![picture 8](images/6044ff55a638ace76bd5299af74a5baf46315df67af74cc883f456f11b45e74a.png)  
- Best description of agile programming is given by *Extreme Programming*.
### Steps to agile
1. Cards are created with just 1-2 word feature (called stories).
2. Then discussion takes place to assign some value to each card from 1-5 (called story points).
3. Then in at first iteration, total story points is estimated and most important cards are picked.
4. At every other iteration, total story points is estimated and cards are chosen.
5. Meanwhile new stories are added as project progresses.

>An iteration never fails, purpose of each iteration is just to provide data on how the project is going.