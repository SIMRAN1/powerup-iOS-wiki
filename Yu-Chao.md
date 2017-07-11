# Yu Chao

## Work Hours
| Days  | Hours (UTC+8) | Meeting | Tool |
| ----- | ----------- | ------- | ---- |
| Monday  | 9:30 - 12:30, 14:00 - 18:00  | N/A | Slack |
| Tuesday  | 9:30 - 12:30, 14:00 - 18:00 | Powerup-iOS | Slack |
| Wednesday  | 9:30 - 12:30, 14:00 - 18:00 | All Teams PWR, 1:1 May | Slack |
| Thursday  | 9:30 - 12:30, 14:00 - 18:00 | N/A | Slack |
| Friday  | 9:30 - 12:30, 14:00 - 18:00 | N/A | Slack |
| Saturday  | REST | N/A | --- |
| Sunday  | REST  | N/A | --- |

## Short Bio

I am a second year computer science major at the Chinese University of Hong Kong. I am enthusiastic about the fields where art and technology meet, particularly, digital game design and development. Aside from programming, I  enjoy drawing and writing in my free time.

## Profile Links
[Gmail](mailto:casd82@gmail.com) | [My Blog](http://shinerightstudio.com) | [GitHub](http://github.com/casd82) | [LinkedIn](https://www.linkedin.com/in/佑-趙-a55b85b2/) | [Facebook](https://www.facebook.com/casd82.yuchao)

## GSoC17 Project Proposal
[Proposal Link](https://drive.google.com/file/d/0B_Q_nlCgdQF4eDRIajVmck9lTkE/view?usp=sharing)

### Weekly Status Report for Week 1

**What have you accomplished this week (list specific items accomplished)?**
1. Merged some hard-coded view controllers into one.
2. Redesigned segues.
3. Fixed all complier warnings.
4. Added comments to improve readability.

**What issues or roadblocks have you encountered this week?**

I was not familiar with the functionalities of different types of segues.

**Have they been resolved, and if so, how?**

Yes. My mentor sent me some tutorial links about unwind and modal segues. After studying those, I successfully redesigned the segues of the project.

**Do any of the issues or roadblocks still exist and what steps have been taken to resolve them?**

No.

**Is further assistance necessary to resolve existing issues?**

No.

**What do you plan to accomplish next week?**

Implement the database model class.

**How does your progress compare to your project schedule?**

It matches my project schedule quite well.

***
### Weekly Status Report for Week 2

**What have you accomplished this week (list specific items accomplished)?**

1. Reorganized database, so it is in sync with the Android project.
2. Created multiple data model classes for abstracting the database entries.
3. Implemented the database accessor class to abstract the operations of the database and simplify database accesses into a single function call.
4. Separated model code from controller code.
5. Added more scenarios to the game.

**What issues or roadblocks have you encountered this week?**

Not sure how to handle database querying failure.

**Have they been resolved, and if so, how?**

Yes. I used error dialog pop-ups to indicate database querying failure.

**Do any of the issues or roadblocks still exist and what steps have been taken to resolve them?**

No.

**Is further assistance necessary to resolve existing issues?**

No.

**What do you plan to accomplish next week?**

Prototype the "Minesweeping" mini game.

**How does your progress compare to your project schedule?**

I am ahead of my schedule.

***
### Weekly Status Report for Week 3

**What have you accomplished this week (list specific items accomplished)?**

1. Implemented Karma Point gain & spend system.
2. Integrated mini games transition into `ScenarioViewController`.
3. Finished Minesweeper game's prototype using SpriteKit.

**What issues or roadblocks have you encountered this week?**

The background banner in Sprite Kit Scene wouldn't show correctly.

**Have they been resolved, and if so, how?**

Yes. It turned out to be a bug of iOS simulator. I switched to use my own iOS device for debugging and testing.

**Do any of the issues or roadblocks still exist and what steps have been taken to resolve them?**

The actual mechanics of Minesweeper game isn't decided yet.

**Is further assistance necessary to resolve existing issues?**

No.

**What do you plan to accomplish next week?**

Finalized the implementation of Minesweeper game.

**How does your progress compare to your project schedule?**

At par with my schedule.

***
### Weekly Status Report for Week 4

**What have you accomplished this week (list specific items accomplished)?**

1. Finalized the mechanics of Minesweeper game and finished implementing it.
2. Wrote error handling code to manage database operation errors.
3. Wrote unit tests for Minesweeper game.
4. Reworked `ShopViewController`.

**What issues or roadblocks have you encountered this week?**

Not sure how to handle the errors ideally.

**Have they been resolved, and if so, how?**

Kind of. The mentor gave me some suggestions and I finished implementing the error handling code according to them, but the mentor will review my code later to see if it is acceptable.

**Do any of the issues or roadblocks still exist and what steps have been taken to resolve them?**

No.

**Is further assistance necessary to resolve existing issues?**

No.

**What do you plan to accomplish next week?**

Probably the prototype of Sink to Swim game.

**How does your progress compare to your project schedule?**

Same as my schedule.

***
### Weekly Status Report for Week 5

**What have you accomplished this week (list specific items accomplished)?**

1. Completed Travis CI configuration.
2. Wrote unit tests for previous code (view controllers, database accessor, database entries).

**What issues or roadblocks have you encountered this week?**

* Don't know if I should create a separate database for unit testing or not.
* Have trouble creating mock data for testing view controllers.

**Have they been resolved, and if so, how?**

Yes they are resolved. I discussed the first issue with my mentors and they decided that the original database could be used for unit tests, but I have to make sure that the data won't be altered after the unit tests. For the second issue, I found a perfect solution on the internet -- use inheritance to make all data providing classes have the same interface, then I can simply switch which data provider to use when performing unit tests.

**Do any of the issues or roadblocks still exist and what steps have been taken to resolve them?**

They are all resolved.

**Is further assistance necessary to resolve existing issues?**

No.

**What do you plan to accomplish next week?**

The *Swim to Drawn* mini game.

**How does your progress compare to your project schedule?**

The work done this week isn't included in my original schedule since we have decided a new schedule.

***
### Weekly Status Report for Week 6

**What have you accomplished this week (list specific items accomplished)?**

1. Applied Kim's UI designs to the game.
2. Prototyped Sink to Swim mini game.
3. Resized graphical assets so iOS simulators could successfully render them.

**What issues or roadblocks have you encountered this week?**

No.

**Have they been resolved, and if so, how?**

N/A

**Do any of the issues or roadblocks still exist and what steps have been taken to resolve them?**

No.

**Is further assistance necessary to resolve existing issues?**

No.

**What do you plan to accomplish next week?**

* Finish Sink to Swim game, write unit tests and documentation for it.
* Write and modify the game design document.

**How does your progress compare to your project schedule?**

About the same as the schedule.