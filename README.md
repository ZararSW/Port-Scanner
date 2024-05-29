# Port-Scanner
Here is a simple port scanner. Which scans which ports are opened by using system's IP Address.

USAGE
  python3 portscanner.py 
      where you will be redirected to a prompt(line) For entering IP Address of Target.
      Target can be single or Multiple where you have Split them using Comma (,)
      [ip1], [ip2], [ip3] 
      Example: 192.168.1.2, 192.168.1.3, 192.168.1.4

      
  In Second Prompt you will asked how many ports you want to scan?
  The number you specify will be considered as the first ports among 65,535 ports.    
      



NOTE: This is a simple port scanner. So it may not find for FILTERED ports which are monitored by Firewalls or IDS (Intrusion Detection System).
