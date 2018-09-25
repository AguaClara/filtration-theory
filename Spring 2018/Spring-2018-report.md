# StaRS Filter Theory, Spring 2018
#### Alison Valibuena, Liz Cantlebary, Dylan Vu
#### April 25, 2018

## Abstract
Sand filters have historically been used to lower the turbidity of water and are still used in conventional filtration systems. The research in this report is based on the hypothesis that flocs are captured in rings created by filter grains, which implies there is an active filtration zone where empty pores become clogged by the flocs. This active zone moves throughout the bed until there is no remaining space for particles to clog. This research examines the factors that influence the time it takes for the filter to clog.  Several key factors affect the failure time including size and density of flocs and were explored through experiments with different coagulant doses and with a constriction placed before the filter.

## Introduction
Sand filtration has been used since ancient times. One of the most common types of sand filtration is the rapid (gravity) sand filtration, used in  AguaClara water treatment plants. This filtration method requires the use of flocculant chemicals to aggregate small particles for filtration. The filter has proven to clean the water below 0.3 NTU, meeting the EPA standards. This can be found from experimentation performed on the model sand filter and sand filters in the water treatment plants built in Honduras.

The goal of the Stacked Rapid Sand (StaRS) Filtration Theory sub-team is to develop a mathematical model describing the interaction of flocs and the filter medium. To do so, the relevant filtration parameters must be determined in order to optimize water filtration, and thus filter performance. The ultimate goal of sand filtration is low effluent turbidity and long filtration duration. Some examples of filter parameters considered were coagulant dosage, influent flow rate, influent turbidity, and backwash duration. The Spring 2018 team incorporated a new factor, floc size, which could potentially affect the effluent turbidity and failure time of the deep bed sand filter.

The main goal of the Spring 2018 team was to investigate the idea that the filter has a volume capacity before failure time. Therefore, the team conducted experiments with a constriction installed inside the tubing of the apparatus. The size of the constriction is  approximately half of the inner diameter of the influent tubing. Its purpose was to reduce the volume of flocs by increasing the shear force felt by the flocs. Additionally, previous teams have found that experiments at lower Polyaluminum Chloride (PACl) dosages saw better filter performance. Thus, the team is conducting experiments at lower coagulant dosages, 0.1mg/L, 0.04mg/L and 0.08mg/L, to confirm this trend. The team seeks to determine the effect of floc volume and low PACl dosage on filter performance after data analysis.

Knowing the parameters affect failure time is the key to enhanced the effectiveness of the stacked filter. In that case the apparatus’ longer failure time and cleaner water, will ensure reduced labor work and energy savings since the filter would not need to be backwashed as frequently at the AguaClara plants. Overall, better water filtration achieved via an understanding of filtration physics will lead to more affordable and cleaner from AguaClara water treatment plants to benefit vulnerable communities worldwide.

## Literature Review

The team’s literature search revolved around finding failure mechanisms for the filter. Many different theories were explored. However, this section will focus on the theories that make the most sense intuitively and and can be readily tested on the team’s apparatus.

One theory the team explored was that the sand filter had a porosity limit that would induce filter failure when reached. A relation between the size of the flocs and the capacity of the sand grain pores to retain particles lead to the hypothesis that porosity affected filter performance. Przekop & Gradoń (2016) stated that the filter failed with a specific reduction in the porosity of the filter bed. Deeper analysis of this mechanism could be studied by comparing the volume of average flocs with the volume of the pores of the filter medium.

To understand how floc size could be related to porosity, another concept was considered: deposition of particles in the medium filter. In their paper, Tien et al. (1979) modeled a sand filter bed using the constricted tube model instead of the classic straight-capillary model, in which pores within the filter were similar to long straws with a constant width. It was found that the process of filtration could be split into two steps. The first part of the model had a clean bed with no particles attached to the grains; as water was run through the bed, particles began to deposit on the sand grains. The second part of this model sought to account for particle deposition, which changed over time, assuming that the particles coated sand grains uniformly. The model demonstrated that deposited particles increased the volume of solids within the filter. As a result, porosity within the sand bed decreased.

Additionally, it was found that reentrainment of particles also affected filter performance. Tien & Turian (1979) proposed that the redeposition of these aggregates was the main reason for pore blockage and filter clogging. Reentrainment in the context of sand filters is an observed phenomenon that deposited particles would become active in the filter and deposit elsewhere. Reentrainment occurs due to hydrodynamics effects, specifically shear stress. In as much as this effect was observed to clog the filter, reentrainment can lead to the chance that particles become active and escape the filter.

The model proposed by previous StaRS Filter Theory teams aimed to combine the information from previous sand bed research and results from experiments and link the effect of microscopic level physics on macroscopic filter performance. The visual model of constrictions found between the sand grains in the filter was developed by previous StaRS Filter Theory teams from the conclusions of several experimental runs until system failure. Filter failure was defined as the moment when effluent turbidity increases sharply. Kuan-mu Yao (1971) stated that the effectiveness of the filter depended on the size of the flocs. Thus, between experimental runs, the coagulant dosage was varied. Varying coagulant dosage changes the size/volume of flocs, which was theorized to affect filter performance.

The Fall 2016 StaRS filter theory team conducted several experiments to examine the effect of varying coagulant dosage on the effluent turbidity and failure time of the filter. The team used 6 different coagulant dosages (Figure 1). It was concluded that there was no visible relationship between effluent turbidity and PACl dosage from these experiments.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/spring%202016.png?raw=true" height=350 width=600>

Figure 1: Data detailing observed filter effluent turbidities over time for the six experiments performed with varying PACl concentrations (0, 0.2, 0.65, 1.1, 1.55, and 2 mg PACl/L.)

The Spring 2017 team’s mathematical and visual model hypothesized that “dirty” particle aggregated within the constricted pores of the sand bed in a washer-like geometry (Adelman, 2017). Additionally, the model predicts that as the pores are clogged, effluent turbidity from the filter would increase. In an attempt to confirm the proposed model, the Fall 2017 team conducted experiments to measure the effects of varying coagulant dosages on filter performance. Despite these predictions, no pattern was found between dosage and optimizing effluent turbidity over time, and no explanation has been offered for this discrepancy between theory and experimental results.

To further these experiments, the Fall 2017 team systematically varied dosages in filter runs to determine the effect of coagulant dose on filter performance and failure time. The team ran the set of experiments twice. The first set was done by gradually increasing PACl dosage, labeled ‘step up’. The second set was obtained by decreasing the PACl dosages, labeled ‘step down’. They also found out that backwashing the filter between filter runs for 20 minutes allowed more consistent results. Their findings are better be understood in the following figure (Figure 2). It was concluded from these experiments that at lower coagulant dosages, failure time was prolonged than that for higher coagulant dosages.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/failure%20time%20compiled.png?raw=true" height=350 width=600>

Figure 2: Failure time as a function of PACl at different dosages.

### Experimental Apparatus
The laboratory stacked rapid sand filter was created with a 65cm length of PVC filled with sand run through sieves that have a hole size 0.5 mm and 0.595 mm in diameter to a height of 40cm. There was one influent pipe and two effluent pipes, all with a diameter of 9.4 mm and made from copper. The apparatus is shown in Figure 3, and a schematic of full system can be seen in Figure 4.  The system was designed to replicate a conventional AguaClara water filtration plant after sedimentation.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/apparatus.png?raw=true" height=350 width=600>

Figure 3: StaRS Filter Theory experimental apparatus.

Tap water was pumped into the system and combined with clay and humic acid based on the concentrations calculated by Mathcad, with the stream having an average influent turbidity of 5 NTU to replicate the turbidity of water leaving sedimentation tanks in existing AguaClara plants. The contaminated water stream then entered the influent turbidimeter before going to the contact chamber, where the contaminated water is mixed with PACl, essentially making the clay particles sticky. After leaving the contact chamber, the water entered the flocculator, a helical coil made of flexible tubing with a 0.625 mm diameter. The flocculator was designed to increase collisions between clay particles to create flocs that could then be more easily removed in the stacked rapid sand filter. As determined by previous teams, the flocculator was designed with a residence time of 2.67 s for a flow rate of 1.98 mL/s. The energy dissipation rate was 0.27 W/kg, which kept flocs small to simulate influent water for filtration after sedimentation.

Once the water exits the flocculator, it is injected into the stacked filter at an average velocity of 1.8 mm/s as determined by previous teams. The residence time in the filter was 43.6 seconds on average ad determined by previous teams, after which the water exits the filter through one of the effluent pipes. The two effluent streams mix and then go into the effluent turbidimeter to measure the turbidity of the water. The difference in turbidity between the influent and effluent water can be used to determine filter quality. There is also a 200 kPA pressure sensor immediately before the water enters the filter and immediately after the two effluent pipes combine to measure the head loss caused by the rapid filtration. The head loss is the amount of energy lost in the filter due to external forces, and needs to be minimized in order to prevent clogging.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/apparatus.jpg?raw=true" height=500 width=1000>

Figure 3: The schematic for the experimental filter apparatus in filter mode showing influent and effluent turbidimeter sampling systems, PACl solution and clay, humic acid solution dosing, pressure sensor to measure filter head loss, and flocculator. Blue connections are used in filter mode while gray connections are used in backwash mode.

### Procedure
The goal of the first set of experiments was to observe if density of particles is the defining factor in filter failure because the flocs would occupy more volume.  A constriction was placed in the influent tubing immediately before the filter. The constriction had half the diameter of the apparatus tubing to create a head loss of approximately 8m in the system. The increased shear force breaks the flocs apart, removing the effect of density and particle size on failure time. This experiment was run with PACl concentration of 2mg/L, 1.55mg/L, 1.1mg/L, 0.65mg/L, 0.2mg/L. All experiments were run with a 1.967mL/s influent flow rate, and the influent turbidity was programmed to stay at 5NTU. The concentration of clay and humic acid in the stock tank was determined by the Mathcad file. The pump speed of the PACl pump and concentration of the PACl stock was calculated based on the team’s Mathcad file to achieve the desired concentration of PACl per liter of water. The runtime of each experiment was 12 hours.

The goal of the second set of experiments confirmed the efficacy of the constriction used in the first experiment. Influent clay particles were mixed with red dye and high definition video footage of the flocs before and after the constriction was filmed. A decrease in the average size of flocs would implicate that the constriction was working as hypothesized. The influent flow rate for this experiment was 1.79mL/s. The clay stock concentration was 1.84g/L, and the pump was set to 13.3RPM. The PACl concentration was 0.025mL/s and 0.0125mL/s. Both PACl doses were run with and without the constriction in place.

The purpose of the third set of experiments was to test the hypothesis that there is an optimal PACl dose below 0.2mg/L. At the optimal PACl dose, the filter would have a longer run time than higher doses of PACl without jeopardizing the quality of the effluent water stream. PACl doses of 0.04mg/L and 0.1mg/L were used in two separate experiments.  Both experiments were run with a 1.967mL/s influent flow rate, and the influent turbidity is programmed to stay at 5NTU. The concentration of clay and humic acid in the stock tank was determined by the Mathcad file. The pump speed of the PACl pump and concentration of the PACl stock was calculated based on the team’s Mathcad file to achieve the desired concentration of PACl per liter of water. The runtime of each experiment was 12 hours.

## Results and Analysis
To ensure the filter performance was consistent with previous semesters, an experiment was performed with a 2mg/L PACl dose, chosen arbitrarily. Figure 5 shows the plot of the effluent turbidity versus time data. Filter failure time, defined as the time at which the effluent turbidity diverges from the constant turbidity, was consistent with previous semesters. From this result, it was concluded that subsequent results would be valid.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/control%202018.PNG?raw=true" height=350 width=600>

Figure 5: Plot showing effluent filter turbidity vs. time for the test performed to confirm system consistency. It was observed that the filter failure time occurred around 1.65 hours, when the effluent turbidity starts to diverge.

The following filter tests were performed to test the effects of particle size on filter performance. A constriction was added before the filter influent line to break the flocs created in the flocculator. The range of PACl dosages experimented with were the same used by previous StaRS Filter Theory teams (0.2-2.0 mg/L of PACl). Error bars for the control experiments were created from StaRS Filter Theory Spring 2016 and Fall 2017 failure times. Figure 6 shows a summary of the failure times for the various PACl dosages in the control and constriction experiments. It was observed that decreasing the PACl dose from 1.55 mg/L to 1.1 mg/L caused a sudden change in the way the filter performance was affected by the constriction. The team hypothesized that the constriction breaks the flocs apart, but the increased flow rate after the constriction may lead to flocculation. For the lower-range PACl dosages, the flocculation at the constriction is minimal compared to the effect of shear force breaking the flocs apart. Based on this, the particles decrease in size before entering the filter, causing the filter to fail later, as the smaller particles can be better entrained in the sand pores. Conversely, for higher PACl dosages, the effect of flocculation at the constriction contributed more to the size of particles entering the filter. Thus, the particles became larger prior to entering the filter, causing the filter to fail sooner.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/constriction%20compiled.png?raw=true" height=350 width=600>

Figure 6: The plot shows failure time as a function of PACl dosage. It compares results for experiments run with a constriction installed before the filter, "Constriction Experiments", and experiments run without a constriction, "Control Experiments", performed in previous semesters.



To verify that the constriction did have an effect on floc size, experiments utilizing red dye were performed. The stream of flocs was recorded with and without the constriction. It was visually determined that the size of the flocs was significantly decreased due to the constriction. Thus, it was determined that the varying filter performance was directly related to the changed particle volume size, as every other parameter was kept constant. The videos can be found by following the link below:


https://github.com/AguaClara/stars_filter_theory/issues/22

The turbidity difference tests were performed to determine whether the size of the particle would have a significant impact on how the turbidimeter read turbidity. It was determined that although there was a consistent difference in turbidity between the influent and effluent turbidity, this difference was insignificant. The average difference in influent and effluent turbidity was around 4% of the controlled turbidity of the water for the experiments. A graphic with the all the performed experiments compiled can be found below (Figure 7).

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/turbidity%20diff.png?raw=true" height=350 width=600>

Figure 7: Plot showing difference between influent turbidity and effluent turbidity when 5NTU water was run through the influent turbidimeter, into the flocculator, and through the effluent turbiditer.

Next, the low PACl concentration experiments were performed without the constriction. The team wanted to explore a lower range of PACl concentrations for filter runs because previous teams have found that while turbidity remained similar throughout all PACl dosages tested, the failure time for lower dosages was much longer. This meant that the filter was operational for a longer period of time when lower PACl dosages were used for same performance levels. The range the team planned to test was 0.02-0.10 mg/L PACL. It was found that the filter did not fail within the 12h time period for the 0.10 mg/L PACl dosage, with effluent turbidity staying between 0.10-0.15 NTU. This was the best performance ever seen for this filter. Next, the 0.04 mg/L PACl dosage was tested. The filter failed around 3.6h, a significant decrease from the 0.10 mg/L PACl dosage. However, it was noted that while effluent turbidity diverged from 3.6h, the divergence was less exaggerated as seen in previous tests for higher PACl dosages. The team believed that there may be an optimal PACl dosage around 0.10 mg/L. The data for each of these tests can be found below (Figures 8 & 9).

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/0.10mgL%20pacl.png?raw=true" height=350 width=600>

Figure 8: Effluent turbidity vs. time for 0.10 mg/L PACl dosage experiment.

<img src="https://github.com/AguaClara/stars_filter_theory/blob/master/0.04mgL%20pacl.png?raw=true" height=350 width=600>

Figure 9: Effluent turbidity vs. time for 0.04 mg/L PACl dosage experiment.

## Conclusions
From the constriction runs and red-dye experiments, it was determined that the size of the particles did affect filter performance. It was known that as PACl dosage changed, the size and density of the flocs also changed as a function of PACl added. The varying filter performance, under a controlled PACl dosage, could only be caused by the placement of the constriction and the resulting change to floc size. However, conflicting results on the effect of the constriction on floc size were found. The constriction seemed to have varying effects on filter performance, as controlled by PACl dosage. At larger PACl concentrations, the filter performed worse. While, at lower PACl concentrations, the filter performed better. The team hypothesized a push/pull relationship between how the constriction can both break flocs and act as a site for further flocculation. This relation was hypothesized to be dependent on particle size, and thus PACl dosage, entering the constriction.

From the effluent turbidity tests, it was concluded that the turbidimeters used largely corrected for potential differences in turbidity readings due to particle size/particle density in the cuvette.

From the low PACl dosage tests without the constriction, the team concluded that there seemed to be an optimal PACl dosage for filter performance. That dosage was somewhere near 0.10 mg/L PACl, but further testing needed to be performed to confirm this. These results could change the way that PACl should be dosed at water treatment plants in Honduras.

## Future Work
The team will continue to run the lower PACl dosage experiments: 0.02 to 0.10 mg/L PACl range. Then, the team will rerun these experiments with the needle valve constriction to replicate the experiments done at the previous PACl dosage range (0.2 to 2 mg/L PACl), during the earlier half of the semester.

In the long term, the team will look to examine the effects of high G flocculation on filter performance. It is hypothesized that the particles that escape the filter are the primary particles that bypassed flocculation. This is due to the assumed effect that when particles aggregate into larger flocs, it becomes harder for these larger flocs to combine with particles smaller than their size (due to shear force and other factors). These primary particles then bypass the filter and exit with the cleaned water. It is believed that high G flocculation will produce a more uniform distribution of smaller flocs, as the steeper velocity gradient will disproportionately-sized flocs from forming. Thus, these smaller flocs will be able to flocculate with isolated primary particles during flocculation. Further, it has been found that in traditional flocculation, PACl particles tend to stick to flocculator walls, decreasing the expected dosage; in contrast, high G flocculation has been found to fix this problem. This should increase the PACl coverage on the clay particles, facilitating better flocculation and entrainment in the filter.

## Bibliography
Kuan-Mu Yao, Mohammad T. Habibian, and Charles R. O'Melia (1971). Water and waste water filtration. Concepts and applications. ACS publications, 5 (11), 1105-1112
doi: 10.1021/es60058a005.

Przekop, R. & Gradoń, L. (2016). Dynamics of particle loading in deep-bed filter. Transport, deposition and reentrainment. Chemical and Process Engineering, 37(3), pp. 405-417. doi:10.1515/cpe-2016-0033

Tien, C., Turian, R. M., and Pendse, H. (1979). Simulation of the dynamic behavior of deep bed filters. AIChE Journal, 25(3):385–395.

# Manual

## Experimental Methods
### Set-up
Replenishing clay & PACl stocks:
1. Set the amount of liters needed for the stock tank
2. Calculate the mass amount necessary for this amount of water.
3. Weigh out the correct amount of clay and humic acid to the thousandths place.
4. Measure the correct amount of tap water in a Volumetric Flask. Use the water to pour any remaining clay or humic acid from the weight balance into the tank.

For PACl stock tank:
1. Use the deionized water in lab to partially fill a 1L  volumetric flask.
2. Pipette the correct volume of PACl needed for 1L of water.
3. Fill the rest of the flask with deionized water.
4. Repeat the process and refill the stock tank.

### Pre-Experiment Checklist
1. Calibrate the water pump by finding the rpm which yields a desired flow rate once a week.
2. Calibrate the PAC pump by finding the rpm which yields a desired flow rate once a week..
3. Calibrate the clay pump through ProCoDa once a week.
4. Follow cleaning protocol.

### Experiment Steps
1. Use the filter no clay state to ensure there are no air bubbles in the system before the filter.
2. Prime PACl pump to get rid of air bubbles in tubing PACl tank to contact chamber.
3. Backwash again if there are air bubbles in the filter.
4. Use the filter no clay state to run water until effluent turbidity is below 0.5 NTU, indicating that residual clay and coagulant is minimal.
5. Use the off state and ensure the height of the settled bed remains constant between experimental runs, if necessary, externally agitate the filter to settle the bed.  Ensure there is no sand stuck a the top of the filer by tapping the pipe with the hammer.
6. Ensure the influent water turbidity is as expected for clean tap water.
7. Ensure the mixer for the clay stock tank is on.
8. Ensure the valves to the bed and the PACl stock tank are open, ensure the lid to the PACl stock tank is unscrewed
9. Ensure that there is enough solution the PACl and clay stock tanks for the experiment run. Instructions for replenishing the stock tanks are below.
10. Ensure the data is going to the proper file on the computer to prevent lost data. It should either be automatically uploaded to Google drive or the data should be manually uploaded after the experiment is completed.
11. State: Open Solenoid Valves. Zero pressure sensor in ProCoDA (Click Volts, click Zero). Turn on the Clay pump.
12. State: Filter. Start a new experiment. Manually set PACl pump speed. Turn on Automatic mode. Turn on the clay pump and the start the PACl pump.
13. Ensure that PID control for the clay pump properly adjusts the influent turbidity to target turbidity.


### Cleaning Procedure
A cleaning protocol was formalized so that each filter run started with a clean filter, flocculator, and system tubing. Cleaning involves steps to help sand in the filter fluidize and clean the filter, clean the walls of the tubing, contact chamber, flocculator, and cuvettes for the next filter run. A successful backwash state is when the filter sand fluidizes completely and the system is in the Backwash state continuously without sand clogging the apparatus and preventing water flow. Vinegar is used in cleaning to reduce the pH of the water and allow the coagulant to dissolve into the water more easily. The state of the system begins in the Off state after a filter run. Only the influent water pump should be on.

Clean filter sand
1. State: Filter no clay for 1 minute.
2. State: Backwash Half Flow. Ensure that the filter bed fluidizes.
3. State: Backwash Toggle. Ensure that the filter bed fluidizes at the full flow rate while the solenoid valve controlling influent water for backwash is toggling.
4. State: Backwash. Run for 20 minutes, and continue backwashing if there are visible clay particles in the filter. If the filter sand has not yet fluidized, Off, Backwash Half Flow, Backwash Toggle, and Backwash helps break up the sand column.
5. State: Off.

Clean contact chamber, flocculator, and tubing from PACl stock tank.
1. Close the manual valve after the flocculator. Disconnect the system at the tubing after the flocculator and before the valve. Turn the clay pump off.
2. State: Filter. Place a bucket at the open end of the flocculator to catch influent water.
3. Replace the PACl stock tank with a tank of vinegar (5\% acidity).
4. Run the PACl pump at full speed for 30 s to flush the contact chamber and flocculator with vinegar.
5. Replace tank of vinegar with tank of water. Run the PACl pump at full speed for 30 s to remove vinegar from the system.
6. State: Off.
7. Clean the contact chamber, flocculator, and tubing. Disconnect the system at the tubing before the contact chamber and flush the dirty parts of the system with water.
8. Reconnect all parts leading up to the filter. Ensure the piece of micro-tubing in the contact chamber is approximately half way in the chamber.

Clean turbidimeters
1. Empty turbidimeter cuvettes and rinse with DI water.
2. Screw cuvettes back in and wipe outside with a Kimwipe. Do not reassemble turbidimeters yet.
3. State: Filter. Ensure that there are no leaks from the cuvettes.
4. Shake to ensure there are no air bubbles in the system.
5. State: Off. Reconnect system at flocculator.
6. If there are no leaks, put the cuvettes back into the turbidimeter.

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
