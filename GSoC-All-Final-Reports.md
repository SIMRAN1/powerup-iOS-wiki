[Yu Chao 2017](#yu-chao-2017)  
[Sanya 2016](#sanya-2016)  

# Yu Chao 2017
### Overview
PowerUp is an educational mobile game app aiming at providing adolescent girls with reproductive health knowledge, empowering them with better self esteem, and teaching them conflict resolution skills in social life.

It is a choose-your-own-adventure game which the players have to navigate an avatar to engage in conversations of different scenarios.
#### Platform
Currently, there are both iOS and Android version of PowerUp. I worked on the iOS version through GSoC 2017.
#### Language & Frameworks
* Swift 3.0
* UIKit - Used for most scenes of the project.
* SpriteKit - Used for the mini games of the project.

### Accomplishments
I worked on three main tasks through GSoC: code refactoring, mini game implementation, and applying new UI elements.

#### Code Refactoring
Before GSoC 2017, the code base of PowerUp was a little unorganized. Not only model code was mixed with controller code but also their were plenty redundant view controllers in the Storyboard which could be cut and merged into one.

I wrote a singleton class to wrap database operations, created some data model classes to wrap the database entries, and most importantly, moved model code (database querying code) out of the controllers.

On top of that, I reorganized the Storyboard by merging some hard-coded view controllers. The number of view controllers is reduced from over 20 to below 10.

I believe that after the code refactoring, PowerUp will be more friendly and less intimidating for future developers.

#### Mini Game Implementation
One way to make a choose-your-own-adventure-game more interactive and fun is to incorporate it with some mini games. I implemented 3 mini games throughout GSoC 2017.
__Minesweeper Game__  
The first one is Minesweeper Game. It aims at helping players to learn the success rate as well as the pros & cons of different contraceptive methods.

The game works like an ordinary Minesweeper game, however, it doesn't give the player information about "bombs", making it a game of pure chance. We designed Minesweeper as a game of pure chance because we would like to simulate the success rates of contraceptive methods. Here is an example to make the idea clearer: When the game presents condom as its current contraceptive method, 2 bombs will be located randomly in the 25 grids because the contraceptive success rate of a condom is around 90% ≈  (23/25), and 25 (total grid count) - 23 ("success" grid count) = 2 ("bombs").

__Vocab Matching Game__  
This game teaches players reproductive health-related vocabulary. We suggest that before learning the actual knowledge about reproductive health, the players should first grasp the meaning of related vocabulary.

The game consists of tiles and clipboards. When the game starts, random tiles with icons on them will  be spawned on the left of the screen. They move to the right side of the screen over time, and the players have to drag and swap the clipboards on the right so that the text on the clipboard matches the icon of the tile in the same lane.

__Sink to Swim Game__  
The last mini game, Sink to Swim, is a "myth buster"-like game with the objective to "bust" sex-related myths feed by peers or public media.

It resembles trivia quiz games where a statement will be presented, and the players have to click on the "true" or "false" button to determine whether it is a true statement or a myth. To make the gameplay more exciting, we added a boat figure with an avatar sailing on it. The boat will sink over time, and the only way to save the avatar from drowning is to answer the correct answer, which raises the boat for a certain altitude.

#### Applying New UI Elements
In GSoC 2017, we had a UI/UX designer team dedicated to redesign UI elements and create new art assets for PowerUp. The GSoC student in the designer team (Kim) submitted pull requests on GitHub which contained her artworks. My job was to check those pull requests weekly, and applied them to PowerUp-iOS.

Thanks to the designer team, new UI elements and graphic assets for PowerUp are more minimalistic, sleek, and modern. I believe that they really defined a great art style for the project which adolescent girls will truly enjoy.
### Challenges
I faced many challenges through GSoC 17 because almost all of the technologies and workflows were new to me.
#### Technologies
__iOS & Swift__  
Before GSoC 17, I was entirely new to native iOS app developing and Swift, not to mention the UIKit and SpriteKit frameworks. Fortunately, since I came from a C# and C++ background, after reading the official tutorial of Swift 3.0, I became confident to code in Swift.

__Unit Testing & Continuous Integration__  
Before GSoC 17, I barely knew the meaning of "unit testing" or "continuous integration", so when I saw those terms in the requirements, I was a little overwhelmed. I did plenty of searches through Stackoverflow and Google, read some articles on Ray Wenderlich, and inquired my mentors. I finally understood the technologies better after researching and asking questions for a week. Now I have integrated PowerUp-iOS with Travis CI and wrote plenty of unit tests.

__Workflows__  
I did not really know the mechanics of GitHub before GSoC 17. For the community bonding period, I spent most of my time trying out GitHub and asking questions about the pull request workflow. I remember that I accidentally deleted a pending PR branch I submitted in community bonding period when I was trying out "push --force". It is good that I figured out the workflow before GSoC coding period actually started, or I may misuse the infamous "--force" again and delete all of my hard work. 

### Take-Aways
I really learned a great deal throughout GSoC 17. As I mentioned above, I learned iOS & Swift development, unit testing with Xcode, continuous integration, and the pull request workflow of GitHub.

Aside from technical knowledge, I learned some remote collaboration skills, demo & presentation skills, as well as some product management skills.

Also, this was actually the first time for me to work in a full English-speaking team. I could not deny that it was a little intimidating in the beginning, but after couple of weekly Hangout meetings, I became more and more confident about my verbal English and communication skills.

### Overall Experience
Google Summer of Code is an entirely new and exciting experience for me. I really like the culture of open source community, which everyone is extremely motivated, enjoying their works, and happy with all of the team members. I also really enjoy the "working at home" life style, which I can manage my time freely and have a nice work-life balance.

A big thanks to my mentors (Ginny, Jennifer, Sally), admin (May), and all the team members of PowerUp! I think we all brought the project to an entirely new level, and it is a real pleasure to work with you all!

# Sanya 2016
### Overview:
PowerUp seeks to empower pre-adolescents to take charge of their reproductive health through a choose-your-own-adventure mobile game that teaches social emotional learning, conflict resolution and health skills in a fun, interactive way. The app aims to advocate development of self-esteem and critical thinking among young girls and support them in the process of self-empowerment. PowerUp-iOS is developed on Xcode IDE using Swift language.

### Accomplishments:
* Implementation of Dressing Room-1 to select facial features,hair and clothes for the Avatar
* Creation of Customised Avatar from the choice of Avatar features
* Implementation of Dressing room-2 to select Avatar accessories,clothes,hairstyles at the end of a scenario
* Assignment of points to Dressing room-2 items
* Added functionality to purchase items from accumulated points and display "Paid" labels
* Implementation of Start and New User Button functionality
* Changes in existing database to store Avatar features for Dressing Rooms implementation

### Challenges:
* Changed the Project name on Github from Database to Powerup. This led to many build errors and many files in the Xcode project had to be altered to resolve the errors.
* Upgraded Xcode to 7.3.1 which supports swift Syntax 2.2. This led to many compile time errors that were fixed by manually changing syntax in many files.         

### Take-Aways:
* The unparalleled experience of collaborating with a diverse team of developers, mentors and admins spread around the globe
* A deeper insight into the stages of software development. I realized the importance of testing and periodic code reviews and feedback from mentors that helped me to refine many features of the app.
* Learned new features of Swift language and acquired new coding skills

### Overall experience:
It was absolutely amazing to work on Powerup, I got an excellent opportunity to develop cool new features for the app. I am proud to be a part of the Systers community. It's a great platform for all of us to come together, leverage each other and help in the continued participation of women in the field of computing. I am glad that by being a Syster, I could contribute to a project that would address the needs of the target population and thus bring a positive change in the society.
Even though GSoC has officially ended, my journey isn't over. I would love to contribute more to this project and help others in whatever capacity I can! And last but not least, a special shout out to my mentors Jennifer Parak and Harshita Kasera who helped me a lot throughout the project by providing periodic code reviews and constructive feedback on different aspects of the game. Thank you so much! :)

### Links:
[Github Repository](https://github.com/systers/powerup-iOS)  
[Documentation](https://docs.google.com/document/d/1N_-zmmjPn6D1H6wTdF4z66mFGT3af_FWbfGvLKkeY1w/edit?usp=sharing)  
[Systers Profile](http://systers.org/systers-soc/doku.php/sanya_jain)  