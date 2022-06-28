<h1 align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/UPocek/Car_AI/blob/main/results/gen5.png">
    <img alt="Flutter" src="https://github.com/UPocek/Car_AI/blob/main/results/gen5.png">
  </picture>
</h1>

# AI Driving

  Artificial intelligence learns how to drive a car on the track. Agents have radars (rays) that help them understand where they are on the road and how far away are they from the edge. The individual car gets eliminated from the population if they collide with the road edge. To accomplish this I am using reinforcement learning with the NEAT genetic algorithm in python.
  
## Progress

  ### Stage 1:
  The initial population size is 30 (but in gen 1 they die so fast I can't even take a screenshot of it ;-)), the activation function is set to tanh, and agents (individuals) that go furthest get to reproduce for the next generation. A reward is calculated as "return self.distance / 50.0" and is used to optimize weights and biases in the neural network.
  
  ![START](https://github.com/UPocek/Car_AI/blob/main/results/gen1.png)
  
  ### Stage 2:
  After a few corners, most of the individuals from the population have died, but others learned from their mistakes, optimized their neural networks, and were able to adapt and learn how to be better at the game. In generation four one or two cars were able to make a few successful laps.
  
  ![MID GAME](https://github.com/UPocek/Car_AI/blob/main/results/gen4.png)
  
  ### Stage 3:
  In generation five we have a car that could make good turns and keep itself away from the edge. This was a very fun project for me I hope you enjoyed it as well.

  ![SUPREMACY](https://github.com/UPocek/Car_AI/blob/main/results/gen5.png)
