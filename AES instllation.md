## Content
1. Required Material for AES Installation				
2. Steps of AES Installation 
3. Import License into SMGR and Get License for AES	
- Reference documentation

------------------------------------------------------

## Required Material for AES Installation	
[^Back to content](#content)

> Get the Reference Documentation from Support website
`Support.avaya.com` `Menu "Supported by Product"` `Documents`
```
Product : AES 
version : 8.1.x
Content Type: Release Notes , Overview , Installation, User Guides, Maintenance & Troubleshooting
```

> Deploying Avaya Aura® Application Enablement Services in Virtualized Environment.pdf
- Plan `IP` `Netmask` `Gateway` `DNS` `NTP` `FQDN`   _in file Lab Info.xlsx_
- Hardware
  - CSR3
- Deployment mode
  - Physical machine *Soft-only, iso file* 
  - *VE* (Virtualized Environment) (? what is VE and its components? refer to P9 and P11) *OVA file* 
  - AVP
  - IaaS
- installation file
  - PLDS website *Download the AES OVA file*
- License
  - PLDS website *Download the license file*
  - WebLM (? where is WebLM? `Standalone WebLM` `SGMR` `embeded WebLM server in AES`)
------------------------------------------------------

## Steps of AES Installation	
[^Back to content](#content)

_We are using VE to deploy the AES_
```
- Go go [VMware EXSi webpage](https://sdlabsvcenter02.gl.avaya.com)
- screenshot of the installation                                           
                                         
P01-VEWebpage.png                                                     
P02-OVA file.png                                                    
P03-CR.png   
P04-Review.png                                                   
P05-LA.png                                                            
P06-RESconfig.png                                                     
P07-storage.png                                                       
P08-Network.png                                                       
P09-CT.png                                                            
P09-CT02.png                                                          
P09-CT03.png                                                          
P09-CT04.png                                                          
P09-CT05.png                                                          
P09-CT06.png                                                          
P09-CT07.png                                                          
P09-CT08.png                                                          
P09-CT09.png                                                          
P09-CT10.png                                                          
P10-VMinList.png                                                      
P11-CheckInstallationProgress.png                                     
P11-CIP02.png                                                         
P12-StartAESVM.png                                                    
P13-CLICheckVersion.png                                               
P13-CLILogin.png                                                      
P14-WebLogin.png                                                      
P14-WebLogin02.png                                                    
P14-WebLogin03.png  
```
<img src="https://avaya365-my.sharepoint.com/:i:/g/personal/liu300_avaya_com/EbHIyW8EamRFpyThWHsxHUgBKxwIEx7dkLZEOgQlxhabsw?e=mzwvvv">
## Import License into SMGR and Get License for AES
























### Reference documentation
- Doc Name: Upgrading Avaya Aura® Appliance Virtualization Platform Release 8.1.x
- Local File Name: [2020-03] 升级AVP平台Upgrading Appliance Virtualization Platform.pdf
Content:
```
Avaya Aura® Virtualized Appliance overview 
1) Avaya Aura® Virtualized Appliance is a turnkey solution.
    The Virtualized Appliance offer is different from Avaya Aura® Virtualized Environment
2) Deployment 
Appliance Virtualization Platform overview
1) From Avaya Aura® Release 7.0 and later, 
    Avaya provides the VMware®-based Avaya Aura® Appliance Virtualization Platform to provide virtualization for Avaya Aura® applications. 
    Appliance Virtualization Platform replaces System Platform.
2) Appliance Virtualization Platform is the customized OEM version of VMware® ESXi 6.5. 
3) Hardware
Supported software
4) SDM 
Avaya Aura® Virtualized Appliance
Customer-provided Virtualized Environment solution
Software-Only environment
```
-------------------------------------------------------------------
- Doc Name: Planning for Deploying Avaya Aura® applications Release 8.1.x
- Local Name: [2020-03] 准备工作 Planning For Deploying AAAPPs.pdf


[^Back to content](#content)




