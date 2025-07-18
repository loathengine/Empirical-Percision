# Empirical Precision: A No-Nonsense Approach to Shooting Analysis

This guide provides a structured methodology for evaluating precision shooting performance. It is intended to assess a rifle system through objective, repeatable techniques.

***

## BLUF: Bottom Line Up Front

Real analysis is neither cheap nor easy.  Mid-tier modern rifles can often exhibit exemplary performance, and surpassing those capabilities requires significant discipline.  There are no shortcuts, gadgets, lucky charms, or rituals to simplify precision shooting. Anyone telling you differently is trying to sell you something.  

***

## Historical Context: Transitioning from Anecdotal to Statistical Evaluation

My first experience with a scoped rifle was sighting in using three-shot groups. Under my father’s direction, I fired three rounds, adjusted the scope, and repeated until it was "dead nuts on".  Leaving the range with over half of the single box of .30-06 Core-Lokt that was brought. That box likely lasted at least two more seasons. This approach proved sufficient for me at the time. I was indoctrinated. For years, I relied on three- or five-shot groups to assess rifle systems because it was simplistic, cost-effective, and... it just worked.

Then came the internet, and with it, as many forum posts and evaluation methods as fathers and sons needing to sight in a rifle.  But something wasn't adding up. How can so many different methods still end up with the same results? If every technique did the job, how could any technique not do the job?  I believe that with so many methods in competition to be the "right" method, it lead to a paradigm shift.  This paradigm was to take advantage of many low standard test we used in our youth that "just worked".   But what worked to sight in a 40 year old rifle with hardware store hunting ammo should not be the same test used to prove if a 0.2 grain change in powder charge moves the system into an advantageous waveform harmonic.  Extraordinary claims require extraordinary evidence.

***

## Statistical Foundation: The Law of Large Numbers

The Law of Large Numbers (LLN) posits that as the number of observations increases, the sample mean approaches the true mean. 

**Randomness in the Short Run**  The small collections in a short-run are inherently uncertain.

**Convergence in the Long Run:** Regardless of the initial conditions, all systems will eventually converge to the same long-run level.    

**Examples of LLN in the wild:**

Casino Games: Casinos rely on the Law of Large Numbers. While a player might win or lose a few spins of roulette, over thousands of spins, the casino is guaranteed to make a profit because the house edge will play out as expected.

Insurance: Insurance companies use the Law of Large Numbers to assess risk. By collecting premiums from a large pool of policyholders, they can reliably predict the number of claims they will have to pay out and adjust premiums accordingly.

Medical: In medical studies, researchers are expected to use large sample sizes to ensure that their observations are representative of the entire population. The fluctuation in small samples can not be expected to accurately reflect the truth.

***

## Data-Driven Methodology: Every shot is important.

All shots contribute valuable information. Discarding data, such as outliers (fliers), compromises data integrity. Record every shot you fire.  The decision to exclude data points from the analysis should not be taken lightly and must be carefully considered and justified. Removing data points can lead to biased or misleading conclusions, undermining the integrity of research or analysis. 

**Bias and distorted results:** Removing shots that don't fit a desired outcome can skew results, creating a distorted picture of the data and leading to inaccurate conclusions.  

**Loss of valuable information:** Fliers or unusual shots might represent valuable information that could shed light on unexpected phenomena, errors in data collection, or even reveal insights about the rifle system.

**Reduced statistical power:** Removing data can decrease the variability in the dataset, which in turn reduces statistical power and potentially impacts the ability to detect true effects or relationships.

**Compromised transparency and reproducibility:** "Rationalizing" reasons for excluding data points compromises transparency and reproducibility, making it difficult to understand and/or replicate the analysis.  Examples of data to exclude would be something like sighter, warm up, and fouling shots.  But once you commit to printing shots... record the shots.    

***

## Establishing a Baseline
A baseline represents the rifle system’s performance in a known state.  When you establish the baseline, you will always be able to reference that baseline to compare all future changes to the system.  

### Cost Considerations
Precision shooting entails significant expense, and this methodology increases initial costs.  However, this short term investment reduces long-term cost by producing concrete results that can be used for the life of the rifle system.  

### Data Collection Protocol
Conduct testing in a controlled environment to minimize variables. I utilize a rest on an ammunition shelf at an indoor facility.  For you, it might be shooting prone with sandbags.  Control for all the variables you can, and never change more than one variable at a time.

Choose a target that is easy to read, and if possible, easy to take back home with you.  Analysis is easier at home on the coffee table than in the field.

Position impacts away from your point of aim.  Its very possible to shoot out your POA, making it harder to maintain your POA.

Record each shot’s horizontal (X) and vertical (Y) distance from the point of aim.  I often adjust the scope so impacts are above and to the right of the point of aim.  This is beneficial when recording data because, on a grid, up (Y) and right (X) can both be positive integers.  I will provide tools that handle negative points on a grid, but if you want to do it by hand, it's easier to keep all the math done in the real of "natural" numbers.  

### Sample Size Guidance
A minimum of twenty shots is advised. In most cases, statistical precision emerges around 30 shots and remains consistent beyond 50.  Based on experience, 20 shots should suffice for our initial purpose, especially compared to 3/5 shot groups. There's no universally "magic" number for a minimum number of shots.  As shooters, we face constraints of time, money, and resources. While larger samples are generally better, there's a point of diminishing returns where the additional precision gained from a larger sample doesn't justify the increased cost and effort. If you are arguing the validity of 30 shots vs 20 shots, then you don't need this guide.

***

## Okay... Now what

Now we apply a bit of math to our data and see what comes out the other end.  All the math basically works with small amounts of data but to reiterate, small data sets only prove that your results can't be proven.   

### Terminology of Key Metrics

| Term | Definition | Example in Shooting |
| :--- | :--- | :--- |
| **Horizontal ES** | Extreme Spread on the horizontal plane |  Usefull for troubleshooting problems like windage correction |
| **Vertical ES** | Extreme Spread on the vertical plane | Usefull for troupleshooting problems like volicity isssues |
| **H/V Ratio** | Ration of horizontal vs virticle plane |  Closer to 1 the better |
| **Mean Radius (MR)** | Average distance of each shot from the group’s center. | Indicator of the dispersion size (smaller is better) |
| **Standard Deviation** | Measure of variability in data points. | Consistency of shot placement (smaller is better). |
| **MoE (95% CI)** | Margin of Error at a 95% Confidence Interval | The error rate expected based on the amount of data (more shots = less error) |
| **P95 Range** | The radius of a circle that contains 95% of the shots with the MoE applied. | A P95 of 0.8 to 1.2 inches means 95% of shots will land within a 0.8 to 1.2-inch radius of the group's center. |

***

## Comparing Extreme Spread (Group size)

Extreme Spread (ES) measures the distance between the two furthest shots, analyzing only the two worst shots.  This is a less useful form of analysis.  If you are printing 3-shot groups, there is no other data to derive from the group.  If you are printing 20-shot groups, there are significantly more tools that make use of EVERY shot.

ES remains useful for diagnosing significant malfunctions. For instance, a $7,000 rifle advertised as sub-0.5 MOA yielding a 6-inch ES after three shots suggests issues such as unsecured optics or defective ammunition, requiring no further testing to identify a problem.  It should be understood that if the group is "bad" there is no reason to continue testing unless you just want to prove how bad the group is.  Example case might be where you print a 6 in group at 100 yards.  The single variable you change is scope rings.  You return to test, and the first 3 shots are 5 inches.  No point wasting shots, three shots is enough to prove that changing the scope rings didn't turn it from a 6moa system to a .5moa system.  

**Mean Radius (MR)** (MR) calculation involves determining the group center, measuring each shot’s distance using the formula $\sqrt{((x_2 - x_1)^2 + (y_2 - y_1)^2)}$, and computing the average. Dont panic, modern technology simplifies this process.  MR offers a more thorough assessment by averaging the distance of each shot from the group’s center, rather than focusing on the two most extreme shots.  When using ES you might be tempted to exclude a "flier" because you realize that one data point is VERY significant to the results.  In using MR any "fleir" is much less significant becuse MR uses averaging... and that's the point.  



***

## Factors Affecting Accuracy in Short-Range Precision Shooting

The accuracy of short-range precision shooting (typically under 100 yards) depends on a hierarchy of components.

### 1. The Shooter (Most Critical)
Human error is often the largest variable.
* **Fundamentals of Marksmanship:** Trigger control, sight picture, breath control, and follow-through are paramount.
* **Position:** A stable, repeatable shooting platform (stance, grip, cheek weld) minimizes movement.
* **Mental State:** Stress, anxiety, and fatigue can severely impact fine motor skills.
* **Practice:** Consistent practice, including dry firing, builds muscle memory and confidence.

### 2. The Rifle System (Hardware)
A good rifle system provides the foundation for consistent accuracy.
* **Barrel Quality:** A high-quality, consistent barrel is essential for consistent bullet flight.
* **Optics:** Clear, high-quality optics with a properly mounted and zeroed scope are crucial.
* **Trigger Quality:** A crisp, consistent trigger with a predictable pull weight aids proper trigger control.
* **Action and Bedding:** A well-built action and proper bedding ensure consistency.
* **Stock:** A stable and comfortable stock contributes to shooter stability.
* **Mounting Systems:** The stability of optic mounts and rails ensures a repeatable zero.

### 3. Ammunition Consistency
Inconsistent ammunition will lead to variations in point of impact.
* **Bullet Consistency:** Uniform bullet weight, shape, and construction are key.
* **Powder Consistency:** Consistent powder charges ensure uniform muzzle velocity.
* **Primer Consistency:** Reliable and consistent ignition of the powder charge is necessary.
* **Case Consistency:** Uniform case dimensions and neck tension contribute to consistent bullet seating and pressure.

### 4. Environmental Factors
While less dominant at short range, these factors are still relevant.
* **Wind:** Even light breezes can push a bullet off course.
* **Temperature:** Affects powder burn rates and air density.
* **Humidity/Barometric Pressure:** Affects air density, which influences bullet drag.
