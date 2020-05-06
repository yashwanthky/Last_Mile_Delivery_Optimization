# Last Mile Delivery Optimization 
Optimize last mile delivery using FICO Xpress IVE

## INTRODUCTION

A transportation company is evaluating a prototype system that combines trucks and drones for last-mile delivery services. The test run considers a set of orders that must be delivered to known locations. A delivery truck starts from a depot and visits “launch sites” corresponding to the customers locations. From each launch site, the truck deploys a series of drones that deliver the orders and return to meet the truck at the launch site. Once all the drones are recovered, the truck moves to the next launch site and repeats the process until all orders are delivered.

This project is aimed at finding the most cost-efficient route for the trucks and the drones. The number of drones were varied between iterations to include 1, 2 and 3 drones as viable options to test how this changes the cost and routes. A linear mixed integer programming approach was taken to achieve the same, with the code tested and results obtained through FICO Xpress IVE software. This report elucidates the model that was built with the sets, decisions and constraints, the iterations on a dataset with varying truck and drones’ combination and the summary of iterations that test the model algorithm on different datasets. A simple cost sensitivity analysis was also performed to check how the routes and decisions change based on changing the cost to serve a customer.
