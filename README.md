# README #

Explanation of repository.

### What is this repository for? ###

* This repo holds the two excel spreadsheets from which a technoeconomic model of a HBES has been designed. A third spreadsheet of key results has been appended.
* The first spreadsheet 'raw_data_process.xlsx' contains all raw data dependent processing. Whilst the second spreadsheet 'synth_data_model.xlsx' demonstrates the combined technoeconomic model, which processes the synthesised data-streams and creates output variables as a function of the modifiable technical parameters, fundamental technical parameters, and fundamental economic parameters. Finally, the third spreadsheet 'results.xlsx' presents some of the key results from a manual optimisation process carried out using the 'synth_data_model.xlsx' file.

### How do I get set up? ###

* To manipulate the base estimates of  thermal load data streams or renewable energy output data streams enter the 'raw_data_process.xlsx' file and alter the fundamental parameters and operating principles setup in each of the sheets; the newly obtained thermal load patterns or energy generation patterns must be copied into the 'synth_data_model.xlsx' file if  HBES optimisation is intended.

* Note that 'synth_data_model.xlsx' contains the majority of the technical and economic fundamantal parameters, as well as the modifiable parameters.

* To test systems: alter modifiable parameters within the modeller file. Output parameters can be referred to during the manual optimisation process.

* These excel files contain data at and hourly resolution over multiple years; which makes the running of these files slow at best for datasets breaking 5 years. They can be run fine through Excel on MAC or Windows to my knowledge.

### Who do I talk to? ###

* Thomas Dodd
* thomasdodd13579@icloud.com
