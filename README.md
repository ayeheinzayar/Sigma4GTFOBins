# sigma4GTFOBins

Sigma is a generic and open signature format that allows you to describe relevant log events in a straight forward manner. The rule format is very flexible, easy to write and applicable to any type of log file. The main purpose of this project is to provide a structured form in which researchers or analysts can describe their once developed detection methods and make them shareable with others.
  - [Sigma](https://github.com/Neo23x0/sigma)


On the other hand, GTFOBins is a list of Unix binaries that can be abused to get the f****k to break out restricted access from Unix local security restrictions. These bypassing techniques can perform multiple abusive functions such as escalate or maintain elevated privileges, transfer files, spawn bind and reverse shells and facilitate the other post-exploitations tasks.
  - [LOLABS](https://lolbas-project.github.io/) inspired for windows and multiple contributors collaborative in GTFOBins for Unix binaries.
  - [GTFOBins](https://github.com/GTFOBins/GTFOBins.github.io)

Detection of GTFOBins with Sigma rule included in,
  - https://github.com/xheinz22/sigma4GTFOBins/blob/master/lnx_shell_gtfobins_commands_1.yml
  - https://github.com/xheinz22/sigma4GTFOBins/blob/master/lnx_shell_gtfobins_commands_2.yml
  - https://github.com/z3riz/Sigma4GTFOBins/blob/master/lnx_shell_gtfobins_commands_3.yml
  - https://github.com/xheinz22/sigma4GTFOBins/blob/master/lnx_shell_gtfobins_command.yml
  - https://github.com/xheinz22/sigma4GTFOBins/blob/master/lnx_shell_gtfobins_shell_commands.yml
  
Raw detections with 7 usecases,
  - [BSidesMM 2019 Sample Rules](https://github.com/xheinz22/sigma4GTFOBins/blob/master/lnx_shell_gtfobins_bsidesmm-2019-samples.yml)
  
**This repo contains the Sigma rules to detect GTFOBins which unix binaries will bypass security restrictions.
