
---


<h3> Bachelor: Visualization of RL with ANNs</h3> 

---

**Project description:** Visualization environment for Deep Reinforcement Learning with Aritifical Neural networks. The environment allows parallel learning and evaluation of agents with visual insight into the parameters of the network. The visualization was realized using the Unity game engine. The basis for the deep learning is a self-made framework in C#.

Furthermore this work was awarded as outstanding work by the municipal utility Trier.

[Download this Work as Pdf](/pdf/Bachelorarbeit_Jonas_Wild.pdf)

[Trier University article about the work](https://www.hochschule-trier.de/informatik/news/beitrag-lesen/reinforcement-learning)

<img src="images/Step1.png?raw=true"/>
<img src="images/Step2.png?raw=true"/>

### 1. About

In order to give a basic insight into the mechanisms of RI, I have implemented the necessary functionalities of neural networks, such as the backpropagation algorithm, the stochastic gradient method, and methods of RI, such as deep Q-learning. Using the Unity development platform, this was integrated into a graphical environment. Thus, RI based training of (computer games) Pong, Tic-Tac-Toe as well as Snake can be observed and analyzed in different network and training configurations.

Artificial neural networks can be used to train an agent in "gaming". In this process, a state of the environment is given to the network as input. For example, a 9-character vector represents a tic-tac-toe playing field. For each of the 9 fields either "1" stands for "player 1 occupies the field", "-1" for "player 2 occupies the field" or "0" for "free field". Based on this input, the neural network calculates an output. The output determines the next action of the agent. There are different ways to interpret an output vector. For example, in Deep Q-Learning, the action with the highest output value is always chosen.

Rl is a collective of methods that can be used to train artificial neural networks. For example, programs have been able to defeat professional players in the real-time strategy game Starcraft 2, in which the artificial intelligence must choose between options at any given moment. The methods are based on the basic principle of upgrading good actions and devaluing bad ones. Applying this to neural networks means changing the parameters in one direction so that an action is chosen more often in a given state. A significant advantage over other learning methods, such as supervised learning, is the independence from labeled data with manually specified outputs. That is, data sets where the correct output is already predetermined. Instead, the data is learned and processed by the agent only during the game. An output is computed by the Rl method and optimized according to the backpropagation algorithm for the parameters of the network. Repeated applications result in a learning process. However, Rl means that learning processes can be lengthy. The artificial intelligence OpenAIFive provided by OpenAI trained for 10 months before it could compete in public against professional players of the strategy game Dota2.

<img src="images/Step2(1).png?raw=true"/>
<img src="images/Step2(2).png?raw=true"/>

### 2. Methods

In order to give a basic insight into the mechanisms of RI, I have implemented the necessary functionalities of neural networks, such as the backpropagation algorithm, the stochastic gradient method, and methods of RI, such as deep Q-learning. Using the Unity development platform, this was integrated into a graphical environment. Thus, RI based training of (computer games) Pong, Tic-Tac-Toe as well as Snake can be observed and analyzed in different network and training configurations.

Artificial neural networks can be used to train an agent in "gaming". In this process, a state of the environment is given to the network as input. For example, a 9-character vector represents a tic-tac-toe playing field. For each of the 9 fields either "1" stands for "player 1 occupies the field", "-1" for "player 2 occupies the field" or "0" for "free field". Based on this input, the neural network calculates an output. The output determines the next action of the agent. There are different ways to interpret an output vector. For example, in Deep Q-Learning, the action with the highest output value is always chosen.

Rl is a collective of methods that can be used to train artificial neural networks. For example, programs have been able to defeat professional players in the real-time strategy game Starcraft 2, in which the artificial intelligence must choose between options at any given moment. The methods are based on the basic principle of upgrading good actions and devaluing bad ones. Applying this to neural networks means changing the parameters in one direction so that an action is chosen more often in a given state. A significant advantage over other learning methods, such as supervised learning, is the independence from labeled data with manually specified outputs. That is, data sets where the correct output is already predetermined. Instead, the data is learned and processed by the agent only during the game. An output is computed by the Rl method and optimized according to the backpropagation algorithm for the parameters of the network. Repeated applications result in a learning process. However, Rl means that learning processes can be lengthy. The artificial intelligence OpenAIFive provided by OpenAI trained for 10 months before it could compete in public against professional players of the strategy game Dota2.

<img src="images/Step3.png?raw=true"/>
<img src="images/Step4.png?raw=true"/>
<img src="images/Step5.png?raw=true"/>
<img src="images/Step6.png?raw=true"/>

---
