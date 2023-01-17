# conductivimeter
A conductivity meter module that can be used with an Arduino board or using a multimeter at voltage mode. This project is based on a scientific paper:

[Rogerio T. da Rocha , Ivano G. R. Gutz , and Claudimir L. do Lago; "A Low-Cost and High-Performance Conductivity Meter"; J. Chem. Educ. 1997, 74, 5, 572.](https://pubs.acs.org/doi/10.1021/ed074p572)

The module is composed by five parts: (1) negative charge pump, (2) triangular oscilator, and (3) current-voltage converter, (4) rectifier, (5) low-pass filter. 

The electrochemical cell or conductivity cell is basically two separated metalic electrodes with a test solution between them. Their shapes can be planar places (face to face or both in the same plane), pins, interdigited, etc. The metal of the electrodes must be inert in the test solution. They can be covered with a film protection. 
