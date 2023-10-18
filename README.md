# VALID Validated Avatar Library

The UCF and Google *Validated Avatar Library for Inclusion and Diversity (VALID)* consists of 210 fully rigged and **perceptually validated** virtual avatars designed to advance diversity and inclusion. The library features avatars of seven different races  (American Indian and Alaskan Native (AIAN), Asian, Black, Hispanic, Middle Eastern and North African (MENA) Native Hawaiian and Pacific Islander (NHPI), and White), providing a diverse selection for researchers to use in their studies. The validated labels can facilitate research on the impact of avatar race, and researchers can choose to use the labels for studies aimed at individuals from different racial backgrounds or same-race labels for specific study populations. Avatars were created using a process that combined data-driven average facial features with extensive collaboration with representative stakeholders from each racial group. 


NOTE: Further updates of this library will be available at the XRT Lab from University of Central Florida:
https://github.com/xrtlab/Validated-Avatar-Library-for-Inclusion-and-Diversity---VALID/


The perception of each avatar's race and gender were evaluated on a global scale. We conducted a large online study ($n=132$) with participants from 33 countries, self-identifying as one of the seven represented races, to determine how the avatars are perceived. The statistically validated labels for each avatar can be found in the chart below, and also in the paper. Please note that different communities may perceive the race of an avatar differently, particularly within community (same-race). 

Additional metadata, including agreement rates disaggregated by all participant backgrounds, are found in the Metadata folder. Please read the paper for more detailed information. 

If you are using the library in your work, please cite the preprint (https://doi.org/10.48550/arXiv.2309.10902): 

    @misc{do2023valid,
      title={VALID: A perceptually validated Virtual Avatar Library for Inclusion and Diversity}, 
      author={Tiffany D. Do and Steve Zelenty and Mar Gonzalez-Franco and Ryan P. McMahan},
      year={2023},
      eprint={2309.10902},
      archivePrefix={arXiv},
      primaryClass={cs.HC},
      doi={10.48550/arXiv.2309.10902}
    }


## Setup
Avatars are available in the FBX format and are ready to use in most game engines, such as Unity and Unreal.  All avatars have embedded textures and materials. Unity usually does not extract them automatically. Below are instructions on importing and animating sample avatars: 

1. Import the avatar into your Assets folder
2. Using the Inspector, go to the "Materials" tab of the asset's Import Settings 
3. Click "Extract textures" and "Extract Materials"
4. Go to the"Rig" tab of the asset's Import Settings
5. Select Animation Type: Humanoid 
6. Select "Create From This Model" 

Avatars should now be ready to animate.

NOTE: 
If you are using an avatar with long hair, you need to apply the hair shader in /HairShader to the wig game object to turn off mesh culling. By default, Unity culls two-sided meshes. 

## Contributors
*All authors* contributed to the conception and design of the library. Below, the authors additionally contributed the following: 
 - **Tiffany D. Do  (University of Central Florida)** - Modeled the initial 210 avatars, conducted design interviews, organized the repository, designed and conducted the validation study, conducted statistical analysis, and created visualizations
 - **Steve Zelenty (University of Central Florida)** - Conducted design interviews
 - **Mar Gonzalez-Franco (Google)** - Advised the project and created visualizations 
 - **Ryan P. McMahan (University of Central Florida)** - Advised the project, designed and conducted the validation study, and created visualizations 



This template uses the Apache license, as is Google's default.  See the
documentation for instructions on using alternate license.
