# A3 – Parametric and FEA

## Parametric Design
<img width="1320" height="908" alt="A3Design" src="https://github.com/user-attachments/assets/034a6c28-a118-4fa3-9329-2f1563efaf24" />

![CAD View 1](./A3Cad1.png)
![CAD View 2](./A3Cad2.png)
[Download the SolidWorks part (A)3.SLDPRT)](./A03.SLDPRT)
## FEA

![Deformation Map](./A3Defmap.png)
![Von Mises Stress](./A3VMSM.png)

## Design Reflection
Calculated Deflection: .00225 in    FEA Result Deflection: .001908 in

15.2% discrepancy, this could have been a result of the research done to get my calculations. The modulus of Elasticity that I used was the smallest value allowed for the tests, beyond that, solidworks rounded my number I got from my calculations for my diameter down when I was inputting the value, this could have been another cause for discrepancy. I would trust the FEA result more because it takes into account more properties of the aluminum I selected than what is being used in my calculations.

The peak stress of the hole would be at 1599 psi and it would come out to have a 1.07 wt which is still below my safety factor of 2.

## Lessons learned
I should try to make sure that all numbers used in my calculations are not rounded. No numbers should be rounded unless the final answer is to be rounded to a certain number, and in that case, only the final answer gets rounded, not any of the numbers required for the calculations of the final answers.
