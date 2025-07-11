# Empirical Percision: A Rational Approach to Shooting Analysis

**This guide provides a systematic, data-driven methodology for evaluating precision shooting performance.** It is intended to objectively assess rifle system modifications (such as comparing reloaded versus factory ammunition or transitioning to a precision chassis) through repeatable, evidence-based techniques.

***

## BLUF: Bottom Line Up Front

**Shooter proficiency is the primary determinant of performance; equipment enhancements yield progressively smaller benefits.** Mid-tier modern rifles often exhibit exemplary performance, and surpassing their capabilities requires significant investment and effort. No device or technique can simplify precision shooting. Anyone telling you differently is trying to sell you something.  There is no easy button.

***

## Historical Context: Transitioning from Anecdotal to Statistical Evaluation

My first experience with a scoped rifle was sighting in using three-shot groups. Under my father’s direction, I fired three rounds, adjusted the scope, and repeated until it was "dead nuts on".  Leaving the range with over half of the single box of .30-06 Core-Lokt that was brought. That box likely lasted at least two more seasons. This approach proved sufficient for me at the time. I was indoctrinated. For years, I relied on three- or five-shot groups to assess rifle systems because it is simplistic, cost-effective, and adequate...  and it just worked

Then came the internet and with it as many forum posts and methods as there were fathers and sons needing to sight in a rifle. Each was endorsed by its proponents. But something wasn't adding up. How can so many different methods, claiming to be the best, still end up with the same results? If every method was best, how could any be the best? I beleive that with so many methods in competition to be the "right" method, a new paradigm formed.  This paradigm was that a small group SUB-MOA was above reproach. Companies were less interested in figuring out if small group MOAs where the best way to evaluate a rifle system and more interested in getting a picture of a three-shot group with a small MOA to post on a shooting forum. It's unclear if the MOA was pushed by the snake oil salesmen or if they just adopted it, but either way they jumped on the bbandwagen and starting selling their wares always claiming sub moa.  Shortly after youtube was also filled with videos demonstrating sub MOA three-shot group as the proof of their products.

**Indicators of Unreliable Information:**
* **Limited sample sizes:** Assertions based on three-shot groups labeled as "sub-MOA."
* **Selective reporting:** Exclusion of outliers to artificially improve results.
* **Insufficient detail:** Absence of testing conditions, such as range or environmental factors.
* **Overstated simplicity:** Claims that inexpensive tools can significantly enhance precision without evidence.

***

## Statistical Foundation: The Law of Large Numbers

The Law of Large Numbers (LLN) posits that as the number of observations increases, the sample mean approaches the true population mean. **In precision shooting, larger shot counts provide a more accurate depiction of a rifle system’s performance.** Consider a coin flipped three times, all resulting in heads: this outcome does not confirm a bias toward heads. Similarly, a three-shot group does not definitively establish sub-MOA capability. Intuitively, one might require 50 or 100 flips to assess a coin’s true nature, yet small shooting samples are often accepted without scrutiny. This discrepancy arises because simple systems are more easily evaluated, while complex systems like rifles obscure judgment. Statistical methods, such as those employed in performance analysis or ammunition testing, leverage the LLN to eliminate subjectivity. Increased shot counts enhance reliability over anecdotal assessments.

***

## Data-Driven Evaluation: A Superior Methodology

All shots contribute valuable information. Discarding data, such as outliers, compromises accuracy and wastes resources. The objective is to compile a comprehensive database of shot impacts for statistical analysis. The tools outlined below, supported by a free resource at [https://loathengine.github.io ](https://loathengine.github.io), facilitate this process. The website provides tools for calculating the metrics discussed and ensuring that the formulas are clearly presented and reliable.

***

## Terminology and Key Metrics

| Term | Definition | Example in Shooting |
| :--- | :--- | :--- |
| **Mean** | Arithmetic average of data points. | Average distance of shots from the point of aim (e.g., 0.8 inches). |
| **Standard Deviation** | Measure of variability in data points. | Consistency of shot placement (e.g., SD of 0.3 inches indicates tight grouping). |
| **Extreme Spread (ES)** | Distance between the two most distant shots. | Total group size (e.g., 1.2 inches for 5 shots). |
| **Mean Radius (MR)** | Average distance of each shot from the group’s center. | Comprehensive precision metric (e.g., MR of 0.5 inches for 10 shots). |
| **H/V Dispersion Ratio**| A ratio of horizontal to vertical standard deviation. >1.0 is a wide group, <1.0 is a tall group. | A ratio of 1.5 indicates the group is 50% wider than it is tall. |
| **P95 (R95)** | The radius of a circle that contains 95% of the shots. | A P95 of 1.2 inches means 95% of shots will land within a 1.2-inch radius of the group's center. |
| **Sample Size** | Number of shots recorded. | Shots taken during testing (e.g., 20 shots). |
| **MOA** | Minute of Angle, an angular unit of measure. | Approximately 1 inch at 100 yards. |
| **MRAD** | Milliradian, an angular unit of measure. | Approximately 0.36 inches at 100 yards for 0.1 MRAD. |

### Horizontal and Vertical Variances
These terms refer to the measure of spread in the horizontal (X-axis) and vertical (Y-axis) directions, respectively. Analyzing these separately can reveal patterns in your shooting. For example, significant vertical variance might point to inconsistent muzzle velocity from ammunition, while horizontal variance could indicate issues with wind reading or trigger pull.

### Circular Error Probable (CEP)
**Circular Error Probable (CEP)**, or P50, is a measure of a weapon system's precision. It is defined as the radius of a circle, centered on the mean point of impact, within which 50% of the projectiles are expected to land. It provides a single, concise metric to describe dispersion and is less sensitive to outlier shots than Extreme Spread.

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
A baseline represents the rifle system’s performance prior to alterations. Conduct testing in a controlled environment, such as an indoor range with a bench rest, to minimize variables. Personally, I utilize a rest on an ammunition shelf at an indoor facility, acknowledging its limitations. Control measurable factors (e.g., wind, shooter position) and document uncontrollable variables (e.g., humidity, barrel temperature).

Record each shot’s horizontal (X) and vertical (Y) distance from the point of aim in millimeters. Positioning impacts above and to the right of the point of aim eliminates negative values, and millimeter measurements provide precision. Targets can be designed with a triangular bullseye, offering a precise point for measurement compared to circular designs. Shots are fired, targets preserved, and measurements taken later using calipers. Limit shots per target to maintain clarity.

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
