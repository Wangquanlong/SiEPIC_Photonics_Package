<p align="center">
<b>Provided by SiEPIC Kits Ltd.</b>
</p>
<p align="center">
<img src="Documentation/img/siepic_kits_logo_0.png" width="40%">
</p>
<p align="center">
<b><a href=http://siepic.com/>SiEPIC.com</a></b>
</p>

# SiEPIC_Photonics_Package
A Python (v3.6.5) package that provides a set of basic functions commonly used by the UBC photonics group.

## Functions
* **calibrate**

Calibrates an input spectrum response with respect to another input response. [Example](https://github.com/SiEPIC-Kits/SiEPIC_Photonics_Package/tree/master/Examples/calibrate)

* **baseline_correction**

Calibrates an input response with respect to it's baseline. [Example](https://github.com/SiEPIC-Kits/SiEPIC_Photonics_Package/tree/master/Examples/baseline_correction)

* **cutback**

Extrapolate the losses of different input data files losses using the cutback method. [Example](https://github.com/SiEPIC-Kits/SiEPIC_Photonics_Package/tree/master/Examples/cutback)


* **to_s_params**

Converts the input data to generate a .dat file compatible with Lumerical INTERCONNECT's N-port s-parameter file format. [Example](https://github.com/SiEPIC-Kits/SiEPIC_Photonics_Package/tree/master/Examples/cutback)

* **download_response**

Downloads a .mat response (Caverley's pyoptomip format) from a url and parses data into a variable. [Example](https://github.com/v/SiEPIC_Photonics_Package/tree/master/Examples/grab_mat_file)

## Simulators and solvers
* **EM_solver**

Eigenmode solver for a 2D waveguide structure.

* **Ring_Designer**

Microrings designer: model N-order rings system spectrum. [Example](https://github.com/SiEPIC-Kits/SiEPIC_Photonics_Package/tree/master/SiEPIC_Photonics_Package/solvers_simulators/rings)

* **MZI_simulator**

Simulate the spectrum of a Mach-Zehnder interferometer with different input parameters. [Example](https://github.com/SiEPIC-Kits/SiEPIC_Photonics_Package/tree/master/SiEPIC_Photonics_Package/solvers_simulators/mzi)

* **Bragg_TMM**

Model the response of a Bragg grating based on the transfer matrix method (TMM). [Example](https://github.com/SiEPIC-Kits/SiEPIC_Photonics_Package/tree/master/SiEPIC_Photonics_Package/solvers_simulators/bragg_tmm)

* **Bragg_CMT**

Model the response of a Bragg grating based on the coupled-mode theory (CMT). [Example](https://github.com/SiEPIC-Kits/SiEPIC_Photonics_Package/tree/master/SiEPIC_Photonics_Package/solvers_simulators/bragg_cmt)

* **Contra_DC**

Model the response of a contra-directional coupler based on a coupled-mode theory (CMT) and transfer matrix method.


## Lab equipment and testing stage scripts

* **Stage control**
* **Keithly 2602B**
* **Agilent OSA**

## To-do:
* Integrate Jupyter Notebook
* Add PCM analysis script
