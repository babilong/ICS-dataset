# ICS-dataset
benign folder for benign traffic.
The vicious folder contains malicious traffic.
The experiment folder contains the data used for thesis training.


In the benign folder:
CJ1 Turns on the industrial control device but does not manipulate it in any way.
CJ2 Start the smart meter module.
CJ3 Start the smart meter module and manipulate the real-time reading of the device's operating values.
CJ4 Switch off the smart meter module and manipulate the remaining modules that communicate using the S7 protocol.
CJ5 Start the smart meter module and control the real-time reading of the device operating values, shut down the smart meter module and control the rest of the modules communicating using the S7 protocol.


In the vicious folder:
3 types of attack traffic are shown.


In experiment folder(experiment_csv and experiment_pcap):
Shows the pcap package and csv file used in the paper.
