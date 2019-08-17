# Dino-Artificial-Intelligence
  ![alt text](https://github.com/lucasstonehc/Dino-Artificial-Intelligence/blob/master/Dino.png)


# What is Reinforcement learning ?

  A reinforcement learning agent interacts with its environment in discrete time steps. At each time t, the agent receives an observation O{t} = observation in time T, which typically includes the reward R{t} = reward in time T.
  
  It then chooses an action  A{t} =  Action in time T from the set of available actions (ALL ACTIONS THE AGENT HAS), Examples of actions (Jump, lie down, fly) which is subsequently sent to the environment. 
  
  The environment moves to a new state S{t+1} =  new state of agente after does action, (T+1) the means that is the next time and the reward  R{t+1} associated with the transition S{t},A{t},S{t+1} = State of agent in time T, Agent does action and the new State of agent is determined.
  
  The goal of a reinforcement learning agent is ***to collect as much reward as possible***. (this part is very important) => The agent can (possibly randomly) choose any action as a function of the ***history***.
  
  Legends:
  
    O{t} = observation in time T.
    
    R{t} = reward in time T.
    
    A{t} =  Action in time T.
    
    S{t},A{t},S{t+1} = State of agent in time T, Agent does action and the new State of agent is determined.
    
    algorithm Q-Learning State->Action->Reward->State.
