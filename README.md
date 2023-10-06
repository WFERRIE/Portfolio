## Welcome
Hi there! Below is a showcase of some of the projects I have worked on. Some of these were for school assignments, so I've gone ahead and redacted some of the code just in case those assignments are still being used.


## 🧪 Machine Learning / Data Science
These projects were all done as part of my Master's in Industrial Engineering. As some of them are for assignments which may still be used, I have chosen to omit some / all of the code depending on the project.

### [Computer Vision for Fracture Detection](https://github.com/WFERRIE/FractureDetection/)
This project was done for a deep learning course I took as part of my Master's. I worked with a team of three others to create a computer vision model that was capable of accurately detecting fractures in images of drill core samples. We achieved this using a fine-tuned [YOLOv8](https://github.com/ultralytics/ultralytics) model. 

My contribution to the project was in the data cleaning and model creation. I first extracted all of the label information from the software my teammates used for labelling and reformatted it into the YOLO format. I created a train, validation, and test set, and imported a YOLOv8 model and performed 100 epochs of fine-tuning. The best model was selected based on the validation set and was evaluated for its precision-confidence curve and F1-confidence curve.

Our final model performed very well on the test set and was even able to generalize to new data it had not seen before (other rock fractures we found on the internet). Overall we are very pleased with our results, and feel that with a larger dataset, even better results can be achieved.

![test_batch0_pred](https://github.com/WFERRIE/Portfolio/assets/58156317/8f427eeb-65ad-4c31-8ae0-48a956371e4f)


### [$MSFT Daily Returns Prediction](https://github.com/WFERRIE/MSFT-Final-Project)
This was done as a final project for an AI in Finance course I took. The goal of the project was to create a model which could trade on the open, and earn a positive return on MSFT. However, accurately predicting the future price of a stock is somewhat of a holy grail problem in finance, so the likelihood of being able to do so was/is very low. So in reality, rather than aiming to have a functioning model that can make me a lot of money, the actual aim of the project was to learn more about machine learning techniques in the financial domain.

In the project, the data was imported, cleaned, and explored. Then, pipelines were created for encoding, smoothing, and feature selection. 14 models were trained and evaluated using pipelines, and the two best models were then chosen to proceed and receive hyperparameter tuning. The final model was chosen, and its trading strategy was evaluated for its cumulative returns across the training set, and the test set. Finally, the CAGR, Phi K, Sharpe Ratio were all calculated to evaluate the model. 

In the end (as expected), the final model earned positive returns, but was not able to consistently do so. However, through this process I learned a lot about financial modelling, and machine learning / statistical techniques within the world of finance. I also got an A+!

![testreturns](https://user-images.githubusercontent.com/58156317/273281119-8b3a061e-ec7f-4ccd-a9ee-a395ad065d0a.png)

## 🤖 Mechatronics
These projects were done in the final year of my undergrad. They were pretty challenging, and I lost a lot of sleep working on them, but I learned a ton, and they were a very rewarding experience. 

### [Pathfinding Robot](https://github.com/WFERRIE/MazeRover)
As part of a mechatronics class, myself and three friends created a robot capable of navigating a maze. More specifically, the robot had to:

 1. Drive around the maze and localize itself within it
 2. Once localized, drive to a predetermined 'pickup' location
 3. At the pickup location, detect and pick up a block
 4. Drive the block to a 'dropoff' zone, and drop it off

The robot had to be designed and built totally from scratch, and we were graded on its performance across three milestones over the course of three weeks. While all four of us contributed to all aspects of the rover, we each had different primary responsibilities, mine being the MATLAB code that controlled the rover inside of the maze, and sent commands to the onboard microcontrollers.

![rover](https://github.com/WFERRIE/Portfolio/assets/58156317/69687f53-7848-4469-bdcc-e153515fb0f5)



### [Robot Card Dealer](https://github.com/WFERRIE/RobotCardDealer)
As part of a microcontrollers class, we had to use microcontrollers to perform some sort of task. Three friends and I thought it'd be fun to create a robot that dealt cards. We originally planned for it to also play Blackjack (serving as the dealer), but after we accidentally fried our Arduino Mega, we had to use two Arduino Unos. Unfortunately, with our new architecture Blackjack just wasn't feasible within our time constraints. However the robot was still able to deal a variable number of cards to a variable number of players, and we ended up with a great final grade!

![IMG_7864](https://github.com/WFERRIE/Portfolio/assets/58156317/4494d772-13b0-4a41-b440-4452064500e0)


## ✨ Personal Projects
This is a list of a few projects I have done either for fun or just for the sake of learning.
### [Pathfinding Algorithm Visualizer](https://github.com/WFERRIE/PathfindingAlgorithmVisualizer)
I started this project after coming across [raylib](https://www.raylib.com/), a C++ library for making video games. At the time I was learning about pathfinding algorithms, so I thought it'd be fun to make some sort of program to visualize how they work. This was my first time making something in C++ from scratch, so there were a lot of lessons learned and many things I could've done better. I also only got around to implementing BFS, but it was still a fun project.

![enter image description here](https://github.com/WFERRIE/PathfindingAlgorithmVisualizer/blob/main/output.PNG?raw=true)


### [Inventory Management System](https://github.com/WFERRIE/InventoryManagementSystem)
This is an old project I did because I was interested in web development - It's a simple web app to keep track of inventory with CRUD functionality. It uses Bootstrap for front end, Flask for the backend, and SQLite for the database. 

![enter image description here](https://user-images.githubusercontent.com/58156317/271704344-c61f59ff-0714-467d-bd60-ed1e33eb6d34.png)



