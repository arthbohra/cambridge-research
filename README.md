# cambridge-research
**Abstract**
In this paper, we utilize computer vision to develop a tool for youth coaches to formulate set-piece tactics for their players. We used the Soccernet database to extract the ResNet features and camera calibration data for over 3000 corner kick across 500 professional matches in the top 6 European leagues (English Premier League, UEFA Champions League, Ligue 1, La Liga, Serie A, Bundesliga). Leveraging the provided homography matrix, we construct a feature vector representing the formation of players on these corner kicks. Additionally, labeling the videos manually, we obtained the pass-trajectory of each of the 3000+ corner kicks by segmenting the field into four zones. Next, after determining the localization of the players and ball, we used event data to give the corner kicks a rating on a 1-4 scale. By employing a Convolutional Neural Network, our model managed to predict the success of a corner kick given the formations of players. This suggests that with the right formations, teams can optimize the way they approach corner kicks. By understanding this, we can help coaches formulate set-piece tactics for their own teams in order to maximize the success of their play. The proposed model can be easily extended; our method could be applied to even more game situations, from free kicks to counterattacks. This research project also gives insight into the myriad of possibilities that artificial intelligence possesses in transforming the domain of sports.

** Links for Presentations**

[Presentation Link](https://www.youtube.com/watch?v=KEOpvitdBwU) @ CCIR Symposium

[Abstract Link](https://publications.waset.org/abstracts/146233/football-smart-coach-analyzing-corner-kicks-using-computer-vision) @ International Conference on Artificial Intelligence in Sports and Entertainment (Barcelona, Spain)

**Skills**
1. computer vision 
2. camera calibration 
3. deep learning 
4. transfer learning 
5. data augmentation 
6. ML + Statistics
7. python 

**Packages**
1. OpenCV
2. Tensorflow/Keras
3. SKLearn
4. MatPlotLib
5. Numpy
