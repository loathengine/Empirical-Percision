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

The Law of Large Numbers (LLN) posits that as the number of observations increases, the sample mean approaches the true population mean.  When applied to shooting every additional shot recorded gets your results closer to the truth.   In precision shooting, larger shot counts provide a more accurate depiction of a rifle system’s performance. Consider a coin flipped three times, all resulting in heads: this outcome does not "prove" the coin will always land on heads.   Similarly, a three-shot group does not definitively establish capability. Intuitively, people might require twenty, thirty, fifty, or even hundreds of coinflips to be convinced the a coin is in fact a heads only coin.  From some reason small shooting samples are often accepted without scrutiny. This might be because simple systems (like coin flips) are more intutivelly evaluated, while complex systems like rifles do not have a simple obvious way to prove out.  The more data you have the more likely your analysis is closer to the truth.

***

## Data-Driven Methodology: Record every data point.

All shots contribute valuable information. Discarding data, such as outliers (fliers), compromises data integrity and wastes resources. Record every shot you fire.  

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

**Extreme Spread (ES)** measures the distance between the two furthest shots, emphasizing the least favorable outcomes. Relying solely on small groups or excluding outliers introduces bias, which may benefit promotional efforts but undermines objective testing. Every recorded shot enhances the dataset’s integrity.

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
