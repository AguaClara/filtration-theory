# StaRS Filter Theory, Fall 2018
#### Barbara Oramah, Lainey Reed, Emily Spiek
##### September 28th, 2018


[EM: Hi StaRS! I will be writing my comments in brackets under the paragraph in which I am referring to. Thanks!]


### Abstract

Stacked Rapid Sand Filtration is the last stage in an AguaClara treatment plant. It is used to further reduce the turbidity of water to match EPA standards of 0.3 NTU or less. In this report, the StaRS team will be researching the effects of different sizes of sand grains as well as ranges of coagulant dosage. By experimenting with the previously stated variables, this will enhance our understanding of the ability of flocs to bind to the surface of the sand grains. The team's goal for this semester is to find out the volume of flocs caught within the pores of the sand grains as well as formulating a mathematical model for calculating the depth of the active zone.


### Introduction
Sand filtration has been used since ancient times. In AguaClara water treatment plants, a common type of sand filtration is used - rapid (gravity) sand filtration. This filtration method requires the use of a chemical coagulant, polyaluminum chloride (PaCl), to aggregate small particles (flocs) to increase the ease of particle filtration. This filter design has proven to reduce turbidity below 0.3 NTU, meeting the EPA standards. This can be found from experimentation performed on the model sand filter and sand filters in the water treatment plants built in Honduras.

[EM: State the common name for PaCl.]

The goal of the Stacked Rapid Sand (StaRS) Filtration Theory sub-team is to develop a mathematical model describing the filter performance. To do so, the relevant filtration parameters must be determined. After the parameters are determined, the filter performance can be optimized to establish low effluent turbidity and long filtration duration. Some examples of filter parameters considered in previous years were coagulant dosage, influent flow rate, influent turbidity, backwash duration, and floc size. The Fall 2018 team will continue research on optimal coagulant dosage and begin experimentation to determine the effects of sand grain size on filter performance.

The Spring 2018 team determined the optimal coagulant dosage varied between 0.02 and 0.10 mg/L of PaCl. The Fall 2018 team will conduct experiments varying the coagulant dosage within this range. Knowing how the coagulant dosage impacts filter performance will lead to a well-developed mathematical model for StaRs filters.

The main goal of the Fall 2018 team is to investigate variation in sand grain size and create a corresponding mathematical model. The team will build 3 new StaRs filters, each of which will contain 1 layer of sand. The sand grain size within each filter will differ. After construction, the filters will be tested and performance will be analyzed.

The team hypothesizes that the filter with the largest sand grains will have the shortest failure time. Failure time corresponds to the time taken for the filter performance efficiency to decrease drastically. The team expects that flocs will be deposited along the sand pores at the same rate in every filter because the rate of the influent stream will be held constant. However, the volume of the filter will be held constant, so when sand grain size increases, the amount of sand grain pores in the filter decreases. Ultimately, this means that for a filter filled with larger sand grains, there will be less fewer sand pores active at one time. This is demonstrated in Figure 1. This is predicted to cause the active filtration zone to move through the filter faster. The team expects the filter to fail faster than for a filter filled with smaller sand grains.

[EM: Fix grammatical mistakes. Make sure to proof-read a few times before submission.]


<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/Fall%202018/Images/sand%20grain%20diagram.jpg" heights=720 width=1260>

**Figure 1** demonstrates that when sand grain sizes are larger, there are fewer pores in the filter.

The results of these experiments could hold major significance for filtration methods of AguaClara and other water filtration plants. If it is discovered that sand grain size does impact filter performance, the team can determine the sand grain size that optimizes effluent turbidity and failure time. This parameter could be included to create a mathematical model that accurately describes StaRs filters. Moreover, using the optimum type of sand in future sand filters could increase filter duration; filters would need to be backwashed less often. This would increase efficiency by saving both time and resources.


### Literature Review

Many models of filters include reentrainment, the process by which precipitated aggregate materials get unstuck from pores due to shear force from water and move through the filter, eventually sticking elsewhere (Tien et al., 1979, Przekop & Gradon, 2016). The team will not be taking into account reentrainment, and instead will be assuming that particles either permanently bind to sand particles or completely pass through the system. The team will be searching to see the impact of neglecting reentrainment in our experiment throughout the semester.

The team will be changing sand grain size to see how it affects ripening time and failure time. Ripening time is the time is takes for the filter to reach maximum particle removal efficiency. Failure time is the time it takes for the filter to fail, measured by an increase in effluent turbidity. Pore size has an effect on ripening time, with smaller pores leading to longer ripening times (Przekop & Gradon, 2016). Physical properties within the filter can affect its efficiency.

Investigations into grain sizes of glass beads have found that they have less of an effect compared to changes in coagulant doses (Chuang & Li, 1997). Larger doses of coagulant lead to a shorter ripening time, but also clog pores at a faster rate, and increase the shear force in unclogged pores. However, grain size can have effects based on the coagulant and flocculant dosages. Larger grains in addition to higher flocculant and coagulant dosages reduce the rate of pore clogging. This is because larger aggregates are able to pass through the glass beads. The team will be varying both coagulant dosage and grain size, as in this study. However, sand will be used as a filter material, as is used in AguaClara plants. Also, AguaClara plants only use PaCl, a coagulant, not both a coagulant and a flocculant.


### Previous Works
The main goal for Fall 2018 has been undergoing major reconstruction of apparatus set-up. This has required the team to look at early teams, such as Fall 2015, for fabrication and calculations to help the team create three new one layer sand filters, as well as fabricating the brass inlet and outlet pipes. The prior filter used by StaRs subteam was a two layer sand filter. The sand bed column was 40 cm in length, and there was an extra 30% included to account for the fluidization of the bed during backwash. The length of the entire filter resulted to be 60 cm in length and it had one inlet and two outlet streams. The inlet stream had an rectangular orifice of a calculated area for water to infuse within the filter whilst the outlet streams were from equidistant from the the inlet located above and below. The Fall 2013 was the first team to implement this design for the filter and it has not been drastically modelled until this semester.

$$ \frac{Area \, of \,orifice }{Area \,of\, sandbed}=\frac{Area\, of \,inlet}{Area\, of\, filter} $$

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

[EM: How is backwash initiated?]


### Manual
This semester, the StaRS team focused on fabricating three new filters. The filters will hold varying sand grain sizes from .354-.5 mm, .5-.707 mm, and .707-1 mm in diameter.

The team will also be attaching a pump after the three filter streams in order to ensure a downward flow. The main challenge the team is how to maintain the three effluent flows through one pump so that they will all flow through their respective turbidimeter.


###### Materials

- Sand sieved to three size ranges: .354-.5 mm (between  35-45 mesh size), .5-.707 mm (25-35 mesh size), and .707-1 mm (18-25 mesh size) in diameter.
- Three turbidimeters
- Three pressure sensors


###### Obtaining Sand

The StaRS team is in the process of obtaining sieved sand. The team first reached out to Standard Sand and Silica Co., a company that AguaClara has obtained sand from previously. The company would not be capable of providing sand sieved to 25 micrometers. The team has been in contact with Philip Carubia from the Cornell Center for Materials Research to discuss the possibility of sieving sand either using a Sonic Sifter on campus or purchasing hand-sieves. The team will decide which sieving method to use within the next week.


#### Procedure

StaRS team has undergone further fabrication training in order to have a holistic and safe understanding of the power tools when building the filters. The length of each filter will be dependent on backwash expansion. The team will note what the height of the stabilised sand bed will be and add 0.6 times that to calculate optimum height of the filters.

1. Obtained a long PVC pipe of inlet diameter 26 mm. This matches the inlet diameter of the previous filter.
2. Drilled hole for inlet pipe using pillar drilling machine. The bottom of the hole is approximately 21 cm from bottom of PVC pipe. The drill bit used was 9/16 inch. We then used a ⅜ inch tap.
3. Attached white caps to bottom of each filter using cement glue. Wait for glue to dry before drilling hole for outlet pipe.
4. Step 2 is repeated but drilled at the bottom of the PVC pipe where white cap is attached. The outlet hole is the same diameter as the inlet diameter.
5. Find brass (or copper) piping to fabricate the inlet and outlet pipe. The inlet pipe should be cut to have an orifice of area: 1.8 centimeters cubed. Contact CEE Machine Shop for that to be done.




### Works Cited

Chuang, C.-J., & Li, K.-Y. (1997). Effect of coagulant dosage and grain size on the performance of direct filtration. Separation and Purification Technology, 12(3), 229–241. https://doi.org/10.1016/S1383-5866(97)00048-8

Przekop, R., & Gradoń, L. (2016). Dynamics of particle loading in deep-bed filter. Transport, deposition and reentrainment. Chemical and Process Engineering, 37(3), 405–417. https://doi.org/10.1515/cpe-2016-0033

Tien, C., Turian, R. M., & Pendse, H. (1979). Simulation of the dynamic behavior of deep bed filters. AIChE Journal, 25(3), 385–395. https://doi.org/10.1002/aic.690250302

Kuan-Mu Yao, Mohammad T. Habibian, and Charles R. O'Melia (1971). Water and waste water filtration. Concepts and applications. ACS publications, 5 (11), 1105-1112 https://doi.org/10.1021/es60058a005.
