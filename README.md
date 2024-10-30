## How to use

- Install Windows in Audit mode (**optionally** with the included Autounattend.xml) into a template VM
- Customize the template VM as you want
- Apply unattend_stage2.xml in audit mode to reseal the image and prepare for cloning
- After cloning, insert CD containing a second Autounattend.xml; Sysprep will take it up and apply it automatically
