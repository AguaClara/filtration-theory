# StaRS Filter Theory, Spring 2018
#### Alison Valibuena, Liz Cantlebary, Dylan Vu
#### March 11, 2018

## Abstract
Sand filters have historically been used to lower the turbidity of water and continue to be used in many conventional water filtration systems. Dynamic modeling, as opposed to static modeling, of rapid stand filtration accounts for the buildup of particles over time in the filter, and this understanding is needed for better filter design and operation. Past sub-teams found that head loss increased linearly with time. This research proposed the hypothesis that flocs were captured in rings created by filter grains, which on a larger scale implies an active filtration zone where empty pores become clogged by the flocs. This active zone moved throughout the bed until there was no remaining space for particles to clog. This research examined the factors that influence the failure time of the filter including size and density of flocs.

## Introduction
The goal of the Stacked Rapid Sand (StaRS) Filtration Theory sub-team was to develop a mathematical model describing the interaction of flocs and the filter medium. Thus, the most effective choice of filtration parameters could be determined in order to optimize water filtration. Lowest effluent turbidity and longest filtration duration in stacked rapid sand filtration were the ultimate goals. The parameters included were coagulant dosage, flow rate of pretreated water, influent turbidity, and backwash duration. Currently the team incorporated a new factor, floc size, which could potentially affect the effluent turbidity and time failure of the deep sand filter.

The sub-team’s work-in-progress mathematical and visual model, proposed by the Spring 2017 StaRS Filter Theory sub-team, hypothesize washer-like “dirty” particle build-up within the constricted pores of the sand bed in the stacked rapid sand filter. As the pores were clogged, effluent turbidity increased and failure time occurred. In an attempt to test the proposed model, the fall 2017 sub-team conducted experiments to measure the effects of varying coagulant dosages on filter performance.

By systematically varying dosages in subsequent filter runs, the effect of coagulant dose on filter performance and failure time was determined. Other experiments were designed to study the effects of shear force between the floc particles and sand medium within the filter by changing the flow rate through the filter. From these studies, a pattern was found between dosage and optimizing effluent turbidity over time balanced with minimizing the required volume of the filter based on filter parameters for the given filtration conditions. Previous AguaClara plants have been built with the assumption that sedimentation processes ought to be designed to achieve the highest particle removal possible, leaving small quantities of floc particles in the effluent water from the sedimentation tanks. However, it was hypothesized that leaving some portion of larger flocs in the influent water by controlling the influent flow rate would allow greater aggregation with the smaller flocs. This aggregation of flocs would create larger clumps of particulate matter that would be easier for the filter medium to capture. Following up, this hypothesis experiments were run to measure the effect of changing the flocs’ particles size and the aggregation of these in the sand bed. It was hypothesize that the the volume per particle decreased with size. Thus, flocs could better be captured in the sand grain pores and failure time of the filter could increase. Further experiments were conducted to observe the strength of shear forces on the smaller sized particles, as well as their volume and the overall volume capacity of the sand filter. By Knowing these parameters the quality of the stacked filter could be enhanced, leading to more affordable water treatment plants to benefit more people worldwide.

## Literature Review and Previous Work
From previous subteams' work and hypothesis, it was known that changing coagulant dosage changes the performance of the filter. When effluent turbidity increases sharply was when the observed failure time occured. Coagulant dosage changed the size of flocs as well. Therefore, the team hypothesized that smaller flocs could improve the time period the filter operates effectively in particle removal. According to Kuan-mu Yao (1971), "For suspended particles larger than 1 μ, removal efficiency increased rapidly with particle size.” Effectiveness of the filter depends on the size and density of the flocs. From our latest experiment, an orifice half the size of the influent tubing was built and connected to the tube right before entering the filter, such a constriction was purposed break up the flocs, effectively decreasing particle size. It was observed that failure time increased while the effluent turbidity decreased significantly. This was assurance that the constriction successfully achieved its purpose. However, further analysis was needed in order to analyze other factors such as head loss and volume-density-relationship of the flocs. A relation between the size of the flocs and the capacity of the sand grain pores to retain particles led to the second main hypothesize of filter failure mechanisms: porosity. It was hypothesized that the filter fails with a specific reduction in the porosity of the filter bed Przekop & Gradoń
(2016). Deeper analysis of this mechanism can be studied by comparing the volume of average flocs with the volume of the pores of the filter medium.

To understand how flocs size could be related to porosity, deposition of particles in the medium filter was researched. In their paper, Tien et al. (1979) modeled a sand filter bed using the constricted tube model instead of the classic capillary tube model, in which pores within the filter were similar to long straws with a constant width. It was found that the process of filtration can be split into a two steps. The first part of the model described a clean bed with no particles attached to the grains; as water was run through the bed, particles began to deposit on the sand grains. The second stage of this model sought to account for particle deposition, which changed over time, assuming that the particles coat sand grains uniformly. The model demonstrated that deposited particles increased the volume of solids within the filter. As a result, porosity within the sand bed decreased.

Further, it has been theorized that particles redeposit in other parts of the of the sand bed in a process known as reentrainment. It was proposed that the redeposition of these aggregates was the main reason pores got blocked and the filter clogged or became nonretentive, Tien & Turian (1979).

Now the spring 2018 team plans to investigate this hypothesis by analyzing the effect of flocs’ size entering the filter as previously stated. Experiments using a constricted tube to part the flocs at different PACL dosages will be conducted. Head loss and shear forces can be analyzed and potentially considered as parameters that could influence failure time of filtration.


## Methods
The apparatus was set-up in the manner described below. Next, a control experiment was run. For this experiment, the apparatus was not modified, and 2mg/L of PACl was used to dose the clay water. The filter was then run using the instructions found in the Manual section, below. Data was recorded using ProCoDA, including influent turbidity, effluent turbidity and headloss data. From these data, the failure time could be observed from the trends of the effluent turbidity. This is further described in Results and Analysis. After, the apparatus was similarly set up for another experiment. A constriction was fabricated using tubing of the same size as the tubing for the influent line in the future, cement glue and a pipette tip. The pipette tip was cut such that the orifice would be half the diameter of the inner side of the tubing. The tip was then covered in glue, placed into the tubing, and left to dry. The constriction was then attached to the influent line of the sand filter using push-to-connects. Then, the experiment was run using the same parameters as the control experiment.

### Experimental Apparatus
The laboratory stacked rapid sand filter was created with a 65cm length of PVC filled with{sand with a diameter of 0.5 mm to 0.595 mm to a height of 40cm. There is one influent pipe and two effluent pipes, all with a diameter of 9.4 mm and made from copper. A schematic of full system can be seen below.

Tap water was pumped into the system and combined with clay and humic acid based on the concentrations calculated by the MatLAB file. The contaminated water stream then entered the influent turbidimeter before going to the contact chamber, where the contaminated water is mixed with Polyaluminium Chloride (PACl), essentially making the clay particles sticky. After leaving the contact chamber, the wastewater entered the flocculator, a helical coil made out of flexible tubing with a diameter of 0.625 mm. The flocculator was designed to increase collisions between clay particles to create flocs that could then be more easily removed in the stacked rapid sand filter. The flocculator was designed with a residence time of 2.67 s for a flow rate of 1.98 mL/s. The energy dissipation rate was 0.27 W/kg, which kept flocs small to simulate influent water for filtration.

Once the water exits the flocculator, it is injected into the stacked filter at an average velocity of 1.8 mm/s. The residence time in the filter was 43.6 seconds on average, after which the water exits the filter through one of the effluent pipes. The two effluents mix and then go into the effluent turbidimeter to measure the turbidity of the water. The difference in turbidity between the influent and effluent water can be used to determine the overall effectiveness of the filter. There is also a 200 kPA pressure sensor immediately before the water enters the filter, and immediately after the two effluent pipes combine in order to measure the head loss caused by the rapid filtration.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/apparatus.jpg?raw=true" height=500 width=1000>

Figure 1: Schematic for the experimental filter apparatus in filter mode showing influent and effluent turbidimeter sampling systems, PACl solution and clay, humic acid solution dosing, pressure sensor to measure filter head loss, and flocculator. Blue connections are used in filter mode. Gray connections are used in backwash mode.

### Procedure
The goal of the first experiment was to observe if density of particles is the defining factor in filter failure because the flocs would occupy more volume. A constriction was placed in the influent tubing immediately before the filter. The constriction was half the diameter of the influent tubing to create a head loss of approximately 8m in the system. The increased pressure breaks the flocs apart, removing the effect of density and particle size on failure time. The influent turbidity of the system was kept at 5NTU during the course of the experiment using Kaolinite clay and humic acid, and the dose of coagulant was 2mg/L. The experiment ran for 12 hours, and the head-loss through the filter and effluent turbidity were measured for the duration of the experiment.

## Results and Analysis
The first filter test was performed to reconfirm the pre-treatment process created in the previous semester to solve inconsistency issues performed between tests. This process can be found below, in the Manual section of this report. Thus, the filter run in which 2mg/L PACl dosage was used. The experiment was performed, and the team observed the effluent turbidity as a function of time. A plot of this data can be found below. The filter failure time was examined in this test. Filter failure time is defined by the team as the time at which the effluent turbidity begins to diverge from the constant, low turbidity observed while the filter is functionally operational. This can be graphically found by observing the time at which there is a sudden upturn in the effluent turbidity data. It was found that the filter failure time was around 1.65 hours. This was consistent with data collected from the previous semester, upon changing the filter pre-treatment process. From this result, the team concluded that the filter pre-treatment process was still viable for the apparatus this semester, and that the team could be assured that data collected in subsequent tests are valid.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/control%202018.PNG?raw=true" height=350 width=600>

Figure 2: Plot showing effluent filter turbidity vs. time for the control test performed to validate filter pre-treatment procedures described in the Manual section of the report. It was observed that the filter failure time occured around 1.65 hours.

The second filter test was performed to test the effects of particle size on filter performance. In this filter test, a constriction was added before the filter influent line. The purpose of this constriction was to increase the flow velocity, hoping to increase the shear force within the line and break up the flocs created in the flocculator. Thus, the size of the particles entering in filter would be smaller, while the density of the floc was unchanged. Again, the effluent turbidity over the duration of the test was collected, along with headloss data. From this data, the filter failure time was determined in the same way as was described above, in the control experiment. It was found that the failure time was around 0.9 hours.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/2mgL%20constriction.PNG?raw=true" height=350 width=600>

Figure 2: Plot showing effluent filter turbidity vs. time for the 2mg/L PACl dosage with constriction performed to examine the effect of particle size on filter performance. It was observed that the filter failure time in this test was about 0.9 hours.

## Conclusions
From the experiments performed, the team can conclude that the cleaning procedure before performing filter runs is reliable for the apparatus. In combination with the reproduced failure times observed in all filter runs performed from the previous semester, the consistency observed in the 2mg/L PACl dosage control filter run performed this semester with corresponding 2mg/L PACl dosage runs from the past semester added to the assurance of the effectiveness of the pre-treatment procedure.

From the constriction run, it was found that the failure time for the 2mg/L PACl dosage was significantly less than that for the control 2mg/L PACl dosage run. There was a decrease in the failure time from about 1.65 hours to 0.9 hours with the added constriction. This suggests that smaller size flocs lead to worse filter performance. However, nothing can be concluded yet until the results can be reproduced and further testing is performed.

## Future Work
In the following weeks, the team will seek to find a trend in the effects of particle size on filter performance. To do so, experiments will be performed involving the 5 different PACl dosages (0.2, 0.65, 1.11, 1.65, and 2mg/L) with the constriction in place. Failure time for each of these tests will be observed and compared with the failure times observed from the last semester. From there a conclusions will be drawn about particle size on filter performance.

In the long term, the team is looking to widen the range of PACl dosages to further delve into the effect of coagulant dosage on filter performance. These experiments will be performed with the intent of future optimization of coagulant dosage to promote the best filter performance. This data can be directly applied to sand filters in Honduras, once scaled appropriately.

## Bibliography
Kuan-Mu Yao, Mohammad T. Habibian, and Charles R. O'Melia (1971). Water and waste water filtration. Concepts and applications. ACS publications, 5 (11), 1105-1112
doi: 10.1021/es60058a005.

Przekop, R. & Gradoń, L. (2016). Dynamics of particle loading in deep-bed filter. Transport, deposition and reentrainment. Chemical and Process Engineering, 37(3), pp. 405-417. doi:10.1515/cpe-2016-0033

Tien, C., Turian, R. M., and Pendse, H. (1979). Simulation of the dynamic behavior of deep bed filters. AIChE Journal, 25(3):385–395.


# Manual

## Experimental Methods
### Set-up
Replenishing Clay & PACl Stocks:
* Set the amount of liters needed for the stock tank
* Calculate the mass amount necessary for this amount of water.
* Weigh out the correct amount of clay and humic acid to the thousandths place.
* Measure the correct amount of tap water in a Volumetric Flask. Use the water to pour any remaining clay or humic acid from the weight balance into the tank.

For PACl stock tank:
* Use the deionized water in lab to partially fill a 1L  volumetric flask.
* Pipette the correct volume of PACl needed for 1L of water.
* Fill the rest of the flask with deionized water.
* Repeat the process and refill the stock tank.

### Experiment
* Once a week: Calibrate the water pump by finding the rpm which yields a desired flow rate.
* Once a week: Calibrate the PAC pump by finding the rpm which yields a desired flow rate.
* Once a week:  Calibrate the clay pump through ProCoDa.
* Follow cleaning protocol.
* State: Filter no clay to ensure there are no air bubbles in the system before the filter.
* Prime PACl pump to get rid of air bubbles in tubing PACl tank to contact chamber.
* Backwash if there are air bubbles in the filter.
* State: Filter no clay. Run until effluent turbidity is below 0.5 NTU, indicating that residual clay and coagulant is minimal.
* State: Off. Ensure the height of the settled bed remains constant between experimental runs, it necessary, externally agitate the filter to settle the bed.  Ensure there is no sand stuck a the top of the filer by tapping the pipe with the hammer.
* Ensure the influent water turbidity is as expected for clean tap water.
* Ensure the mixer for the clay stock tank is on.
* Ensure the valves to the bed and the PACl stock tank are open, ensure the lid to the PACl stock tank is unscrewed
* Ensure that there is enough solution the PACl and clay stock tanks for the experiment run. Instructions for replenishing the stock tanks are below.
* Ensure the data is going to the proper file on the computer to prevent lost data. It should either be automatically uploaded to Google drive or the data should be manually uploaded after the experiment is completed.
* State: Open Solenoid Valves. Zero pressure sensor in ProCoDA (Click Volts, click Zero). Turn on the Clay pump.
* State: Filter. Start a new experiment. Manually set PACl pump speed. Turn on Automatic mode. Turn on the clay pump and the start the PACl pump.
* Ensure that PID control for the clay pump properly adjusts the influent turbidity to target turbidity.


### Cleaning Procedure
A cleaning protocol was formalized so that each filter run started with a clean filter, flocculator, and system tubing. Cleaning involves steps to help sand in the filter fluidize and clean the filter, clean the walls of the tubing, contact chamber, flocculator, and cuvettes for the next filter run. A successful backwash state is when the filter sand fluidizes completely and the system is in the Backwash state continuously without sand clogging the apparatus and preventing water flow. Vinegar is used in cleaning to reduce the pH of the water and allow the coagulant to dissolve into the water more easily. The state of the system begins in the Off state after a filter run. Only the influent water pump should be on.

Clean filter sand
* State: Filter no clay for 1 minute.
* State: Backwash Half Flow. Ensure that the filter bed fluidizes.
* State: Backwash Toggle. Ensure that the filter bed fluidizes at the full flow rate while the solenoid valve controlling influent water for backwash is toggling.
* State: Backwash. Run for 20 minutes, and continue backwashing if there are visible clay particles in the filter. If the filter sand has not yet fluidized, Off, Backwash Half Flow, Backwash Toggle, and Backwash helps break up the sand column.
* State: Off.

Clean contact chamber, flocculator, and tubing from PACl stock tank.
* Close the manual valve after the flocculator. Disconnect the system at the tubing after the flocculator and before the valve. Turn the clay pump off.
* State: Filter. Place a bucket at the open end of the flocculator to catch influent water.
* Replace the PACl stock tank with a tank of vinegar (5\% acidity).
* Run the PACl pump at full speed for 30 s to flush the contact chamber and flocculator with vinegar.
* Replace tank of vinegar with tank of water. Run the PACl pump at full speed for 30 s to remove vinegar from the system.
* State: Off.
* Clean the contact chamber, flocculator, and tubing. Disconnect the system at the tubing before the contact chamber and flush the dirty parts of the system with water.
* Reconnect all parts leading up to the filter. Ensure the piece of micro-tubing in the contact chamber is approximately half way in the chamber.

Clean turbidimeters
* Empty turbidimeter cuvettes and rinse with DI water.
* Screw cuvettes back in and wipe outside with a Kimwipe. Do not reassemble turbidimeters yet.
* State: Filter. Ensure that there are no leaks from the cuvettes.
* Shake to ensure there are no air bubbles in the system.
* State: Off. Reconnect system at flocculator.
* If there are no leaks, put the cuvettes back into the turbidimeter.

Prepare for a new experiment.

## ProCoDA Method File

### States

* _Off_: All solenoid valves are closed. All pumps are off.
* _Filter_: Pumps clay-suspended water, PACl, and clean water into the influent system for testing filter performance.
  - Open - solenoid valves A, C, E
  - On - clay pump, PACl pump, influent pump
* _Backwash_: Removes clay particles from the experimental apparatus.
  - Open - solenoid valves B, D
  - On - influent pump
* _Backwash Half Flow_: Removes clay particles from the experimental apparatus. Operates at half flow in order to reduce sand rising as a column and to help the sand fluidize earlier
  - Open - solenoid valves B, D
  - On - influent pump
* _Backwash Toggle_: Solenoid B is open and closed periodically so that the water pulses through the filter during backwash. Pulsing the water helps the sand fluidize.
  - Open - solenoid valves B, D
  - On - influent pump
* _Backwash and Inflow_: Water flows through the influent and backwash systems
  - Open - solenoid valves A, B, C, D
  - On - influent pump
* _Open Solenoid Valves_: Pre-experimental state opens solenoid valves so that pressure sensor readings between Off and Filter states change minimally
  - Open - solenoid valves A, C, E
* _Calibrate pumps_: Turn a pump on for calibration.
  - On - desired pump for calibration.
* _Toggle_: Tests solenoid valves individually. The setpoint Toggle is used to set a solenoid valve to switch off and on quickly.

### Set Points
* _On_: This setpoint corresponds to Boolean 1 and is used to turn pumps on and open solenoid valves.
* _Off_: This setpoint corresponds to Boolean 0 and is used to turn pumps off and close solenoid valves.
* _Runtime_: This setpoint corresponds to the amount of time a certain state will run until it transitions into the next state (this setpoint is used in automatic mode).

### Variables
* _Influent/Backwash/PACl Pump Speed_: These variables use pump control code. It has inputs of flow rate and mL/revolution. It outputs a pump fraction.
* _Clay Pump Speed_: This variable uses Proportional-Integral-Derivative (PID) control code. It has inputs of P, I, D, a target value, and a current value. It outputs a pump speed. P is the proportional term used to compile present values of error. I is the integral term that integrates the past values of error such that the system can detect how much change in the pump speed is needed to acquire the target value. The P and I values used were 500m and 200m, respectively.
* _PACl Flow Rate_: This variable uses chemical dosing pump speed code. It has inputs of influent flow rate, PACl stock concentration, and PACl dose concentration. It outputs a flow rate, which is used to determine the PACl pump speed.
* _Turbidity_: This variable uses turbidimeter code. It has an input of turbidimeter ID. It outputs the turbidity reading.
