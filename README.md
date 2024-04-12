# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering


## OUTPUT:

![Screenshot 2024-04-10 085141](https://github.com/hema-dharshini5/InformationGathering/assets/147117728/b2d096d5-b244-49f2-ae1b-d6cbb7b4a74d)
## finding ip address
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## outrput
![Screenshot 2024-04-12 092018](https://github.com/hema-dharshini5/InformationGathering/assets/147117728/2f728bc7-9956-4234-a102-508f1d365fde)

## finding hosting company
get further detail by using ip2location.com website.
## output
![Screenshot 2024-04-12 092145](https://github.com/hema-dharshini5/InformationGathering/assets/147117728/73f8c95c-2249-49b3-ad2e-fce949525916)

## History of the website:
## output
![Screenshot 2024-04-12 092248](https://github.com/hema-dharshini5/InformationGathering/assets/147117728/b699c750-c878-4ecb-aeee-89ae728f842f)

## netcat
```
nc 172.17.52.118 80
```
## output
![Screenshot 2024-04-12 092312](https://github.com/hema-dharshini5/InformationGathering/assets/147117728/fbcb7c6d-2c9a-4cbe-ac56-de19e96d59d3)
## whatweb
```
whatweb infosys.com
```
whatweb zoho.com
```
whatweb -v -a 3 172.17.52.201
````
## output
![Screenshot 2024-04-12 092327](https://github.com/hema-dharshini5/InformationGathering/assets/147117728/2994305b-7f98-437c-84a1-e22897054674)

## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## output
![Screenshot 2024-04-12 092421](https://github.com/hema-dharshini5/InformationGathering/assets/147117728/532bbf99-8030-4ff3-8e9e-902959e08986)

## Tracing the location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## output
![Screenshot 2024-04-12 092446](https://github.com/hema-dharshini5/InformationGathering/assets/147117728/8b424ef0-3e80-472a-8102-3a57355aea94)
## UDP Traceroute:
```
 sudo traceroute -U www.saveetha.ac.in
```
## output
![Screenshot 2024-04-12 092517](https://github.com/hema-dharshini5/InformationGathering/assets/147117728/164d8520-9c0c-4e8d-acbf-9dee306b3b5f)
## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## output
![Screenshot 2024-04-12 092533](https://github.com/hema-dharshini5/InformationGathering/assets/147117728/c5585d44-dc4d-4ccf-9781-c07a63d1bb74)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
