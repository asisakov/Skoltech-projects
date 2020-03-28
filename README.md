# Skoltech-projects
Skoltech programming projects:

1. A "IOT Waspmote" can be found project with temperature and CO2 concentration regulation with sensors. The main idea is to send the microclimate parameters in the room to the cloud (in this case Thingspeak Cloud) using Waspmote device, collect and vizualize it, after read by next device, which connected to the ventilation and conditioner valves. Depending on a room parameters, the 2nd device will regulate the valves opening and provide comfort conditions for human inside the room.

2. "Intro to DS" contains the final project, which related to the classification of sport articles using classical machine learning. Binary classification was proposed by authors of used dataset to define "objective" or "subjective" articles from their syntax analysis. In the project was achieved f1 score = 84.9 % using SVM classifier. RandomForest, GradientBoosting also was used, but showed a lower accuracy.

3. Folder "SDP relaxations" refers to optimization problem in Optimal Power Flow calculations. Optimal Power Flow is method, which used to calculate minimal generation price for n-bus systems, depending on a demands and constraints, which usually solved using gradient descent, but has a few number of local minimums. Semi-definite Programming used to rewrite the optimization problem above as convex and try to find global optimal point to propose the best solution. Julia programming language used here as optimal tool to solve optimization problems.
