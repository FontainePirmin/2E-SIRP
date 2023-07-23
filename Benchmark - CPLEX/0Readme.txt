The .txt files include the varying parameter settings for each instance for inserting in CPLEX in the following order:

C: Number of clinics without the central clinic
Omegamax: Number of considered scenarios
P: Number of products
v: Volume of product p
KS: Payload in standard delivery
kS: Costs for traveling from clinic i to j in standard delivery
kem: Costs for serving clinic i in emergency delivery (first entry is central clinic)
kI: Inventory holding costs for product p
Q: Delivery quantity for central clinic
d: Demand. Note that the entries have a different order as this is easier to read in CPLEX: d[Omega,Clinics,Periods,Products]