
# Project Report


## Learning Algorithim

## Parameters

BUFFER_SIZE = int(1e5)  # replay buffer size<br/>
BATCH_SIZE = 64         # minibatch size<br/>
GAMMA = 0.99            # discount factor<br/>
TAU = 1e-3              # for soft update of target parameters<br/>
LR = 5e-4               # learning rate<br/>
UPDATE_EVERY = 4        # how often to update the network<br/>

## Neural Network Archetecture

The Neural Network consists of three fully connected layers.<br/>  
The first has an input size equal to the state size, output 64.<br/> 
The second input 64, output 64.<br/> 
The third input 64, output is the action_size<br/> 
Relu activation functions and adam optimizer are used.

## Results

Episode 100	Average Score: 0.02<br/>
Episode 200	Average Score: 0.652<br/>
Episode 300	Average Score: 1.32<br/>
Episode 400	Average Score: 2.14<br/>
Episode 500	Average Score: 3.35<br/> 
Episode 600	Average Score: 4.21<br/>
Episode 700	Average Score: 5.17<br/> 
Episode 800	Average Score: 6.23<br/> 
Episode 900	Average Score: 6.46<br/>
Episode 1000	Average Score: 8.18<br/> 
Episode 1100	Average Score: 8.01<br/>
Episode 1200	Average Score: 8.91<br/>
Episode 1300	Average Score: 9.71<br/>
Episode 1400	Average Score: 8.74<br/>
Episode 1500	Average Score: 10.56<br/> 
Episode 1600	Average Score: 10.83<br/>
Episode 1700	Average Score: 11.29<br/> 
Episode 1800	Average Score: 11.94<br/> 
Episode 1900	Average Score: 11.82<br/> 
Episode 2000	Average Score: 11.92<br/> 
Episode 2100	Average Score: 12.41<br/> 
Episode 2135	Average Score: 13.03<br/>
Environment solved in 2035 episodes!	Average Score: 13.03<br/>

## Plot of Rewards
![Plot of Rewards](plot.png)

## Future Work

Double Deep Q Network<br/>
Prioritized Experience Replay<br/>
Dueling Deep Q Networks<br/>
Tune hyperparameters<br/>
Learning from pixels<br/>
