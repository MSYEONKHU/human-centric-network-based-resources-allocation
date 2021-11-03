# Human-centric-network-based-resources-allocation
An approach for allocating Human resources based on Human-centric network for Process-Aware information system

Efficient allocating resources for organizations is one of the main concerns in enterprises. Along with the development of the organizations right from the start of their business, the resources allocation task dramatically determines the success of businesses, especially with human resources. Recognizing the business's resources from which to operate, exploit, and serve in business activities is the key to the success and development of organizations.

There are several different approaches and solutions to support allocating resources efficiently. In this paper, we propose a method using the human-centric network as the central part for providing human resources allocation plans in the process-aware information system. In particular, we use the knowledge derived from human-centric networks that formed through the operation phases of the information system. Subsequently, the process-aware enterprise social network, the affiliation network discovered from the system enactment log history are used for making resource allocation strategies in the organizations. This approach gives the business managers a clear, intuitive, and detailed view of the organization's resources and their role in the operation phases. 

Aside from describing theoretical, algorithms to discover the networks, we also describe the system architecture and the scenarios for planning human resources allocation based on these networks. Furthermore, we use real-life data set for getting experimental results and proving the theoretical proposal. This approach will be a promising solution to effectively support businesses for allocating resources in their organizations.


**The system architecture**

![The system architecture](5_system_architecture.png?raw=true "The system architecture")


**The discovered Process-aware enterprise social network (PESN) (Degree centrality view) from Help desk data set**

![The system architecture](9_PESN_Degree.png?raw=true "The system architecture")

**The discovered PESN (Betweenness centrality view) from Help desk data set**

![The system architecture](10_PESN_Betweenness.png?raw=true "The system architecture")



The system was use Django frame work with Graphviz and Cytoscape library. To learn how to install the Django, see at: https://www.djangoproject.com/start/

_How to install the system:_
- Install the required Python packages (described in requirements.txt):

  matplotlib==3.2.2
  numpy==1.18.5
  pandas==1.0.5
  PyMySQL==0.9.3
  Django==3.0.8
  networkx==2.4
  python_dateutil==2.8.1
  Install MySQL database version >= 5.1. The SQL script of database is stored in folder "Database"

- Run the application by using this command: python manage.py runserver

If you have trouble installing the source code, don't hestitate to contact me msyeon (at) khu (dot) ac (dot) kr


