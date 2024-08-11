# Lunar_Lander
Lunar Lander using Reinforcement Learning

#### Bellman Equation:

Q(s,a) = R(s,a) + γ max Q(s´,a´) 

Q(s,a): action-value function, expected return of taking action a in state s and following the optimal policy thereafter.  
R(s,a): immediate reward received after taking action a in state s.  
γ: discount factor, determines the importance of future rewards.  
max Q(s´,a´): maximum expected return for the next state s´.  
