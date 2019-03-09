# StaRS Filter Theory, Spring 2019
#### Barbara Oramah, Lainey Reed, Pablo Alonso Alguacil and Ronya Strom
##### 19th February, 2019

### Abstract

Stacked Rapid Sand Filtration is the last stage in an AguaClara treatment plant. The filters are used to further reduce the turbidity of water to meet EPA standards of 0.3 NTU or less. This semester, the Stacked Rapid Sand (StaRS) Filter Theory team will be running experiments with the three newly constructed StaRS filters with varying sand grain sizes. These filters will be used in future experiments to analyze how specific parameters affect filter performance. The team's goal is to understand the impact of sand grain size on filtration.


### Table of Contents

- [Introduction](#Introduction)
- [Literature Review](#Literature-review)
- [Previous Works](#Previous-Works)
- [Bibliography](#Bibliography)


### Introduction
Sand filtration has been used since ancient times. In AguaClara water treatment plants, a common type of sand filtration is used - rapid (gravity) sand filtration. This filtration method requires the use of a chemical coagulant, polyaluminum chloride (PaCl), to aggregate small particles (flocs) to increase the ease of particle filtration. This filter design has proven to reduce turbidity below 0.3 NTU, which meets the EPA standards. Experimentation performed on the model sand filter in the lab and the sand filters in the water treatment plants built in Honduras have proved the effectiveness of StaRS filters.

The goal of the StaRS Filter Theory sub-team is to develop a mathematical model describing the filter performance. To do so, the relevant filtration parameters must be determined through experimentation. These parameters can then be used to optimize filter performance for minimum effluent turbidity and maximum failure time. The filter parameters that were investigated by previous sub-teams have include coagulant dosage, influent flow rate, influent turbidity, backwash duration and floc size. The Spring 2019 team will be working on running experiments and analyzing the performance with the 3 new StaRS filters that were built by the previous team. Each of the filters contain 1 layer of sand. The sand grain size within each filter differs.

Last semester, while focusing on fabricating three new filters, the team developed a hypothesis for how sand grain size affects filter performance. The team hypothesized that the filter with the largest sand grains would have the shortest failure time. This hypothesis has not changed within the Spring 2019 team. Failure time corresponds to the time taken for the filter performance efficiency to decrease drastically. The team expects that flocs will be deposited along the sand pores at the same rate in every filter because the rate of the influent stream will be held constant. However, the volume of the filter will be held constant, so when sand grain size increases, the number of sand grain pores in the filter decreases. Ultimately, this means that for a filter filled with larger sand grains, there will be fewer sand pores active at one time. This is demonstrated in Figure 1. This decrease in pore number may cause the active filtration zone to move through the filter faster, leading to a quicker failure time.


<p align="center">
<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/Fall%202018/Images/sand.jpg?raw=true" heights=720 width=1260>
</p>

<p align="center">
<b>Figure 1 </b>: Demonstrates that when sand grain sizes are larger, there are fewer pores in the filter.
</p>


The results of these experiments could hold major significance for filtration methods of AguaClara and other water filtration plants. If it is discovered that sand grain size does impact filter performance, the team will be able to determine the sand grain size that maximizes failure time while maintaining the desired effluent turbidity. This parameter would need to be included in a mathematical model that accurately describes StaRS filters. Moreover, using the optimum size of sand in future filters would lead to a longer period between backwash cycles, saving the AguaClara plants both time and resources.


### Literature Review

The team conducted a thorough literature review to understand the existing research on sand filtration. The team especially looked into how these other experiments took into account different parameters, including grain size, in their mathematical models.

Many models of filtration include reentrainment, the process by which precipitated aggregate materials get unstuck from pores due to shear force from water and move through the filter, eventually sticking elsewhere ([Przekop & Gradon, 2016](https://doi.org/10.1515/cpe-2016-0033), [Tien et al., 1979](https://doi.org/10.1002/aic.690250302), [Yao et al., 1971](https://doi.org/10.1021/es60058a005)). The team will not be taking into account reentrainment, and instead will be assuming that particles either permanently bind to sand particles or completely pass through the system. Once experimentation begins, the team will try see the impact of neglecting reentrainment in our calculations.

One of the team's goals in varying sand grain size is to understand how the grain size influences ripening time and failure time. Ripening time is the time taken for the filter to reach maximum particle removal efficiency. Failure time is the time it takes for the filter to fail, measured by a dramatic increase in effluent turbidity. Other studies have found that pore size has an effect on ripening time, with smaller pores on a filter leading to longer ripening times ([Przekop & Gradon, 2016](https://doi.org/10.1515/cpe-2016-0033)). This study has proven that physical properties within the filter can affect its efficiency. In this semester, the physical property that the team will investigate is sand grain size.

Investigations into grain sizes of glass beads have found that they have less of an effect compared to changes in coagulant doses ([Chuang & Li, 1997](https://doi.org/10.1016/S1383-5866(97)00048-8)). Larger doses of coagulant lead to a shorter ripening time, but also clogged pores at a faster rate and increased the shear force in unclogged pores. However, grain size can have effects based on the coagulant and flocculant dosages. In this study, a flocculant, separate from the coagulant was used to further increase flocculation. The researchers found that larger grains in addition to flocculant and higher coagulant dosages reduced the rate of pore clogging. They hypothesized that it was because larger aggregates were able to pass through the pores between the larger glass beads. In the future, the team will be varying both coagulant dosage and grain size, as in this study. However, sand will be used as a filter material, as is used in AguaClara plants. Furthermore, AguaClara plants only use PaCl, a coagulant, not both a coagulant and a flocculant. The flocculant increased the extent to which the reduction in clogging was observed within the study. The team would expect to see greater clogging than what was seen in this study in the larger sand grains.

As the semester progresses and we run experiments, the team hopes to review more literature to aid with our research.

### Previous Works

Previous StaRS Filter Theory teams focused on combining information from sand bed research with the effects of microscopic level physics and macroscopic filter performance. A visual model of constrictions between the sand grains was developed by previous StaRS Filter Theory teams from the conclusions of several experimental runs. Once the constriction model was developed, the StaRS teams moved to varying coagulant dosage, which was hypothesized to affect filter performance.

The Fall 2017 team systematically varied coagulant dosages to determine its effect on filter performance. The team ran the set of experiments twice. The first set was done by gradually increasing PACl dosage, labeled ‘step up’. The second set was obtained by decreasing the PACl dosages, labeled ‘step down’. They concluded from these experiments that lower coagulant dosages prolonged failure time compared to higher dosages. They also found out that backwashing the filter between filter runs for 20 minutes allowed for more consistent results.

The Spring 2018 team focused primarily on changing the density of floc particles and varying coagulant dosages. Varying coagulant dosages affects the size of the floc particles that enter the filter. By measuring the different floc sizes, the team was able to deduce that the size of flocs did affect the performance of the filter. Large flocs, caused by higher coagulant dosages, proved to make the performance worse.

The main goal of the Fall 2018 Team was to construct the apparatus for future experimentation. The team focused on building three 1-layered sand filters, each of them connected to a turbidimeter that would measure the NTU units of the filtered water. The team was also focused on creating a detailed manual for future teams. The prior filter design used by different teams was the 2-layer filter.

The 2-layered sand filter was first used by the Fall 2013 team and the design had not been changed until Fall 2018. The height of the sand bed was 40 cm, but due to the fluidization of the sand bed, an additional 30% of the height was needed. The final height of the filter was 60 cm. The filter had one inlet stream that drove water into the filter through a downward rectangular orifice at the center of the column, and two outlets near the top and bottom of the filter column.

In contrast, the 1-layered filter that Fall 2018 started to build was designed to have a sand bed of 20 cm. Calculations deemed a 30 cm filter as satisfactory for the requirements of the backwash cycle. To be on the safe side, the final height of the filter was decided to be 40 cm. The sand that would be used for the filters was sieved to get different diameters that ranged from 18-25, 25-35, and 35-45 mesh sizes. Porosity tests were conducted to understand the material properties of the sand. The filter columns were PVC pipes with a diameter of 0.5 inches, and one inlet and one outlet, instead of two.

The findings of the previous StaRS teams are crucial for understanding filter performance as well as choosing which variables to test to develop efficient filters.

### Bibliography

Chuang, C.J., & Li, K.-Y. (1997). Effect of coagulant dosage and grain size on the performance of direct filtration. Separation and Purification Technology, 12(3), 229–241. https://doi.org/10.1016/S1383-5866(97)00048-8

Przekop, R., & Gradoń, L. (2016). Dynamics of particle loading in deep-bed filter. Transport, deposition and reentrainment. Chemical and Process Engineering, 37(3), 405–417. https://doi.org/10.1515/cpe-2016-0033

Kuan-Mu Yao, Mohammad T. Habibian, and Charles R. O'Melia (1971). Water and waste water filtration. Concepts and applications. ACS publications, 5 (11), 1105-1112 https://doi.org/10.1021/es60058a005.
