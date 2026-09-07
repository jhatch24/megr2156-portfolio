# A3 – Parametric and FEA

## **Objective**  
We were asked to design a bar which has a circular cross section where the values of the criteria given for the material, maximum deflection and load. Determine the bar’s minimum geometry (ie.. length, diameter, and weight) through parametric design while under direct tension. Then verify the geometry through finite element analysis. Our goals were to use axial deflection modeling to design its dimensions, use parametric design to determine a bars length, an introduction to FEA as well as linking dimensions to appropriate CAD parameters, and finally compare and contrast the different analysis.  

## **Analyze**
## Parametric Design  
![pg1](IMG_0197.jpeg)  
![pg2](IMG_0198.jpeg)  
These are detailed calculations about how I found the deflection, length, and Area. I first listed my knowns and unknowns so that I could effectively isolate my variables and solve for the appropriate dimensions I was missing. I chose 1 inch in diameter as my "d" value because it was simple and made my calculations clean. Additionally, I chose my Force to be 400 lbf because it was in between the recommended range for Force "F". Same thought process was applied for picking the Elasticity Modulus of my Aluminum beam. I picked 10x10^6 psi for my "E" because it was an even number and make my calculations easy to work through. After working through all my calculations solving for Area and Inertia. I used the recommended formulas in the Machinery's Handbook to solve for Length of my beam. I was now ready to start modeling my system in CAD and set parameters to test my beam.  
  
Parametric Design process and FEA Simulation in CAD:  
<object data="A3_parametric_design_screenshots.pdf" type="application/pdf" width="100%" height="800px">
    <p>Your browser does not support inline PDFs. <a href="A3_parametric_design_screenshots.pdf">Click here to view or download the A3 parametric design screenshots PDF</a>.</p>
</object>  
  
Solidworks Simulation FEA Report:  
<object data="A3_FEA_Solidworks.pdf" type="application/pdf" width="100%" height="800px">
    <p>Your browser does not support inline PDFs. <a href="A3_FEA_Solidworks.pdf">Click here to view or download the A3 parametric design screenshots PDF</a>.</p>
</object>  
My maximum stress is lower than the strength of Aluminum (Sy = 40). My calculated maximum stress was 0.509 ksi. Which ended up giving me a safety factor of 78.54. (SF = 78.54)   
## **Decide**  
I would trust the hand calculations more than a CAD model simulation because the hand calculations are solved based on single values and give a foundation and guide towards a parametric design. The CAD simulation should be used as a visualization tool, to analyze and verify that your hand calculations are correct and accurately represent a system one is trying to design. Although, I would not be completely reliant on just hand calculations, especially when I have such a great tool at my disposal to represent a visual of my model.  

## **Communicate**
Some lessons learned while working on this assignment was learning how to run an FEA test in Solidworks with parameters set in the equation tab. I also learned how to evaluate these properties and compare them with calculations by hand, and FEA calculations in Solidworks. I started this assignment Wednesday and completed my final revisions Monday. The total time I worked on this assignment was around 8 hours.  
<a href="A3_FEA_beam.SLDPRT" download>Download SolidWorks Assembly</a>   
