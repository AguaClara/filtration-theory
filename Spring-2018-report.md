# StaRS Filter Theory, Spring 2018
#### Alison Valibuena, Liz Cantlebary, Dylan Vu
#### March 11, 2018

## Abstract
Sand filters have historically been used to lower the turbidity of water and continue to be used in many conventional water filtration systems. Dynamic modeling, as opposed to static modeling, of rapid stand filtration accounts for the buildup of particles over time in the filter, and this understanding is needed for better filter design and operation. Past sub-teams found that head loss increases linearly with time. This research proposes the hypothesis that flocs are captured in rings created by filter grains, which on a larger scale implies an active filtration zone where empty pores become clogged by the flocs. This active zone moves throughout the bed until there is no remaining space for particles to clog. This research examines the factors that influence the failure time of the filter including size and density of flocs.

## Introduction
The goal of the Stacked Rapid Sand (StaRS) Filtration Theory sub-team is to develop a mathematical model describing the interaction of flocs and the filter medium. Thus, the most effective choice of filtration parameters could be determined in order to optimize water filtration. Lowest effluent turbidity and longest filtration duration in stacked rapid sand filtration are the ultimate goals. The parameters included were coagulant dosage, flow rate of pretreated water, influent turbidity, and backwash duration. Currently the team incorporated a new factor, floc size, which could potentially affect the effluent turbidity and time failure of the deep sand filter.

The sub-team’s work-in-progress mathematical and visual model, proposed by the Spring 2017 StaRS Filter Theory sub-team, hypothesize washer-like “dirty” particle build-up within the constricted pores of the sand bed in the stacked rapid sand filter. As the pores were clogged, effluent turbidity increased and failure time occurred. In an attempt to test the proposed model, the fall 2017 sub-team conducted experiments to measure the effects of varying coagulant dosages on filter performance.

By systematically varying dosages in subsequent filter runs, the effect of coagulant dose on filter performance and failure time was determined. Other experiments were designed to study the effects of shear force between the floc particles and sand medium within the filter by changing the flow rate through the filter. From these studies, a pattern was found between dosage and optimizing effluent turbidity over time balanced with minimizing the required volume of the filter based on filter parameters for the given filtration conditions. Previous AguaClara plants have been built with the assumption that sedimentation processes ought to be designed to achieve the highest particle removal possible, leaving small quantities of floc particles in the effluent water from the sedimentation tanks. However, it was hypothesized that leaving some portion of larger flocs in the influent water by controlling the influent flow rate would allow greater aggregation with the smaller flocs. This aggregation of flocs would create larger clumps of particulate matter that would be easier for the filter medium to capture. Following up, this hypothesis experiments were run to measure the effect of changing the flocs’ particles size and the aggregation of these in the sand bed. It was hypothesize that the the volume per particle decreased with size. Thus, flocs could better be captured in the sand grain pores and failure time of the filter could increase. Further experiments were conducted to observe the strength of shear forces on the smaller sized particles, as well as their volume and the overall volume capacity of the sand filter. By Knowing these parameters the quality of the stacked filter could be enhanced, leading to more affordable water treatment plants to benefit more people worldwide.

## Literature Review and Previous Work
From previous subteams' work and hypothesis, it is known that changing coagulant dosage changes the performance of the filter. When effluent turbidity increases sharply is when the observed failure time happens. Coagulant dosage changes the size of flocs as well. Therefore, the team now hypothesizes that smaller flocs could improve the time period the filter is retentive . According to Kuan-mu Yao (1971) “ For suspended particles larger than 1 μ, removal efficiency increases rapidly with particle size.” Effectiveness of the filter depends on the size and density of the flocs. From our latest experiment, an orifice of ____μ was build and connected to the tube right before entering the filter, such constriction was meant to break up the flocs. It was observed that failure time increased while the effluent turbidity decreased significantly, which made us conclude that the constriction successfully achieved its purpose. However, further analysis is needed in order to analyze other factors such as head loss and volume-density-relationship of the flocs. A relation between the size of the flocs and the capacity of the sand grain pores to retain particles leads to the second main hypothesize we believe affects filter performance, and that is Porosity. It is known that the filter fails with a specific reduction in the porosity of the filter bed Przekop & Gradoń
(2016). Deeper analysis of this mechanism can be studied by comparing the volume of average flocs with the volume of the pores of the filter medium.

To understand how flocs size could be related to porosity another terms was taken into account, deposition of particles in the medium filter. In their paper, Tien et al. (1979) modeled a sand filter bed using the constricted tube model instead of the classic spherical model where pores within the filter were similar to long straws with a constant width. It was found that the process of filtration can be split into a two step process.The first part of the model is has a clean bed with no particles attached to the grains; as water was run through the bed, particles began to deposit on the sand grains. Therefore, the second stage of this model sought to account for particle deposition, which changes over time,assuming that the particles coat sand grains uniformly. The model demonstrates that deposited particles increased the volume of solids within the filter. As a result, porosity within the sand bed decreased.

Eventually particles redeposit in other parts of the of the sand bed.The redeposition of these aggregates is the main reason pores get blocked and the filter becomes clogged or nonretentive, Tien & Turian (1979). Additionally, The model proposed by the Spring 2017 StaRS filter theory team aimed to combine the information from previous sand bed research and results from experiments run to propose what is happening on a molecular level in the bed through looking at factors such as turbidity and head loss.
Now the spring 2018 team plans to investigate this hypothesis by analyzing the effect of flocs’ size entering the filter as previously stated. Experiments using a constricted tube to part the flocs at different PACL dosages will be conducted. Head loss and shear forces can be analyzed and potentially considered as parameters that could influence failure time of filtration.


## Methods
Explain the techniques you have used to acquire additional data and insights. Reserve fine detail for the Manual at the end of the report, but use this section to give an overview with enough detail for the reader to understand your Results and Analysis. Describe your apparatus, and have a justification for every decision you made and every parameter you chose in the design of the apparatus. Be especially careful to detail the conditions your experiments were conducted under, as this information is especially important for interpreting your results

Below, some example sections are given. Sectioning the report is meant to keep similar information together.  Continue making sections as necessary, or delete sections if you do not need them. Feel free to add subsubsections to further delineate the information. For example, under the Experimental Apparatus section below, the EStaRS team might consider having sections such as "Filter Design" and "Filter Fabrication".

### Experimental Apparatus
The laboratory stacked rapid sand filter was created with a 65cm length of PVC filled with{sand with a diameter of 0.5 mm to 0.595 mm to a height of 40cm. There is one influent pipe and two effluent pipes, all with a diameter of 9.4 mm and made from copper. A schematic of full system can be seen below.

Tap water was pumped into the system and combined with clay and humic acid based on the concentrations calculated by the MatLAB file. The contaminated water stream then entered the influent turbidimeter before going to the contact chamber, where the contaminated water is mixed with Polyaluminium Chloride (PACl), essentially making the clay particles sticky. After leaving the contact chamber, the wastewater entered the flocculator, a helical coil made out of flexible tubing with a diameter of 0.625 mm. The flocculator was designed to increase collisions between clay particles to create flocs that could then be more easily removed in the stacked rapid sand filter. The flocculator was designed with a residence time of 2.67 s for a flow rate of 1.98 mL/s. The energy dissipation rate was 0.27 W/kg, which kept flocs small to simulate influent water for filtration.

Once the water exits the flocculator, it is injected into the stacked filter at an average velocity of 1.8 mm/s. The residence time in the filter was 43.6 seconds on average, after which the water exits the filter through one of the effluent pipes. The two effluents mix and then go into the effluent turbidimeter to measure the turbidity of the water. The difference in turbidity between the influent and effluent water can be used to determine the overall effectiveness of the filter. There is also a 200 kPA pressure sensor immediately before the water enters the filter, and immediately after the two effluent pipes combine in order to measure the head loss caused by the rapid filtration.




<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/apparatus.jpg?raw=true" height=500 width=10000>
Figure 1: Schematic for the experimental filter apparatus in filter mode showing influent and effluent turbidimeter sampling systems, PACl solution and clay, humic acid solution dosing, pressure sensor to measure filter head loss, and flocculator. Blue connections are used in filter mode. Gray connections are used in backwash mode.


* Image (from lab; label parts)
* Materials (dimensions, materials)
* Complications in construction
* If already constructed: write a brief summary of important constraints, include any revisions to apparatus, also reference the prior report where construction is described

### Procedure
The goal of the first experiment was to observe if density of particles is the defining factor in filter failure because the flocs would occupy more volume.  A constriction was placed in the influent tubing immediately before the filter. The constriction has a diameter of ** in order to create a head loss of approximately 8m in the system. The increased pressure breaks the flocs apart, removing the effect of density and particle size on failure time.

## Results and Analysis
The first filter test was performed to reconfirm the pre-treatment process created in the previous semester to solve inconsistency issues performed between tests. This process can be found below, in the Manual section of this report. Thus, the filter run in which 2mg/L PACl dosage was used. The experiment was performed, and the team observed the effluent turbidity as a function of time. A plot of this data can be found below. The filter failure time was examined in this test. Filter failure time is defined by the team as the time at which the effluent turbidity begins to diverge from the constant, low turbidity observed while the filter is functionally operational. This can be graphically found by observing the time at which there is a sudden upturn in the effluent turbidity data. It was found that the filter failure time was around 1.65 hours. This was consistent with data collected from the previous semester, upon changing the filter pre-treatment process. From this result, the team concluded that the filter pre-treatment process was still viable for the apparatus this semester, and that the team could be assured that data collected in subsequent tests are valid.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/control%202018.PNG?raw=true" height=350 width=600>
Figure 2: Plot showing effluent filter turbidity vs. time for the control test performed to validate filter pre-treatment procedures described in the Manual section of the report. It was observed that the filter failure time occured around 1.65 hours.

The second filter test was performed to test the effects of particle size on filter performance. In this filter test, a constriction was added before the filter influent line. The purpose of this constriction was to increase the flow velocity, hoping to increase the shear force within the line and break up the flocs created in the flocculator. Thus, the size of the particles entering in filter would be smaller, while the density of the floc was unchanged. Again, the effluent turbidity over the duration of the test was collected, along with headloss data. From this data, the filter failure time was determined in the same way as was described above, for the control experiment. 

## Conclusions
Explain what you have learned and how that influences your next steps. Why does what you discovered matter to AguaClara?

Make sure that you defend your conclusions with facts and results.

## Future Work
Describe your plan of action for the next several weeks of research. Detail the next steps for this team. How can AguaClara use what you discovered for future projects? Your suggestions for challenges for future teams are most welcome. Should research in this area continue?

## Bibliography
Logan, B. E., Hermanowicz, S. W., & Parker,A. S. (1987). A Fundamental Model for Trickling Filter Process Design. Journal (Water Pollution Control Federation), 59(12), 1029–1042.

# Manual
The goal of this section is to provide all of the guidance that would be necessary for a future team to pick up your work where you left off. Please try to be thorough and put yourselves in the shoes of a newcomer to the project. Below are some recommended sections, but the manual will likely take a slightly different form for each team.

## Fabrication Details
Include any information related to the fabrication of equipment, experimental apparatuses, or technologies. Include the purpose of each step and the fabrication methods used. Reference appropriate safety precautions.

## Special Components
If your subteam uses a particular part that is unique and you could foresee a future subteam needing to order it or learn more about it, please include basic information like the vendor where it was purchased, catalog/item number, and a link to any documentation.

## Experimental Methods
### Set-up
Step 1.
* Put tasks in a sequential order.
* It is okay to have sub-lists.
  - Like this.

### Experiment
Step 1.

### Cleaning Procedure
Step 1.

## Experimental Checklist
Another potential section could include a list of things that you need to check before running an experiment.

## ProCoDA Method File
Use this section to explain your method file. This could be broken up into several components as shown below:

### States
Here, you should describe the function of each state in your method file, both in terms of its overall purpose and also in terms of the details that make it distinct from other states. For example:
\begin{itemize}
\item \underline{OFF} - Resting state of ProCoDA. All sensors, relays, and pumps are turned off.
\end{itemize}

### Set Points
Here, you should list the set points used in your method file and explain their use as well as how each was calculated.

## Python Code

### Variables
$g$: gravity
$\sigma$: dispersion
$a$: amplitude
$h$: water depth
$H$: distance from wave crest to trough (2$a$)
$T$: wave period
$\lambda$: wavelength
$k$: wavenumber
$c_p$: celerity (wave phase speed)
$P$: pressure
$F$: force
$u$, $w$: x-velocity, z-velocity components

```python
# Comment
```

# Add/Delete/Change this Template as you see Fit
When using this template keep in mind that this serves three purposes. The first is to provide your team feedback on your progress, assumptions, and conclusions. The second is to keep your team focused on what you are learning and doing for AguaClara. Another is to educate future teams on what you've learned and done. This document should be comprehensive, consistent, and well-written. With that in mind, add, subtract, or move sections. Reach out to the RAs and graders for help with figuring out what should or shouldn't include. Focus on how wonderful a reference you are making through this and work hard on communicating amongst yourselves and with future teammates. (Delete this section before submitting)

```python
# To convert the document from markdown to pdf
pandoc Name_of_this_file.md -o TeamName_Research_Report.pdf
```
