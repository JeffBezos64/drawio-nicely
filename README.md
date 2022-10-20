# buggy script zone

## templates folder 
The templates folder contains the template you'll want to copy paste into the draw.io insert -> advanced -> from csv.

## Nmap-Scan-To-CSV folder
This folder contains the actual script to use to make the scan.csv you'll copy in under the template within the draw.io insert -> advanced -> from csv window.



## Usage
1. Copy the template example into draw.io insert -> advanced -> from csv.
2. Take your nmap scan (in xml output) and copy paste it into the Nmap-Scan-To-CSV folder.
3. With Nmap-Scan-To-CSV as your working directory run `python3 nmap_xml_parser.py -f nmap_scan.xml -fl` This will yield scan.csv
4. Open Scan.csv and copy paste it in under the draw.io template I provided.
5. click submit(?) idr and it will fill the draw.io canvas with all the hosts, hover over them to see open ports and network services.




## I'm Sorry there's not a full one-click script, you can definitely wrap it with probably five line bash script but I'm friggin busy. 
