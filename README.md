# MDP REPRESENTATION

## AIM:

To create a MDP (Markov Decision Process) for the undertaken problem statement

## PROBLEM STATEMENT:

### Problem Description

The problem involves detecting road blockages in a city. The goal is to identify the optimal path for vehicles to take when a road blockage occurs. The environment is modeled as a Markov Decision Process, where states represent road conditions, actions represent possible routes or decisions, and rewards are based on reaching a destination efficiently.

### State Space

The state space consists of all possible road conditions at a given time. Each state represents a specific configuration of roads, including whether they are blocked or clear.

    State variables: S = {S_1, S_2, ..., S_n}, where S_i represents a possible state, including the conditions of different roads (e.g., road open, road blocked).

### Sample State

A sample state could be: S = {Road_1: Clear, Road_2: Blocked, Road_3: Clear}

### Action Space

The action space consists of the set of possible actions that a vehicle can take when encountering a blocked road. These actions involve choosing an alternative route or proceeding along the current path.

    Action variables: A = {A_1, A_2, ..., A_n}, where A_i represents an action, such as "Take Alternate Route 1" or "Proceed on Current Route."

### Sample Action

A sample action could be: A = {Take Alternate Route}

### Reward Function

The reward function assigns rewards based on the effectiveness of the chosen action in reaching the destination without delay. A higher reward is given for efficient routes, while a penalty is assigned for blocked roads or unnecessary detours.

    Reward function: R(S, A) = Positive reward for reaching the destination efficiently, negative reward for taking a detour or encountering a blockage.

### Graphical Representation

![WhatsApp Image 2024-09-03 at 16 33 51_cad4ad2e](https://github.com/user-attachments/assets/1576ca9e-b2f6-45d5-a1e4-b630f7becf9b)


## PYTHON REPRESENTATION:

![image](https://github.com/user-attachments/assets/d1289e5a-f490-4a1e-bb0b-cb712679eef1)


## OUTPUT:

![image](https://github.com/user-attachments/assets/d6e82257-b4d2-48cf-8541-d0d833d1b5b6)


## RESULT:

The MDP simulation successfully detects road blockages and determines optimal actions for avoiding blocked roads. The rewards indicate the efficiency of the chosen routes, helping vehicles reach their destinations while minimizing delays due to road blockages.

