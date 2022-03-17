

### agent:
entity that perceives its environment and acts upon it

### state:
a configuration of the agent

### initial state:
the first configuration of the agent


To go from the initial state to the result
we need actions: choices that are made
We can think of them as functions

let actions(s) returns the set of actions that can
be executed in state s

We need a description of the states, and the actions

Also a description of the relation between them
How an action affects the state

### transition model
a description of what state results from
performing any applicable action in any state

formally:
result(s, a) returns the state resulting from performing
action a in state s

generalizing all possible actions/states:

### state space:
the set of all states reachable from the
initial state by any sequence of actions

we can represent this better by using a graph
where the nodes are states
and the edges(directed) are the actions

How we know when the AI finishes
In other words, when the current node is the finishing node

### goal test:
way to determine whether a given state is a goal test

### path cost:
numerical cost associated with a given path


### node:
data structure that holds:
a state
a parent 
an action (action applied to parent to to get node)
a path cost (from initial state to node)


Playing against another player
who will try to win us
