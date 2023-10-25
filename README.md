### Dino - AI 

Dino - AI was my first project involving Artificial Intelligence. It was developed during my period of study in Reinforcement Learning and was my first attempt at implementing AI algorithms on my own.

To do this, I used online guides and videos as a basis. In addition to a first contact with the Stable Baselines 3 Documentation.

##

A ```CnnPolicy``` was implemented along with a ```DQN``` algorithm from Stable Baselines 3 to detect, interpret and evaluate on-screen events, as well as identify game ends so that episodes could be restarted appropriately.

![image](https://github.com/Henrique-Bidarte/dino-ai/assets/134324510/d44116b4-85da-42e1-b935-43acd54d9701)
- This is a representation of what the algorithm is capturing from the screen.

##

It is possible to control the project flow through the constants section in the Jupyter notebook. There it is possible not only to assign values ​​to the different variables consumed, but also to indicate whether the project should generate a new ```model``` for experimentation or train an existing one.

Logs will be saved within the ```logs``` folder so they can be analyzed.

Trained models are saved in the ```models``` folder, along with the number of steps executed in the training.

A ```best_model``` file can be found in the project root folder. There I placed the last model trained by me and it should be replaced as it becomes more trained.


  
