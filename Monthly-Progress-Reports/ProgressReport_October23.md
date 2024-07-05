# Report on Research Progress

**Ph.D. Student:** Decory Edwards
**Main Advisor:** Chris Carroll
**Work Completed in (month/year):** October 2023
**Date Filed:** October 4 2023

1. Please list meetings (frequency, forum, etc.) with your main advisor.
* We meet every Friday at 4pm with some exceptions.

2. Please list meetings with other faculty and/or advisors.

* For now, my only meetings are with my main advisor, Chris. My second advisor is Nick. I have been thinking that, since I am seeming to go down the road of “macroeconometrics” , my second advisor should be Professor Wright (with whom I am currently taking a class with). 

3. For my job market paper, 

I planned (last month) to accomplish the following:
* Finish solving and understanding the results of the most baseline version of the model.
* Prepare adequately enough to give a presentation during the Macro Seminar.

For my job market paper, I accomplished the following:
* I would say that I accomplished both of these.

Supposing there are discrepancies between a and b, explain why.

For my job market paper, I plan to accomplish the following next month:
* “Code up” the life-cycle version of the model and compare the solution there to the solution to the baseline model. 
* Extensively go through the JEDC volume and provide citations from each of the (eight) papers there regarding the calibration methods used in those models. In particular, I want to be very clear on where each of these values come from. Some are more straightforward than others; in particular, I want to be sure where the capital-to-output ratio comes from. In my first reading of the volume, I could not find it anywhere.

4. What other papers are you working on? With whom?
* The other things I am working on are not “papers” in particular at the moment. However, my RA work with Chris and the rest of the econ-ark team will help me to complete my JMP. I will now outline these “adjacent” tasks below.

* In the DoW repository,, I need to amend the code so that it restricts the search space for the estimation using i) log differences and ii) truncated lognormal distribution. Task ii) may not be necessary, since I am considering discretizations of the lognormal distribution. However, I need to be sure that the selected points do not violate a certain condition.

* I want to write a python program that computes the empirical targets that are used to estimate the model in my JMP and other similar models. The goal is that this code gets merged into the HARK toolkit, since reproducibility is both a goal of that toolkit and the primary motivation for me writing this code. There is a recent paper which summarizes the SCF wealth data by Wolff which will be a useful comparison in making sure the code accomplishes this task.

* To be specific, I want to write code which does the following for each SCF wave:
    * Computes a measure of net worth and net worth minus retirement
    * Computes a measure of liquid wealth and liquid wealth minus retirement
    * Computes the aggregate capital-to-output ratio for all four of these wealth measures
    * Computes the wealth shares (both the full lorenz curve and the shares held by the 20,40,60, and 80 percentiles) for all four of these wealth measures

I will also need to understand the tools/code already available in HARK which is related to using SCF data.

* Finish working on “SolvingMicroDSOPs”. To complete this, I need to meet with an older student to understand some code in the associated repository (as well as read the accompanying paper). 

5. For each paper listed in 4, please answer the questions in 3?
