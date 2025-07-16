# Empirical Precision: A Rational Approach to Shooting Analysis

This guide provides a systematic methodology for evaluating precision shooting performance. It is intended to assess a rifle system through objective, repeatable techniques.

***

## BLUF: Bottom Line Up Front

Deep analysis is neither cheap nor easy.  Shooter proficiency is still the primary determinant of performance; equipment upgrades yield progressively smaller benefits. Mid-tier modern rifles often exhibit exemplary performance, and surpassing their capabilities requires significant discipline. No gadget can simplify precision shooting. Anyone telling you differently is trying to sell you something.  If the best someone can provide is a three or five shot group, they are not proving it works; they are proving that they don't intend to show you a large sample of it working.  

***

## Historical Context: Transitioning from Anecdotal to Statistical Evaluation

My first experience with a scoped rifle was sighting in using three-shot groups. Under my father’s direction, I fired three rounds, adjusted the scope, and repeated until it was "dead nuts on".  Leaving the range with over half of the single box of .30-06 Core-Lokt that was brought. That box likely lasted at least two more seasons. This approach proved sufficient for me at the time. I was indoctrinated. For years, I relied on three- or five-shot groups to assess rifle systems because it is simplistic, cost-effective, and adequate...  and it just worked.

Then came the internet, and with it, as many forum posts and evaluation methods as fathers and sons needed to sight in a rifle. Each was endorsed by its proponents. But something wasn't adding up. How can so many different methods, claiming to be the best, still end up with the same results? If every method were best, how could any be the best? I believe that with so many methods in competition to be the "right" method, a new paradigm has formed.  This paradigm was that a small group SUB-MOA was above reproach. Companies were less interested in figuring out if small MOAs were the best way to evaluate a rifle system and more interested in getting a picture of a three-shot group with a small MOA to post on a shooting forum. It's unclear if the MOA was pushed by the snake oil salesmen or if they just adopted it, but either way they jumped on the bandwagon and started selling their sub moa wares.  Shortly after, youtube was also filled with videos demonstrating sub MOA three shot groups as proof of the product.

**Indicators of Unreliable Information:**
* **Limited sample sizes:** Assertions based on three-shot groups labeled as "sub-MOA."
* **Selective reporting:** Exclusion of outliers to artificially improve results.
* **Insufficient detail:** Absence of testing conditions, such as the number of groups previously shot.
* **Overstated simplicity:** Claims that inexpensive tools can significantly enhance precision.  Chances are high that if something is cheap and easy rifle manufacturers would already be doing it.  

***

## Statistical Foundation: The Law of Large Numbers

The Law of Large Numbers is a principle in probability that states that as the number of trials of a random process increases, the average of the outcomes will converge towards the expected value. In simpler terms, the more times you repeat an experiment, the closer the average result will get to the theoretical average. 
Here's a more detailed explanation:

### Expected Value:
Every random event has an expected value, which is the average outcome you would expect if the event were repeated infinitely many times. For example, a fair coin flip has an expected value of 0.5 (50% chance of heads). 
### Randomness in the Short Run:
In the short term, random events can be unpredictable. Flipping a coin a few times might result in a sequence of mostly heads or mostly tails, even though the long-term probability is 50/50. 
###Convergence in the Long Run:
As the number of coin flips increases, the proportion of heads will get closer and closer to 50%. This is the essence of the Law of Large Numbers. The average of the results will tend to stabilize around the expected value. 
### Examples:
Casino Games: Casinos rely on the Law of Large Numbers. While a player might win or lose a few spins of roulette, over thousands of spins, the casino is guaranteed to make a profit because the house edge will play out as expected. 
Insurance: Insurance companies use the Law of Large Numbers to assess risk. By collecting premiums from a large pool of policyholders, they can reliably predict the number of claims they will have to pay out and adjust premiums accordingly. 
Research: In scientific studies, researchers use large sample sizes to ensure that their results are representative of the population they are studying. Small sample sizes are more prone to random fluctuations and may not accurately reflect the true population average. 
Law of Truly Large Numbers:
There's also a related concept called the "Law of Truly Large Numbers," which suggests that with a large enough number of trials, even extremely unlikely events can eventually occur. For instance, while it's improbable to win the lottery, if you play for a very long time, the odds of winning at some point increase. 


The Law of Large Numbers (LLN) posits that as the number of observations increases, the sample mean approaches the true mean.  In precision shooting, larger shot counts provide a more accurate depiction of a rifle system’s performance.  An analogy of when it is natural to expect a large sample size would be if considering someone selling a coin that they claim will always land on heads.  The vendor then flips a coin three times, and all three flips the coin landed heads up. Its is intuitive to us that this outcome does not "prove" the coin will always land on heads.  We would seek a large sample size to prove the coin vender claims.  Similarly, a three-shot SUB-MOA group does not prove the rifle is SUB-MOA. To prove a coin will never land on tails, people might expect twenty, thirty, fifty, or even hundreds of coin flips to be performed to prove the claim.  The more data you have, the more likely your analysis is closer to the truth.

***

## Data-Driven Methodology: Every shot is important.

All shots contribute valuable information. Discarding data, such as outliers (fliers), compromises data integrity and wastes resources. Record every shot you fire.  Also make use of every data point.   

***

## Terminology and Key Metrics

| Term | Definition | Example in Shooting |
| :--- | :--- | :--- |
| **Standard Deviation** | Measure of variability in data points. | Consistency of shot placement (smaller is better). |
| **Mean Radius (MR)** | Average distance of each shot from the group’s center. | Indicator of the dispersion size (smaller is better) |
| **H/V Dispersion Ratio**| A ratio of horizontal to vertical standard deviation.  | >1.0 is a wide group, <1.0 is a tall group. | Tall groups (less than 1) can indicate volicity issues.
| **P95 (R95)** | The radius of a circle that contains 95% of the shots. | A P95 of 1.2 inches means 95% of shots will land within a 1.2-inch radius of the group's center. |


Horizontal ES:
Vertical ES:
H/V Ratio:
Mean Radius:
Std. Deviation:
MoE (95% CI):
P95 Range:

***

## Comparing Extreme Spread and Mean Radius

Extreme Spread (ES) measures the distance between the two furthest shots, analyzing only the two worst shots. Relying solely on small groups or excluding outliers introduces bias, which may benefit promotional efforts but undermine objective testing. Every recorded shot enhances the dataset’s integrity.

ES remains useful for diagnosing significant malfunctions. For instance, a $7,000 rifle advertised as sub-0.5 MOA yielding a 6-inch ES after three shots suggests issues such as unsecured optics or defective ammunition, requiring no further testing to identify a problem.

**Mean Radius (MR)** offers a more thorough assessment by averaging the distance of each shot from the group’s center, rather than focusing on extremes. For example, a 3-shot group with a 0.98-inch ES compared to a 10-shot group with the same ES intuitively differs in quality; MR quantifies this distinction. However, small samples (e.g., 3 or 10 shots) limit the applicability of the Law of Large Numbers. A minimum of 20 shots is recommended for dependable results.

MR calculation involves determining the group center, measuring each shot’s distance using the formula $\sqrt{((x_2 - x_1)^2 + (y_2 - y_1)^2)}$, and computing the average. Modern technology simplifies this process.

***

## Establishing a Baseline

### Cost Considerations
Precision shooting entails significant expense, and this methodology increases initial costs. A 20-shot baseline may require $20 to $50 in ammunition, depending on caliber. However, this investment reduces long-term inefficiencies by minimizing reliance on untested modifications.

### Data Collection Protocol
A baseline represents the rifle system’s performance before alterations. Conduct testing in a controlled environment, such as an indoor range with a bench rest, to minimize variables. I utilize a rest on an ammunition shelf at an indoor facility, acknowledging its limitations. Control measurable factors (e.g., wind, shooter position) and document uncontrollable variables (e.g., humidity, barrel temperature).

Record each shot’s horizontal (X) and vertical (Y) distance from the point of aim. Positioning impacts above and to the right of the point of aim eliminates negative values. Shots are fired, targets preserved, and measurements taken later using calipers. Limit shots per target to maintain clarity.

### Sample Size Guidance
A minimum of 20 shots is advised. Statistical reliability emerges around 20 shots, stabilizes by 30, and remains consistent beyond 50. Advanced tests, such as the Shapiro-Wilk method, assess data normality and are available on the referenced website, though optional. Based on experience, 20 shots suffice for practical purposes. All shots, including outliers, should be recorded.

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
