# Empirical Precision: A No-Nonsense Approach to Shooting Analysis

This guide provides a structured methodology for evaluating precision shooting performance. It is intended to assess a rifle system through objective, repeatable techniques.

---

## BLUF: Bottom Line Up Front

Real analysis is neither cheap nor easy. Mid-tier modern rifles can often exhibit exemplary performance, and surpassing those capabilities requires significant discipline. There are no shortcuts, gadgets, lucky charms, or rituals to simplify precision shooting. Anyone telling you differently is trying to sell you something. 

---

## Historical Context: Transitioning from Anecdotal to Statistical Evaluation

I fondly remember the day my father had me zero my own rifle. We used a simple, unquestioned method: fire three shots, adjust the scope, and repeat until the shots were "dead nuts on," while maybe throwing out a few shots I must have "pulled." We left the range that afternoon with maybe just a little less than half a box of .30-30 Super-X still in the yellow cardboard box. Not only was it a form of a rite of passage, it "just worked." For years, I carried that tradition forward, relying on three-shot and five-shot groups to tell me everything I thought I needed to know about a rifle. It was cheap, it was simple, and it was the way it had always been.

Time passed, the targets stretched further out, the rifles changed, and the old ways began to show their cracks. But the process still "just worked"... didn't it? Then the internet arrived, bringing with it a flood of forum posts, competing theories, and endless arguments over what "just worked." Everyone had a system that "just worked," yet somehow, many claimed their system was the only one that "just worked." I happened to start reading about competition shooting, F-class, and benchrest. I always knew these groups existed, but I just thought it was good ol' boys with more money than sense playing with shiny rifles and reloading to save money. Turns out these competitors are serious. They are the real deal, and they all have a system... and it "just worked." It caused a reckoning in me. No longer was a process that "just worked" good enough. I wanted to know exactly how well it worked. How well your process works compared to mine. How can I change my process to make it just work better? Did the change actually make an improvement? Then I had a second reckoning. I made a pan of white-trash lasagna. I took a square from the corner. It was as close to perfect as I have ever made in the realm of white-trash-style lasagna; browned on the top with crispy cheese on the sides. It was not too sloppy but not too dry. Just what I wanted. Then I saw a cut from near the center... it was still cold. The cheese wasn't even melted. How could this be?  It was obvious.  I have no right to claim my lasagna is perfect based only from the single square I cut from my favorite corner.  

The nostalgia of those early range days is a great memory. One of my favorites. But what worked for a Stevens .30-30 with ammo bought from the local hardware store wasn't working for me anymore. Extraordinary claims require extraordinary evidence. So let's go get some evidence.

---

## Terminology of Key Metrics

To execute any modern evaluation, you must understand the exact definitions of the metrics used to track performance.

| Term | Definition | Application in this Methodology |
| :--- | :--- | :--- |
| **Extreme Spread (ES)** | The distance between the centers of the two furthest shots in a group. | Used primarily to diagnose massive hardware failures early on; otherwise discarded as a metric because it ignores the majority of the data. |
| **Mean Point of Impact (MPI)** | The calculated geometric center of a dataset of shots, derived from the average of all X and Y coordinates. | The dynamic center point from which all radial distances are measured. |
| **Mean Radius (MR)** | The average distance of all shots from the Mean Point of Impact. | The primary statistical indicator of dispersion size (smaller is better) and the core variable used for evaluations. |
| **Sample Size (n)** | The cumulative total number of recorded shots for a specific recipe. | Dictates the statistical power of the evaluation framework (e.g., the Welch's t-test). |
| **p-value** | The statistical probability that a competing recipe is equal to or better than the current leader. | The strict mathematical trigger for elimination. A value below 0.05 proves inferiority and permanently eliminates a recipe. |

---

## Statistical Foundation: The Law of Large Numbers

The Law of Large Numbers (LLN) posits that as the number of observations increases, the sample mean approaches the true mean. 

* **Randomness in the Short Run**: The small collections in a short-run are inherently uncertain.
* **Convergence in the Long Run**: Regardless of the initial conditions, all systems will eventually converge to the same long-run level.

To understand why small shot groups lie to you, you have to understand how the LLN governs reality in other industries. Here are examples of the Law of Large Numbers in the wild:

**1. The Casino's Edge (Variance vs. Truth)**
A gambler walks up to a roulette table, bets on black, and wins three times in a row. In this tiny sample size ($n=3$), black has hit 100% of the time. The gambler thinks he has discovered a winning system. The casino owners, however, aren't panicking. They trust the Law of Large Numbers. They know that over 10,000 spins, the true probability (47.4% for black on an American wheel) will inevitably emerge, and the house will smoothly extract its 5.26% mathematical edge. 
* *The Shooting Parallel:* A tiny 3-shot group is just a gambler hitting black three times. It feels like a permanent system, but it is just a temporary, lucky clustering of statistical noise.

**2. The Coin Flip (The Illusion of Precision)**
If you flip a perfectly balanced coin 10 times, getting 8 heads and 2 tails is an entirely plausible outcome. If you stop testing there, your data tells you the coin is rigged to land on heads 80% of the time. But if you flip that exact same coin 10,000 times, the results will aggressively smooth out and converge onto a 50/50 split. 
* *The Shooting Parallel:* Your 5-shot "bug hole" group is just 8 heads in a row. It does not reflect the rifle system's true mechanical capability; it only reflects a momentary anomaly that will vanish as round count increases.

**3. Medical Trials (Life and Death Math)**
If a pharmaceutical company gives a new, experimental heart medication to only 5 people, and 4 of them see their symptoms vanish, the FDA will absolutely not approve the drug. Why? Because a sample size of 5 is entirely too small to separate the drug's actual effect from random chance (perhaps those 4 patients simply had stronger immune systems). The FDA requires trials with thousands of patients to wash out the "noise" and isolate the true mathematical effect of the medication. 
* *The Shooting Parallel:* You should not make expensive, barrel-burning decisions about your equipment based on a sample size that the scientific community would laugh at.

---

## Data-Driven Methodology: Every Shot Matters

All shots contribute valuable information. Discarding data, such as outliers (fliers), compromises data integrity. Record every shot you fire. The decision to exclude data points from the analysis should not be taken lightly and must be carefully considered and justified. Removing data points can lead to biased or misleading conclusions, undermining the integrity of research or analysis.

* **Bias and distorted results**: Removing shots that don't fit a desired outcome can skew results, creating a distorted picture of the data and leading to inaccurate conclusions.
* **Loss of valuable information**: Fliers or unusual shots might represent valuable information that could shed light on unexpected phenomena, errors in data collection, or even reveal insights about the rifle system.
* **Reduced statistical power**: Removing data can decrease the variability in the dataset, which in turn reduces statistical power and potentially impacts the ability to detect true effects or relationships.
* **Compromised transparency and reproducibility**: "Rationalizing" reasons for excluding data points compromises transparency and reproducibility, making it difficult to understand and/or replicate the analysis. Examples of data to exclude would be something like sighter, warm up, and fouling shots. But once you commit to printing shots... record the shots.

---

## Comparing Extreme Spread vs. Mean Radius

Extreme Spread (ES) measures the distance between the two furthest shots, analyzing only the two worst shots. This is a less useful form of analysis. If you are printing 3-shot groups, there is no other data to derive from the group. If you are printing 20-shot groups, there are significantly more tools that make use of EVERY shot.

ES remains useful for diagnosing significant malfunctions. For instance, a $7,000 rifle advertised as sub-0.5 MOA yielding a 6-inch ES after three shots suggests issues such as unsecured optics or defective ammunition, requiring no further testing to identify a problem. It should be understood that if the group is "bad" there is no reason to continue testing unless you just want to prove how bad the group is. Example case might be where you print a 6-inch group at 100 yards. The single variable you change is scope rings. You return to test, and the first 3 shots are 5 inches. No point wasting shots; three shots is enough to prove that changing the scope rings didn't turn it from a 6-MOA system to a 0.5-MOA system.

**Mean Radius (MR)** calculation involves determining the group center (Mean Point of Impact), measuring each shot’s distance using the formula $\sqrt{((x_2 - x_1)^2 + (y_2 - y_1)^2)}$, and computing the average. Don't panic, modern technology simplifies this process. MR offers a more thorough assessment by averaging the distance of each shot from the group’s center, rather than focusing on the two most extreme shots. When using ES you might be tempted to exclude a "flier" because you realize that one data point is VERY significant to the results. In using MR any "flier" is much less significant because MR uses averaging... and that's the point.

---

## Establishing a Hardware Baseline

A baseline represents the rifle system’s performance in a **strictly defined physical state**. When you establish the baseline, you will always be able to reference that baseline to compare all future component changes. 

However, it is critical to understand that this baseline is tied entirely to the hardware configuration at the time of testing. **You must completely solidify your rifle system before starting a rigorous evaluation.** You can completely invalidate your results by making a significant physical change to the rifle mid-test. Changing the scope, swapping the stock, replacing scope rings, or installing a new trigger fundamentally alters the system's physical attributes and interface. 

For example, if you are halfway through testing a batch of ammunition and you install an upgraded, lighter trigger, your group sizes might suddenly shrink. The new data will make those later ammunition recipes look mathematically superior. In reality, the improvement came from your upgraded trigger control reducing human error, not from the ammunition itself. You will have permanently corrupted your dataset because you are no longer comparing apples to apples. If you change the hardware, your previous baseline is void, and you must establish a new one.

---

## Managing Session-to-Session Variance (Environment)

Because establishing statistical significance requires shooting multiple blocks of ammunition over time, you must be acutely aware of external factors that can skew your data between range trips. You are evaluating the load components, not the weather, but the weather *will* affect the components.

**1. Temperature (The Undisputed King of Session-to-Session Variance)**
* **Internal Ballistics:** Critical. If you develop a load during a hot July session and then take that same ammo on a freezing November hunt, you will likely see a massive drop in muzzle velocity (sometimes 30 to 50+ fps). Conversely, ammo left sitting in a hot car or chambered in a hot gun between strings of fire can spike pressures to dangerous levels. Temperature stability of your powder is the single biggest internal variable between sessions.
* **External Ballistics:** Critical. Temperature swings radically change air density from month to month. Your bullet will strike significantly lower in dense, cold winter air compared to thin, hot summer air, meaning your 500-yard DOPE (Data On Previous Engagements) from August will be completely wrong in December.

**2. Elevation / Station Pressure (The Baseline Shifter)**
* **External Ballistics:** Major. If your multiple sessions take place at different geographic locations (e.g., zeroing your rifle at your home range at 500 feet above sea level, then traveling to a match or hunt at 6,000 feet), barometric pressure and elevation become your biggest external hurdles. The thinner air at high elevations drastically reduces aerodynamic drag. Your rifle will shoot much flatter, and you will need to recalculate your entire drop table.
* **Internal Ballistics:** None.

**3. Humidity (The Storage Killer)**
* **Internal Ballistics:** Moderate to Severe. While atmospheric humidity still barely affects a bullet in flight, storage humidity between sessions is a major issue. Brass casings are not hermetically sealed unless you seal them yourself. If your ammo or unburnt powder sits in a humid garage or damp basement for months between sessions, the powder can degrade, resulting in erratic velocities, hang-fires, or complete duds.
* **External Ballistics:** Minor. Still mathematically insignificant for trajectory unless you are shooting extreme long ranges.

**4. Wind**
* **External Ballistics:** Moderate (Contextually). Wind is still the hardest thing to read while you are shooting, but it ranks lowest for session-to-session variance because it is not a baseline shift. You don't have to change your rifle's zero or rewrite your drop charts between sessions just because it was windy last Tuesday. You simply hold for the wind you have in that exact moment.

---

## Range Data Collection Protocol

Before choosing a statistical analysis framework, you must establish strict range discipline and data handling procedures. Garbage data in yields garbage data out.

* Conduct testing in a controlled environment to minimize variables. Utilize a stable rest at an indoor facility if possible, or shoot prone with sandbags. Control for all the variables you can, and never change more than one variable at a time.
* Choose a target that is easy to read, and if possible, easy to take back home with you. Analysis is easier at home on the coffee table than in the field.
* Position impacts away from your point of aim. It is very possible to shoot out your POA, making it harder to maintain a consistent hold.
* Record each shot’s horizontal (X) and vertical (Y) distance from the point of aim. Adjusting the scope so impacts are above and to the right of the point of aim is highly beneficial. On a grid, up (Y) and right (X) can both be positive integers, which keeps all the math in the realm of "natural" numbers and avoids negative coordinate confusion.

### The Raw Data Architecture
Rather than calculating and storing averages of previous averages (which artificially shrinks variance and destroys degrees of freedom), the shooter's database—whether hand-calculated on paper, tracked in a spreadsheet, or managed via a sophisticated database—stores the absolute, raw data for every shot fired. Each entry records the exact horizontal ($x$) offset and vertical ($y$) offset. All subsequent statistical analysis is drawn directly from this continuously growing master pool of raw coordinates.

### The Iterative Block Protocol
To mitigate the effects of barrel heat, shooter fatigue, and logistical chaos, multi-phase testing is conducted in blocks. A block is simply a physical batch of ammunition fired in a single session to add individual data points to your growing master database. The size of the block does not dictate your statistical power—the total accumulated database does. However, the size of the block you choose comes with practical and environmental trade-offs:

* **3-Round Blocks:** * *Pros:* Extremely fast to shoot, minimal barrel heat, conserves components early on. 
  * *Cons:* Logistically tedious and environmentally exposed. Tracking 10 different recipes of 3 rounds each on a single target is much harder to keep organized than tracking fewer recipes of larger counts. Furthermore, it causes environmental fragmentation. If you need 30 rounds for a full dataset, shooting 3-round blocks means you are spreading that recipe across 10 different range trips. Mixing a 3-round block fired on a hot July day with another fired on a freezing November day introduces massive environmental noise into that recipe's database.
* **5-Round Blocks:** * *Pros:* The logistical "sweet spot." Standard ammo boxes are divided into rows of 5, making bench organization simple. It is easier to track 6 different recipes of 5 rounds (30 total rounds) per range session than juggling 10 different recipes of 3 rounds. It balances component usage while reducing the number of total sessions (and weather changes) required to build a full dataset.
  * *Cons:* Still requires multiple range trips to complete a robust dataset, leaving the data somewhat exposed to session-to-session environmental shifts.
* **10-Round Blocks:** * *Pros:* Consolidates the dataset into fewer environmental conditions, meaning the majority of your data for that recipe shares the exact same weather and baseline pressure. 
  * *Cons:* Noticeable barrel heat which can induce vertical stringing, increases shooter fatigue, and consumes components faster on losing recipes before you get home to run the math.
* **20-Round Blocks:** * *Pros:* Eliminates day-to-day environmental variance entirely. All data for that recipe is collected under identical atmospheric conditions. 
  * *Cons:* Severe barrel heat, high fatigue, and wastes significant components if the recipe was inherently flawed by shot three.

---

## Statistical Evaluation Frameworks

To move from conceptual math to a rigorously applied scientific study, there are a couple of different methods to use. Each has its pros and cons, allowing you to choose the approach that best fits your workflow, component availability, and analytical software infrastructure.

### Method 1: The Fixed-Sample Brute Force Method (Easiest)

This is the most straightforward, "set-and-forget" approach to statistical analysis. You choose a robust sample size upfront, load every single round before hitting the range, and shoot the entire batch to establish a complete dataset for every recipe in a single phase.

#### Execution Directions
1. **Select a Target Sample Size:** Choose a statistically significant round count per recipe (e.g., 30 to 35 rounds per combination).
2. **Load Everything Upfront:** If you are testing 5 different component recipes, load 35 rounds of each (175 rounds total).
3. **Fire in Structured Blocks:** To prevent barrel heat or shooter fatigue from biasing a single recipe, do not shoot all 35 rounds of Recipe A in a row. Instead, shoot them in interleaved blocks (e.g., a 5-round block of Recipe A, then a 5-round block of Recipe B, rotating through until all 175 rounds are fired).
4. **Analyze the Final Pool:** Once every round is recorded, paste all the raw coordinates into your analysis software or spreadsheet. Calculate the final Mean Point of Impact (MPI) and Mean Radius (MR) for each recipe. The recipe with the smallest cumulative MR is your winner.

#### Pros and Cons
* **Pros:** * *Zero Math at the Range:* No need to run calculations between strings; you just pull the trigger and log data.
    * *No Premature Elimination:* Ensures every recipe gets a complete, fair trial over a large sample size, preventing a recipe from being dropped early due to a single bad block caused by user error.
* **Cons:**
    * *High Component Waste:* If Recipe C is inherently terrible, you will still end up loading and shooting all 35 rounds of it, wasting powder, primers, bullets, and barrel life on a known loser.
    * *High Logistics/Fatigue:* Requires preparing and firing a massive volume of ammunition upfront.

### Method 2: The Two-Phase Screening Method (The Balanced Filter)

This method acts as a middle ground, using a small-sample "screening" phase to weed out obviously poor performers before committing heavy components to the top contenders.

#### Execution Directions
1. **Phase 1 (Screening):** Load a small, uniform block for every recipe—typically 10 rounds each. 
2. **Execute and Filter:** Fire the 10-round blocks. Calculate the initial MR for each recipe. Eliminate the worst-performing options immediately (e.g., if you started with 6 recipes, cut the bottom 3).
3. **Phase 2 (Validation):** Take the remaining top-performing recipes and load a much larger validation batch (e.g., an additional 25 rounds each).
4. **Combine and Conclude:** Fire the validation rounds, pool the new data with the Phase 1 data for those specific recipes, and evaluate the final statistical leader.

#### Pros and Cons
* **Pros:**
    * *Saves Components:* You avoid loading heavy volume for recipes that exhibit massive dispersion right out of the gate.
    * *Structured Workflow:* Clearly separates the "exploratory" phase from the "verification" phase.
* **Cons:**
    * *Risk of False Negatives:* Because a 10-round sample size is still subject to statistical noise, an inherently good recipe could accidentally be eliminated in Phase 1 if you happen to experience a string of bad luck or poor environmental conditions during its screening block.

### Method 3: The Sequential Analysis Protocol (The Automated Optimizer)

This is the dynamic, software-driven approach. It treats evaluation as an ongoing tournament, utilizing real-time hypothesis testing to drop losers as early as mathematically possible to preserve components and barrel life.

#### Execution Directions
1. **Load Initial Iterative Blocks:** Load a small initial block (typically 5 rounds) for every recipe in the cohort.
2. **Log and Recalculate:** Fire the blocks, record the raw X and Y coordinates, and update the master database. After a block is recorded, the entire cumulative dataset for that specific recipe is re-evaluated. The geometric center (MPI) is dynamically recalculated, and the radial distance of every historical shot is re-measured to yield the current cumulative MR.
3. **Run Hypothesis Testing:** Identify the "Current Leader" (lowest cumulative MR). The protocol then runs a **Welch’s t-test** against every other surviving recipe in the cohort. Welch's test is specifically utilized because sample sizes ($n$) and variances between competing recipes will inevitably differ during the sequence.
4. **Apply the Statistical Trigger:** The system tests the hypothesis that a competing recipe is significantly worse than the leader. If the resulting $p$-value falls below 0.05 (meaning there is a 95% statistical certainty that the competing load is inferior), the load is permanently eliminated from your testing queue.
5. **Repeat the Loop:** Only load and fire the next 5-round block for recipes that survived elimination. Repeat this cycle until only one recipe remains or your maximum sample size is achieved.

#### Pros and Cons
* **Pros:**
    * *Maximum Efficiency:* Minimizes total component consumption and preserves precious barrel life by cutting losers the exact moment they are mathematically proven inferior.
    * *Strict Statistical Rigor:* Uses adaptive math (Welch's t-test) to handle varying sample sizes and variances objectively.
* **Cons:**
    * *High Administrative Overhead:* Requires you to log data and run statistical calculations between range sessions or loading cycles before you know what to load next.
    * *Environmental Fragmentation:* If a winning recipe takes multiple sessions to confirm, its dataset will span across different days, potentially introducing session-to-session environmental noise (like temperature or air density shifts) into the final numbers.
