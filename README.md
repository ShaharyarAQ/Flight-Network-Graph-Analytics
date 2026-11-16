# Flight-Network-Graph-Analytics

Project Overview 
This project focuses on analysing flight interconnected data using Apache Spark and GraphFrames. The 
objective is to model the flight network as a graph and study airport connectivity and flight patterns within 
the network. The analysis is based on a historical dataset containing flight records, where each row 
represents a flight between an origin and a destination airport along with associated flight information. 
Using Spark’s distributed processing capabilities, the dataset is transformed into a graph structure where 
airports are represented as vertices and flights as directed edges. Several graph analytics techniques are 
applied to compute network statistics, identify highly connected airports, and evaluate the importance of 
airports using centrality measures and PageRank. 
