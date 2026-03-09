## [Download MorePowerTool 1.3.8](https://github.com/MorePowerTool/MorePowerTool/releases)

1.3.8 – Ability to save registry file, Debug Overrides and Throttler Control

New curve options have been added. Of course we would be very happy about a feedback in the forum about the use of this new function! The More PowerTool (MPT) has been also revised once again for the detection of the installed graphics adapters (keyword Unicode) and also detects different variants of the driver entries. In case of doubt, the VGA Devive Manager (freeware, last page) also helps with the detection of the most current entry and the removal of superfluous entries.

The MPT now also supports the Radeon RX 6500 and RX 6400 with different SPPT . Besides helpful defaults for the power budget and various voltages, the tool also allows improvements in memory settings and other areas as usual, which AMD’s Wattman unfortunately does not offer. We are working on a steady expansion and look forward to Navi 3x as well!

![mpt](https://github.com/user-attachments/assets/2fa78350-e20e-4104-9458-2fc93bd863f4)

## What is MorePowerTool?

MorePowerTool - is a utility designed to help you squeeze out as much performance as possible while overclocking your graphics card. MorePowerTool is unofficial overclocking software not authorized by AMD. This means that you use it at your own risk.

## Supported GPUs:

Currently, MPT works with all released Navi maps, with the SPPT (SoftPowerPlayTables) in the registry extremely slowing down or artificially restricting the drivers. The current version of RBE (Red BIOS Editor) allows writing all MPT modifications directly to the BIOS of the RX 5700, 5700 XT (X) and RX 5600 XT and saving this BIOS as a flashable file. However, at present, only the only adapted version of the ATI Flash Tool allows flashing the BIOS created in this way in the RX 5700 and RX 5700 XT (X).

### DISCLAIMER – BE SURE TO READ!

- All procedures described below represent a massive intervention in the regulation of the graphics card as well as its software (BIOS)! The RBE and the MPT are used exclusively at the user’s own risk and under his complete responsibility and may only be used by experienced users for pure evaluation purposes! Only those who agree to the following terms and conditions may download this software.
- The publication igor’sLAB is not the author or commercial distributor of this software and therefore cannot assume any liability for the software, its use and the possible consequences of improper use. This also applies to possible program incompatibilities or data loss. 
- Whoever uses these tools, such as the RBE or the MPT, already fully agrees to these conditions when downloading and waives any claims arising from the consequences of the use.
- Permanent operation of the components with values not intended by the manufacturer can lead to irreparable damage! The protection functions (shutdown limits) are all still enabled, which minimizes the risk somewhat, but components, such as the GPU, the SOC, the memory or the voltage converters can still suffer unforeseen damage, of course!
- The software linked here in the article is a purely experimental intervention in the system and not intended with all settings for 24/7 use in production systems!
- The higher voltages that are now possible may damage or destroy the modified hardware in the short or long term.
- The software accesses settings of service or third-party programs, especially those of AMD Wattman. These data may be copyrighted materials of their authors.
- For legal reasons, we cannot and are not allowed to offer the Flash software required for flashing the individualized experimental BIOSes created in this way for direct download, but we do provide links to versions that have been reported to us by the community as suitable. But also here we can not take any responsibility for the content of third parties. Anyone who downloads and uses these programs also does so at their own risk and within the scope of the restrictions listed at the beginning.

You are welcome to discuss the newly added functions in the forum, because we have only tightened up and optimized everything from the individual betas and now also included it in the final version. In this regard, we would like to thank the community, which has diligently tested the tool and provided valuable feedback, because testing is not only about putting the functionality through its paces, but also about providing suggestions based on the experience (and wishes) of using the tool on a daily basis.

In this context, we have implemented a frequently expressed wish for a registry file export, so that now all changes just made can also be written to a normal registry file. These can then later, for example, even be exchanged and their contents written back to the registry on any system without a tool simply by double-clicking. It doesn’t really get any simpler than that. To write such a re-file, simply click on the “Save” button

<img width="487" height="500" alt="1 2026-03-09 075821" src="https://github.com/user-attachments/assets/378e92a8-ed56-450b-8fb2-12e8ab888804" />

In the file dialog (“Save as”) you assign the file name in the first step and could now save this template directly as an MPT file. But since we want a registry file, we simply unfold the list box for the file type in the dialog window and select “Registry File”. This now allows the tool to write a reg file that you can reuse as you wish.

### Downloads
We have deliberately removed all previous beta versions, because some versions have been linked to third party sites without our permission and still contain bugs without this being obvious to the end user. This also contributes to the security of every user and we therefore ask for your understanding. This also applies to all the changelogs, which in the end have become completely obsolete with the current, final versions.

Whoever downloads and uses the software linked here automatically accepts the terms of use (“Disclaimer”) listed above! Should an error message occur when downloading or starting our installation programs for the MPT or the RBE, such as messages from inappropriate antivirus software, which our official and licensed installation programs with online downloader recognize as malware, this can be safely ignored. If in doubt, briefly disable the AV software during installation.
