# psrchive_epos
Dockerfile offering PSRCHIVE functionality for EPOS format


Dockerfile that compiles PSRCHIVE with added EPOS functionality. The previous EPOS functionality of PSRCHIVE read only 2 out of the 4 channels. This modification ensures that all 4 channels from an adding polarimeter output are read into a timer file. Note that you cannot directly use PSRCHIVE for polarisation calibration since it assumes a multipying polarimeter. You can do this using https://github.com/prajwalvp/EPOS_calibrator 
