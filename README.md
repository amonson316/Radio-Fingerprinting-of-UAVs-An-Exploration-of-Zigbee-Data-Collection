# Radio Fingerprinting of UAVs: An Exploration of Zigbee Data Collection

An Undergraduate Honors Thesis
Submitted in Partial fulfillments of
University Honors Program Requirements
University of Nebraska-Lincoln

Arielle Monson, BS
Computer Science
School of Computing

May, 2023

Faculty Advisors:
Brittany Duncan, Ph.D.<br>
Nirnimesh Ghose, Ph.D.

Radio fingerprinting creates a way to uniquely identify devices based on slight variations [NG1] in the signal they transmit . These variations occur due to fluctuations in the manufacturing processes of wireless hardware. Research has been completed in this area for IoT devices to determine the best way to translate this practice into a network security context. I was curious if it was possible, then, to utilize radio fingerprinting to identify signals from UAV devices. I used a UAV device with a Zigbee antenna to collect data, which supports the possibility of identifying these devices through radio fingerprinting. 

Flowcharts can be found in the Source Code directory<br>
Data collected can be found in the data directory

## Running the code
- open the desired flowgraph in GNU radio and ensure all out-of-tree packets have been installed
- if you wish to see the data being pulled in real-time, open a terminal and navigate to the apps directory
  - update the filename in transceiver.sh and run ./transceiver.sh to open wireshark and begin collecting data
- otherwise simple generate the flowgraph and run it with the playbutton <br>
** Note ** You must be on the correct channel for your Zigbee device to pull data from it
