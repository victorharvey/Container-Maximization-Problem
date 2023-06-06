## Containers Loading Optimization 
*How can we use heuristic algorithms to find the right strategy to load a maximum number of pallets in a sea container?*

Let us say you have to ship goods internationally and you have 2 sets of pallets (EU and US) and 2 types of containers (20ft and 40ft).

Constraints
- There are 24 pallets
- They can be in the the form of EU and/or US pallets 
- You can use 20ft or 40ft shipping container
- No Pallet Stacking 

Objective: Load a maximum number of pallets per container

Pallet size:
- US pallet sizes: 100 cm x 120 cm
- European pallet sizes: 80 cm x 120 cm

Container size:
- 20ft Dry Container: 590 cm x 235 cm x 239 cm 
- 40ft Dry container : 1203 cm x 235 cm x 239 cm

What would be the correct ratio to maximize the number of pallets shipped?

In the old days this problem would be done through trial and error. 

Often the container is not being maximized to its potential. 

This process of not maximizing the space in a container would take up valuable company resources
- Time
- Cost

In the modern era, thankfully we have machine learning and Two Dimensional Knapsack Problem.

Two-Dimensional knapsack problem (2D-KP) states that given a set of rectangular pieces and a rectangular container what is the orthogonal way of packing the pieces within the container such that the sum of the values of the packed pieces is maximized.

A computer algorithm can use math in 2D-KP and solve this problem very fast.

The business value of adopting the machine algorithm is:
- Reduction in forklift downtime
- Reduction in freight truck downtime
- Reduction in product lead times
- Increase in forklift operator efficiency

The result for this specific problem is a 40 ft container packed as: 
- 20 European Pallets 80 x 120 (cm)
- 4 North American Pallets 100 x 120 (cm)

## About me
Supply Chain Professional with international experience and a passion for data science. 
Connect with me on LinkedIn: Profile [Profile](https://www.linkedin.com/in/victorkharvey/)
