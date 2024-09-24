Chris,

As you suggested, I've been trying to replicate the results in ["Returns Heterogeneity and Consumption Inequality over the Life Cycle"](https://www.nber.org/system/files/working_papers/w32490/w32490.pdf) by Claudio Daminato and Luigi Pistaferri. 

I want to run a regression like the one used to produce Table 1 on page 9 in the paper. To do so, I collected data from the 2019 PSID on age (ER72017), employment (ER72164), and years of education (ER76922), and for total net worth and wealth shares (cash and bonds (ER73848, ER73854), risky assets (ER73821), real estate (ER73799), private business wealth (ER73808), and pensions/IRA (ER73842, ER74036)).

The final step is where I'm stuck. I now want to collect the variables needed to compute returns to net worth, which is equation 1 in the paper, $$r_t = \frac{y_{t}^{c} + cg_t + y_{t}^{d}}{A_{t-1} + .5F_t}$$.

I was able to find interest income (ER73143) and dividends (ER73126). I also found a footnote that describes how to compute capital gains and losses. **But I cannot determine what lines of the PSID codebook the variables** $y_{t}^{c}$ **(payments on debt) and** $F_t$ **(net investment flows) are referring to**.

For example, there is a variable ER72053 "A25 MNTHLY PMTS MOR 1" with associated question "A25. How much are your monthly loan payments?--FIRST MORTGAGE". This was the closest reference to a payment on debt that I could find, and it is only for a single asset class. The same issue is true for net investment flows.  

Do you have any advice about what to do next?
