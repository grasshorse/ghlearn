# ghlearn
Grasshorse Learning Material

## [GrasshorseLearn](https://www.youtube.com/channel/UCmsVjwDg8Qc6NQbsAuXeh5A) YouTube Learning Tutorials
# Overview for gh.lan
- [Netstack](https://netstack.org/docs) for [gh.lan](http://gh.lan) detail [gh.2cld.net](http://gh.2cld.net/)
- [youtube - ghlearn Overview 2020](https://youtu.be/NyJJvPpoafA) Digital Infrastructure principles
- [youtube - glearn Netstack 2020](https://youtu.be/fWCfG13xkaQ) Netstack methods at Grasshorse [https://netstack.org/docs/lan/](https://netstack.org/docs/lan/)

----

## [Network](https://netstack.org/docs/lan/network/) via [pfsense](https://pfsense.org) for [ng.gh.lan](http://ng.gh.lan) lan IP [192.168.253.254](http://192.168.253.254) sb 252.1
1. [youtube - ghlearn Network Overview 2020](https://youtu.be/INU3BqtyBZQ)
2. [youtube - ghlearn gh.lan Network Detail](https://youtu.be/HJzfB8MpkJg) detail index [document - ghlanOverviewDetail](http://gh.2cld.net/docs/pfsense/ghlanOverviewDetail)

## [Storage](https://netstack.org/docs/lan/storage/) via [freenas](https://freenas.org) for [sg.gh.lan](http://sg.gh.lan) lan IP [192.168.252.2](http://192.168.252.2)
1. [youtube - ghlearn Storage Gateway Part1 - Media Share](https://youtu.be/QW0eGZtrELs) - [document - Netstack FreeNAS - Setup](https://netstack.org/docs/lan/storage/freenas/setup)
2. [youtube - ghlearn Storage Gateway Part2 - Create DataSet](https://youtu.be/kt5hubC1tX0) - [document - Netstack FreeNAS - Setup](https://netstack.org/docs/lan/storage/freenas/setup)
3. [youtube - ghlearn Storage Gateway Part3 - TestStorage](https://youtu.be/i1UxlGZPs1c)

## [Compute](https://netstack.org/docs/lan/compute/) via [xcp-ng](https://xcp-ng.org) for [cg.gh.lan](http://cg.gh.lan) lan IP [192.168.252.3](http://192.168.252.3)
1. [tbd youtube - compute - cg.gh.lan]()

---

## [Document](https://netstack.org/docs/lan/document/) via [gitlab](gitlab.org) for [dg.gh.lan](http://dg.gh.lan) lan IP [192.168.252.9](http://192.168.252.9)
1. [tbd youtube - document - dg.gh.lan]()

## [Backup](https://netstack.org/docs/lan/backup/)
1. [tbd youtube - backup - bg.gh.lan]()

<!-- Grasshorse Learning youtube maintained by ghadmin - horseoff -->

### References
- [Grasshorse Main Site](https://www.grasshorse.com/)
- [ghlearn github](https://github.com/grasshorse/ghlearn)
- [ghlearn netstack site](http://ghlearn.2cld.net/) repo [https://github.com/grasshorse/ghlearn](https://github.com/grasshorse/ghlearn)
- [gh netstack site](http://gh.2cld.net/) repo [https://github.com/2cld/gh](https://github.com/2cld/gh)
<!-- ghlearn maintained by ghadmin - horseoff -->
<!-- gh maintained by admin - 2cld -->

----
----
Pulled from 2cld/gh/docs/README.md
----
----
# gh docs
Documents for Grasshorse Workflows

## Video Learning [GrasshorseLearn](https://www.youtube.com/channel/UCmsVjwDg8Qc6NQbsAuXeh5A)
- Grasshorse Learning [youtube - Overview](https://youtu.be/NyJJvPpoafA)
- Grasshorse Netstack [youtube - Netstack Overview](https://youtu.be/fWCfG13xkaQ) [netstack.org](https://netstack.org/docs/)
- Grasshorse Network Overview [youtube - network gh.lan](https://youtu.be/INU3BqtyBZQ)

### Grasshorse Netstack 3 service gateways
- Grasshorse Network Gateway Overview [youtube - network - ng.gh.lan](https://youtu.be/HJzfB8MpkJg) detail [document - pfsense - ng.gh.lan](./pfsense/ghlanOverviewDetail)
- Grasshorse Storage Gateway Overview [tbd youtube - storage - sg.gh.lan]()
- Grasshorse Compute Gateway Overview [tbd youtube - compute - cg.gh.lan]()

### Grasshorse Network Gateway configuration with [pfsense.org](https://www.pfsense.org/)
- Grasshorse pfsense [document - pfsense](./pfsense/)
- Grasshorse [youtube - network - ng.gh.lan](https://youtu.be/HJzfB8MpkJg) detail [document - pfsense - ng.gh.lan](./pfsense/ghlanOverviewDetail)
- Grasshorse network setup [document - Netstack pfSense - Setup](https://netstack.org/docs/lan/network/pfsense/setup)
- Grasshorse network maintainace - tbd
- Grasshorse network disaster recovery (dr) - tbd

### Grasshorse Storage Gateway configuration with [freenas.org](https://www.freenas.org/) 
- Grasshorse storage - freenas [document - freenas](./freeNAS/)
- Grasshorse [tbd youtube - storage - sg.gh.lan]() detail [document - freenas - sg.gh.lan](./freeNAS/ghlanStorageOverviewDetail)
- Grasshorse storage setup [document - Netstack freenas - Setup](https://netstack.org/docs/lan/storage/freenas/setup)
- Grasshorse storage maintainace - tbd
- Grasshorse storage disaster recovery (dr) - tbd

-----
1. Storage Gateway configuration [youtube - Part 1 - Media Share](https://youtu.be/QW0eGZtrELs) setup using [document - Netstack Freenas - Setup](https://netstack.org/docs/lan/storage/freenas/setup)
    1. Pool Setup [local link - Storage/Pools/EditPermissions on catFreeNAS](http://192.168.252.2/ui/storage/pools/id/MediaVolume/dataset/permissions/MediaVolume%2FMedia)
    2. Sharing Setup [local link - Sharing/SMB/Edit on catFreeNAS](http://192.168.252.2/ui/sharing/smb/edit/1)
2. Storage Gateway configuration [youtube - Part 2a - Create a new dataset](https://youtu.be/kt5hubC1tX0) following the [document - Netstack Freenas - Setup - SMB Share](https://github.com/2cld/netstack/blob/master/docs/lan/storage/freenas/setup.md#freenas-smb-share-dataset-configuration)
    1. Check Status of pool [TC 1:49](https://youtu.be/kt5hubC1tX0?t=109)
    2. Add "TestStorage" dataset [TC 3:20](https://youtu.be/kt5hubC1tX0?t=200)
    3. Skip (instructions add "Projects" and "Public" datasets)
    4. Create user/group testuser [TC 5:25](https://youtu.be/kt5hubC1tX0?t=325)
    5. Skip nsprojects
    6. Skip nspubuser
    7. Add TestStorage SMB share [TC 13:20](https://youtu.be/kt5hubC1tX0?t=780) I forgot and had to come back to this later.
    8. Edit ACL on TestStorage [TC 8:52](https://youtu.be/kt5hubC1tX0?t=532)
    9. Skip 
    10. Skip
    11. RESTART SMB Service [TC 10:13](https://youtu.be/kt5hubC1tX0?t=613)
    12. Verify TestStorge SMB share via File Browse 
    13. Windows 10 SMB Share browse [TC 10:42](https://youtu.be/kt5hubC1tX0?t=642) then after SMB share [TC 15:27](https://youtu.be/kt5hubC1tX0?t=927)
        - Open File Exploer
        - Type \192.168.252.2 into path bar
        - Windows should request credintials (input testuser and pw)
    14. Windows 10 Map Network Drive [TC 11:00](https://youtu.be/i1UxlGZPs1c?t=660)
        - Right click on “This PC”
        - Select “Map network drive…”
        - Select Drive to map: “Z:”
        - Folder: “\sg.ns.lan” (or \192.168.128.4)
        - Reconnect at sign-in: checked (yes)
        - Connect using different credentials: checked (yes)
        - Enter credentials: nsprouser - thepasswordyouset
        - Finish
    15. The END - You should have access I ran out of time on the video to show the auth logic
3. Storage Gateway Review [youtube - Part2b - TestStorage Review](https://youtu.be/i1UxlGZPs1c) 
    1. Explain Remote Setup [TC 1:43](https://youtu.be/i1UxlGZPs1c?t=103) with [zerotier.com](), [remotedesktop.google.com]() and Microsoft Remote Desktop.
    2. Explain IP Address Mappings of Network, Storage and Compute Gateways [TC 4:30](https://youtu.be/i1UxlGZPs1c?t=270) [document - NetStack - LAN](https://netstack.org/docs/lan/)
    3. Windows 10 Map Network Drive Fail again [TC 11:00](https://youtu.be/i1UxlGZPs1c?t=660)
    4. Windows 10 Map Network Drive with user Fail [TC 13:35](https://youtu.be/i1UxlGZPs1c?t=815)
    5. FreeNAS ACL on TestStorage Share [TC 13:48](https://youtu.be/i1UxlGZPs1c?t=828)
    6. FreeNAS Lookup testuser info [TC 14:40](https://youtu.be/i1UxlGZPs1c?t=880)
    7. Windows 10 Map Network Drive with testuser [TC 16:00](https://youtu.be/i1UxlGZPs1c?t=960) but fail due to SMB only ONE user
    8. Explain Pool ACL on Media and why SMB sucks [TC 19:00](https://youtu.be/i1UxlGZPs1c?t=1140)
    9. Start to bitch about gh current setup and why I need to clean house [TC 21:27](https://youtu.be/i1UxlGZPs1c?t=1287)
4. Storage Gateway SMB Client Access
    1. tbd [TC ]()
    1. tbd [TC ]()
    1. tbd [TC ]()
    1. tbd [TC ]()
    1. tbd [TC ]()
    1. tbd [TC ]()
    1. tbd [TC ]()
    1. tbd [TC ]()
    1. tbd [TC ]()
    1. tbd [TC ]()

### Compute Gateway configuration
- Grasshorse compute - xcp-ng [document - xcp-ng](./xcp-ng/)
- Grasshorse [tbd youtube - storage - sg.gh.lan]() detail [document - freenas - sg.gh.lan](./xcp-ng/ghlanComputeOverviewDetail)
- Grasshorse storage setup [document - Netstack xcp-ng - Setup](https://netstack.org/docs/lan/compute/xcp-ng/setup)
- Grasshorse storage maintainace - tbd
- Grasshorse storage disaster recovery (dr) - tbd


- [Data and Backups]()
- [Workstation Setup]()
- [Magma Useage]()
- [Blender]()
- [Render Grid]()

## General
1. Grasshorse [Artist Overview](artistOverview.md)
2. Grasshorse [Artist Workflow](artestWorkflow.md)
3. Grasshorse [rendergrid Overview](overview.html)
4. Grasshorse [rendergrid Workflow](workflow.html)
5. Grasshorse [rendergrid Manage Grid](gridmanage.html)
6. Grasshorse [rendergrid Farm - Shared Storage](gridfarm.html)

## Setup
Grasshorse rendernode bn000template](bn000template.html) setup
Grasshorse rendernode ghrenderService](ghrenderService.html) create

## FIX Notes
- Grasshorse rendernode [blenderCacheBake](blenderCacheBake.html) FIX

