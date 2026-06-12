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
| **Extreme Spread (ES)** | The distance between the centers of the two furthest shots in a group. | Used primarily to diagnose massive hardware failures early on; otherwise discarded as a metric for group sizes because it ignores the majority of the data. |
| **Mean Point of Impact (MPI)** | The calculated geometric center of a dataset of shots, derived from the average of all X and Y coordinates. | The dynamic center point from which all radial distances are measured. |
| **Mean Radius (MR)** | The average distance of all shots from the Mean Point of Impact. | The primary statistical indicator of dispersion size (smaller is better) and the core variable used for evaluations. |
| **Velocity SD ($SD_{MV}$)** | The Standard Deviation of muzzle velocities within a batch. | The critical indicator of internal ballistic consistency for long-range performance. |
| **Sample Size (n)** | The cumulative total number of recorded shots for a specific recipe. | Dictates the statistical power of the evaluation framework (e.g., the Welch's t-test). |
| **Confidence Interval (CI)** | A mathematical range representing the margin of error around your calculated average (e.g., a 95% CI). | Proves whether two recipes are actually different, or if their performance margins simply overlap due to statistical noise. |
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

## The Geometry of Dispersion: Normal and Rayleigh Distributions

To truly comprehend your rifle's capabilities, you must understand how shots disperse
