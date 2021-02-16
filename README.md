# Inventory-Movement-Plan-with-Knime


This Knime Workflow represents a solution to create an Inventory Movement Plan, that is a crucial step in any Inventory Management System.
Using an item's current units in the warehouse, it's units in each distribution pods, it's sale rates, and the number of days it takes for an item to reach a distribution pod, the workflow calculates the amount of units of that item that should be transferred.
Incase the requirement is more than the units  available in warehouse, a priority logic is also implemented that takes each pods current supply and it's priority among the other pods to finalise how the limted stock should be transferred.

All this is implemented on Knime Analytics Platform and can be deployed on a Knime Server as a Guided Web Application. This deployment provides the end user an interface to visualize each step of the calculation. 

<B>To use a knime workflow on knime analytics platform</B>

1. Clone the repo
2. Zip the folder created
3. On knime analytics platform, go to file > Import workflow
4. Here, select the zip folder. The data files, along with the workflow will be imported in the Analytics Platform.
5. In the "Node" tab at the top of the platform, select execute All to run the workflow.
