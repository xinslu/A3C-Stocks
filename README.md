# Asynchronous Advantage Actor Critic Method
## Breaking Down the 3 As
### Asynchronous
A3C has a global network with multiple agents having their own set of parameters, which creates every agent’s situation interacting with its environment and harvests the experiences for overall training. This helps deal with input corelation.
### Advantage
Advantage measures the "advantage" an actor gets by taking a certain action. This is defined as Q value minus value of the state as $A(s.a) = Q(s,a) - V(s)$

