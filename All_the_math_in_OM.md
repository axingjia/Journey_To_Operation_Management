###### Measuring Supply Chain Performance
Percentage invested in ventory=Total inventory investment/Total assets*100

Inventory Turnover(week of supply):    
Inventory turnover=cost of goods sole/inventory investment    
Inventory investment is the average inventory value for the same period. This may be the average of several periods of inventory or beginning and ending inventory added together and divided by two.

Weeks of supply, may have more meaning in the wholesale and retail portions of the service sector than in manufacturing.    
Week of supply= inventory investment/Annual cost of goods sole/52 weeks

###### A bullwhip effect measure 
Bullwhip=variance of orders/variance of demand

Variance amplification is present if the bullwhip measure is greater than 1. This means the size of a company's orders fluctuates more than the size of its incoming demand. If the measure equals 1, then no amplification is present. A value less than 1 would imply a smoothing or dampening scenario as orders move up the supply chain towards suppliers.

###### Transportation Mode analysis 
Daily cost of holding the product=annaul holding cost* product value/365=0.4*$1750/365=$1.92

###### Minimizing cost 
1. Annual setup cost=number of orders placed per year * setup or order cost per order=(annual demand/number of units in each order)* (setup or order cost per order)=D/Q*S    
Where D=Annual demand in units for the inventory item, Q=Number of units per order; S=Setup or ordering cost for each order
2. Annual holding cost=(Average inventory level)* (holding cost per unit per year)=(order quantity/2)(Holding cost per unit per year)=Q/2*H where Q=Number of unit per order; H=Holding or carrying cost per unit per year
3. So the optimal order is D/Q*S=Q/2*H, 2DS=Q^2*H, Q^2=2DS/H; Q=Math.Sqrt(2DS/H)

Because of this, we can calculate the expected number of order placed during the year and the expected time between order(T):
* Expected number of orders= N =Demand/Order quantity 
* Expected time between order= T= Number of working days per year/N

Total annual cost=setup cost+ holding cost     
TC=D/Q*S+Q/2*H

Inventory cost may also be expressed to include the actual cost of the material purchased:    
TC=D/Q*S+Q/2*H+PD

###### Reorder point (ROP)
* ROP=Demand per day*lead time for a new order in days=d*L
* the demand per day, d is found by dividing the annual demand, D, by the number of working days in a year= d=D/Number of working days in a year
* example: ROP=8000/250*3=96, thus, an order should be placed at 96 units