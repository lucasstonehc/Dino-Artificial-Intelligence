# Dino-Artificial-Intelligence
  ![alt text](https://github.com/lucasstonehc/Dino-Artificial-Intelligence/blob/master/Dino.png)


# What is Reinforcement learning ?

  A reinforcement learning agent interacts with its environment in discrete time steps. At each time t, the agent receives an observation O{t} = observation in time T, which typically includes the reward R{t} = reward in time T.
  
  It then chooses an action  A{t} =  Action in time T from the set of available actions (ALL ACTIONS THE AGENT HAS), Examples of actions (Jump, lie down, fly) which is subsequently sent to the environment. 
  
  The environment moves to a new state S{t+1} =  new state of agente after does action, (T+1) the means that is the next time and the reward  R{t+1} associated with the transition S{t},A{t},S{t+1} = State of agent in time T, Agent does action and the new State of agent is determined.
  
  The goal of a reinforcement learning agent is ***to collect as much reward as possible***. (this part is very important) => The agent can (possibly randomly) choose any action as a function of the ***history***.
  
  ### Legends:
  
  O{t} = observation in time T.

  R{t} = reward in time T.

  A{t} =  Action in time T.

  S{t},A{t},S{t+1} = State of agent in time T, Agent does action and the new State of agent is determined.

  # Algorithm Q-Learning (State->Action->Reward->State).
  The goal of Q-learning is to learn a policy, which tells an agent what action to take under what circumstances.
  
  
  The algorithm, therefore, has a function that calculates the quality of a ***state-action*** combination:
   Q: S x A => {R}. 
   
   this part is how to algorithm works:
   
   Before learning begins, Q is initialized to a possibly arbitrary fixed value ***(chosen by the programmer)***. Then, at each time T the agent selects an action A{t}, observes a reward R{t}, and go to a new state S{t+1} (that may depend on both the previous state S{t} and the selected action), and Q is updated. 
   
   The ***core of the algorithm*** is a simple value iteration update, using the ***weighted average of the old value*** and the new information.

### Influence of variables into the Algorithm Q-Learing
  Learning Rate is optimal when ***Alpha*** is equal 1.

