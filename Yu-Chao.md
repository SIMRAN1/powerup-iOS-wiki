# Yu Chao

## Work Hours
| Days  | Hours (UTC+8) | Meeting | Tool |
| ----- | ----------- | ------- | ---- |
| Monday  | 9:30 - 12:30, 14:00 - 18:00  | N/A | Slack |
| Tuesday  | 9:30 - 12:30, 14:00 - 18:00 | Powerup-iOS | Slack |
| Wednesday  | 9:30 - 12:30, 14:00 - 18:00 | All Teams PWR, 1:1 May | Slack |
| Thursday  | 14:00 - 21:00 | N/A | Slack |
| Friday  | 9:30 - 12:30, 14:00 - 18:00 | N/A | Slack |
| Saturday  | REST | N/A | --- |
| Sunday  | REST  | N/A | --- |

## Short Bio

I am a second year computer science major at the Chinese University of Hong Kong. I am enthusiastic about the fields where art and technology meet, particularly, digital game design and development. Aside from programming, I  enjoy drawing and writing.

## Profile Links
[Gmail](mailto:casd82@gmail.com) | [Blog](http://shinerightstudio.com) | [GitHub](http://github.com/casd82) | [LinkedIn](https://www.linkedin.com/in/佑-趙-a55b85b2/) | [Facebook](https://www.facebook.com/casd82.yuchao)

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

The *Sink to Swim* mini game.

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

***
### Weekly Status Report for Week 7

**What have you accomplished this week (list specific items accomplished)?**

1. Added animation and ending scene to Sink to Swim mini game.
2. Updated UI elements (Dialogue boxes, Karma motif, background image for scenarios, font color, home button icon).
3. Wrote unit tests for Sink to Swim mini game.
4. Wrote documentation for Sink to Swim mini game.
5. Added Sink to Swim mini game to the game design document.

**What issues or roadblocks have you encountered this week?**

Everything goes pretty well.

**Have they been resolved, and if so, how?**

N/A

**Do any of the issues or roadblocks still exist and what steps have been taken to resolve them?**

No.

**Is further assistance necessary to resolve existing issues?**

No.

**What do you plan to accomplish next week?**

The vocabulary matching mini game.

**How does your progress compare to your project schedule?**

On time.

***
### Weekly Status Report for Week 8

**What have you accomplished this week (list specific items accomplished)?**

1. Completed the prototype of Vocab Matching mini game.
2. Added App Icon.
3. Added splash screen.
4. Changed the UI of start scene.
5. Added a replay button at the end of results view, so the players could now replay each scenario.

**What issues or roadblocks have you encountered this week?**

No.

**Have they been resolved, and if so, how?**

N/A

**Do any of the issues or roadblocks still exist and what steps have been taken to resolve them?**

No.

**Is further assistance necessary to resolve existing issues?**

No.

**What do you plan to accomplish next week?**

* Complete the ending scene for Vocab Matching game.
* Write documentation for Vocab Matching game.
* Write unit tests for Vocab Matching game.
* Add tutorial scenes for Minesweeper game & Sink to Swim game.

**How does your progress compare to your project schedule?**

On time.

***
### Weekly Status Report for Week 9

**What have you accomplished this week (list specific items accomplished)?**

1. Added Travis CI status badge to the GitHub repo.
2. Added tutorial scenes for each mini game.
3. Added "running out of questions" ending condition to Sink to Swim game.
4. Updated ending image for Sink to Swim game.
5. Wrote unit tests and documentation for Vocab Matching game.
6. Adjusted tile movement and tile spawn pattern in Vocab Matching game.
7. Added clipboard star blinking animation to Vocab Matching game.
8. Changed the choices of scenarios to a scroll view.
9. Updated hospital scenario background image. Updated dialogue UI, so that they have lighter stripes.

**What issues or roadblocks have you encountered this week?**

No.

**Have they been resolved, and if so, how?**

N/A

**Do any of the issues or roadblocks still exist and what steps have been taken to resolve them?**

No.

**Is further assistance necessary to resolve existing issues?**

No.

**What do you plan to accomplish next week?**

* Complete game transition of Map Scene (darken the buildings if they aren't completed).
* Test and try to make the sink animation of Sink to Swim game look better.
* Apply newly designed UI.
* Do some research on sound effects for the game.

**How does your progress compare to your project schedule?**

On time.

***
### Weekly Status Report for Week 10

**What have you accomplished this week (list specific items accomplished)?**

1. Implemented the building locks for Map Scene.
2. Added more tiles to Vocab Matching game.
3. Refactored Vocab Matching game.
4. Updated Sink to Swim game animation.

**What issues or roadblocks have you encountered this week?**

No.

**Have they been resolved, and if so, how?**

N/A

**Do any of the issues or roadblocks still exist and what steps have been taken to resolve them?**

No.

**Is further assistance necessary to resolve existing issues?**

No.

**What do you plan to accomplish next week?**

* Fix inconsistencies between Android.
* Apply the newly designed Shop UIs.

**How does your progress compare to your project schedule?**

On time.

***
### Weekly Status Report for Week 11

**What have you accomplished this week (list specific items accomplished)?**

1. Updated the Shop Scene with the new UI elements.
2. Added the new ending scene to Result Scene.

**What issues or roadblocks have you encountered this week?**

No.

**Have they been resolved, and if so, how?**

N/A

**Do any of the issues or roadblocks still exist and what steps have been taken to resolve them?**

No.

**Is further assistance necessary to resolve existing issues?**

No.

**What do you plan to accomplish next week?**

* Replace the old avatars with the newly designed ones.
* Find inconsistencies between iOS & Android version and list them.
* Find little bugs and open them on GitHub as issues.

**How does your progress compare to your project schedule?**

On time.

***
### Weekly Status Report for Week 12

**What have you accomplished this week (list specific items accomplished)?**

1. Applied the new avatar to the game.
2. Discussed the solutions with Sachin about the inconsistencies between iOS and Android and fixed them.

**What issues or roadblocks have you encountered this week?**

No.

**Have they been resolved, and if so, how?**

N/A

**Do any of the issues or roadblocks still exist and what steps have been taken to resolve them?**

No.

**Is further assistance necessary to resolve existing issues?**

No.

**What do you plan to accomplish next week?**

* Prepare for the live demo.
* Polish documentation.
* Write blog post Systers' Blogger.

**How does your progress compare to your project schedule?**

On time.