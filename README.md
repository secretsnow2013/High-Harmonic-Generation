# High-Harmonic-Generation
<img align="left" src="https://raw.githubusercontent.com/Aurelien-Pelissier/High-Harmonic-Generation/master/report/HHG.png" width=200>
High harmonic generation (HHG) refers to the process of creating vacuum (VUV) or extreme (XUV) ultraviolet light through a nonlinear interaction of an intense laser field with a gas target. This repository contains the source code to calculate the high harmonics amplitude accounting for all involved physical phenomenons (Quantum mechanic, Supersonic flow physics, Plasma physics and Nonlinear optics). More specifically, we consider supersonic gas flow at the nozzle outlet, ions dynamic in the plasma, quantum atomic response of freed electrons, phase matching and absorption.




## Involved parameters

#### Laser parameters

- Peak intensity
- Pulse length (FWHM)
- Wavelength
- Beam Radius
- Frequency
- Harmonic order

#### Gas parameters
- Gas Velocity
- Peak preassure
- Nozzle diameter
- Nozzle position
- Gas (Krypton, Argon, Xenon)


<table>
    <thead>
        <tr>
            <th>header 1</th>
            <th align="center">header 2</th>
            <th align="right">header 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>line 1</td>
            <td align="center">1</td>
            <td align="right">value</td>
        </tr>
        <tr>
            <td>row 2</td>
            <td align="center">2</td>
            <td align="right">value</td>
        </tr>
        <tr>
            <td>line 3</td>
            <td align="center">3</td>
            <td align="right">value</td>
        </tr>
    </tbody>
</table>



## Code structure

main

	detectdipole
		  dipole
			    potde		              %potential depth

	phasematching
		  detectetha  				      %check if file already exist
			    ethap 			      %ioniation fraction after one pulse
				      Ipot		      %ionization potentiel
				      Nt

		detectethan  				      %check if file already exist
			  etharz 			      %ioniation fraction after n pulse
				    ethabp 		      %between 2 pulses
					      solvepde 	      %for a fixed z
						        Ndens
						        mobility
						        Press

		phase
			  refractive
			  Igauss
			  Press
			  ioniz

	  amplitude
		    absorb





## Running the code









## Results




## Reports
