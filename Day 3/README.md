# Day 3 ; Study and Analysis of the Voltage Transfer Characteristics .
## Todays Goals : 
## 1.Plot the Voltage Transfer Characteristics (VTC) of a CMOS inverter .
## 2.Perform Transient Analysis to calculate the inverter's rise and fall delays .

<details>
  <summary> Part 1 :Run the SPICE Simulation </summary>
  We have to run the NGSPIICE file of [day3_inv_vtc_Wp084_Wn036.spice] as it is configured  for a DC sweep to generate the VTC curve. 
  
  Here we can see that the DC voltage is being sweeped and also the terminal output shows that the simulation has successfully completed, and the relevant vectors, including in and out, are ready for plotting.
</details>

<details>
  <summary> Part 2 :Plot the VTC Curve </summary>
  Once the simulation is complete, use the plot command in terminal . This wil show the output voltage as a function of the input voltage . 
  command :  plot out vs in 
  
</details>
