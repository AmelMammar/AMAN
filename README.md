# Arrival MANager system (called AMAN)
This repository contains the following elements: 
1. The archive of the Event-B modeling of the AMAN system: The Event-B project has been developed and proved under Rodin (Version:  3.8.0-af2f57e1e). To replay the proof obligations, you need to install the following external provers:
  - STM provers
  - PRoB (dis)Prove using ProB 
  - Mono-Lemna prover
2. The requirement document describing the case study.
3. The Event-B models in a pdf format

# Installation instructions
To import the Event-B project under Rodin, you should select the option Import under the menu File and follow these steps:
<img width="240" alt="replay" src="https://github.com/AmelMammar/AMAN/assets/60692373/cacca64e-5c45-4702-a24f-76c9a0440470"> <img width="240" alt="replay" src="https://github.com/AmelMammar/AMAN/assets/60692373/ae275752-1d9d-4341-92a3-857339505d3d">
<img width="240" alt="replay" src="https://github.com/AmelMammar/AMAN/assets/60692373/bd541b70-ee4d-440e-80e7-96fd636ff2ac">

After importing the Zip file STTT2024.zip under the Rodin platform (Version: 3.8.0-af2f57e1e), some proofs may appear as not discharged. So, you should replay all the proofs by a right click as depicted by the following figure:

<img width="240" alt="replay" src="https://github.com/AmelMammar/AMAN/assets/60692373/6fec0a24-f2c7-4900-a46c-759625d2626f">

To discharge the interactive proofs, we have imported the AtelierB provers, ProB Disprover and the SMT provers as depicted by the following figure:

![ProBDis](https://github.com/AmelMammar/SpeedControlSystem/assets/60692373/d97f69ce-3535-4e69-95d0-7dc052816da4)

To install the external provers, users should select the "Install New Software" menu and then select the desired plugin:

![newSoft](https://github.com/AmelMammar/SpeedControlSystem/assets/60692373/4516c199-6901-432c-a281-154cc7ea0698)

![plug](https://github.com/AmelMammar/SpeedControlSystem/assets/60692373/d9a2a063-a9e9-4f47-b1d6-2233e11b9b66)

Fo any question about the models, please contact amel.mammar@telecom-sudparis.eu

