# B. Equilibrium and Information — Stability, Beliefs, and Strategic Knowledge Systems

Strategic analysis, as established in the foundational ontology of this canon, rests upon the transition from individual optimization to the recursive complexity of strategic interdependence. While the first report defined the primitives of players, actions, and utilities, it operated largely in an informational vacuum where the parameters of the game were assumed to be static and transparent. This second report addresses the critical deepening of that trunk ontology: the realization that strategic stability is not merely a product of material incentives, but a property of the structured knowledge environment in which players operate.1

In a world of perfect and complete information, equilibrium is a straightforward mathematical fixed point. However, the deepest reality of social, economic, and political systems is one of uncertainty—uncertainty not just about the state of nature, but about the motives, capabilities, and observations of others.1 Here, equilibrium and information become a coupled system. Equilibrium without information is sterile, as it ignores the inferential labor required to sustain a best response; information without equilibrium is unanchored, providing data without a stable interpretive frame for how that data will be utilized by rational agents.3 This document serves as the account of how strategic stability depends on the distribution of knowledge, the structure of belief hierarchies, and the rigorous consistency requirements that make coordination possible in a world of hidden types and noisy signals.

## **Inherited Primitives from Report 1**

To preserve modular discipline, this report takes as given the basic infrastructure of non-cooperative game theory. A player is understood as an autonomous agent with a preference ordering represented by a utility function.1 A strategy is not a single action but a comprehensive plan for every contingency the player might face. The concept of the best response—the choice that maximizes utility given the anticipated strategies of others—remains the causal engine of the field.1 Finally, Nash equilibrium is inherited as the candidate rest-state of mutual strategic fit, where expectations and actions are consistent with one another.1

The new burden of Report 2 is to explain why these primitives often fail to generate stable predictions without an explicit account of information. The core question shifts from "what is the equilibrium?" to "what kind of informational world must exist for equilibrium to mean anything at all?".2

## **The Coupled Architecture of Information and Equilibrium**

The resolution of strategic uncertainty requires a precise taxonomy of informational regimes. These regimes are not mere descriptors but fundamental constraints that shape the feasible set of beliefs and, consequently, the stability of the resulting equilibrium.

### **Categorizing Informational Regimes**

Strategic reality changes qualitatively across four primary axes of information. The analyst must distinguish these to determine which solution concepts—ranging from simple Nash equilibrium to the more refined Sequential Equilibrium—are appropriate for the task.

| Informational Axis | Distinction | Definition and Strategic Impact |
| :---- | :---- | :---- |
| **History of Play** | Perfect vs. Imperfect | Perfect information implies all previous moves are observed (e.g., chess). Imperfect information occurs when moves are simultaneous or hidden, requiring belief systems.1 |
| **Game Structure** | Complete vs. Incomplete | Complete information implies payoffs and rules are common knowledge. Incomplete information involves uncertainty about "types" (payoffs, motives, or costs).9 |
| **Distribution** | Symmetric vs. Asymmetric | Symmetric information means all players have the same data. Asymmetric information creates incentives for signaling (revealing) or screening (extracting) data.3 |
| **Synchronization** | Public vs. Private | Public signals synchronize beliefs and facilitate common knowledge. Private signals lead to diverging beliefs and coordination fragility.14 |

Strategic reasoning undergoes a phase shift as one moves from complete to incomplete information. In a complete-information game, uncertainty is strategic: "What will they do?".1 In an incomplete-information game, uncertainty is both strategic and structural: "What will they do, given who they might be?".16 This requires the introduction of "types," a formal packaging of hidden characteristics that converts structural uncertainty into a manageable probability distribution.18

### **The Information Set as a Foundational Unit**

In the extensive form of a game, information is captured through "information sets." An information set is a collection of decision nodes that a player cannot distinguish between at the time they must act.3 If an information set contains multiple nodes, the game is one of imperfect information. This formalization prevents the "Robinson Crusoe" error of assuming an agent knows exactly where they are in a sequence of events.1

The size and distribution of information sets determine the degree of "informational fog." In high-resolution modeling, the information set is where belief formation begins. A player at a non-singleton information set must assign a probability to being at each node within that set. This probability is not a guess; in equilibrium, it must be consistent with the strategies of the other players and the rules of the game.20

## **Beliefs, Higher-Order Beliefs, and Common Knowledge**

In an environment of strategic interdependence, what a player believes about the world is less important than what they believe about their opponents. This realization led to the development of **Interactive Epistemology**, the study of the recursive knowledge structures that support equilibrium.8

### **The Hierarchy of Beliefs**

A player's epistemic state is not a single point but a hierarchy:

1. **First-Order Beliefs**: Beliefs about payoff-relevant parameters (e.g., "I believe the market demand is high") or about the opponent's actions.23  
2. **Second-Order Beliefs**: Beliefs about the opponent's first-order beliefs (e.g., "I believe that the competitor believes market demand is low").23  
3. **Higher-Order Beliefs**: The infinite sequence of "I believe that you believe that I believe...".16

These hierarchies are the load-bearing core of strategic reasoning. Many coordination failures occur not because players disagree on the facts, but because they disagree on what others believe about the facts. The Mertens and Zamir (1985) formulation proved that any coherent infinite hierarchy of beliefs could be represented as a single "type" in a universal type space, effectively closing the model and allowing analysts to treat beliefs as an input rather than an infinite regress.26

### **Common Knowledge and its Fragility**

The ultimate synchronization of a belief hierarchy is **Common Knowledge**. A fact X is common knowledge if everyone knows X, everyone knows that everyone else knows X, and so on.1 Most standard equilibrium concepts, such as Nash equilibrium, implicitly assume common knowledge of the game's rules and the players' rationality.2

However, common knowledge is notoriously fragile. The **Electronic Mail Game** (Rubinstein, 1989) serves as the canonical warning.32 In this game, two players wish to coordinate on a risky action that pays off only if both participate. Player 1 receives a signal that the state is "Good" and sends an automated message to Player 2. The technology is slightly faulty—there is a small chance a message is lost. If Player 2 receives the message, an automated confirmation is sent. If Player 1 receives the confirmation, another confirmation is sent, and so on.

Rubinstein proved that no matter how many confirmations are sent (e.g., 1,000), the players will never coordinate on the risky action.32 The reason is that there is never common knowledge; there is always a "last message" that might have been lost, creating a wedge of doubt that ripples down the belief hierarchy. Strategic stability thus depends on the *mode* of knowledge acquisition: public announcements create common knowledge, while private, asynchronous communication often fails to do so.14

### **Aumann’s Agreement Theorem**

A central pillar of interactive epistemology is Robert Aumann’s (1976) "Agreeing to Disagree." It states that if two rational Bayesian agents start with a **Common Prior** and their posterior beliefs about an event are common knowledge, those beliefs *must* be identical.30

The insight here is that the mere knowledge of another person's differing opinion is itself a signal. If you know I disagree with you, and you believe I am rational and have access to private information, you should revise your belief to account for my insight. This process continues until beliefs converge. This theorem provides a rigorous foundation for the "No-Trade" results in economics: risk-averse agents will not trade purely because of different information, as the offer to trade signals that the other party knows something you do not, making the trade unfavorable for you.3

## **Type Uncertainty and the Bayesian Revolution**

When information is incomplete, the standard Nash equilibrium is replaced by the **Bayesian Nash Equilibrium (BNE)**. This concept, pioneered by John Harsanyi, allows analysts to maintain the assumption of rational optimization even when players are "in the dark" about their opponents' preferences.11

### **The Harsanyi Transformation**

The breakthrough of the Harsanyi transformation was to treat uncertainty about *types* (who the players are) as uncertainty about *moves of Nature* (what has happened).18

1. **Ex-Ante Stage**: Nature draws a type profile for all players from a commonly known distribution (the common prior).9  
2. **Interim Stage**: Each player learns their own type but not the types of others.9  
3. **Ex-Post Stage**: All types are revealed (this stage is used primarily for evaluation, not decision-making).9

In a BNE, a strategy si(ti) is a function that specifies an action for every possible type a player might have. The equilibrium condition is that for every type ti that occurs with positive probability, the action si(ti) must maximize the player’s expected utility, given the distribution of types and strategies of their opponents.17

### **Types as Packages of Hidden Characteristics**

A "type" is a formal way of packaging everything that is not common knowledge. This includes:

* **Payoff Parameters**: Production costs, risk tolerance, or valuation of an object.10  
* **Capabilities**: Budget constraints, technological levels, or cognitive depth.1  
* **Higher-Order Beliefs**: What the player believes about others' beliefs.16

By using type spaces, theorists can model incredibly complex interactions—like auctions or trade negotiations—without having to explicitly list every possible thought a player might have. The "type" becomes the sufficient statistic for the player's strategic reality.41

### **Example: Bayesian Stability in First-Price Auctions**

Consider a first-price sealed-bid auction with two bidders whose valuations (v) are uniformly distributed between 0 and 100. A bidder's type is their valuation v. In a BNE, each type v adopts a strategy b(v) = v/2.17

* **Best Response**: Bidding half one's value balances the trade-off between the profit margin (if you win) and the probability of winning (which increases with a higher bid).17  
* **Stability**: This strategy is stable because if one bidder uses b(v) = v/2, the other bidder's best response is also b(v) = v/2. This equilibrium is conditioned entirely on the informational assumption (the common prior of the uniform distribution).17

## **The Hierarchy of Equilibrium Refinements**

Ordinary Nash equilibrium often creates pathologies in informational settings, particularly in dynamic games where players take turns. BNE can support "non-credible" outcomes that rely on threats which would be irrational to carry out if the player were actually forced to act.6 To resolve this, the field has developed a family of refinements.

### **Perfect Bayesian Equilibrium (PBE)**

The **Perfect Bayesian Equilibrium** (PBE) is the "bread and butter" solution for dynamic games with incomplete information.43 A PBE consists of an assessment (sigma, mu), where sigma is a strategy profile and mu is a **belief system**—a probability distribution over nodes for every information set in the game.20

PBE requires:

1. **Sequential Rationality**: At every information set (including those off the equilibrium path), the player whose turn it is must be maximizing their expected utility given their beliefs mu.43  
2. **Bayesian Consistency**: Beliefs must be updated using Bayes' rule at every information set reached with positive probability in equilibrium.43

The "Weak PBE" concept is often used in practice, but it has a significant flaw: it places no restrictions on beliefs at information sets that are *never* reached (off-path nodes).43 This allows an analyst to "support" almost any strategy by assuming that if an off-path move occurred, the players would hold some arbitrary, "crazy" belief that makes their response rational.22

### **Sequential Equilibrium**

To provide more discipline, Kreps and Wilson (1982) introduced **Sequential Equilibrium**. This refinement demands **Kreps-Wilson Consistency**: the assessment (sigma, mu) must be the limit of a sequence of assessments (sigma_n, mu_n) where each sigma_n is a "totally mixed" strategy profile.43

By assuming that every action has at least a tiny probability of being chosen (a "tremble"), every information set becomes reachable. This forces off-path beliefs to be derived from a coherent theory of mistakes, preventing the use of arbitrary belief-threats to sustain an equilibrium.20 Sequential equilibrium is more restrictive than PBE and filters out many "unreasonable" outcomes, particularly in reputation and entry-deterrence games.20

| Solution Concept | Information Type | Key Innovation |
| :---- | :---- | :---- |
| **Nash Equilibrium** | Complete | Mutual consistency of strategies. |
| **Subgame Perfect (SPE)** | Dynamic/Complete | Eliminates non-credible threats in subgames. |
| **Bayesian Nash (BNE)** | Incomplete | Handles uncertainty about types and payoffs. |
| **Perfect Bayesian (PBE)** | Dynamic/Incomplete | Pairs strategies with a belief system (mu). |
| **Sequential Equilibrium** | Dynamic/Incomplete | Forces off-path beliefs to be "consistent" via trembles. |

20

## **Signaling and Screening: The Strategic Use of Hidden Information**

Asymmetric information creates two fundamental strategic movements: **signaling**, where the informed party acts to reveal their type, and **screening**, where the uninformed party acts to force the informed to reveal their type.12

### **Signaling Games: The Spence Model**

In a signaling game, the informed party moves first. The classic model is Michael Spence’s (1973) account of job market education.51 Workers know their productivity (High or Low) and choose a level of education (e). Education is costly, and crucially, it is *more* costly for Low-productivity workers. Firms observe e and offer a wage (w).51

The signaling world typically admits three kinds of PBE:

* **Separating Equilibrium**: Different types choose different signals (e.g., High-types get degrees, Low-types do not). The signal perfectly reveals the type, and firms pay wages accordingly.45  
* **Pooling Equilibrium**: All types choose the same signal (e.g., everyone gets a degree). The signal reveals nothing, and firms offer a wage based on the average productivity.45  
* **Semi-Separating Equilibrium**: Some types randomize, leading to partial information revelation.39

### **Screening Games: Rothschild and Stiglitz**

In screening games, the uninformed party moves first, offering a "menu" of contracts. In the insurance market model of Rothschild and Stiglitz (1976), firms offer different combinations of coverage and premiums.13 The goal is to design contracts that satisfy **Incentive Compatibility (IC)**: each type finds it optimal to choose the contract intended for them. A fundamental result of the screening literature is the **Non-existence of Pooling Equilibria** in competitive environments. A firm could always offer a "cream-skimming" contract that is slightly better for low-risk types but unprofitable for high-risk types, thereby breaking the pool.51

### **Refining Signaling: The Intuitive Criterion and D1**

Signaling games are notorious for "equilibrium multiplicity." For example, in the Spence model, there is a continuum of pooling and separating equilibria.51 To select the most "reasonable" one, theorists use refinements like the **Intuitive Criterion** (Cho and Kreps, 1987).52

The Intuitive Criterion restricts off-path beliefs by asking if a deviation could possibly be rational for a certain type. If type T1 could never benefit from an off-path signal S*, even if the receiver responded in the most favorable way possible, then the receiver should place zero probability on the sender being type T1 if they observe S*.52 This refinement often eliminates pooling equilibria in the Spence model, selecting the **least-cost separating equilibrium** (the Riley outcome) as the unique prediction.52

The **D1 refinement** (Banks and Sobel, 1987) is even more powerful. It compares types to see which one has a "stronger" incentive to deviate. If type A would deviate for a wider range of receiver responses than type B, the receiver should conclude the deviator is type A.52 D1 is the standard tool for ensuring that signaling models produce sharp, unique predictions in multi-type environments.54

## **Global Games: The Impact of Noisy Information**

A major critique of equilibrium analysis is its sensitivity to the "Common Knowledge of Payoffs" assumption. If a tiny change in a player's observation of the game can lead to a massive change in the equilibrium outcome, the theory is arguably too fragile for real-world application.14

**Global Games** (Carlsson and van Damme, 1993) address this by introducing a small amount of noise into the players' observations of the game's fundamentals.14 In many coordination games (like bank runs or currency crises), standard theory predicts multiple equilibria: everyone attacks or no one attacks. In a global game, however, players receive private, noisy signals. Because each player must now guess what others' signals are, and what others believe *their* signals are, the "strategic uncertainty" (guessing others) becomes the dominant force.14

The "Magical Result" of global games is that even as the noise becomes infinitesimally small, the multiple equilibria disappear, leaving a **unique equilibrium selection**—typically the **Risk-Dominant** equilibrium.14 This shows that strategic stability is often a function of how information is "smeared" across the population, rather than the absolute clarity of the payoffs themselves.14

## **Epistemic Game Theory: The Conditions of Rationality**

As the canon deepens, it moves from asking "what happens?" to "what must players know for this to happen?" This is the domain of **Epistemic Game Theory**.7

### **Rationality and Belief in Rationality**

A strategy is **Rationalizable** if it is a best response to *some* belief about the actions of others, which in turn is a best response to *some* belief about others' actions, and so on.7

* **Mutual Knowledge of Rationality**: Everyone is rational.8  
* **Common Belief in Rationality**: Everyone is rational, everyone knows everyone is rational, etc..23

For a Nash equilibrium to be a plausible prediction, we must assume **Common Knowledge of the Game** and **Common Knowledge of Rationality**.2 If a player has even a slight doubt that their opponent is rational, they may deviate from the equilibrium strategy to hedge against "irrational" play. This explains why many theoretically stable equilibria fail in the laboratory: the epistemic scaffolding required to support them is too demanding for human strategic cognition.1

### **The Limits of Common Priors**

The Common Prior Assumption (CPA)—that all differences in belief are due to information—is the link between epistemic foundations and Bayesian Nash Equilibrium.17 Without the CPA, BNE becomes indistinguishable from correlated equilibrium; any outcome can be explained away as "the players just had different starting beliefs".69 While theoretically convenient, the CPA is increasingly challenged by behavioral game theory, which finds that humans often "agree to disagree" due to cognitive biases rather than private information.30

## **Debates, Critiques, and Scope Conditions**

The coupled architecture of equilibrium and information provides high-resolution insights, but it also reveals the boundaries of the non-cooperative framework.

### **The Computational Critique**

A significant contemporary challenge is **Computational Complexity**. Daskalakis and others have proved that computing a Nash equilibrium is **PPAD-complete**, meaning that for complex games with many players or large type spaces, finding the equilibrium is effectively impossible for both real agents and computers.40

This creates a "time skew" between canonical theory and serious practice: while the theory treats equilibrium as an instant rest-state, modern analysts often use **Learning Dynamics** or **MARL (Multi-Agent Reinforcement Learning)** to see if agents can *discover* the equilibrium through trial and error.40 If an equilibrium is computationally inaccessible, its status as a "behavioral prediction" is severely compromised.40

### **Multiplicity and Refinement-Chasing**

The "refinement program" (PBE, Sequential, Divinity) has been criticized for being ad-hoc. For every refinement that "solves" a pathology in one game, another game can be constructed where that refinement produces a counter-intuitive result.44 This has led some researchers to pivot away from mathematical refinements toward **Structural Estimation** and **Behavioral Data**, asking what beliefs players *actually* hold rather than what beliefs they *must* hold to satisfy a consistency theorem.1

### **Where the Framework Illuminates Powerfully**

The equilibrium-information lens is at its most potent in:

1. **High-Stakes Signaling**: Sovereign debt crises, nuclear deterrence, and corporate takeover defenses where costly actions are used to prove type.1  
2. **Institutional Design**: Mechanism design for auctions, carbon credits, and insurance markets where the "rules" are engineered to manage informational flow.1  
3. **Coordination Diagnostics**: Understanding why bank runs or revolutions happen by mapping the breakdown of common knowledge.34

### **Where the Framework Becomes Thin**

The framework struggles or distorts reality in:

1. **Radically Bounded Cognition**: Environments where belief hierarchies are too deep to be processed.1  
2. **Unstable Preferences**: Cases where identity or social contagion causes mid-game shifts in utility, rendering the "type" concept moot.1  
3. **Endogenous Rules**: Situations where the informational environment is itself a choice of the players, creating a meta-game that static analysis cannot capture.1

## **Anchor Cases for Strategic Knowledge**

The following cases provide the grounded geometry for the concepts developed in this report.

| Case | Informational Burden | Core Lesson |
| :---- | :---- | :---- |
| **Electronic Mail Game** | Lack of Common Knowledge | Finite levels of knowledge do not approximate common knowledge; coordination collapsess.32 |
| **Spence Labor Market** | Signaling Asymmetry | Costly signals (education) can separate types even if they don't increase productivity.51 |
| **Rothschild-Stiglitz** | Screening/Adverse Selection | Competitive pooling is unstable; firms must separate types through contract menus.51 |
| **Global Games** | Strategic Uncertainty | Small amounts of noise can resolve multiplicity and select a unique risk-dominant outcome.14 |
| **Beer-Quiche Game** | Equilibrium Dominance | Off-path beliefs must be "reasonable"; wimps won't drink beer even if it fools people.56 |

14

## **Downstream Dependencies**

This report establishes the epistemic and informational infrastructure for the remainder of the canon:

* **Report 3 (Formal Representation)**: Will translate these information sets and type spaces into advanced game trees and extensive-form modeling craft.  
* **Report 4 (Sequential Strategy)**: Will deepen the logic of PBE to explore the "power of commitment" and the "shadow of the future."  
* **Report 7 (Mechanism Design)**: Will use screening and incentive compatibility to engineer entire institutional architectures.  
* **Report 11 (Strategic Failure)**: Will use the breakdown of common knowledge as a diagnostic for systemic coordination collapse.

## **What This Report Does Not Yet Cover**

To maintain structural boundaries, the following are reserved for later modules:

* **Full Extensive-Form Craft**: The visual "art" of tree construction and labeling information sets.  
* **Repeated-Game Cooperation**: The "Folk Theorem" and the informational conditions (public monitoring) required for long-term trust.  
* **Applied Mechanism Design**: The specific blueprints for auction formats or matching algorithms.  
* **Coalitional Information**: How secret communication and side-deals work in cooperative game settings.

## **Glossary of Canonical Terms**

* **Assessment (sigma, mu)**: A pair consisting of a strategy profile and a belief system.43  
* **Belief System (mu)**: A mapping for every information set to a probability distribution over its nodes.20  
* **Common Knowledge**: A condition where every player knows X, knows everyone knows X, and so on.1  
* **Incentive Compatibility (IC)**: A set of constraints ensuring each type finds it optimal to act as intended.13  
* **Information Set**: Indistinguishable decision nodes for a player at a specific point in time.3  
* **Off-Path Beliefs**: Beliefs held by players at nodes that are never reached in equilibrium.43  
* **Sequential Rationality**: Optimization at every decision point, given current beliefs and others' future play.43  
* **Single-Crossing Property**: A condition on payoffs where different types have different marginal rates of substitution.57  
* **Type (t)**: A formal encapsulation of a player's private information and beliefs.11

## **Synthesis: Strategic Stability as a Knowledge Problem**

The central claim of this analysis is that strategic stability is never merely a matter of aligned material incentives. It is a state of **knowledge synchronization**. An equilibrium is truly stable only when it is supported by a structured knowledge environment in which beliefs, observations, and inferential expectations support mutual strategic fit.

The field’s shift from simple Nash equilibrium to Sequential Equilibrium and beyond reflects the recognition that the "informational world" is the load-bearing pillar of the "strategic world." Informational asymmetries and the fragility of common knowledge explain why "rational" outcomes are often hard to achieve in the real world. Institutions, therefore, do not only work by changing payoffs (e.g., through fines or rewards); they work by reshaping knowledge conditions—creating public signals, standardizing contracts, and providing the verification mechanisms that allow common knowledge to form.

By treating equilibrium and information as one coupled system, the strategist moves from a two-dimensional view of "who wins what" to a high-resolution understanding of how the invisible scaffolding of beliefs either holds a system together or allows it to collapse. Strategic analysis, in its most advanced form, is the art of diagnosing and architecting the informational conditions under which stability becomes possible.1

#### **Works cited**

1. Game Theory 1 - The Geometry of Strategic Conflict — An Ontology of Incentives, Interdependence, and Equilibrium  
2. The Prize in Economics 1994 - Press release - NobelPrize.org, accessed April 18, 2026, [https://www.nobelprize.org/prizes/economic-sciences/1994/press-release/](https://www.nobelprize.org/prizes/economic-sciences/1994/press-release/)  
3. Information and Beliefs in Game Theory - Archived events, projects ..., accessed April 18, 2026, [https://archive.illc.uva.nl/HPI/Draft_Information_and_beliefs.pdf](https://archive.illc.uva.nl/HPI/Draft_Information_and_beliefs.pdf)  
4. Epistemic Foundations of Game Theory - Stanford Encyclopedia of Philosophy, accessed April 18, 2026, [https://plato.stanford.edu/archives/sum2015/entries/epistemic-game/](https://plato.stanford.edu/archives/sum2015/entries/epistemic-game/)  
5. Game Theory | Internet Encyclopedia of Philosophy, accessed April 18, 2026, [https://iep.utm.edu/game-th/](https://iep.utm.edu/game-th/)  
6. Nash equilibrium - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Nash_equilibrium](https://en.wikipedia.org/wiki/Nash_equilibrium)  
7. Epistemic Game Theory - Adam Brandenburger, accessed April 18, 2026, [https://www.adambrandenburger.com/aux/material/epistemic-game-theory-optimized-06-06-19.pdf](https://www.adambrandenburger.com/aux/material/epistemic-game-theory-optimized-06-06-19.pdf)  
8. Epistemic Foundations of Game Theory - Stanford Encyclopedia of Philosophy, accessed April 18, 2026, [https://plato.stanford.edu/entries/epistemic-game/](https://plato.stanford.edu/entries/epistemic-game/)  
9. Information set (game theory) - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Information_set_(game_theory)](https://en.wikipedia.org/wiki/Information_set_(game_theory))  
10. Week 8: Games of Incomplete Information - University of Warwick, accessed April 18, 2026, [https://warwick.ac.uk/fac/soc/economics/staff/dsgroi/ec202/w08_games_of_incomplete_information.pdf](https://warwick.ac.uk/fac/soc/economics/staff/dsgroi/ec202/w08_games_of_incomplete_information.pdf)  
11. John Harsanyi - Jewish Virtual Library, accessed April 18, 2026, [https://www.jewishvirtuallibrary.org/john-harsanyi](https://www.jewishvirtuallibrary.org/john-harsanyi)  
12. Signaling vs. Screening Models with Asymmetric Information | Policy Commons, accessed April 18, 2026, [https://policycommons.net/artifacts/1381687/sorting-out-the-differences-between-signaling-and-screening-models/1995951/](https://policycommons.net/artifacts/1381687/sorting-out-the-differences-between-signaling-and-screening-models/1995951/)  
13. Screening (economics) - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Screening_(economics)](https://en.wikipedia.org/wiki/Screening_(economics))  
14. Coordination, timing and common knowledge - MIT Economics, accessed April 18, 2026, [https://economics.mit.edu/sites/default/files/publications/coordination.pdf](https://economics.mit.edu/sites/default/files/publications/coordination.pdf)  
15. Common Belief Foundations of Global Games - MIT Economics, accessed April 18, 2026, [https://economics.mit.edu/sites/default/files/publications/cbf%20JET%20Final.pdf](https://economics.mit.edu/sites/default/files/publications/cbf%20JET%20Final.pdf)  
16. Bayesian Games: Games with Incomplete Information, accessed April 18, 2026, [http://www.ma.huji.ac.il/~zamir/documents/BayesianGames_ShmuelZamir.pdf](http://www.ma.huji.ac.il/~zamir/documents/BayesianGames_ShmuelZamir.pdf)  
17. Bayes–Nash equilibrium - Microeconomic Theory Concepts, accessed April 18, 2026, [https://umbrex.com/resources/economics-concepts/microeconomic-theory/bayes-nash-equilibrium/](https://umbrex.com/resources/economics-concepts/microeconomic-theory/bayes-nash-equilibrium/)  
18. Games with Incomplete Information Played by "Bayesian" Players, I-III. Part II. Bayesian Equilibrium Points - John C. Harsanyi, accessed April 18, 2026, [https://www1.cmc.edu/pages/faculty/MONeill/math188/papers/harsanyi4.pdf](https://www1.cmc.edu/pages/faculty/MONeill/math188/papers/harsanyi4.pdf)  
19. Analytic Theory II: Static Games with Incomplete Information - Branislav L. Slantchev (UCSD) - University of California San Diego, accessed April 18, 2026, [http://slantchev.ucsd.edu/courses/ps203b/04%20Static%20Games%20with%20Incomplete%20Information.pdf](http://slantchev.ucsd.edu/courses/ps203b/04%20Static%20Games%20with%20Incomplete%20Information.pdf)  
20. Sequential equilibrium - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Sequential_equilibrium](https://en.wikipedia.org/wiki/Sequential_equilibrium)  
21. G5212: Game Theory Mark Dean Spring 2017, accessed April 18, 2026, [http://www.columbia.edu/~md3405/GT_Game_12_17.pdf](http://www.columbia.edu/~md3405/GT_Game_12_17.pdf)  
22. Perfect Bayesian equilibrium - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Perfect_Bayesian_equilibrium](https://en.wikipedia.org/wiki/Perfect_Bayesian_equilibrium)  
23. 9.2 Epistemic Game Theory - Andrés Perea - EPICENTER, accessed April 18, 2026, [https://epicenter.name/Perea/Papers/581-93313_ch42_1P.pdf](https://epicenter.name/Perea/Papers/581-93313_ch42_1P.pdf)  
24. Epistemic Game Theory: Beliefs and Types | Request PDF - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/397483216_Epistemic_Game_Theory_Beliefs_and_Types](https://www.researchgate.net/publication/397483216_Epistemic_Game_Theory_Beliefs_and_Types)  
25. Hierarchy of beliefs - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Hierarchy_of_beliefs](https://en.wikipedia.org/wiki/Hierarchy_of_beliefs)  
26. 14 aug '08 09:22 center rationality 972 2 6513681, accessed April 18, 2026, [http://www.ma.huji.ac.il/~zamir/ijgt85.pdf](http://www.ma.huji.ac.il/~zamir/ijgt85.pdf)  
27. Hierarchies of Beliefs for Many Player Games - IDEAS/RePEc, accessed April 18, 2026, [https://ideas.repec.org/p/wrk/wrkesp/72.html](https://ideas.repec.org/p/wrk/wrkesp/72.html)  
28. Strategic Type Spaces∗ - Rafael Veiel, accessed April 18, 2026, [https://veiel.com/wp-content/uploads/Strategic-Type-Spaces.pdf](https://veiel.com/wp-content/uploads/Strategic-Type-Spaces.pdf)  
29. Agreeing to disagree: a survey - Economics, accessed April 18, 2026, [https://faculty.econ.ucdavis.edu/faculty/bonanno/PDF/agree.pdf](https://faculty.econ.ucdavis.edu/faculty/bonanno/PDF/agree.pdf)  
30. Agreeing to Disagree - Robert J. Aumann, accessed April 18, 2026, [https://people.maths.bris.ac.uk/~maxvd/Aumann_1976.pdf](https://people.maths.bris.ac.uk/~maxvd/Aumann_1976.pdf)  
31. Common Knowledge in Game Theory | Cairn.info, accessed April 18, 2026, [https://shs.cairn.info/journal-revue-economique-2023-4-page-569?lang=en](https://shs.cairn.info/journal-revue-economique-2023-4-page-569?lang=en)  
32. Faulty Communication: Some Variations on the Electronic Mail Game - MIT Economics, accessed April 18, 2026, [https://economics.mit.edu/sites/default/files/publications/paper_30_Faulty_Communication.pdf](https://economics.mit.edu/sites/default/files/publications/paper_30_Faulty_Communication.pdf)  
33. Electronic mail game - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Electronic_mail_game](https://en.wikipedia.org/wiki/Electronic_mail_game)  
34. Coordination, Communication and Common Knowledge: A Retrospective on the Electronic Mail Game - EliScholar, accessed April 18, 2026, [https://elischolar.library.yale.edu/cgi/viewcontent.cgi?article=2668&context=cowles-discussion-paper-series](https://elischolar.library.yale.edu/cgi/viewcontent.cgi?article=2668&context=cowles-discussion-paper-series)  
35. Agreement and disagreement in a non-classical world - PMC, accessed April 18, 2026, [https://pmc.ncbi.nlm.nih.gov/articles/PMC10822709/](https://pmc.ncbi.nlm.nih.gov/articles/PMC10822709/)  
36. Aumann's agreement theorem - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Aumann%27s_agreement_theorem](https://en.wikipedia.org/wiki/Aumann%27s_agreement_theorem)  
37. STRICT ROBUSTNESS TO INCOMPLETE INFORMATION 1. Introduction Equilibrium may be fragile to seemingly small departure from common - MIT Economics, accessed April 18, 2026, [https://economics.mit.edu/sites/default/files/inline-files/STRICT%20ROBUSTNESS%20TO%20INCOMPLETE%20INFORMATION.pdf](https://economics.mit.edu/sites/default/files/inline-files/STRICT%20ROBUSTNESS%20TO%20INCOMPLETE%20INFORMATION.pdf)  
38. Testing for Monotone Equilibrium Strategies in Games of Incomplete Information - arXiv, accessed April 18, 2026, [https://arxiv.org/html/2604.06643v1](https://arxiv.org/html/2604.06643v1)  
39. Incomplete Information: Bayesian Nash Equilibria, Auctions and Introduction to Social Learning - MIT Economics, accessed April 18, 2026, [https://economics.mit.edu/sites/default/files/inline-files/Lectures%2019-21%20-%20Bayesian%20Nash%20Equilibria%2C%20Auctions%20and%20Introduction%20to%20Social%20Learning.pdf](https://economics.mit.edu/sites/default/files/inline-files/Lectures%2019-21%20-%20Bayesian%20Nash%20Equilibria%2C%20Auctions%20and%20Introduction%20to%20Social%20Learning.pdf)  
40. The Bayesian Nash Equilibrium That (Practically) Can't Be Computed - Medium, accessed April 18, 2026, [https://medium.com/@aditrizky052/the-bayesian-nash-equilibrium-that-practically-cant-be-computed-e0cbe422349b](https://medium.com/@aditrizky052/the-bayesian-nash-equilibrium-that-practically-cant-be-computed-e0cbe422349b)  
41. Typical Types | MIT Economics, accessed April 18, 2026, [https://economics.mit.edu/sites/default/files/inline-files/Typical%20Types.pdf](https://economics.mit.edu/sites/default/files/inline-files/Typical%20Types.pdf)  
42. Non-wellfounded Set Theory > Universal Harsanyi type spaces ..., accessed April 18, 2026, [https://plato.stanford.edu/entries/nonwellfounded-set-theory/harsanyi-type-spaces.html](https://plato.stanford.edu/entries/nonwellfounded-set-theory/harsanyi-type-spaces.html)  
43. Game Theory, Lecture 2: Equilibrium Refinements - MIT OpenCourseWare, accessed April 18, 2026, [https://ocw.mit.edu/courses/14.126-game-theory-spring-2024/mit14_126_s24_lecture_2_refinements.pdf](https://ocw.mit.edu/courses/14.126-game-theory-spring-2024/mit14_126_s24_lecture_2_refinements.pdf)  
44. Dynamic Games with Incomplete Information - Stanford University, accessed April 18, 2026, [https://web.stanford.edu/~jdlevin/Econ%20203/DynamicGames.pdf](https://web.stanford.edu/~jdlevin/Econ%20203/DynamicGames.pdf)  
45. Perfect Bayesian Equilibrium When players move sequentially and have private infor, accessed April 18, 2026, [https://www.asc.ohio-state.edu/peck.33/Econ601/Econ601L15.pdf](https://www.asc.ohio-state.edu/peck.33/Econ601/Econ601L15.pdf)  
46. Dynamic Games: Perfect Bayesian Equilibrium | Game Theory... - Fiveable, accessed April 18, 2026, [https://fiveable.me/game-theory-economic-behavior/unit-8](https://fiveable.me/game-theory-economic-behavior/unit-8)  
47. Microeconomics II Lecture 5: Equilibrium Refinements Karl Wärneryd Stockholm School of Economics November 2016 1 - Jose-Elias Gallegos, accessed April 18, 2026, [https://www.joseeliasgallegos.com/uploads/7/5/1/4/75144577/miii1605.pdf](https://www.joseeliasgallegos.com/uploads/7/5/1/4/75144577/miii1605.pdf)  
48. Perfect Bayesian and sequential equilibria : a clarifying note - DSpace@MIT, accessed April 18, 2026, [http://dspace.mit.edu/bitstream/handle/1721.1/64017/perfectbayesians00fude.pdf?sequenc=1](http://dspace.mit.edu/bitstream/handle/1721.1/64017/perfectbayesians00fude.pdf?sequenc=1)  
49. Sequential equilibrium - Microeconomic Theory Concepts - Umbrex, accessed April 18, 2026, [https://umbrex.com/resources/economics-concepts/microeconomic-theory/sequential-equilibrium/](https://umbrex.com/resources/economics-concepts/microeconomic-theory/sequential-equilibrium/)  
50. Exploring the gap between perfect Bayesian equilibrium and sequential equilibrium - Economics, accessed April 18, 2026, [https://faculty.econ.ucdavis.edu/faculty/bonanno/PDF/PBEIII.pdf](https://faculty.econ.ucdavis.edu/faculty/bonanno/PDF/PBEIII.pdf)  
51. Signalling And Screening, accessed April 18, 2026, [http://www.dklevine.com/econ504/signallingb.pdf](http://www.dklevine.com/econ504/signallingb.pdf)  
52. Game Theory, Lecture 3: Signaling Games - MIT OpenCourseWare, accessed April 18, 2026, [https://ocw.mit.edu/courses/14.126-game-theory-spring-2024/mit14_126_s24_lecture_3_signaling.pdf](https://ocw.mit.edu/courses/14.126-game-theory-spring-2024/mit14_126_s24_lecture_3_signaling.pdf)  
53. Screening And Signaling Games | Encyclopedia.com, accessed April 18, 2026, [https://www.encyclopedia.com/social-sciences/applied-and-social-sciences-magazines/screening-and-signaling-games](https://www.encyclopedia.com/social-sciences/applied-and-social-sciences-magazines/screening-and-signaling-games)  
54. The Intuitive and Divinity Criterion: Interpretation and Step-by-Step Examples, accessed April 18, 2026, [https://www.researchgate.net/publication/227378854_The_Intuitive_and_Divinity_Criterion_Interpretation_and_Step-by-Step_Examples](https://www.researchgate.net/publication/227378854_The_Intuitive_and_Divinity_Criterion_Interpretation_and_Step-by-Step_Examples)  
55. Signaling game - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Signaling_game](https://en.wikipedia.org/wiki/Signaling_game)  
56. The Beer-Quiche Game - Game Theory 101, accessed April 18, 2026, [https://gametheory101.com/courses/game-theory-101/the-beer-quiche-game/](https://gametheory101.com/courses/game-theory-101/the-beer-quiche-game/)  
57. Understanding the Screening Model: Self-Selection in Microeconomics - Umbrex, accessed April 18, 2026, [https://umbrex.com/resources/economics-concepts/microeconomic-theory/screening-model-self-selection/](https://umbrex.com/resources/economics-concepts/microeconomic-theory/screening-model-self-selection/)  
58. Econ 506A (2007) Topics in Advanced Theory I ... - David Levine, accessed April 18, 2026, [http://www.dklevine.com/econ506/ergin.signal.pdf](http://www.dklevine.com/econ506/ergin.signal.pdf)  
59. Signaling Games and the Intuitive Criterion (Cho & Kreps, 1987) - David Levine, accessed April 18, 2026, [http://dklevine.com/econ506/ergin.signal.pdf](http://dklevine.com/econ506/ergin.signal.pdf)  
60. Intuitive criterion - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Intuitive_criterion](https://en.wikipedia.org/wiki/Intuitive_criterion)  
61. Natural Language Equilibrium I: Off-Path Conventions, accessed April 18, 2026, [https://bfi.uchicago.edu/wp-content/uploads/2025/05/BFI_WP_2025-64.pdf](https://bfi.uchicago.edu/wp-content/uploads/2025/05/BFI_WP_2025-64.pdf)  
62. The Intuitive and Divinity Criterion: - Felix Munoz-Garcia, accessed April 18, 2026, [https://felixmunozgarcia.com/wp-content/uploads/2020/10/intuitive-and-d1-criterion_fmg.pdf](https://felixmunozgarcia.com/wp-content/uploads/2020/10/intuitive-and-d1-criterion_fmg.pdf)  
63. Global Games, accessed April 18, 2026, [https://www.jyu.fi/sites/default/files/2025-06/Global%20games%20FINLAND%20SS.pdf](https://www.jyu.fi/sites/default/files/2025-06/Global%20games%20FINLAND%20SS.pdf)  
64. Coordination and Higher Order Uncertainty - Stanford University, accessed April 18, 2026, [https://web.stanford.edu/~jdlevin/Econ%20286/Global%20Games.pdf](https://web.stanford.edu/~jdlevin/Econ%20286/Global%20Games.pdf)  
65. The Robustness of Equilibria to Incomplete Information - UPenn Economics Department, accessed April 18, 2026, [https://economics.sas.upenn.edu/pier/working-paper/1995/robustness-equilibria-incomplete-information](https://economics.sas.upenn.edu/pier/working-paper/1995/robustness-equilibria-incomplete-information)  
66. Epistemic Game Theory - IDEAS/RePEc, accessed April 18, 2026, [https://ideas.repec.org/h/eee/gamchp/v4y2015icp619-702.html](https://ideas.repec.org/h/eee/gamchp/v4y2015icp619-702.html)  
67. Epistemic Game Theory - Cambridge University Press & Assessment, accessed April 18, 2026, [https://www.cambridge.org/core/books/epistemic-game-theory/21FD6D87C66B3BCF1B6D880A10D71D51](https://www.cambridge.org/core/books/epistemic-game-theory/21FD6D87C66B3BCF1B6D880A10D71D51)  
68. Common belief in rationality (Chapter 3) - Epistemic Game Theory, accessed April 18, 2026, [https://www.cambridge.org/core/books/epistemic-game-theory/common-belief-in-rationality/263E6FD8C99ED866F5DF568EE09D388B](https://www.cambridge.org/core/books/epistemic-game-theory/common-belief-in-rationality/263E6FD8C99ED866F5DF568EE09D388B)  
69. THE COMMON PRIOR ASSUMPTION IN ... - MIT Economics, accessed April 18, 2026, [https://economics.mit.edu/sites/default/files/publications/morris-thecommonpriorassumptionineconomictheory.pdf](https://economics.mit.edu/sites/default/files/publications/morris-thecommonpriorassumptionineconomictheory.pdf)  
70. Epistemic Conditions for Bayesian Equilibrium - Maastricht University, accessed April 18, 2026, [https://cris.maastrichtuniversity.nl/en/publications/epistemic-conditions-for-bayesian-equilibrium/](https://cris.maastrichtuniversity.nl/en/publications/epistemic-conditions-for-bayesian-equilibrium/)  
71. The Robustness of Equilibria to Incomplete Information - Atsushi Kajii; Stephen Morris - MIT Economics, accessed April 18, 2026, [https://economics.mit.edu/sites/default/files/publications/morris-therobustnessofequilibriatoincompleteinform.pdf](https://economics.mit.edu/sites/default/files/publications/morris-therobustnessofequilibriatoincompleteinform.pdf)  
72. Agreeing to Disagree - Robert J. Aumann, accessed April 18, 2026, [https://pages.ucsd.edu/~aronatas/project/academic/aumann%20agree%20to%20disagree.pdf](https://pages.ucsd.edu/~aronatas/project/academic/aumann%20agree%20to%20disagree.pdf)  
73. Verbalized Bayesian Persuasion - arXiv, accessed April 18, 2026, [https://arxiv.org/html/2502.01587v1](https://arxiv.org/html/2502.01587v1)  
74. Overview of Quantitative Courses for 2025-2026 - UChicago Voices, accessed April 18, 2026, [https://voices.uchicago.edu/qrmeth/courses/](https://voices.uchicago.edu/qrmeth/courses/)  
75. On the Notion of Perfect Bayesian Equilibrium, accessed April 18, 2026, [http://eio.usc.es/pub/julio/papers/16._On_the_notion_of_perfect_Bayesian_Equilibrium_web.pdf](http://eio.usc.es/pub/julio/papers/16._On_the_notion_of_perfect_Bayesian_Equilibrium_web.pdf)  
76. Persuasive Selection in Signaling Games - arXiv, accessed April 18, 2026, [https://arxiv.org/pdf/2511.00718](https://arxiv.org/pdf/2511.00718)  
77. Coordination and learning in dynamic global games: experimental evidence, accessed April 18, 2026, [https://www.cambridge.org/core/journals/experimental-economics/article/coordination-and-learning-in-dynamic-global-games-experimental-evidence/0873176ACB86303AC17EA3FFBB1A61E3](https://www.cambridge.org/core/journals/experimental-economics/article/coordination-and-learning-in-dynamic-global-games-experimental-evidence/0873176ACB86303AC17EA3FFBB1A61E3)  
78. (PDF) The Electronic Mail Game: Strategic Behavior Under" Almost Common Knowledge", accessed April 18, 2026, [https://www.researchgate.net/publication/4719889_The_Electronic_Mail_Game_Strategic_Behavior_Under_Almost_Common_Knowledge](https://www.researchgate.net/publication/4719889_The_Electronic_Mail_Game_Strategic_Behavior_Under_Almost_Common_Knowledge)  
79. Sorting Out the Differences Between Signaling and Screening Models - IDEAS/RePEc, accessed April 18, 2026, [https://ideas.repec.org/p/nbr/nberte/0093.html](https://ideas.repec.org/p/nbr/nberte/0093.html)

---