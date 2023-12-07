# VALID Validated Avatar Library

We present VALID, a validated avatar library for inclusivity and diversity created by the University of Central Florida and Google. The library features 210 fully rigged 3D avatars representing the seven ethnicities recommended by U.S. Census Bureau research. The avatars are freely available and were modeled through an iterative design process with the participation of the representatives of each ethnicity. This library is released together with validated labels for each avatar's perceived ethnicity and gender, as provided through surveying of 132 participants from 33 countries. 
The library features avatars of American Indian and Alaskan Native (AIAN), Asian, Black, Hispanic, Middle Eastern and North African (MENA) Native Hawaiian and Pacific Islander (NHPI), and White ethnicities, providing a diverse selection for researchers to use in their studies. The **perceptually validated**  labels can facilitate research on the impact of avatar race, and researchers can choose to use the labels for studies aimed at individuals from different racial backgrounds or same-race labels for specific study populations. Avatars were created using a process that combined data-driven average facial features with extensive collaboration with representative stakeholders from each racial group. 


**NOTE: Further updates of this library will be available at the XRT Lab from University of Central Florida:
https://github.com/xrtlab/Validated-Avatar-Library-for-Inclusion-and-Diversity---VALID/**


The perception of each avatar's race and gender were evaluated on a global scale. We conducted a large online study ($n=132$) with participants from 33 countries, self-identifying as one of the seven represented races, to determine how the avatars are perceived. The statistically validated labels for each avatar can be found in the chart below, and also in the paper. Please note that different communities may perceive the race of an avatar differently, particularly within community (same-race). 

Additional metadata, including agreement rates disaggregated by all participant backgrounds, are found in the Metadata folder. As well as the summary of Validated-Labels https://github.com/google/valid-avatar-library/blob/main/Metadata/Agreement-Rates/Validated-Labels.csv Please read the paper for more detailed information. 


If you are using the library in your work, please cite the [paper](https://www.frontiersin.org/articles/10.3389/frvir.2023.1248915/full).

    @article{do2023,
    AUTHOR={Do, Tiffany D. and Zelenty, Steve and Gonzalez-Franco, Mar and McMahan, Ryan P.},   
    TITLE={VALID: a perceptually validated Virtual Avatar Library for Inclusion and Diversity},      
    JOURNAL={Frontiers in Virtual Reality},      
    VOLUME={4},           
    YEAR={2023},       
    URL={https://www.frontiersin.org/articles/10.3389/frvir.2023.1248915},       
    DOI={10.3389/frvir.2023.1248915},      
    ISSN={2673-4192},    
    ABSTRACT={As consumer adoption of immersive technologies grows, virtual avatars will play a prominent role in the future of social computing. However, as people begin to interact more frequently through virtual avatars, it is important to ensure that the research community has validated tools to evaluate the effects and consequences of such technologies. We present the first iteration of a new, freely available 3D avatar library called the Virtual Avatar Library for Inclusion and Diversity (VALID), which includes 210 fully rigged avatars with a focus on advancing racial diversity and inclusion. We also provide a detailed process for creating, iterating, and validating avatars of diversity. Through a large online study (n = 132) with participants from 33 countries, we provide statistically validated labels for each avatar’s perceived race and gender. Through our validation study, we also advance knowledge pertaining to the perception of an avatar’s race. In particular, we found that avatars of some races were more accurately identified by participants of the same race.}


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
