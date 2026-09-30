
<img width="369" height="301" alt="image" src="https://github.com/user-attachments/assets/63671a6b-7fdb-4abd-9772-c80c96c44b02" />

## Category: Forensics
### Description: The flag is split inside different signals in this pcap file, can you recover it.
### Flag format: CTFkom{fake_flag}


## Solution

<img width="932" height="475" alt="image" src="https://github.com/user-attachments/assets/1d116cf0-49d5-4300-961b-c180e18e1460" />

### Open the file in Wireshark and look trough the network patches, you will find a spot where a part of the flag is shown. 

<img width="105" height="111" alt="image" src="https://github.com/user-attachments/assets/cef4e7c1-1ac9-48f0-ba12-5342536dee74" />

### Click on follow the tcp stream and you will find the other signals as mentioned in the description

<img width="140" height="236" alt="image" src="https://github.com/user-attachments/assets/48959780-af7a-4269-a27f-1ed287676aea" />
 
### Combine all the parts of the flag you found and you will get this CTFkom{4nalyzing_traff1c_is_c00l}
