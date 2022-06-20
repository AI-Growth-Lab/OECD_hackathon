Hi guys, how is it going? Could you all maybe give me a hand and do the following:
 
1. Push all your (optimally commented) r/python scripts in the corresponding folder of our github.
2. Push all your important outputs (tables, figures, rendered notebooks) in the output folder
3. Please also write a brief description of what you have done, where the corresponding scripts are to be found, and how to use them. Optimally, push that as a markdown in the output folder.


**Initiatives by themes folder:**
- The policy initiatives are linked based on the common themes.
- The node itself is the policy initiative.
- The edge represents the number of policy initiatives which have more than one theme in the particular year (2016,2017,2021).
- Themes picked for cocreation and knowledge transfer: TH42,TH43,TH47,TH46,TH44,TH41
- Color shows communities which separate policies clearly based on themes, meaning that the majority of the policies have one main theme. 
- The codes for the plot can be found in Katie_STIP_Compass.Rmd under 4.Network viz of Indicators By themes

**Actors network folder:**
- Actor A is connected to Actor B if they both are the target groups of one policy.
- Size of the edge represents number of policy initiatives that target both target groups/actors.
- ECON = Economic actors. FA = Firms by age. FS = Firms by size. GOV = government sectors. INT = intermediaries. REO = Researcher and Education Organization. RST = Researchers, Students, and Teachers.  SOC = Social groups.
- See more categories in Github's data folder > STIP_Survey_Codebook_2021.xlsx > 'TargetGroups' tab
- The codes for the plot can be found in Katie_STIP_Compass.Rmd under 4.Network viz of Indicators By target groups
