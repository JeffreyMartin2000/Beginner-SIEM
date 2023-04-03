# Beginner-SIEM
My goal in this project is to learn how to create a SIEM and log events using one virtual machine acting as a honeypot. I learned how to create a log and even output geodata from attackers. I used a powershell script open to the public that shows the events and the geodata from attackers through Windows Powershell ISE. 
- <h> Started up a HoneyPot VM, LAW, and SIEM through Microsoft Azure<img width="958" alt="Screenshot 2023-04-02 213234" src="https://user-images.githubusercontent.com/129632324/229392330-fdb770b0-06ba-412d-83a4-0ee5dcfbff85.png">

- <h> RDP to the VM and turned off the windows firewall. Make it easy for atttackers to find the Honeypot.
- <h> I obtained an API key from https://app.ipgeolocation.io/. This allows the script to output the geolocation.  
- <h> Loaded the Powershell script in Windows Powershell ISE [Powershell Script.txt](https://github.com/JeffreyMartin2000/Beginner-SIEM/files/11134176/Powershell.Script.txt)
- <h> I ran the script in Windows Powershell ISE and it looks like the VM honepot had some activity.
[Failed.RDP.Log](https://github.com/JeffreyMartin2000/Beginner-SIEM/files/11134185/Failed.RDP.Log)
<img width="1557" alt="Screenshot 2023-04-02 222651" src="https://user-images.githubusercontent.com/129632324/229397868-381f071d-f28f-4078-b5cf-805dfa45717c.png">
