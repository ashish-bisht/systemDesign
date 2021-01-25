#CAP

Cap theorem states that it is impossible to obtain all three in distrubuted systems. We need to have tradeoff's , and the best suited for us we will take.


#Consistency
All nodes will have same data, reads are restricted until same data is on all he nodes.
It is important for bank like applications.


#Availability

Every request will get response. It is achieved by replicating data across many servers.
Example can be facebook feeds, it is not necessary that some post is there in every feed at same time only, it can take some time to update, here more focus is on availability of the server.


#Partion tolerence
Cluster continues to work even if there is communication break between the nodes.

