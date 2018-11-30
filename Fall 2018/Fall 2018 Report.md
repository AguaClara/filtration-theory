# StaRS Filter Theory, Fall 2018
#### Barbara Oramah, Lainey Reed, Emily Spiek
##### November 30th, 2018

### Abstract

Stacked Rapid Sand Filtration is the last stage in an AguaClara treatment plant. The filters are used to further reduce the turbidity of water to meet EPA standards of 0.3 NTU or less. In this report, the Stacked Rapid Sand (StaRS) Filter Theory team began to research the effects of different sizes of sand grains. By experimenting with different variables such as coagulant dosage, this will enhance AguaClara's understanding of the ability of flocs to bind to the surface of the sand grains. The StaRS team has spent the semester constructing three new filters and compiling a manual so that future teams can run experiments to investigate pore sizes and further understand how stacked filters work.


### Introduction
Sand filtration has been used since ancient times. In AguaClara water treatment plants, a common type of sand filtration is used - rapid (gravity) sand filtration. This filtration method requires the use of a chemical coagulant, polyaluminum chloride (PaCl), to aggregate small particles (flocs) to increase the ease of particle filtration. This filter design has proven to reduce turbidity below 0.3 NTU, which meets the EPA standards. Experimentation performed on the model sand filter and the sand filters in the water treatment plants built in Honduras have proved the effectiveness of StaRS filters.

The goal of the StaRS sub-team is to develop a mathematical model describing the filter performance. To do so, the relevant filtration parameters must be determined through experimentation. These parameters can then be used to optimize filter performance for effluent turbidity and duration. The filter parameters that were investigated in previous years are coagulant dosage, influent flow rate, influent turbidity, backwash duration and floc size. The main goal of the Fall 2018 team was to investigate variation in sand grain size and create a corresponding mathematical model. The Fall 2018 team built 3 new StaRs filters, each of which contains 1 layer of sand. The sand grain size within each filter differs. Next semester, the team will test the filters and analyze performance.

Although the team focused the entire semester on fabrication and did not conduct experiments, the team The team hypothesizes that the filter with the largest sand grains will have the shortest failure time. Failure time corresponds to the time taken for the filter performance efficiency to decrease drastically. The team expects that flocs will be deposited along the sand pores at the same rate in every filter because the rate of the influent stream will be held constant. However, the volume of the filter will be held constant, so when sand grain size increases, the amount of sand grain pores in the filter decreases. Ultimately, this means that for a filter filled with larger sand grains, there will be fewer sand pores active at one time. This is demonstrated in Figure 1. This is predicted to cause the active filtration zone to move through the filter faster.


<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/Fall%202018/Images/sand%20grain%20diagram.jpg" heights=720 width=1260>

**Figure 1** demonstrates that when sand grain sizes are larger, there are fewer pores in the filter.

The results of these experiments could hold major significance for filtration methods of AguaClara and other water filtration plants. If it is discovered that sand grain size does impact filter performance, the team will be able to determine the sand grain size that optimizes effluent turbidity and failure time. This parameter could potentially hold major significance when creating a mathematical model that accurately describes StaRS filters. Moreover, using the optimum size of sand in future filters could increase filter duration; filters would need to be backwashed less often, saving the AguaClara plants both time and resources.


### Literature Review

The team conducted a thorough literature review to understand the existing research on sand filtration. The team especially looked into how these other experiments took into account different parameters, including grain size, in their mathematical models.

Many models of filtration include reentrainment, the process by which precipitated aggregate materials get unstuck from pores due to shear force from water and move through the filter, eventually sticking elsewhere ([Przekop & Gradon, 2016](https://doi.org/10.1515/cpe-2016-0033), [Tien et al., 1979](https://doi.org/10.1002/aic.690250302), [Yao et al., 1971](https://doi.org/10.1021/es60058a005)). The team will not be taking into account reentrainment, and instead will be assuming that particles either permanently bind to sand particles or completely pass through the system. Once experimentation begins, the team will be searching to see the impact of neglecting reentrainment in our experiment throughout the semester.

One of the team's goals in varying sand grain size is to understand how the grain size influences ripening time and failure time. Ripening time is the time is takes for the filter to reach maximum particle removal efficiency. Failure time is the time it takes for the filter to fail, measured by a dramatic increase in effluent turbidity. Other studies have found that pore size has an effect on ripening time, with smaller pores on a filter leading to longer ripening times ([Przekop & Gradon, 2016](https://doi.org/10.1515/cpe-2016-0033)). This study has shown that physical properties within the filter can affect its efficiency. In the case of this experiment, the property that will be changed is the sand grain size.

Investigations into grain sizes of glass beads have found that they have less of an effect compared to changes in coagulant doses ([Chuang & Li, 1997](https://doi.org/10.1016/S1383-5866(97)00048-8)). Larger doses of coagulant lead to a shorter ripening time, but also clogged pores at a faster rate and increased the shear force in unclogged pores. However, grain size can have effects based on the coagulant and flocculant dosages. In this study, a flocculant, separate from the coagulant was used to further increase flocculation. The researchers found that larger grains in addition to flocculant and higher coagulant dosages reduced the rate of pore clogging. They hypothesized that it was because larger aggregates were able to pass through the pores between the larger glass beads. The team will be varying both coagulant dosage and grain size, as in this study. However, sand will be used as a filter material, as is used in AguaClara plants. Furthermore, AguaClara plants only use PaCl, a coagulant, not both a coagulant and a flocculant. The flocculant increased the extent to which the effect was observed within the study. The team would expect to see less of the reduction in clogging that was seen in this study.


### Previous Works
The main goal for Fall 2018 was to reconstruct the apparatus for future experimentation. The team analyzed StaRS reports from pasts years, such as Fall 2015, for fabrication methods and calculations used. The team constructed three new one layer sand filters, and fabricated the three new sets of brass inlet and outlet pipes. The prior filter used by the StaRS subteam was a two layer sand filter. The sand bed column was 40 cm in length, and there was an extra 30% included to account for the fluidization of the bed during backwash. The length of the entire filter resulted to be 60 cm in length and it had one inlet and two outlet streams. The inlet stream had a rectangular orifice of a calculated area for water to infuse within the filter whilst the outlet streams were from equidistant from the inlet located both above and below. The Fall 2013 StaRS team was the first team to implement this design for the filter and it has not been drastically remodeled until this semester.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/Fall%202018/Images/orifice%20eqn.jpg?raw=true" heights=70 width=418>

**Equation 1** The relationship used to determine orifice area

The Fall 2018 will be centering its calculations from previous teams and scaling them down to be compatible with smaller filters.

The previous models proposed by StaRS Filter Theory teams were focused on combining information from the previous sand bed research and link the effects of microscopic level physics and macroscopic filter performance. A visual model of constrictions found between the sand grains in the filter was developed by previous StaRS Filter Theory teams from the conclusions of several experimental runs until system failure. Filter failure is defined as the moment when effluent turbidity increases sharply. Kuan-mu Yao (1971) stated that the effectiveness of the filter depended on the size of the flocs. Thus, between experimental runs, the coagulant dosage was varied. Varying coagulant dosage changes the size/volume of flocs, which was theorized to affect filter performance.

To further understand the effect of coagulant dosages, the Fall 2017 team systematically varied dosages in filter runs to determine the effect of coagulant dose on filter performance and failure time. The team ran the set of experiments twice. The first set was done by gradually increasing PACl dosage, labeled ‘step up’. The second set was obtained by decreasing the PACl dosages, labeled ‘step down’. They also found out that backwashing the filter between filter runs for 20 minutes allowed for more consistent results. It was concluded from these experiments that at lower coagulant dosages, failure time was prolonged than that for higher coagulant dosages.

The Spring 2018 team focused primarily on changing the density of the particles as well as looking at coagulant dosages. By varying the coagulant dosage this in turn increased the size of the floc particles flowing into the filters. In order to see the effects of the varying constrictions, the Spring 2018 team put red dye in order to visualize the floc sizes flowing into the filter. By measuring the different floc sizes, the team was able to deduce that the size of flocs did affect the performance of the filter. Large coagulant dosages proved to make the performance worse.

The findings of the previous StaRS teams are important as the crucial for how the Fall 2018 team to choose an accurate range for the coagulant dosages that will be use in the future. Furthermore, it allows us to test different variables to find filter efficiency as well as improving the ripening time of the filters.


### Methods


#### Experimental Apparatus

##### Schematic
The schematic below shows the apparatus used by the StaRS Filter Theory Team during Fall 2018.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/Fall%202018/Images/Apparatus%20Design.jpg" heights=540 width=960>

**Figure 2:** The schematic used by the StaRS Filter Theory Team during Spring 2018.

Clean water enters the system and is then mixed with a clay-water solution. This mixture enters the influent turbidimeter, where the turbidity is set in ProCoDa to be 5 NTU. This turbidity is meant to mimic the turbidity of the sedimentation effluent stream before it enters filtration.

The stream then enters the contact chamber, where it comes into first contact with the PaCl (coagulant) solution. This is when flocs begin to form. The stream then enters the flocculator, where flocs grow in size. The stream then splits into 3 separate streams, and each stream enters a filter.

The sand grain size in each filter varies. Filter 1, filter 2, and filter 3 contain sand grains that are in the ranges of .354-.5 mm, .5-.707 mm, and .707-1 mm in diameter, respectively. Each filter is a one-layer StaRS filter. The stream then flows through the filter, and flocs are separated from water. There will be pressure sensors present between the influent and effluent stream for each of the filters. This will be to measure the headloss and note if there will be greater headloss amongst the different sand grain sizes.

The water streams exit their respective filters and then enter effluent turbidimeters. By having 3 separate effluent turbidimeters, the team will be able to compare the turbidity and failure time for each filter. The stream then exits the system.

There is a backwash system that pushes water up through the filters and out the top to remove the filters of flocs.


### Manual
This semester, the StaRS team focused on fabricating three new filters. The filters will hold varying sand grain sizes from .354-.5 mm, .5-.707 mm, and .707-1 mm in diameter. The team will also be attaching a pump after the three filter streams in order to ensure a downward flow.


#### Obtaining Sand

The StaRs Team obtained sand sieved to the desired diameters. Due to confusion over the classification for diameter sizes and mesh sizes, the team had difficulty obtaining sand of the right size. Initially, the team members confused mesh size 35 for being equivalent to 0.35 microns in diameter. The team realized the mistake and decided what range of sand grain size would be appropriate . The team decided to sieve sand found in the lab, rather than buy pre-sieved sand. The team met with Philip Carubia of the Cornell Center for Materials Research to sift sand to the three size ranges (18-25, 25-35, and 35-45 mesh sizes). The team used a combination of hand sieves from the Bovay Lab to sieve the sand into the proper sizes. Future teams looking to sieve sand should contact James Strait of the Bovay Lab for sieve use.


#### Fabrication Details

The StaRS team has undergone further fabrication training in order to have a holistic and safe understanding of the power tools when fabricating the three new filters. Each filter will be constructed identically, with one influent stream and one effluent stream. In previous years, the team’s filter was composed of two stacked filter layers (total sand depth was 40 cm), but the team this year decided that one layer (total sand depth 20 cm) would be equally effective for the purposes of our research.

When determining the height of the new filters, backwash expansion was considered. During backwash, the sand in a StaRs filter is pushed up and it expands throughout the column. Previous teams determined the sand rises to about 1.5 times its original height.

(height of sand) * 1.5 = (height of sand during backwash expansion)

As a result, the team determined it was necessary that the height of the new filters be at least 30 cm. To stay on the safe side, the team planned to construct filters of heights 40 cm.


#### Materials
- Transparent PVC pipe of inner diameter 1 in. and >120 cm in length (Obtained from AguaClara Lab)
- 3 PVC Pipe caps of inner diameter 1.32 in. (Obtained from AguaClara Lab)
- Brass or copper pipe of outer diameter 0.50 in., inner diameter 0.436 in., and length >120 cm. (Obtained from McMaster-Carr)
- 6 Push-to-connect reducers, 1/2" to 3/8"
- Sand sieved to three size ranges: .354-.5 mm (between  35-45 mesh size), .5-.707 mm (25-35 mesh size), and .707-1 mm (18-25 mesh size) in diameter. (Obtained from AguaClara Lab and Sieved in Cornell Center for Materials Research)
- Three turbidimeters (Obtained from the AguaClara lab)
- Three pressure sensors (Obtained from the AguaClara Lab)
- Teflon Tape

##### Materials for Top of Filter (x3 each)
- 1" LASCOtite Adapter MPT x Gasket, Part Number: 21305
- LASCO Sch80 Reducer Bushing (Flush Style) MPT x FPT, Part Number: 839128
- 2" McMaster-Carr Straight Adaptor with Hex Body, Part Number: 4596K57
- Push-to-Connect Fitting for Drinking Water, Straight Adapter, for 1/4" Tube OD x 1/8 BSPT Male, Part Number: 5104K15


#### Tool List
- Sawzall or Band Saw
- Drill Press
- 9/16 in. drill bit
- 3/8 in. tap


#### Procedure
1. Using the Sawzall and band saw, the team cut the PVC pipe into approximately three 40 cm long pieces. These pieces became the three filters.

2. The team drilled a hole for the inlet pipe using the drill press and the 9/16 in. drill bit. The bottom of the hole was approximately 21 cm from the bottom of the PVC pipe. The team then used a ⅜ inch tap to tap the holes.

3. To create closed containers, the team attached the PVC caps to the bottom of each filter using primer and cement glue. The glue was left to dry for several days.

4. The team repeated step 2 and drilled holes for the outlet pipes at the bottom of the filters. The center of the outlet hole is located about 1.5 cm from the bottom of the filter. The hole was drilled on the opposite side of the filter from the hole constructed in step 2.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/Fall%202018/Images/filter%20models.jpg?raw=true" heights=540 width=960>
**Figure 3:** illustrates the appearance of 1 filter.

5. The team constructed the three inlet pipes out of brass, although copper was also considered. Each inlet pipe is 10 cm in length. They were cut to have a rectangular orifice located 0.2 cm from the end of the pipe. The width of the hole will be 0.8 cm and the length 2.25 cm. These values are the same as the ones from the apparatus from previous years. This hole is meant to mimic the shape of the inlet pipes in the AguaClara plants in Honduras. The team capped the end of the pipe nearest the hole with brass.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/Fall%202018/Images/in%20pipe%20model.jpg?raw=true" heights=310 width=927>
**Figure 4:** illustrates the appearance of the inlet pipe.

6. The team also constructed the outlet pipes out of brass. The outlet pipes are 10 cm long and have fine mesh soldered on one end. The team attached the mesh to prevent sand from leaving the filter column with the effluent stream.

Note: The team contacted the CEE machine shop to assist in the construction of the three inlet and three outlet pipes.

7. The team then attached threaded fittings to the 6 pipes so that they could be screwed into the PVC filter. Because the inlet and outlet pipes needed to extend into the filter column, the team needed to drill into the threaded fittings. The team first disassembled the fitting into its pieces so that it could be drilled into. The team then had help from the CEE machine shop in opening the fittings using a .5" drill bit followed by a .505" ream to widen the hole slightly. The team then slid the reassembled fittings onto the inlet and outlet pipes on the side of the pipe that would extend into the filter. For the inlet pipes, this is the end with the rectangular orifice. The fitting was pushed far enough back for the rectangular orifice to be visible, which allows for the orifice to extend into the filter column when the inlet pipe is attached to it. For the outlet pipes, the team attached the fitting to the end of the pipe with the soldered mesh. The team wrapped the threaded fittings with Teflon tape to water-proof the system and prevent leaks. On the opposite end of all 6 pipes, the team slid on push-to-connect reducers. The reducers will connect the brass pipes to the water tubing.

8. The team constructed the tops of the filters, modeling them after the filter top from the previous team's filter. Before attaching any of the parts, the team wrapped the threaded pieces in Teflon tape to prevent water leaks. The team placed the Adapter MPT x Gasket part to the top of the filter PVC pipe and then attached the Straight Adaptor with Hex Body part. The team then attached the Reducer Bushing (Flush Style) MPT x FPT part to the top of the Straight Adaptor and attached the push-to-connect fitting at the top. The top of the filter is necessary, as it will connect the filter to the outlet stream for backwash.


### Conclusion
***Explain what you have learned and how that influences your next steps. Why does what you discovered matter to AguaClara? Make sure that you defend your conclusions with facts and results***

To conclude the work done by the Fall 2018 StaRS team, the team has made significant advances in the fabrication of the new apparatus design. In doing so, the team was able to write a detailed manual that highlights clearly how the different sand grain sizes were obtained as well as manufacturing the brass inlet and outlet pipes.

The issues the StaRS team faced have been centralized around interpreting previous teams reports as the team required clear manuals



### Future Work
The Fall 2018 StaRS team has spent their time predominately focused on fabrication of the new apparatus. The team is eager to continue the research for StaRS in the future.

The team will finish connecting the tubings within the apparatus to accommodate for three filters as opposed to one. This task will require the team to find three different 3-point connects to account for the inflow, and outflow of waste and the outflow stream to the effluent pump. Moreover, two effluent turbidimeters and additional pump is needed for the apparatus set-up to be complete.

The team has conducted a porosity test. This allowed the team to understand the material properties of the sand. In addition the calculation for finding the the porosity will be used to calculate the flow rate that will be used for the experiment. The team will need to write new ProCoDa methods for the new apparatus set-up. The new apparatus will have a pump for backwash with three heads, instead of one, and it will have three effluent turbidimeters, which will act as variables in the new code. ProCoDa testing will not be able to begin until the new apparatus is complete.

The Spring 2018 team determined the optimal coagulant dosage varied between 0.02 and 0.10 mg/L of PaCl. As the Fall 2018 team was unable to conduct experiments, the team recommends that future teams should vary the coagulant dosage within this range. Knowing how the coagulant dosage impacts filter performance will lead to a well-developed mathematical model for StaRs filters.

The challenges the Fall 2018 team foresee for future teams is ensuring that ProCoDa operates smoothly when the three filters are connected. Additionally, fixing leaks within the apparatus is another concern the team has. The research of this team is necessary for the development for AguaClara's filter as the results will show ways filters in Honduras can be adapted to be more efficient.


### Bibliography

Chuang, C.-J., & Li, K.-Y. (1997). Effect of coagulant dosage and grain size on the performance of direct filtration. Separation and Purification Technology, 12(3), 229–241. https://doi.org/10.1016/S1383-5866(97)00048-8

Przekop, R., & Gradoń, L. (2016). Dynamics of particle loading in deep-bed filter. Transport, deposition and reentrainment. Chemical and Process Engineering, 37(3), 405–417. https://doi.org/10.1515/cpe-2016-0033

Tien, C., Turian, R. M., & Pendse, H. (1979). Simulation of the dynamic behavior of deep bed filters. AIChE Journal, 25(3), 385–395. https://doi.org/10.1002/aic.690250302

Kuan-Mu Yao, Mohammad T. Habibian, and Charles R. O'Melia (1971). Water and waste water filtration. Concepts and applications. ACS publications, 5 (11), 1105-1112 https://doi.org/10.1021/es60058a005.
