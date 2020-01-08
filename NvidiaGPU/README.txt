To update links, go to

https://redirectiontool.trafficmanager.net/am/redirection/home

switch domain to go.microsoft.com,

and modify the links for 

2016/10
"Type" : "GRID",
    "FwLink" : "https://go.microsoft.com/fwlink/?linkid=874181"

2012R2
"Type" : "GRID",
    "FwLink" : "https://go.microsoft.com/fwlink/?linkid=874184"

Linux  (both ubuntu and rhel/centos)
 "Type" : "GRID",
     "FwLink" : "https://go.microsoft.com/fwlink/?linkid=874272"
 "Type" : "GRID",
     "FwLink" : "https://go.microsoft.com/fwlink/?linkid=874272"

Then change the appropriate stanzas within the GRID sections of resources.json to match
and merge to master.
