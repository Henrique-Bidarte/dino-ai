### Dino - AI

Dino - AI was my first project involving Artificial Intelligence. It was developed during my Reinforcement Learning studies and this was my first attempt at implementing AI algorithms on my own.

To do this, I used online guides and videos as a basis and the Stable Baselines 3 Documentation.

##

To run this project, it is necessary to previously install the following tools:

```PyTorch```, as it is consumed by Stable Baselines 3. You can find installation instructions through this link: https://pytorch.org/

```Google Tesseract```, since it is used to detect screen elements through Pytesseract, its implementation in Python. Installation instructions can be found at this link: https://github.com/tesseract-ocr/tesseract

Other dependencies will be installed through their respective sections in the project automatically in the system.

##

A ```CnnPolicy``` was implemented along with a ```DQN``` algorithm from Stable Baselines 3 to detect, interpret and evaluate on-screen events, as well as identify when the game ends and restarting the episodes appropriately.

![image](https://github.com/Henrique-Bidarte/dino-ai/assets/134324510/d44116b4-85da-42e1-b935-43acd54d9701)
- This is a representation of what the algorithm is capturing from the screen.

##

It is possible to control the project flow through the ```constants``` section in the Jupyter notebook. Not only it assigns values ​​to the different variables consumed, but it indicates whether the project should generate a new model for experimentation or train an existing one.

Logs will be saved within the ```logs``` folder so they can be analyzed accordingly.

Trained models are saved in the ```models``` folder alongside the number of steps executed in the training.

A ```best_model``` file can be found in the project root folder. It is an appropriate starting point and should be replaced periodically with better trained versions.

## 

![Untitled (1)](https://github.com/Henrique-Bidarte/dino-ai/assets/134324510/8464670b-a154-4cfa-ae4e-1a2648e78073)

Unfortunately, the project wasn't completely successful. While the dinossaur does not take actions randomly, it is not very smart...

This lack of efficiency in converging the values ​​might be attributed to an insufficient number of trained episodes or to a defect in the implementation of the algorithm. Regardless, it was a fun project and a good first experience.

It is possible that in the future this project will be improved or even reproduced in another repository with a more exemplary methodology. For now, we just have a mildly intelligent dinosaur.

  



