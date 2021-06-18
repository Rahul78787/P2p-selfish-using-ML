# P2p-selfish-using-ML


Сlient–server mоdel is а distributed аррliсаtiоn struсture thаt раrtitiоns tаsks
оr wоrklоаds between the рrоviders оf а resоurсe оr serviсe, саlled servers,
аnd serviсe requesters, саlled сlients.
[1]In a Peer-to-Peer (P-to-P, P2P,…) network the participants share a part of their
own hardware resources (processing power, storage capacity, network link
capacity, printers,...). These shared resources are necessary to provide the Service
and content offered by the network (e.g. file sharing or shared workspaces for
collaboration). They are accessible by other peers directly, without passing
intermediary entities.



A peer to peer network produces huge amounts of data in terms of logs, these logs
may include information about source and destination, metadata like time, quantity
etc about the data being transmitted, information about types of connections being
used like protocol information and port numbers and various other information.
Our approach towards the solution is to leverage this data and apply machine
learning techniques to solve the problem of identifying selfish peers present in the
network.
We plan to
● Apply various machine learning techniques to generate multiple models
based on different algorithms.
● Compare and analyse these algorithms so as to find an algorithm with best
performance and accuracy.
● Further optimise the algorithms using nature inspired machine learning
algorithms to study and ultimately provide a best solution.
Detailed Solution
We obtained the dataset from NIT Sikkim with the help of our mentor.
The dataset has multiple columns namely:
● Source: IP address of the source peer. (String, Categorical Variable)
● Destination: IP address of the destination peer. (String, Categorical Variable)
● Protocol: Protocol used. (String, Categorical Variable)
● Src_port: Source port used for communication.
● Dest_port: Destination port used for communication.
● Flow_count: Total number of flow during the connection.
● Flow_size: Amount of data transferred.
● Pkt_size_of_first_flow: Packet size of the first flow.
● Flow_duration: Duration of the flow.
● First_flow_inter_arrival_time: Arrival time for the first flow.
