Simple pipeline to convert pihole logs to CIM-compliants fields for the Network_Resolution datamodel in Splunk.
As mentioned on:
https://medium.com/@datoui/collecting-pi-hole-logs-and-parsing-them-with-cribl-stream-046bcf612188



Remember you still need to add your tags/eventtypes within Splunk

Turn this:
/var/log/pihole/pihole.log

![image](https://github.com/user-attachments/assets/89c502b7-cc6e-4d3d-b741-e6ba196669ef)


Into: 

![image](https://github.com/user-attachments/assets/c923dc63-2ec0-4349-86a3-cd6d9559ca0d)
