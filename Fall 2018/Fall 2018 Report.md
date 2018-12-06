# StaRS Filter Theory, Fall 2018
#### Barbara Oramah, Lainey Reed, Emily Spiek
##### November 30th, 2018

### Abstract

Stacked Rapid Sand Filtration is the last stage in an AguaClara treatment plant. The filters are used to further reduce the turbidity of water to meet EPA standards of 0.3 NTU or less. This semester, the Stacked Rapid Sand (StaRS) Filter Theory team constructed 3 StaRS filters with sand of varying sizes. These filters will be used in future experiments to analyze how specific parameters, including sand grain size and coagulant dosage, affect filter performance. The StaRS team has spent the semester compiling a manual so that future teams can run experiments and reconstruct experimental filters if necessary.

[**Jonathan: Very nice abstract! Also, please include a Table of Contents. I started it for you below**]
### Table of Contents

- [Introduction](#Introduction)

### Introduction
Sand filtration has been used since ancient times. In AguaClara water treatment plants, a common type of sand filtration is used - rapid (gravity) sand filtration. This filtration method requires the use of a chemical coagulant, polyaluminum chloride (PaCl), to aggregate small particles (flocs) to increase the ease of particle filtration. This filter design has proven to reduce turbidity below 0.3 NTU, which meets the EPA standards. Experimentation performed on the model sand filter in the lab and the sand filters in the water treatment plants built in Honduras have proved the effectiveness of StaRS filters.

The goal of the StaRS [**Filter Theory**] sub-team is to develop a mathematical model describing the filter performance. To do so, the relevant filtration parameters must be determined through experimentation. These parameters can then be used to optimize filter performance for minimum effluent turbidity and maximum failure time. The filter parameters that were investigated in previous years include coagulant dosage, influent flow rate, influent turbidity, backwash duration and floc size. The Fall 2018 team built 3 new StaRs filters, each of which contains 1 layer of sand. The sand grain size within each filter differs. Next semester, the team will test the filters and analyze performance. The main goal of the future teams will be to investigate the effects of variation in sand grain size and to create a corresponding mathematical model.

Although the team focused the entire semester on fabrication and did not conduct experiments, the team developed a hypothesis for how sand grain size affects filter performance. The team hypothesized that the filter with the largest sand grains ~~will~~ [**would**] have the shortest failure time. Failure time corresponds to the time taken for the filter performance efficiency to decrease drastically. The team expects that flocs will be deposited along the sand pores at the same rate in every filter because the rate of the influent stream will be held constant. However, the volume of the filter will be held constant, so when sand grain size increases, the amount [**number, maybe?**] of sand grain pores in the filter decreases. Ultimately, this means that for a filter filled with larger sand grains, there will be fewer sand pores active at one time. This is demonstrated in Figure 1. This is predicted to cause the active filtration zone to move through the filter faster.

[**Jonathan: Before**]
<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/Fall%202018/Images/sand%20grain%20diagram.jpg" heights=720 width=1260>

[**After**]
<p style="text-align: center;">
<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/Fall%202018/Images/sand%20grain%20diagram.jpg?raw=true" heights=720 width=1260>
<b>Figure 1 </b>: demonstrates that when sand grain sizes are larger, there are fewer pores in the filter.
</p>

[**Jonathan: I could not see Figure 1. I corrected the mistake for you guys this time; please correct them for the rest of the figures. Make sure to copy 'image address' which adds the extra end after .jpg**]

The results of these experiments could hold major significance for filtration methods of AguaClara and other water filtration plants. If it is discovered that sand grain size does impact filter performance, the team will be able to determine the sand grain size that optimizes effluent turbidity and failure time. This parameter could potentially hold major significance when creating a mathematical model that accurately describes StaRS filters. Moreover, using the optimum size of sand in future filters could increase filter duration; filters would need to be backwashed less often, saving the AguaClara plants both time and resources.


### Literature Review

The team conducted a thorough literature review to understand the existing research on sand filtration. The team especially looked into how these other experiments took into account different parameters, including grain size, in their mathematical models.

Many models of filtration include reentrainment, the process by which precipitated aggregate materials get unstuck from pores due to shear force from water and move through the filter, eventually sticking elsewhere ([Przekop & Gradon, 2016](https://doi.org/10.1515/cpe-2016-0033), [Tien et al., 1979](https://doi.org/10.1002/aic.690250302), [Yao et al., 1971](https://doi.org/10.1021/es60058a005)). The team will not be taking into account reentrainment, and instead will be assuming that particles either permanently bind to sand particles or completely pass through the system. Once experimentation begins, the team will be searching to see the impact of neglecting reentrainment in our experiment throughout the semester.

One of the team's goals in varying sand grain size is to understand how the grain size influences ripening time and failure time. Ripening time ~~is~~ [**it**] the time is takes for the filter to reach maximum particle removal efficiency. Failure time is the time it takes for the filter to fail, measured by a dramatic increase in effluent turbidity. Other studies have found that pore size has an effect on ripening time, with smaller pores on a filter leading to longer ripening times ([Przekop & Gradon, 2016](https://doi.org/10.1515/cpe-2016-0033)). This study has shown that physical properties within the filter can affect its efficiency. In future semesters, the property that the team will change is sand grain size.

Investigations into grain sizes of glass beads have found that they have less of an effect compared to changes in coagulant doses ([Chuang & Li, 1997](https://doi.org/10.1016/S1383-5866(97)00048-8)). Larger doses of coagulant lead to a shorter ripening time, but also clogged pores at a faster rate and increased the shear force in unclogged pores. However, grain size can have effects based on the coagulant and flocculant dosages. In this study, a flocculant, separate from the coagulant was used to further increase flocculation. The researchers found that larger grains in addition to flocculant and higher coagulant dosages reduced the rate of pore clogging. They hypothesized that it was because larger aggregates were able to pass through the pores between the larger glass beads. In the future, the team will be varying both coagulant dosage and grain size, as in this study. However, sand will be used as a filter material, as is used in AguaClara plants. Furthermore, AguaClara plants only use PaCl, a coagulant, not both a coagulant and a flocculant. The flocculant increased the extent to which the effect was observed within the study. The team would expect to see less of the reduction in clogging that was seen in this study.


### Previous Works
The main goal for Fall 2018 was to reconstruct the apparatus for future experimentation. The team analyzed StaRS reports from pasts years, such as Fall 2015, for fabrication methods and calculations used. The team constructed three 1-layer sand filters and fabricated brass inlet and outlet pipes. The prior filter used by the StaRS subteam was a 2-layer sand filter, and the height of the sand bed column was 40 cm. There was an extra 30% included to account for the fluidization of the sand bed during backwash. The height of the entire filter was then about 60 cm, and it had one inlet stream and two outlet streams. The inlet stream had a rectangular orifice for water to infuse within the filter. The area of the orifice was determined using Equation 1. The outlet streams were located equidistantly above and below the inlet. The Fall 2013 StaRS team was the first team to implement this design for the filter and it has not been drastically remodeled until this semester.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/Fall%202018/Images/orifice%20eqn.jpg?raw=true" heights=70 width=418>

$$ \frac{A_{hole}}{A_{column}} = \frac{A_{inlet \space system}}{A_{filter}} $$
**Equation 1:** The relationship used to determine orifice area

[**Jonathan: It may be better to just write out this equation in LaTeX form. Since this is your only equation, I just wrote it out for you. You can decide which way you like better. Also I suggest centering this image and caption. If you use my equation, you may want to add to the paragraph about  what $A_{hole}$ means and so on to make it easy for readers to follow along.**]

The Fall 2018 used calculations from previous teams' reports, scaling the values down to be compatible with the new 1-layer filters.

Previous StaRS Filter Theory teams focused on combining information from sand bed research with the effects of microscopic level physics and macroscopic filter performance. A visual model of constrictions between the sand grains was developed by previous StaRS Filter Theory teams from the conclusions of several experimental runs. Once the constriction model was developed, the StaRS teams moved to varying coagulant dosage, which was hypothesized to affect filter performance.

The Fall 2017 team systematically varied coagulant dosages to determine its effect on filter performance. The team ran the set of experiments twice. The first set was done by gradually increasing PACl dosage, labeled ‘step up’. The second set was obtained by decreasing the PACl dosages, labeled ‘step down’. They concluded from these experiments that lower coagulant dosages prolonged failure time compared to higher dosages. They also found out that backwashing the filter between filter runs for 20 minutes allowed for more consistent results.

The Spring 2018 team focused primarily on changing the density of floc particles and varying coagulant dosages. Varying coagulant dosages affects the size of the floc particles that enter the filter. By measuring the different floc sizes, the team was able to deduce that the size of flocs did affect the performance of the filter. Large flocs, caused by higher coagulant dosages, proved to make the performance worse.

The findings of the previous StaRS teams are crucial for understanding filter performance. Furthermore, these findings allowed the current team to know which variables to test to develop efficient filters.


### Methods


#### Experimental Apparatus

##### Schematic
The schematic below shows the apparatus used by the StaRS Filter Theory Team during Fall 2018.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/Fall%202018/Images/Apparatus%20Design.jpg" heights=540 width=960>

**Figure 2:** The schematic used by the StaRS Filter Theory Team during Spring 2018.

[**Jonathan: Again, cannot see this image**]

Clean water enters the system and is then mixed with a clay-water solution. This mixture enters the influent turbidimeter, where the turbidity is set in ProCoDa to be 5 NTU. This turbidity is meant to mimic the turbidity of the sedimentation effluent stream before it enters filtration in an AguaClara plant.

The stream then enters the contact chamber, where it comes into first contact with the PaCl (coagulant) solution. This is when flocs begin to form. The stream flows into the flocculator, where flocs grow in size. The stream then splits into 3 separate streams, and each stream enters a filter.

The sand grain size in each filter varies. Filter 1, filter 2, and filter 3 contain sand grains that are in the ranges of 35-45 mesh size, 25-35 mesh size, and 18-25 mesh size, respectively. Each filter is a 1-layer StaRS filter. The stream flows through the filter, and flocs are separated from water by the sand grains via adhesion. There are pressure sensors present between the influent and effluent stream for each of the filters to measure head loss. The team will determine if there is a relationship between head loss and sand grain size in future experiments.

The water streams exit their respective filters and enter effluent turbidimeters. By having 3 separate effluent turbidimeters, the team will be able to compare the effluent turbidity and failure time for each filter. The stream then exits the system.

There is a backwash system that pushes water up through the filter columns and out the top to clean the filters by removing the adhered flocs.


### Manual
This semester, the StaRS team focused on fabricating three new filters. Each filter holds specific sand grain sizes: .354-.5 mm diameter sand in Filter 1, .5-.707 mm diameter sand in Filter 2, and .707-1 mm diameter sand in diameter in Filter 3.


#### Obtaining Sand

The StaRs Team sieved sand to the desired diameters. The team decided to sieve sand found in the lab, rather than buy pre-sieved sand. The team met with Philip Carubia of the Cornell Center for Materials Research to sift sand to the three size ranges (18-25, 25-35, and 35-45 mesh sizes). Approximately 110 cm^3 of each sand size was required to fill the column to slightly above the inlet pipe, located at 21 cm. The team used a combination of hand sieves from the Bovay Lab to sieve the sand into the proper sizes. Future teams looking to sieve sand should contact James Strait of the Bovay Lab for sieve use.


#### Conducting Porosity Tests

The team conducted porosity tests on the different sand grain sizes (Table 1). To conduct this test, the team filled a graduated cylinder with sand and measured the volume of the sand column. The team then poured water into the graduated cylinder. The water distributed itself in the sand pores. The team stopped pouring water when it began to pool at the top. The porosity was calculated using the relationship Porosity = (Volume water added)/(Total volume of sand column). The team conducted 2 trials for each sand grain size and averaged the calculated porosity values together. Knowing porosity will help the team in the future to understand the material properties of the sand. These values will also be used in future calculations for water flow rate in the filters.


| Sand Grain Size (mm)  | Average Porosity  |
| --- | --- |
| 0.707-1 | 0.37  |
| 0.50-0.707 |  0.33 |
| 0.354-0.5 | 0.33 |

**Table 1:** The calculated porosity of each sand grain size.

The team faced an issue with air bubbles when conducting the porosity tests. When the water was poured into the column with the smallest sand grain size, air bubbles began to form in the middle of the column. These air bubbles most likely affected the accuracy of the calculated values. The formation of air bubbles in the sand column may be an issue future teams face in conducting experiments with smaller sand grain sizes.


#### Fabrication Details

The StaRS team received fabrication training in order to have a holistic and safe understanding of the power tools when fabricating the three new filters. Each filter was constructed identically, with one influent stream and one effluent stream. In previous years, the team’s filter was composed of two stacked filter layers (total sand depth was 40 cm), but the team this year decided that one layer (total sand depth 20 cm) would be equally effective for the purposes of the research.

When determining the height of the new filters, the backwash expansion needed to considered. During backwash, the sand in a StaRS filter is pushed up by the water and it expands throughout the column. Previous teams determined the sand rises to about 1.5 times its original height. [**Jonathan: Introduce this equation. Like "The following equation ___"**]

(height of sand column) * 1.5 = (height of sand during backwash expansion)

[**Jonathan: please write this out as an equation. See Eq 1 for an example. You may want to call them like $h_{sand}$ and $h_{expansion}$ or something like that.**]

As a result, the team determined it was necessary that the height of the new filters be at least 30 cm. To stay on the safe side, the team  constructed the three filters at a height of 40cm.

The team also needed to determine the orifice size for the inlet pipes into the filters. Previous teams determined this size using equation 1. However, the reasoning behind the equation and the influence of orifice size on the filter has yet to be fully investigated. Therefore, the team chose to use the same orifice dimensions as the inlet pipe for the previous apparatus, which is 0.8 cm x 2.25 cm, located 0.2 cm from the end of the inlet pipe (Fig. 4).


#### Materials
- Transparent PVC pipe of inner diameter 1 in. and $\geq$120 cm in length (Obtained from AguaClara Lab)
- 3x PVC Pipe caps of inner diameter 1.32 in. (Obtained from AguaClara Lab)
- Brass (or copper) pipe of outer diameter 0.50 in., inner diameter 0.436 in., and length >120 cm. The team used brass for the apparatus, obtained from McMaster-Carr, Part Number: 5157K133.
- 3x unthreaded push-to-connect reducers, 1/2" to 3/8"
- 3x threaded push-to-connect reducers, 1/2" to 3/8"
- Sand sieved to three size ranges: .354-.5 mm (between  35-45 mesh size), .5-.707 mm (25-35 mesh size), and .707-1 mm (18-25 mesh size) in diameter. Approximately 110 cm^3 of each type of sand was required (Obtained from AguaClara Lab and Sieved in Cornell Center for Materials Research)
- 3x turbidimeters (Obtained from the AguaClara lab)
- 3x pressure sensors (Obtained from the AguaClara Lab)
- Teflon Tape
- 3x 1" LASCOtite Adapter MPT x Gasket, Part Number: 21305
- 3x LASCO Sch80 Reducer Bushing (Flush Style) MPT x FPT, Part Number: 839128
- 3x 2" McMaster-Carr Straight Adaptor with Hex Body, Part Number: 4596K57
- 3x Push-to-Connect Fitting for Drinking Water, Straight Adapter, for 1/4" Tube OD x 1/8 BSPT Male, Part Number: 5104K15
- Wire mesh


#### Tool List
- Sawzall or Band Saw
- Drill Press
- Hand Drill
- 9/16 in. drill bit
- 3/8 in. tap
- 1/2 in. drill built
- .5050" ream


#### Procedure
1. Using the Sawzall and band saw, the team cut the PVC pipe into three 40 cm long pieces. These pieces became the three filters.

2. The team drilled a hole for the inlet pipe using the drill press and the 9/16 in. drill bit. The bottom of the hole was approximately 21 cm from the bottom of the PVC pipe. The team then used a 3/8 inch tap to tap the holes.

3. To create closed containers, the team attached the PVC caps to the bottom of each filter using primer and cement glue. The glue was left to dry for several days.

4. The team repeated step 2 and drilled holes for the outlet pipes at the bottom of the filters. The center of the outlet hole is located about 1.5 cm from the bottom of the filter. The hole was drilled on the opposite side of the filter from the hole constructed in step 2.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/Fall%202018/Images/filter%20models.jpg?raw=true" heights=540 width=960>
**Figure 3:** illustrates the appearance of 1 filter.

5. The team constructed the three inlet pipes out of brass. Each inlet pipe is 10 cm in length. The team cut a rectangular orifice located 0.2 cm from the end of the pipe. The width of the hole is 0.8 cm and the length 2.25 cm. These values are the same as the ones from the apparatus from previous years. This hole is meant to mimic the shape of the inlet pipes in the AguaClara plants in Honduras. The team soldered brass to the end of the pipe that is submerged in the filter (the end nearer to the orifice).

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/Fall%202018/Images/in%20pipe%20model.jpg?raw=true" heights=310 width=927>
**Figure 4:** illustrates the appearance of the inlet pipe.

6. The team also constructed the outlet pipes out of brass. The outlet pipes are 10 cm long and have fine mesh soldered on one end. The team attached the mesh to prevent sand from leaving the filter column with the effluent stream.

Note: The team contacted the CEE machine shop to assist in the construction of the three inlet and three outlet pipes.

7. The team then attached threaded fittings to the 6 pipes so that they could be screwed into the PVC filter. Because the inlet and outlet pipes were larger than the threaded end of the fittings, the team needed to drill into them and expand the opening. The team first disassembled the fitting into its pieces. The team then had help from the CEE machine shop in opening the fittings using a .5" drill bit followed by a .505" ream to widen the hole slightly.

8. The team then slid the reassembled fittings onto the inlet and outlet pipes on the side of the pipe that would extend into the filter. For the inlet pipes, this is the end with the rectangular orifice. The fitting was pushed far enough back for the rectangular orifice to be mostly visible, which allows for the orifice to extend into the filter column when the inlet pipe is attached to it. The fitting should also be pushed enough so the inlet pipe, when screwed in, is close to the opposite side of the pipe. The inlet pipes, when screwed in, also need to face downwards. For the outlet pipes, the team attached the fitting to the end of the pipe with the soldered mesh. The team wrapped the threaded fittings on both the inlet and outlet pipes with Teflon tape to water-proof the system and prevent leaks. On the opposite end of all 6 pipes, the team slid on push-to-connect reducers. The reducers connect the brass pipes to the water tubing.

9. The team constructed the tops of the filters, modeling them after the filter top from the previous team's filter. Before attaching any of the parts, the team wrapped the threaded pieces in Teflon tape to prevent water leaks. The team placed wire mesh inside the Adapter MPT x Gasket part to prevent sand from leaving the filter during backwash. The team then placed this part on the top of the filter and then attached the Straight Adaptor with Hex Body part. The team then attached the Reducer Bushing (Flush Style) MPT x FPT part to the top of the Straight Adaptor and attached the push-to-connect fitting at the top. The top of the filter is necessary, as it will connect the filter to the outlet stream for backwash.

<p align="center">
<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/Fall%202018/Images/top%20of%20filter.JPG?raw=true" heights=336 width=448>
 </p>

**Figure 5:** The top of the filter. There is wire mesh inside the part to prevent sand from leaving the filter.


### Conclusion

The Fall 2018 StaRS team made significant advances in the fabrication of the new apparatus design. In doing so, the team was able to write a detailed manual that clearly highlights how the different sand grain sizes were obtained and how the brass inlet and outlet pipes were fabricated. The issues the StaRS team faced were centralized around understanding classification for sand grain sizes, interpreting previous teams' reports, and understanding how filtration works, as all three members were new to this subteam. Due to confusion over the classification for diameter sizes and mesh sizes, the team had difficulty obtaining sand of the desired sizes. Initially, the team members confused mesh size 35 for being equivalent to 0.35 microns in diameter. The team realized the mistake and decided what range of sand grain size would be appropriate. The team also required clear manuals to assist with the fabrication, but past reports were not as detailed in their calculations as the Fall 2018 team needed. Therefore, the Fall 2018 team attempted to be as detailed as possible in the manual for constructing experimental StaRS Filters. The team also had to spend time at the beginning of the semester learning about how filtration works, which delayed filter fabrication. Due to these factors, the Fall 2018 team did not begin experimentation.

### Future Work
The Fall 2018 StaRS filter team has spent their time predominately focused on fabrication of the new apparatus. The team is eager to continue the research for StaRS filter in the future.

The team will finish connecting the tubing within the apparatus to accommodate for three filters. This task will require three different 3-way connectors to account for the separation of the influent streams, the effluent streams, and the outflow streams above the filter columns. Moreover, two more effluent turbidimeters and a pump will be needed for the apparatus set-up to be complete.

The team will need to write new ProCoDa methods for the new apparatus set-up, taking into account the calculated porosity values. The new apparatus will have a pump for backwash with three heads, instead of one, and it will have three effluent turbidimeters, which will act as variables in the new code. ProCoDa testing will not be able to begin until the new apparatus is complete.

Future teams will be conducting experiments varying the coagulant dosage. between 0.02 and 0.10 mg/L of PaCl. As the Fall 2018 team was unable to conduct any experiments, the team recommends that future teams should vary the coagulant dosage between 0.02 and 0.10 mg/L of PaCl, which is the range that optimizes filter performance as determined by the Spring 2018 team. Knowing how the coagulant dosage impacts filter performance within the three filters will lead to a well-developed mathematical model for StaRS filters in general.

The challenges the Fall 2018 team foresees for future teams is ensuring that ProCoDa operates smoothly when the three filters are connected. Additionally, the team expects there to be water leaks when the apparatus is initially set up. The team also believes that air bubbles may form in the sand column, affecting experimental results.

### Bibliography

Chuang, C.-J., & Li, K.-Y. (1997). Effect of coagulant dosage and grain size on the performance of direct filtration. Separation and Purification Technology, 12(3), 229–241. https://doi.org/10.1016/S1383-5866(97)00048-8

Przekop, R., & Gradoń, L. (2016). Dynamics of particle loading in deep-bed filter. Transport, deposition and reentrainment. Chemical and Process Engineering, 37(3), 405–417. https://doi.org/10.1515/cpe-2016-0033

Tien, C., Turian, R. M., & Pendse, H. (1979). Simulation of the dynamic behavior of deep bed filters. AIChE Journal, 25(3), 385–395. https://doi.org/10.1002/aic.690250302

Kuan-Mu Yao, Mohammad T. Habibian, and Charles R. O'Melia (1971). Water and waste water filtration. Concepts and applications. ACS publications, 5 (11), 1105-1112 https://doi.org/10.1021/es60058a005.
