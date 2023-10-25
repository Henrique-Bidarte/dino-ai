### Dino - AI 

Dino - AI was my first project involving Artificial Intelligence. It was developed during my period of study in Reinforcement Learning and was my first attempt at implementing AI algorithms on my own.

To do this, I used online guides and videos as a basis. In addition to a first contact with the Stable Baselines 3 Documentation.

##

To run this project it is necessary to previously install some tools on the computer.

You need to install PyTorch, as it is consumed by Stable Baselines 3. You can find installation instructions through this link: https://pytorch.org/

Furthermore, it is necessary to install Google Tesseract, since we will use it to detect screen elements through Pytesseract, its implementation in Python. Installation instructions can be found at this link: https://github.com/tesseract-ocr/tesseract

Other dependencies will be installed through their respective sections in the project, without the need for manual installations in the system.

##

A ```CnnPolicy``` was implemented along with a ```DQN``` algorithm from Stable Baselines 3 to detect, interpret and evaluate on-screen events, as well as identify game ends so that episodes could be restarted appropriately.

![image](https://github.com/Henrique-Bidarte/dino-ai/assets/134324510/d44116b4-85da-42e1-b935-43acd54d9701)
- This is a representation of what the algorithm is capturing from the screen.

##

It is possible to control the project flow through the constants section in the Jupyter notebook. There it is possible not only to assign values ​​to the different variables consumed, but also to indicate whether the project should generate a new ```model``` for experimentation or train an existing one.

Logs will be saved within the ```logs``` folder so they can be analyzed.

Trained models are saved in the ```models``` folder, along with the number of steps executed in the training.

A ```best_model``` file can be found in the project root folder. There I placed the last model trained by me and it should be replaced as it becomes more trained.

## 

![Untitled (1)](https://github.com/Henrique-Bidarte/dino-ai/assets/134324510/8464670b-a154-4cfa-ae4e-1a2648e78073)

The project was not a great success. It is possible to notice that the dinosaur does not take actions randomly, but it is not very smart.

This lack of efficiency in converging the values ​​can perhaps be attributed to an insufficient number of trained episodes, or to a defect in the implementation of the algorithm. However, it was a fun project and a good first experience.

It is possible that in the future this project will be improved or even reproduced in another repository with a more exemplary methodology. For now, we just have a mildly intelligent dinosaur.

  



