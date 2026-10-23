# CS-370 Portfolio

## Pirate Intelligent Agent

### Project Overview

For this project, I developed an intelligent pirate agent that could navigate through a maze environment to find treasure. The main goal of the project was to apply concepts from artificial intelligence, neural networks, and reinforcement learning to a pathfinding problem. Instead of programming the pirate with one specific path to follow, the agent was designed to learn from its experiences and improve its ability to reach the treasure through deep Q-learning.

I was provided with starter code that established much of the environment for the project. This included the `TreasureMaze.py` class, which represented the maze environment, and the `GameExperience.py` class, which helped store the agent's experiences as it interacted with the environment. The starter notebook also contained supporting code for building and testing the neural network and a skeleton of the deep Q-learning implementation.

The main code I worked on was the deep Q-learning training process for the pirate agent. I completed and modified the training logic that allowed the agent to move through the maze, choose actions, receive rewards or penalties, store experiences, and use those experiences to improve future decisions. The training process involved balancing exploration, where the agent tried different actions, with exploitation, where it used what it had already learned to select actions. I also worked with experience replay, epsilon decay, the neural network, and a target network to improve the learning process.

One of the biggest lessons I took away from this project was that an intelligent agent is not simply given the correct solution. Instead, it learns by repeatedly interacting with its environment. Successful decisions can be reinforced through rewards, while unsuccessful decisions can be discouraged through penalties. Over time, those experiences allow the agent to improve its decision-making.

## What Do Computer Scientists Do and Why Does It Matter?

Throughout this course, my understanding of what computer scientists do has expanded. Computer science involves much more than simply writing code. Computer scientists use algorithms, data, logical thinking, experimentation, and technology to solve problems. They analyze a problem, determine what information and resources are available, design possible solutions, and then develop and test systems that can accomplish a specific goal.

The Pirate Intelligent Agent is a good example of this process. A simple solution could have been to program an exact path for the pirate to follow. However, that would not allow the agent to learn or adapt. Reinforcement learning provided a different solution by allowing the pirate to learn a strategy through interaction with its environment.

This type of work matters because the same concepts can be applied to much larger real-world problems. Artificial intelligence and machine learning are used in areas such as robotics, transportation, cybersecurity, healthcare, recommendation systems, automation, and many other fields. Computer scientists help turn complex problems into systems that can process information and produce useful results.

## How Do I Approach a Problem as a Computer Scientist?

One of the most important things I have learned throughout this course is to break complicated problems into smaller and more manageable parts. When I first look at a large program, it can be difficult to understand how every piece works together. Instead of trying to solve everything at once, I try to identify the individual components and understand the purpose of each one.

For this project, that meant asking questions such as: What represents the current state of the environment? What actions can the pirate take? How does the agent determine whether an action was successful? How should previous experiences be stored? How can the neural network use those experiences to make better decisions in the future? Breaking the project into smaller questions made the overall problem easier to understand.

Testing and troubleshooting are also important parts of my approach. Code does not always work correctly the first time, especially with something as complex as reinforcement learning. When I encounter a problem, I try to examine the output, identify where the unexpected behavior begins, make a targeted change, and test the program again.

This project also taught me that a program running without errors does not necessarily mean the problem has been solved. With machine learning, the code can execute correctly while the model still does not perform as expected. Because of this, I have learned to evaluate both whether the program works technically and whether it actually accomplishes its intended goal.

## What Are My Ethical Responsibilities to the End User and the Organization?

As a computer scientist, my responsibilities go beyond simply creating software that works. I also have to consider how the technology affects the people who use it and the organization responsible for it.

One of my main responsibilities to the end user is to develop technology that is reliable, secure, and respectful of privacy. Users should have a reasonable understanding of how their information is being used, especially when artificial intelligence is involved. Developers should avoid collecting unnecessary information and should take appropriate steps to protect any data that is collected.

Fairness is also an important responsibility when developing AI systems. Artificial intelligence learns from data, experiences, and environments, which means poor training data or poorly designed reward systems can result in unintended behavior. Developers need to test AI systems carefully and recognize that an AI-generated decision is not automatically correct or fair.

I also have responsibilities to the organization developing or using the software. These include writing maintainable code, documenting my work, protecting organizational and customer information, testing software carefully, and being honest about the limitations of a system. If a security problem, bias, or other serious issue is discovered, it should be addressed rather than ignored.

Ultimately, organizations may have technical and business goals, but those goals should be balanced with the safety, privacy, and trust of the people using the technology.

## Reflection

Overall, this project gave me a much stronger understanding of artificial intelligence and reinforcement learning. Before this course, I understood AI mostly from the perspective of what an intelligent system could accomplish. After completing this project, I have a better understanding of what happens behind the scenes and how an intelligent agent can learn through states, actions, rewards, experiences, and repeated training.

Working with deep Q-learning also showed me how neural networks and reinforcement learning can work together. The neural network helped the agent estimate the value of different actions,
