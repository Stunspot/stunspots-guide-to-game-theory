# H. Evolutionary and Population Game Dynamics — Strategy Without Deliberation

The movement from individual optimization to strategic interdependence represents the foundational shift of this 12-report canon, but the deepest reality of systemic interaction is not found in the sterile deliberation of hyper-rational agents. It is found in the relentless, decentralized flow of populations. While earlier reports established the geometry of conflict, the architecture of information, and the engineering of institutions, this eighth report addresses the governing burden of spontaneous strategic order. It explains how strategic behavior is discovered, selected, stabilized, and transformed when agents operate without full reflective optimization or top-down design. In this register, strategic order emerges because successful behaviors spread through selection, imitation, or reinforcement, while failing behaviors are culled by the friction of the environment.1

## **The Ontological Foundations of Strategy Without Deliberation**

The transition from classical non-cooperative theory to evolutionary game dynamics marks a departure from the "Robinson Crusoe" model of isolated maximization toward a relational reality governed by frequency-dependent fitness.1 In the classical register, a player is an autonomous unit of agency that solves a recursive puzzle: "I think that you think that I think".1 In the evolutionary register, the unit of analysis is the "replicator"—an entity, whether a gene, a technique, or a belief, that possesses the means to make approximately accurate copies of itself.7 The "best response" is no longer an internal calculation but an external outcome of survival.2

### **Frequency-Dependent Fitness and the Strategic Element of Evolution**

The foundational insight of this field, articulated by R.A. Fisher and later formalized by Maynard Smith and Price, is that the success of a trait is not absolute but relative to its prevalence in the population.5 Fisher’s analysis of the sex ratio serves as the prototypical population game: the individual fitness of having a male or female offspring depends entirely on the current distribution of males and females in the population.5 When one sex is rare, the individuals producing that sex earn a higher "fitness" (in terms of grandchildren), leading the population to move toward an equal ratio where the advantage disappears.10

This frequency dependence introduces a strategic element into systems that previously seemed purely parametric.5 In a strategic field, incentives are best responses to the anticipated actions of others; in a population field, incentives are best responses to the *actual distribution* of others.1 This shift transforms the "payoff" from a scalar utility value into a growth rate.2

### **Replicators and the Macro-Social Shift**

Evolutionary and population game theory describes macro-social behavioral regularities rather than temporally isolated encounters.7 The "player" in this framework is a carrier of a strategy, often programmed by genetics or habit to act in a specific way.2 Because the identity of these players is not fixed—they are born, they die, and they imitate—the population composition changes over time as more successful strategies crowd out the less successful ones.2

| Dimension | Classical Strategic Analysis | Evolutionary Population Dynamics |
| :---- | :---- | :---- |
| **Primary Agent** | Rational Deliberator 1 | Strategy Replicator 7 |
| **Decision Logic** | Recursive Anticipation 1 | Differential Success 2 |
| **Stability Concept** | Nash Equilibrium 1 | Evolutionary Stability (ESS) 12 |
| **Outcome Nature** | Static/Instantaneous 6 | Dynamic/Flowing 16 |
| **Information Load** | Common Knowledge 6 | Environmental Feedback 17 |

## **Evolutionary Stability: The Mechanics of Invasion Resistance**

The most significant stabilization of the population register was achieved through the concept of the Evolutionarily Stable Strategy (ESS). Developed as a refinement of the Nash equilibrium, an ESS identifies behavioral programs that, once established in a population, cannot be displaced by any rare alternative strategy.5 This resistance to "invasion" is the social glue of the evolutionary framework; it explains why some conventions and norms persist even when they are socially suboptimal or when no central authority enforces them.5

### **The Maynard Smith-Price Refinement**

The standard Nash equilibrium (NE) is necessary but insufficient for evolutionary stability. A strategy sigma is an NE if no individual has an incentive to switch to a different strategy mu, given that everyone else is playing sigma. However, evolution is noisy; small groups of "mutants" or innovators appear constantly.5 If an NE allows for a "neutral invasion"—where the mutant mu does just as well as the incumbent sigma—the population may drift away from the equilibrium, eventually leading to a collapse of the original order.18

To prevent this drift, an ESS sigma must satisfy a higher burden of proof. For every possible mutant strategy mu, one of two conditions must hold 5:

1. **Strict Best Response:** pi(sigma, sigma) > pi(mu, sigma). The incumbent earns a strictly higher payoff against itself than the mutant earns against the incumbent. The mutant is culled before it can gain a foothold.5  
2. **Neutral Resistance:** If pi(sigma, sigma) = pi(mu, sigma), then pi(sigma, mu) > pi(mu, mu). If the mutant does as well as the incumbent against the "crowd," the incumbent must be superior when interacting with the mutants themselves. This ensures that as the mutants begin to interact with each other, they suffer a relative fitness loss that prevents their expansion.2

### **The Uniform Invasion Barrier and Local Superiority**

Later refinements by Hofbauer and others proved that the ESS concept is equivalent to having a "uniform invasion barrier".12 This means there is a specific proportion epsilon such that any mutant strategy comprising less than epsilon of the population will inevitably be eliminated by selection pressure.8 An ESS is therefore a state of "local superiority": in a sufficiently small neighborhood of the ESS, the incumbent strategy earns a higher average payoff than any alternative mixture of strategies.5

### **The Anchor Case: Hawk-Dove and the Logic of Aggression**

The Hawk-Dove game serves as the definitive model for how population dynamics discover limited conflict.23 Two individuals compete for a resource of value V. A Hawk initiates aggressive behavior and continues until injured (cost C) or the opponent retreats. A Dove retreats immediately if the opponent is aggressive.10

If the value of the resource exceeds the cost of injury (V > C), "Hawk" is a dominant strategy, and the population converges to an All-Hawk ESS.5 However, if the cost of conflict is high (V < C), the All-Hawk state is not an ESS because a Dove can invade by avoiding the negative payoffs of injury.5 Similarly, an All-Dove state is not an ESS because a Hawk can invade by capturing every resource without cost.5

The resulting strategic order is a mixed ESS: a population where a specific fraction p = V/C of the population plays Hawk and 1-p plays Dove.19 In this state, the average payoffs of Hawks and Doves are equalized, and any movement away from this proportion is corrected by selection pressure.19 This macro-pattern of "ritualized aggression" is not the result of a treaty or a conscious balance of power, but a self-enforcing property of the fitness landscape.9

| Population State | Payoff Relationship | Evolutionary Trajectory |
| :---- | :---- | :---- |
| **All Doves** | E(H, D) > E(D, D) | Hawks invade rapidly.24 |
| **All Hawks** | E(D, H) > E(H, H) | Doves invade (if C > V).24 |
| **Mixed ESS** | E(H, x*) = E(D, x*) | Stable rest state.19 |
| **Extreme Aggression** | E(H, H) < 0 | High selection pressure for restraint.5 |

## **Replicator Dynamics: The Mathematics of Behavior Flow**

While the ESS provides a static definition of stability, it does not describe the path by which a population discovers it.12 Replicator dynamics provide the governing differential equations for strategy prevalence over time, assuming that the mass of agents using a given strategy grows at a rate proportional to that strategy’s current performance relative to the average.2

### **The Replicator Equation and the Taylor-Jonker Result**

In a symmetric population game with a finite set of pure strategies i = 1,..., n, let x_i be the population share of strategy i. The state of the population is represented by a point in the simplex Sn. The continuous-time replicator equation, pioneered by Taylor and Jonker (1978), is defined as 13:

x_dot_i = x_i * [f_i(x) - avg_f(x)]

Where f_i(x) is the expected payoff (fitness) of strategy i given the population state x, and avg_f(x) = sum(x_j * f_j(x)) is the mean fitness of the population.2

This equation produces three critical insights into the emergence of strategic order:

1. **Survival of the Fitter:** Strategies that earn more than the average increase their share; those that earn less shrink.2  
2. **Boundary Stasis:** If a strategy is not present in the population (x_i = 0), the replicator dynamics cannot "invent" it. Strategy discovery in these models requires an external source of variation, such as mutation or experimentation.2  
3. **Nash Stationarity:** Every Nash equilibrium is a steady state (a fixed point) of the replicator dynamics because at an NE, all strategies in use earn the same payoff, and no unused strategy earns more.13

### **Replicator Dynamics vs. Rationality**

A central result in this canon is that ESS implies asymptotic stability under the replicator dynamic.13 If a population is in an ESS, any small perturbation will be corrected, and the system will return to the ESS.13 This bridges the gap between biological selection and economic rationality: population flow "solves" the game that rational agents are supposed to solve by deliberation.5

However, the converse is not always true. Not every asymptotically stable state of the replicator dynamic is an ESS, and not every Nash equilibrium is stable.13 Specifically, non-Nash steady states (where a strategy earns less than the average but its share is zero) cannot be asymptotically stable; a small weight on a better-performing deviation will cause it to grow.13

### **Pathological Cycles and Rock-Paper-Scissors**

Strategic order is not always a static resting point. In games with cyclic dominance, such as Rock-Paper-Scissors, the replicator dynamics produce endless oscillations.2 In this environment, the "totally mixed" Nash equilibrium (where everyone plays each move with 1/3 probability) is a steady state, but it is not asymptotically stable.9 Any deviation from this point triggers a cycle where the population "chases" the strategy that beats the current majority.33 This demonstrates that some systems are inherently dynamic, where strategic behavior is a permanent process of transformation rather than a settled convention.9

## **Cultural Evolution: Strategy Revision Through Imitation and Learning**

Evolutionary dynamics are not restricted to birth-and-death processes. In human and organizational systems, the "replicator" is a social artifact—a norm, a technique, or a rule of thumb—that spreads through "revision protocols".14 These protocols describe how myopic individuals switch strategies based on local feedback rather than global optimization.28

### **Imitation Dynamics: The Social Replicator**

The most common model for social systems is the imitation protocol. An agent occasionally samples a peer, observes their strategy and payoff, and switches to that strategy if the peer is doing better.2 Weibull and Björnerstedt (1996) demonstrated that this imitation process in a large population converges exactly to the deterministic replicator equation.14 This provides a social microfoundation for biological dynamics: successful strategies proliferate not because people are "born" with them, but because people copy what works.2

### **Best-Response Dynamics and Fictitious Play**

Alternatively, agents may be more "rational" but still myopic, using best-response dynamics (also known as fictitious play).16 Here, an agent estimates the current strategy distribution of the population and switches to the strategy that would maximize their expected payoff against that estimate.38

| Protocol Type | Mechanism | Cognitive Burden | Dynamical Property |
| :---- | :---- | :---- | :---- |
| **Imitation** | Copy successful peers.2 | Low; observe neighbors. | Converges to Replicator Dynamic.14 |
| **Best-Response** | Local optimization against state.16 | Moderate; requires local estimation. | Jumpy; may fail to converge in coord. games.38 |
| **Reinforcement** | Increase weight on high payoffs.39 | Low; requires internal feedback. | Smooth; eliminates dominated strategies.37 |
| **Aspiration** | Switch if benchmark is not met.17 | Minimal; internal only. | Highly robust to noisy environments.17 |

The interaction of these protocols determines the speed and stability of norm emergence. In "Battle of the Sexes" coordination games, the quick movements of best-response dynamics can cause the population to "over-correct," leading to instability, whereas the gradual adjustment of imitation/replicator dynamics often permits convergence to a stable convention.37

### **Interactive Trial and Error: Learning in the Dark**

A sophisticated model of behavior discovery is "Interactive Trial and Error Learning".17 This protocol applies to environments where agents do not know the game, the payoffs of others, or even who their opponents are.17 Behavior is determined by psychological states or "moods" triggered by the relationship between realized payoffs and internal expectations (aspirations) 17:

* **Content:** The agent occasionally experiments with small probability. They only switch permanently if the new strategy is strictly better.17  
* **Discontent:** Triggered when payoffs drop significantly due to others' actions. The agent enters a "random search," thrashing around until they find a strategy that restores a level of satisfaction.17  
* **Watchful/Hopeful:** Transitional states where the agent monitors whether a payoff change is temporary or permanent before shifting moods.17

This "completely uncoupled" rule shows that populations can implement pure Nash equilibrium behavior even when every single actor is "in the dark" about the strategic field.17

## **The Evolution of Meaning: Signaling and Spontaneous Coordination**

One of the most profound instances of strategic order without design is the spontaneous emergence of signaling conventions and linguistic meaning.45 Brian Skyrms utilizes evolutionary game theory to model how "cheap talk"—signals that carry no inherent cost or meaning—acquires content through repeated interaction and selection.45

### **Symmetry Breaking and the Emergence of Meaning**

In a standard signaling game, there are two equally efficient conventions (e.g., Signal A means State 1, Signal B means State 2; or vice versa).45 Rational choice theory provides no reason to prefer one over the other, leading to "babbling equilibria" where information is never transferred.45 However, evolutionary dynamics spontaneously "break the symmetry".45

As the population interacts, small accidental correlations between signals and states are amplified by the positive feedback of successful coordination.45 Over time, the population "finds" a convention because those who use it earn higher mutual payoffs than those who do not communicate.46 This process demonstrates how complex information-processing tasks can be implemented by very simple means, and how signaling networks can coordinate action without a central "dictionary".48

### **Deception and the Stag Hunt**

The evolution of meaning is often complicated by conflicting interests. In the "Stag Hunt" coordination game, pre-play signaling can stabilize the cooperative (Stag) equilibrium.45 However, evolutionary dynamics can also lead to "deceptive signaling," where "Hare Hunters" evolve to send the "Stag" signal to attract partners, only to exploit them later.45 The success of cooperative conventions in these cases depends on the relative speed of "structure modification" (who interacts with whom) versus "strategy revision".45 If agents can quickly change their social network to interact only with those who signal honestly, cooperation can thrive; if structures are frozen, cooperation often collapses.45

## **Stochastic Stability: Norms, Persistence, and Punctuated Equilibrium**

Strategic order is not just a resting point of a deterministic flow; it is a stationary distribution of a noisy system.32 Real-world populations are subject to "trembles"—small, persistent random errors or experiments by individuals.6 H. Peyton Young’s theory of "Adaptive Play" uses stochastic evolutionary game theory to identify which norms are truly robust to these errors.32

### **Tipping Points and Persistence**

Social norms typically exhibit "punctuated equilibrium": long periods of stasis followed by sudden, rapid shifts.51 A norm (like a 50/50 bargaining split or a rule of the road) is stochastically stable if it is the equilibrium that the population spends almost all of its time in as the probability of "trembles" goes to zero.32

These shifts are rarely incremental.51 A social innovation may exist at a low frequency for centuries, unable to cross the "tipping point" required for coordination benefits to kick in.51 However, once a critical threshold of penetration is reached, the positive feedback of the coordination technology causes the old norm to collapse and the new one to become established in a "big burst" of change.51

### **Risk Dominance and Focal Points**

In coordination games with multiple equilibria, stochastic stability often selects the "risk-dominant" equilibrium—the one that is safer to play if the agent is uncertain about what others will do.32 This provides a powerful explanation for why suboptimal or "fair" conventions persist.2 For example, the 50/50 split in bargaining may emerge as an evolutionary "focal point" because it simplifies the cognitive burden of coordination and acts as a "Darwinian veil of ignorance," where agents do not know their future roles and thus settle on a robustly safe division.32

| Stability Type | Key Mechanism | Outcome Prediction |
| :---- | :---- | :---- |
| **Static ESS** | Resistance to rare mutants.5 | Locally superior strategy.22 |
| **Asymptotic Stability** | Convergence of deterministic flow.13 | Attractor of the replicator dynamic.31 |
| **Stochastic Stability** | Resilience against persistent noise.32 | Risk-dominant conventions.32 |
| **Fixation Probability** | Likelihood of mutant takeover.55 | Stationary distribution in finite pop.49 |

## **The Geography of Strategy: Networks, Space, and Structure**

The "well-mixed" population assumption, where any two individuals interact with equal probability, is a reference point that rarely holds in reality.21 Population structure—the social network or spatial grid that determines "who interacts with whom"—fundamentally alters the dynamics of strategic order.49

### **Cluster Stability and Network Reciprocity**

In a well-mixed population, defectors often exploit and eliminate altruists or cooperators. However, on a network or lattice, cooperators can survive by forming local "clumps" or enclaves.21 Within these clusters, cooperators interact primarily with each other, earning high mutual payoffs that provide a defense against the "predation" of defectors at the boundaries of the cluster.21

This "network reciprocity" explains how macro-patterns of altruism and coordination can thrive in a world of self-interested actors.21 The structure of the network also governs the rate of diffusion: innovations spread rapidly in "small-world" networks where everyone is a few steps away, but may become trapped in fragmented communities.45

### **The Role of "Thickness" and "Congestion"**

Institutional engineering in populations (such as the design of platform markets or matching systems) must manage the "social geometry" of the game.57

* **Thickness:** A successful population game requires a high concentration of participants to ensure diverse options and coordination efficiency.60  
* **Congestion:** Conversely, too many participants can lead to informational overload, where the "revision protocol" of agents fails because they cannot process all available signals.60  
* **Decentralized Control:** In engineering problems like power grid management or building lighting systems, population dynamics are used to split limited resources among lamps or substations without a central controller, using the aggregate "mass" of the population to reach an optimal coupled constraint.61

## **Finite Populations: Drift, Stochasticity, and the 1/3 Rule**

Most classical EGT models assume infinite populations to permit deterministic differential equations. However, real strategic systems are finite, and in small populations, random "drift" can be as decisive as selection pressure.21 In a finite population, even a "worse" strategy can occasionally take over the entire population simply by chance.21

### **The Moran Process and Fixation**

The "fixation probability" is the likelihood that a single mutant will eventually displace the entire resident population.49 In a population of size N, this process is modeled as a Markov chain.2

* **Neutral Selection:** If all strategies have equal fitness, the fixation probability of a mutant is simply 1/N.54  
* **Weak Selection:** In cases where fitness differences are small, a famous result is the "1/3 rule": a single cooperator can invade a population of defectors in a Prisoner's Dilemma if the cooperator’s fitness crosses a threshold where the basin of attraction for cooperation is wider than 1/3.54

This stochastic approach reveals that strategic stability in finite populations is probabilistic.21 Order is represented not as a single fixed point, but as a stationary distribution where the population spends the majority of its history.49

### **Payoff Stochasticity**

A further complication in finite systems is "payoff stochasticity," where individuals using the same strategy earn different payoffs due to a randomly distributed number of interactions.55 This reducing of selection intensity essentially "increases the temperature" of the system, making it more likely for the population to drift away from strict Nash equilibria and potentially move toward more efficient, but less stable, cooperative regimes.54

## **Organizational Routines and the Evolutionary Theory of the Firm**

The concepts of strategy without deliberation find their most practical application in the "Evolutionary Economics" of Nelson and Winter.35 This perspective rejects the view of the firm as a unitary rational actor and instead treats it as a repository of "organizational routines".35

### **Routines as Genes**

Routines are regular, predictable behavioral patterns that allow organizations to achieve their goals habitually.35 They function as the firm's "genes," embodying collective knowledge perceived by organizational members.35

* **Inertia and Stability:** Routines lead to organizational inertia, providing a stable "truce" that coordinates actions without the need for constant, explicit bargaining.35  
* **Search and Adaptation:** Organizations "evolve" by changing these routines through a process of trial-and-error search for novelty.35  
* **Selection and Growth:** The market acts as the environment that selects among firms with different bundles of routines. Successful firms grow and replicate their routines; failing firms are culled.64

The evolution of the "Platform Market" (Industry 4.0/5.0) is a macro-example of this routine-based selection.57 The technology embedded in a platform reshapes its structural and institutional configuration, creating a new "technological paradigm" that replaces old routines with more efficient digital coordination mechanisms.57

## **AI and MARL: Strategy Discovery in Algorithmic Populations**

The most recent extension of this register is the interaction of algorithmic agents in Multi-Agent Reinforcement Learning (MARL) environments.67 Unlike humans, whose deliberation is bounded by biology, AI agents learn through the relentless iteration of successful reward-seeking, making them the purest form of strategic replicators.39

### **The AI4Games Framework**

Current research (2025) has introduced frameworks like "AI4Games" that transform strategy design into a reinforcement learning optimization task.56 This pipeline abstracts strategy representation, interaction design, and reward construction to systematically "mine" strategies with long-term evolutionary advantages.56

* **Strategy Discovery:** Instead of human experts designing heuristics (like Tit-for-Tat), the AI explores vast strategy spaces to identify behavioral programs that are uninvadable and possess high fitness across dynamic environments.56  
* **Tacit Collusion:** In high-frequency environments, these agents often "discover" collusive patterns (implicit cooperation) that were never explicitly programmed, purely because such patterns maximize the long-term reward stream.56

### **Explainable AI (XAI) and Strategic Policy Evolution**

As strategic behaviors evolve beyond human design, XAI becomes essential for interpreting why a certain policy was selected by the dynamic.69 By applying XAI to agents in adversarial settings like Connect-4 or financial markets, analysts can "debug" strategy formation and understand the move selection that leads to stable macro-patterns of coordination or competition.69

## **Diagnostic Framework for Strategic Population Analysis**

To troubleshoot systemic failure or predict the transition of conventions, the analyst must treat the population as a dynamical system. The following diagnostic indicators are used to read the state of strategic population order 72:

1. **Effective Population Size (Ne):** Determine whether the population is large enough for deterministic replicator dynamics to hold. If Ne is small, assume that stochastic drift will dominate and look for "fixation probabilities" rather than static ESS.54  
2. **Revision Protocol Identification:** Observe how agents change behavior. Is it by imitation of peers (Replicator flow), local optimization (Best-Response), or internal satisfaction (Aspiration-based)?17  
3. **Environmental Stationarity:** Assess whether the "fitness landscape" is static or shifting due to external technological or pricing shocks.19 Norm shifts are often triggered by "bursts" of idiosyncratic changes in individual perceptions.53  
4. **Interaction Topology:** Map the social network. Identify "clumps" of interacting agents that might support local conventions or altruistic norms that would be unstable in a well-mixed population.21  
5. **Signal Synchronicity:** Check for "public signals" (triggering common knowledge) versus "private signals" (causing divergent beliefs and coordination breakdown).6

## **Synthesis: The Resilience of Spontaneous Order**

The governing burden of this eighth report has been to demonstrate that strategic stability is an emergent property of population dynamics rather than a calculated choice of individuals. In the classical non-cooperative reports, order required "Common Knowledge of Rationality"—a fragile epistemic scaffolding that often fails in the real world.5 Population game dynamics provide a more robust alternative: strategic behavior as a living commercial relationship between agents and their history.9

Strategic order is discovered through the sheer pressure of success, selected by the environment's rewards, stabilized by the invasion barriers of ESS, and transformed by the punctuated equilibrium of social innovations.12 Whether in the biological struggle of the Hawk and the Dove, the organizational evolution of firms, or the algorithmic competition of MARL agents, the underlying principle remains constant: the system "solves" the game.5

By shifting the strategic camera angle from the mind of the player to the flow of the population, the analyst moves from observing conflict to understanding the architecture of civilization.1 Strategic systems analysis, in its most comprehensive form, is the study of how civilization endures through the selection of self-enforcing conventions that survive the presence of their neighbors.2 This report completes the evolutionary layer of the canon, providing the infrastructure for the final modules on systemic failure and the diagnostic troubleshooting of "Nash Traps" where successful but destructive behaviors become stochastically locked into the social fabric.

#### **Works cited**

1. Game Theory 1 - The Geometry of Strategic Conflict — An Ontology of Incentives, Interdependence, and Equilibrium  
2. Evolutionary game theory - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Evolutionary_game_theory](https://en.wikipedia.org/wiki/Evolutionary_game_theory)  
3. Evolutionary Game Theory: Darwinian Dynamics and the G Function Approach - MDPI, accessed April 18, 2026, [https://www.mdpi.com/2073-4336/12/4/72](https://www.mdpi.com/2073-4336/12/4/72)  
4. The Contribution of Evolutionary Game Theory to Understanding and Treating Cancer, accessed April 18, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC9117378/](https://pmc.ncbi.nlm.nih.gov/articles/PMC9117378/)  
5. Evolutionary Game Theory - Stanford Encyclopedia of Philosophy, accessed April 18, 2026, [https://plato.stanford.edu/archives/win2020/entries/game-evolutionary/](https://plato.stanford.edu/archives/win2020/entries/game-evolutionary/)  
6. Game Theory 2 - Equilibrium and Information — Stability, Beliefs, and Strategic Knowledge Systems  
7. commentary discussion of brian skyrms' paper - 300 - classical versus evolutionary game theory, accessed April 18, 2026, [https://www.umass.edu/preferen/gintis/Skyrms%20Critique%20JCS.pdf](https://www.umass.edu/preferen/gintis/Skyrms%20Critique%20JCS.pdf)  
8. Evolutionary Game Theory for linguists. A primer, accessed April 18, 2026, [https://profgerhard.de/sfs/publications/egtPrimer.pdf](https://profgerhard.de/sfs/publications/egtPrimer.pdf)  
9. Evolutionary Games and Population Dynamics by Josef Hofbauer | Goodreads, accessed April 18, 2026, [https://www.goodreads.com/book/show/1659003.Evolutionary_Games_and_Population_Dynamics](https://www.goodreads.com/book/show/1659003.Evolutionary_Games_and_Population_Dynamics)  
10. Evolutionary Game Theory - Stanford Encyclopedia of Philosophy, accessed April 18, 2026, [https://plato.stanford.edu/archives/fall2013/entries/game-evolutionary/](https://plato.stanford.edu/archives/fall2013/entries/game-evolutionary/)  
11. Evolutionary Game Theory - Stanford Encyclopedia of Philosophy, accessed April 18, 2026, [https://plato.stanford.edu/entries/game-evolutionary/](https://plato.stanford.edu/entries/game-evolutionary/)  
12. Evolutionary Game Theory (Stanford Encyclopedia of Philosophy ..., accessed April 18, 2026, [https://plato.stanford.edu/archives/spr2024/entries/game-evolutionary/](https://plato.stanford.edu/archives/spr2024/entries/game-evolutionary/)  
13. In a Nash equilibrium, each player's strategy is a best response to the strategies of the other players. Nash equilibrium an, accessed April 18, 2026, [https://www.cirje.e.u-tokyo.ac.jp/research/workshops/micro/micropaper04/fudenberg_lecture_note.pdf](https://www.cirje.e.u-tokyo.ac.jp/research/workshops/micro/micropaper04/fudenberg_lecture_note.pdf)  
14. Jörgen Weibull - Evolutionary Game Theory - JASSS, accessed April 18, 2026, [https://www.jasss.org/2/1/review3.html](https://www.jasss.org/2/1/review3.html)  
15. Evolutionary Game Theory - University of Puget Sound, accessed April 18, 2026, [https://www.pugetsound.edu/sites/default/files/file/evolutionarygametheorysample_0.pdf](https://www.pugetsound.edu/sites/default/files/file/evolutionarygametheorysample_0.pdf)  
16. Dynamics in Games, accessed April 18, 2026, [https://www.ma.imperial.ac.uk/~svanstri/Files/dynamics-in-games-lyndsey-clark.pdf](https://www.ma.imperial.ac.uk/~svanstri/Files/dynamics-in-games-lyndsey-clark.pdf)  
17. Learning a Game by Trial and Error - Economics, accessed April 18, 2026, [http://www.econ2.jhu.edu/People/Young/Learning22Feb08.pdf](http://www.econ2.jhu.edu/People/Young/Learning22Feb08.pdf)  
18. Evolutionarily stable strategy - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Evolutionarily_stable_strategy](https://en.wikipedia.org/wiki/Evolutionarily_stable_strategy)  
19. Understanding Evolutionarily Stable Strategy (ESS) in ... - Umbrex, accessed April 18, 2026, [https://umbrex.com/resources/economics-concepts/microeconomic-theory/evolutionarily-stable-strategy-ess/](https://umbrex.com/resources/economics-concepts/microeconomic-theory/evolutionarily-stable-strategy-ess/)  
20. Evolutionary Stable Strategies (ESS) - SIUE, accessed April 18, 2026, [https://www.siue.edu/~evailat/ev-gt.htm](https://www.siue.edu/~evailat/ev-gt.htm)  
21. Evolutionary dynamics in structured populations, accessed April 18, 2026, [https://webhomes.maths.ed.ac.uk/~antal/Mypapers/sigmarev10.pdf](https://webhomes.maths.ed.ac.uk/~antal/Mypapers/sigmarev10.pdf)  
22. Evolutionary Game Theory - Stanford Encyclopedia of Philosophy, accessed April 18, 2026, [https://seop.illc.uva.nl/entries/game-evolutionary/](https://seop.illc.uva.nl/entries/game-evolutionary/)  
23. accessed April 18, 2026, [https://www.rug.nl/research/gelifes/tres/_pdf/socialbehavch4.pdf](https://www.rug.nl/research/gelifes/tres/_pdf/socialbehavch4.pdf)  
24. 13.1: App. E: Evolutionary Game Theory | AI Safety, Ethics, and Society Textbook, accessed April 18, 2026, [https://www.aisafetybook.com/textbook/appendix-evolutionary-game-theory](https://www.aisafetybook.com/textbook/appendix-evolutionary-game-theory)  
25. Evolutionary Game Theory.pdf - Middlebury College, accessed April 18, 2026, [https://f24.middlebury.edu/MATH0315A/Additional%20Chapters/Evolutionary%20Game%20Theory.pdf](https://f24.middlebury.edu/MATH0315A/Additional%20Chapters/Evolutionary%20Game%20Theory.pdf)  
26. Picking strategies in games of cooperation - PNAS, accessed April 18, 2026, [https://www.pnas.org/doi/10.1073/pnas.2319925121](https://www.pnas.org/doi/10.1073/pnas.2319925121)  
27. The Projection Dynamic and the Replicator Dynamic, accessed April 18, 2026, [https://users.ssc.wisc.edu/~whs/research/proj2.pdf](https://users.ssc.wisc.edu/~whs/research/proj2.pdf)  
28. Population Games and Deterministic Evolutionary Dynamics - EconPapers, accessed April 18, 2026, [https://econpapers.repec.org/RePEc:eee:gamchp:v:4:y:2015:i:c:p:703-778](https://econpapers.repec.org/RePEc:eee:gamchp:v:4:y:2015:i:c:p:703-778)  
29. Other game dynamics (Chapter 8) - Evolutionary Games and Population Dynamics, accessed April 18, 2026, [https://www.cambridge.org/core/books/evolutionary-games-and-population-dynamics/other-game-dynamics/4984DC6DDD54D437688251C6452A1283](https://www.cambridge.org/core/books/evolutionary-games-and-population-dynamics/other-game-dynamics/4984DC6DDD54D437688251C6452A1283)  
30. Strategy variability: How too much of a good thing can hurt performance, accessed April 18, 2026, [https://lrdc.pitt.edu/schunn/research/papers/StrategyVariabilityM&C2006.pdf](https://lrdc.pitt.edu/schunn/research/papers/StrategyVariabilityM&C2006.pdf)  
31. Evolutionarily stable strategies in stable and periodically fluctuating populations: The Rosenzweig–MacArthur predator–prey model - PNAS, accessed April 18, 2026, [https://www.pnas.org/doi/pdf/10.1073/pnas.2017463118](https://www.pnas.org/doi/pdf/10.1073/pnas.2017463118)  
32. H. Peyton Young: Individual Strategy and Social Structure - An Evolutionary Theory of Institutions - JASSS, accessed April 18, 2026, [https://jasss.soc.surrey.ac.uk/3/4/reviews/kirchkamp.html](https://jasss.soc.surrey.ac.uk/3/4/reviews/kirchkamp.html)  
33. Reinforcement learning in population games | Request PDF - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/257315008_Reinforcement_learning_in_population_games](https://www.researchgate.net/publication/257315008_Reinforcement_learning_in_population_games)  
34. Lecture 6 Game theory and replicator dynamics | Theoretical Community Ecology, accessed April 18, 2026, [https://stefanoallesina.github.io/Theoretical_Community_Ecology/game-theory-and-replicator-dynamics.html](https://stefanoallesina.github.io/Theoretical_Community_Ecology/game-theory-and-replicator-dynamics.html)  
35. Chapter 2: Organizational Routines (ORs) - Emerald Insight, accessed April 18, 2026, [https://www.emerald.com/books/edited-volume/11838/chapter/81806909/Organizational-Routines-ORs](https://www.emerald.com/books/edited-volume/11838/chapter/81806909/Organizational-Routines-ORs)  
36. [PDF] CHAPTER 13 Population Games and Deterministic Evolutionary Dynamics | Semantic Scholar, accessed April 18, 2026, [https://www.semanticscholar.org/paper/CHAPTER-13-Population-Games-and-Deterministic-Sandholm/0877d84de9bcd4a665f48b954a7b389d037bb4b4](https://www.semanticscholar.org/paper/CHAPTER-13-Population-Games-and-Deterministic-Sandholm/0877d84de9bcd4a665f48b954a7b389d037bb4b4)  
37. Learning Through Reinforcement and Replicator Dynamics ¤, accessed April 18, 2026, [http://www.dklevine.com/archive/refs4380.pdf](http://www.dklevine.com/archive/refs4380.pdf)  
38. A Note on Best Response Dynamics - School of Economics Home Pages Server, accessed April 18, 2026, [https://homepages.econ.ed.ac.uk/~hopkinse/brd.pdf](https://homepages.econ.ed.ac.uk/~hopkinse/brd.pdf)  
39. (PDF) Evolutionary game theory and multi-agent reinforcement learning - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/220254307_Evolutionary_game_theory_and_multi-agent_reinforcement_learning](https://www.researchgate.net/publication/220254307_Evolutionary_game_theory_and_multi-agent_reinforcement_learning)  
40. Young, Individual Strategy and Social Structure - Cosma Shalizi, accessed April 18, 2026, [https://bactra.org/reviews/young-strategy-and-structure/](https://bactra.org/reviews/young-strategy-and-structure/)  
41. Reinforcement Learning in Repeated Interaction Games - BU Personal Websites, accessed April 18, 2026, [https://people.bu.edu/dilipm/publications/BendorMookherjeeRay2001%20ATE.pdf](https://people.bu.edu/dilipm/publications/BendorMookherjeeRay2001%20ATE.pdf)  
42. Aspiration dynamics of multi-player games in finite populations - PMC, accessed April 18, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC3973373/](https://pmc.ncbi.nlm.nih.gov/articles/PMC3973373/)  
43. Learning by trial and error - IDEAS/RePEc, accessed April 18, 2026, [https://ideas.repec.org/a/eee/gamebe/v65y2009i2p626-643.html](https://ideas.repec.org/a/eee/gamebe/v65y2009i2p626-643.html)  
44. Aspiration-based Perturbed Learning Automata in Games with Noisy Utility Measurements. Part B - arXiv, accessed April 18, 2026, [https://arxiv.org/pdf/2511.18418](https://arxiv.org/pdf/2511.18418)  
45. EVOLUTION, NORMS, AND THE SOCIAL CONTRACT Brian Skyrms* - Arizona State Law Journal, accessed April 18, 2026, [https://arizonastatelawjournal.org/wp-content/uploads/2017/03/Skyrms_final.pdf](https://arizonastatelawjournal.org/wp-content/uploads/2017/03/Skyrms_final.pdf)  
46. Evolution of the Social Contract, accessed April 18, 2026, [https://faculty.washington.edu/conormw/Teaching/Files/Models/Summer_School/Recommended_Readings/Summer_School_Further_Readings/Skyrms-Evolution_of_the_Social_Contract.pdf](https://faculty.washington.edu/conormw/Teaching/Files/Models/Summer_School/Recommended_Readings/Summer_School_Further_Readings/Skyrms-Evolution_of_the_Social_Contract.pdf)  
47. Evolution of the Social Contract - Brian Skyrms - Google Books, accessed April 18, 2026, [https://books.google.co.ls/books?id=BENfDAAAQBAJ&source=gbs_navlinks_s](https://books.google.co.ls/books?id=BENfDAAAQBAJ&source=gbs_navlinks_s)  
48. [7] Skyrms (2010) Signals.pdf - Code Biology, accessed April 18, 2026, [https://www.codebiology.org/pdf/%5B7%5D%20Skyrms%20(2010)%20Signals.pdf](https://www.codebiology.org/pdf/%5B7%5D%20Skyrms%20(2010)%20Signals.pdf)  
49. Strategy selection in structured populations - PMC - NIH, accessed April 18, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC2710410/](https://pmc.ncbi.nlm.nih.gov/articles/PMC2710410/)  
50. Path Dependence, its critics, and the quest for 'historical economics', accessed April 18, 2026, [https://faculty.sites.iastate.edu/tesfatsi/archive/tesfatsi/pathdep.pdavid.pdf](https://faculty.sites.iastate.edu/tesfatsi/archive/tesfatsi/pathdep.pdavid.pdf)  
51. The Evolution of Social Norms - Economics, accessed April 18, 2026, [http://www.econ2.jhu.edu/people/young/SocialNormsFinal.pdf](http://www.econ2.jhu.edu/people/young/SocialNormsFinal.pdf)  
52. Individual Strategy and Social Structure: An Evolutionary Theory of Institutions - Young, Hobart Peyton: 9780691086873 - AbeBooks, accessed April 18, 2026, [https://www.abebooks.com/9780691086873/Individual-Strategy-Social-Structure-Evolutionary-0691086877/plp](https://www.abebooks.com/9780691086873/Individual-Strategy-Social-Structure-Evolutionary-0691086877/plp)  
53. The Dynamics of Social Innovation H. Peyton Young Department of Economics, University of Oxford, Oxford OX1 3UQ, UK Abstract. So, accessed April 18, 2026, [https://warwick.ac.uk/fac/soc/economics/seminars/seminars/conferences/theoryworkshop/dynsocinnovation.pdf](https://warwick.ac.uk/fac/soc/economics/seminars/seminars/conferences/theoryworkshop/dynsocinnovation.pdf)  
54. (PDF) Stochasticity and evolutionary stability - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/6770532_Stochasticity_and_evolutionary_stability](https://www.researchgate.net/publication/6770532_Stochasticity_and_evolutionary_stability)  
55. Stochastic payoff evaluation increases the temperature of selection - PMC - NIH, accessed April 18, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC1866307/](https://pmc.ncbi.nlm.nih.gov/articles/PMC1866307/)  
56. AI4Games: A General Strategy Search Frame- work for Evolutionary Games, accessed April 18, 2026, [https://f004.backblazeb2.com/file/chinaxiv/english_pdfs/chinaxiv-202508.00255.pdf](https://f004.backblazeb2.com/file/chinaxiv/english_pdfs/chinaxiv-202508.00255.pdf)  
57. Platform market: The evolution of research paradigms - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/393379208_Platform_market_The_evolution_of_research_paradigms](https://www.researchgate.net/publication/393379208_Platform_market_The_evolution_of_research_paradigms)  
58. The platform economy and futures of market societies: Salient tensions in ecosystem evolution - IDEAS/RePEc, accessed April 18, 2026, [https://ideas.repec.org/a/eee/jbrese/v189y2025ics0148296324005411.html](https://ideas.repec.org/a/eee/jbrese/v189y2025ics0148296324005411.html)  
59. Can AgentExchange Cement Salesforce's Lead in the Agentic AI Platform Race? - The Futurum Group, accessed April 18, 2026, [https://futurumgroup.com/insights/can-agentexchange-cement-salesforces-lead-in-the-agentic-ai-platform-race/](https://futurumgroup.com/insights/can-agentexchange-cement-salesforces-lead-in-the-agentic-ai-platform-race/)  
60. Game Theory 7 - Mechanism Design and Institutional Engineering — Designing Rules So Incentives Produce Desired Outcomes  
61. The Role of Population Games and Evolutionary Dynamics in Distributed Control Systems, accessed April 18, 2026, [http://www.iri.upc.edu/files/scidoc/1783-The-Role-of-Population-Games-and-Evolutionary-Dynamics-in-Distributed-Control-Systems.pdf](http://www.iri.upc.edu/files/scidoc/1783-The-Role-of-Population-Games-and-Evolutionary-Dynamics-in-Distributed-Control-Systems.pdf)  
62. The Nature And Dynamics Of Organizational Capabilities | Request PDF - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/200465508_The_Nature_And_Dynamics_Of_Organizational_Capabilities](https://www.researchgate.net/publication/200465508_The_Nature_And_Dynamics_Of_Organizational_Capabilities)  
63. Materiality and Routine Dynamics (Chapter 7) - Cambridge University Press & Assessment, accessed April 18, 2026, [https://www.cambridge.org/core/books/cambridge-handbook-of-routine-dynamics/materiality-and-routine-dynamics/DE9B48AD7F92C510F83DAB04703AFA77](https://www.cambridge.org/core/books/cambridge-handbook-of-routine-dynamics/materiality-and-routine-dynamics/DE9B48AD7F92C510F83DAB04703AFA77)  
64. Demystifying emergence of organizational routines - Emerald Insight, accessed April 18, 2026, [https://www.emerald.com/jocm/article/30/4/525/250079/Demystifying-emergence-of-organizational-routines](https://www.emerald.com/jocm/article/30/4/525/250079/Demystifying-emergence-of-organizational-routines)  
65. Organizational Evolution, Learning, and Selection: A Genetic-Algorithm-Based Model, accessed April 18, 2026, [https://journals.aom.org/doi/10.5465/257001](https://journals.aom.org/doi/10.5465/257001)  
66. The Evolutionary Dynamics of the Artificial Intelligence Ecosystem - Semantic Scholar, accessed April 18, 2026, [https://pdfs.semanticscholar.org/6a49/a26aa12d00d5227c51805c6ed422e1d8788c.pdf](https://pdfs.semanticscholar.org/6a49/a26aa12d00d5227c51805c6ed422e1d8788c.pdf)  
67. Evolutionary game theory and multi-agent reinforcement learning - Maximum Academic Press, accessed April 18, 2026, [https://maxapress.com/data/article/ker/preview/pdf/S026988890500041X.pdf](https://maxapress.com/data/article/ker/preview/pdf/S026988890500041X.pdf)  
68. Game Theory and Multi-Agent Reinforcement Learning : From Nash Equilibria to Evolutionary Dynamics - arXiv, accessed April 18, 2026, [https://arxiv.org/html/2412.20523v1](https://arxiv.org/html/2412.20523v1)  
69. Connect-4 AI: A Comprehensive Taxonomy and Critical Review of Methods and Metrics, accessed April 18, 2026, [https://www.preprints.org/manuscript/202601.2416](https://www.preprints.org/manuscript/202601.2416)  
70. Game Theory 6 - Repeated Interaction, Reputation, and the Shadow of the Future — Cooperation, Punishment, and Relational Stability  
71. Connect-4 AI: A Comprehensive Taxonomy and Critical Review of Methods and Metrics, accessed April 18, 2026, [https://www.mdpi.com/2073-8994/18/2/293](https://www.mdpi.com/2073-8994/18/2/293)  
72. Evolution and population dynamics questions (practice) - Khan Academy, accessed April 18, 2026, [https://www.khanacademy.org/test-prep/mcat/biomolecules/evolution-population-dynmaics/e/evolution-and-population-dynamics-questions](https://www.khanacademy.org/test-prep/mcat/biomolecules/evolution-population-dynmaics/e/evolution-and-population-dynamics-questions)  
73. Measuring Population Dynamics: Ne, Bottlenecks & Migration - CD Genomics, accessed April 18, 2026, [https://www.cd-genomics.com/pop-genomics/resources/measuring-population-dynamics.html](https://www.cd-genomics.com/pop-genomics/resources/measuring-population-dynamics.html)  
74. Population Ecology Virtual Lab Answers - CLaME, accessed April 18, 2026, [https://clame.nyu.edu/index.jsp/E05E80/311895/PopulationEcologyVirtualLabAnswers.pdf](https://clame.nyu.edu/index.jsp/E05E80/311895/PopulationEcologyVirtualLabAnswers.pdf)  
75. Evolution Games Theory: Population Games - CSE, CUHK, accessed April 18, 2026, [https://www.cse.cuhk.edu.hk/~cslui/CSC6480/population_games.pdf](https://www.cse.cuhk.edu.hk/~cslui/CSC6480/population_games.pdf)  
76. Evolution of learned strategy choice in a frequency-dependent game - PMC - NIH, accessed April 18, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC3267151/](https://pmc.ncbi.nlm.nih.gov/articles/PMC3267151/)  
77. Game Theory 3 - Strategic Representation and Formalization — Modeling Strategic Reality with Matrices, Trees, Information Sets, and Type Spaces

---