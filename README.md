# software-failure-propagation-prediction
A failure in large software systems can be catastrophic.  A proactive approachto detect possible failures and measure their potential impact and propagation can be critical to the reliability of the business.  This proactive approach canbe achieved by various means, one of which is by monitoring the system’s components and utilizing this information to predict and estimate how the current system  state  may  cause  a  failure  and  how  this  failure  may  propagate.

We use Graphs as large software systems can naturally be represented by graphs. The microservices can be represented by nodes and the calls between those microservices can be represented by edges.

This repository contains two GNN implementations using two models; EnocdeProcessDecode & InteractionNetwork. The implmentation of the two models hve been done on two phases; In the first one there is a single feature for each node and edge. While on the scond one, there are four features on the node level and two features on the edge level.


