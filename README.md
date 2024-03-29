<p align="center">
  <b>Learning representation of the structured environments through a complex graphs inference</b><br>
</p>

<p align="center">
  Bachelor Thesis <br>
  Cognitive Science <br>
  Faculty of Philosophy and Social Sciences <br>
  Nicolaus Copernicus University <br>
</p>

-------------------------------------------------------------------------------------------------------

##### Abstract

Humans and animals succeed in searching through various complex environments. Back in the thirties, Tolman argued that such abilities arise from the construction of “cognitive maps” through exploration. Such maps enable active mapping of real-world environments to simplified cognitive representations. Although, this theory is widely accepted and studied, the way of how different cognitive maps are stored in the brain is still discussed. Some authors proposed that cognitive maps represent the environment as Euclidean space, but in my thesis I provide evidences that support the hypothesis that graph-theoretical approach provide a more robust framework that additionally allows for behavior flexibility. Here, I investigate a potential of reinforcement learning algorithms trained in navigation of different environments to construct an internal graph-based representation of these spaces. An ability to form a cognitive map in parallel with real-time exploration may underlie human ability to navigate in various spaces, represent the world structure and generalize to novel tasks.
  
  ##### Folders
 

- <i> algorithms </i> with possible solutions that can be applied to a grid-maze environment
- <i> mazes </i> configurations of a 2D grid stored in .txt file
- <i> simulations </i> ran on given maze together with the simulations recordinds
- <i> tests </i> consist of code used to practice different libraries 
- <i> thesis </i> 


 ##### Pipeline
 
<i> 01_create_maze</i>: how to create various mazes using numpy or loaded mazes from txt files. See examples in folder [graph_navigation/mazes/src](https://github.com/wsojka00/graph_navigation/tree/main/mazes/src).

<i> 02_algorithm_run</i>: apply defined solvers to various mazes. See examples in folder [graph_navigation/algorithms](https://github.com/wsojka00/graph_navigation/tree/main/algorithms).

 ##### Resources
 
Big thanks to Xingdong Zuo for creating [mazelab](https://github.com/zuoxingdong/mazelab) framework that speeds up the process of starting with the task of putting an agent in the maze in which it has to navigate. Besides, I would like to strongly recommend acknowledge all interested people to check [neuronav](https://github.com/awjuliani/neuro-nav) created for the purpose of standardization of spatial navigation tasks in various environments using multiple RL algorithms from recent papers. 
