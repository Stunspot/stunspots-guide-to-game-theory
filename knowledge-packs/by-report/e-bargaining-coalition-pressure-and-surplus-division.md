# E. Bargaining, Coalition Pressure, and Surplus Division — Strategic Settlement Under Conflict and Mutual Dependence

The movement from individual optimization to strategic interdependence finds its most acute expression in the bargaining problem. In the foundational geometry of strategic conflict, as established in the opening of this canon, interaction begins where the Robinson Crusoe model of isolated maximization fails: at the point where an agent’s best possible outcome depends on the choices of others who are simultaneously attempting to optimize their own results.1 This relational reality is nowhere more visible than in the negotiation over a cooperative surplus. Bargaining is a strategic field defined by a fundamental duality: players are interdependent enough to create value through joint action but divided enough to engage in conflict over the distribution of that value.2

This report, the fifth in a 12-part canon on non-cooperative game theory and strategic systems analysis, serves as the definitive account of how the "cost of no deal" structures the terms of agreement. It explores the mechanisms by which settlement emerges, stalls, or collapses, focusing on how the division of surplus is conditioned by fallback positions, the temporal pressures of delay, and the complex externalities of coalition pressure. By establishing the rigorous link between the static axiomatic benchmarks of the 1950s and the sequential strategic models of the late twentieth century, this document provides the analytical infrastructure for understanding settlement in environments ranging from management-labor disputes to international policy coordination.3

## **The Ontology of the Bargaining Field: Conflict within Cooperation**

The "pure bargaining problem" stands at the opposite pole of economic phenomena from "perfect competition." In a perfectly competitive market, the strategic aspect of interaction is reduced to negligible proportions by the discipline of a market that allows agents to behave as solitary decision-makers.6 In contrast, pure bargaining is a state where the market plays no role other than to set the bounds of discussion, within which the final outcome is determined entirely by the strategic interaction of the participants.6 This interaction is governed by the recursive anticipation of moves, where incentives are never isolated but are best responses to the anticipated actions and beliefs of others.1

### **The Primitives of Settlement**

To model the emergence of settlement, the field identifies three necessary conditions that constitute a bargaining situation:

1. **Mutual Benefit**: There exists a set of feasible agreements that are preferred by all parties over the status quo of no agreement.2  
2. **Conflict of Interest**: Within that feasible set, there is no single agreement that is best for everyone; a gain for one player typically implies a smaller share for another.2  
3. **Mutual Veto Power**: No agreement can be imposed on any individual without their approval, meaning every player has the power to sink the deal by refusing to participate.2

In non-cooperative game theory, the central burden is to move from the "indeterminacy" of these conditions—the fact that many outcomes are possible—to a unique prediction of what will happen when rational agents interact.6 The resolution of this indeterminacy requires a precise taxonomy of the "disagreement point" and the "feasible set," which together define the "bargaining range" or the zone of possible agreement (ZOPA).5

| Feature | Parametric Decision Theory | Strategic Bargaining Theory |
| :---- | :---- | :---- |
| **Agent Focus** | Isolated individual optimizing against nature.1 | Interacting agents mutually determining a split.1 |
| **Recursive Reasoning** | Absent; the environment does not react to thoughts.1 | Central; players account for others' anticipation.1 |
| **Core Problem** | Choice under uncertainty or risk.1 | Choice under strategic interdependence.1 |
| **Example Situation** | A firm setting prices based on weather.1 | A firm and union dividing firm profits.2 |

## **The Axiomatic Regime: The Nash Bargaining Solution**

The first major stabilization of the bargaining problem was achieved by John Nash in 1950 through an "axiomatic" approach. This method abstracts away from the messy details of the bargaining process—the offers, counter-offers, and bluffs—and asks what properties a "reasonable" or "fair" settlement should possess.2 Nash conceptualized a bargaining problem as a pair (U, d), where U represents the set of possible payoff pairs that can be achieved through cooperation, and d represents the "disagreement point" or the payoffs the players receive if negotiation fails.2

### **The Four Pillars of Rational Settlement**

Nash proved that there is only one solution function that satisfies a specific set of four axioms. These axioms are not merely mathematical conveniences; they are theoretical commitments to how rationality behaves in a social context.2

1. **Pareto Efficiency**: The agreement must lie on the "frontier" of the feasible set. No surplus is wasted; the parties do not leave money on the table that both would prefer to have.2  
2. **Symmetry**: If the feasible set is symmetric and the disagreement point assigns equal values to both players, then the solution must also assign equal shares. This ensures that differences in outcomes are driven only by differences in fallback positions or preferences.2  
3. **Invariance to Equivalent Utility Representations**: The solution should not change if the utility functions are rescaled. This protects the theory from being sensitive to arbitrary units of measurement.2  
4. **Independence of Irrelevant Alternatives (IIA)**: If an agreement is chosen from a large set of options, and then some of the unchosen options are removed, the original agreement should still be the winner. This ensures that the settlement depends only on the relationship between the chosen outcome and the fallback position.2

The result of these axioms is the **Nash Bargaining Solution**, which is the unique pair of payoffs that maximizes the product of the players' gains over their disagreement points: (u1 - d1)(u2 - d2). This "Nash Product" serves as the foundational metric for most cooperative and many non-cooperative bargaining analyses. It implies that a player’s share of the surplus is directly tied to the strength of their disagreement position; the better your fallback, the higher your final share.9

### **The Nash Program: Bridging the Axiomatic and the Strategic**

While the axiomatic approach is elegant, it lacks a causal grammar. It does not explain how players, acting out of individual self-interest without an external arbitrator, would arrive at such a point. This led Nash to propose the "Nash Program": the attempt to model the bargaining process as a non-cooperative game whose equilibrium results in the Nash bargaining solution.5 In the Nash demand game—where players simultaneously name their requests—any split on the frontier can be a Nash equilibrium, leading to massive indeterminacy.3 To resolve this, the canon moved toward "strategic" models that explicitly account for timing, observability, and the cost of delay.

## **The Strategic Shift: Time, Patience, and the Rubinstein Model**

The modern theory of bargaining was transformed by Ariel Rubinstein’s 1982 paper, which introduced a non-cooperative framework of alternating offers over an infinite time horizon.12 This model addresses the "inefficiency of indeterminacy" in the Nash demand game by introducing a critical resource: time.13

### **The Mechanics of Alternating Offers**

In the Rubinstein protocol, two players negotiate over a "pie" of size 1. At time t=0, Player 1 makes a proposal (x, 1-x). Player 2 can either accept, ending the game, or reject. If Player 2 rejects, the game moves to t=1, where Player 2 makes a counter-proposal. This continues indefinitely until an agreement is reached.12

The defining feature of this interaction is that "delays are costly".13 This cost is represented by discount factors delta1, delta2 between 0 and 1, where the pie "shrinks" at each step.12 A player’s incentive to reach an agreement stems from the fact that a 50/50 split today is worth more than a 50/50 split tomorrow.13

Rubinstein proved that this game has a unique subgame perfect equilibrium (SPE). In this equilibrium, Player 1 makes a proposal that Player 2 accepts immediately. The split is determined by the relative patience of the parties.13 If the players are identical (delta1 = delta2 = delta), the share for the first mover is:

x1 = 1 / (1 + delta)

while the share for the responder is:

x2 = delta / (1 + delta)

### **The Vanishing First-Mover Advantage**

The Rubinstein model quantifies the "first-mover advantage" as a function of the discount factor.12 Because the first player to move can force the other to choose between a smaller share now and a potentially larger but discounted share later, the initiator extracts a premium for their position.12

However, as the players become infinitely patient or the time between offers approaches zero (delta approaches 1), the first-mover advantage disappears.2 The unique SPE converges to the (1/2, 1/2) split, which is exactly the result predicted by the axiomatic Nash solution.2 This convergence provides the "causal proof" for the Nash program: the fair, axiomatic split is the natural resting point for rational, strategic agents when the friction of time is minimized.2

| Parameter | Impact on Proposer's Share | Theoretical Consequence |
| :---- | :---- | :---- |
| **High delta (Patient)** | Share decreases toward 1/2.2 | Convergence to Nash Solution.15 |
| **Low delta (Impatient)** | Share increases toward 1.15 | Proposer exploits responder's desperation.18 |
| **Finite Horizon N** | Determined by who moves last.12 | Backward induction gives "Take-it-or-leave-it" power.12 |
| **Asymmetric delta1 > delta2** | Proposer extracts even higher rents.12 | Patience translates directly into bargaining power.13 |

## **The Structure of Leverage: Fallback Positions and the Outside Option Principle**

One of the most profound realizations in strategic bargaining is that the "cost of no deal" is not a monolithic concept. The field distinguishes between different types of fallback positions, each providing a different kind of leverage.9 Understanding the nuances of these positions—disagreement points, reservation values, and outside options—is essential for diagnosing why some settlements favor one party over another.

### **Disagreement Points vs. Outside Options**

A **Disagreement Point** (or inside option) is the payoff an agent receives while negotiations are temporarily stalled.9 In labor bargaining, this might be the strike fund payments for workers or the continued operation at reduced capacity for the firm.11 Inside options are "reversible" and do not terminate the relationship.11 In the Nash bargaining solution, an improvement in a player's inside option always increases their final share of the surplus—a phenomenon known as "splitting the difference".9

An **Outside Option** is an alternative that a bargainer can take only by permanently quitting the negotiation.9 For a seller of a house, a backup offer from a second buyer is an outside option; once taken, the deal with the first buyer is dead.11 Unlike inside options, outside options are mutually exclusive with the current agreement.9

### **The Outside Option Principle (OOP)**

The **Outside Option Principle** (OOP) is a classical result that contradicts the cooperative "split-the-difference" approach.9 It establishes that an outside option affects the equilibrium strategies of a game only if the payoff from that option is superior to the share the player would have received in a standard negotiation without any outside options.9

1. **Non-Binding Options**: If a player's outside option is less than their "Rubinstein share" (the share they get from patience alone), the outside option is strategically irrelevant. The player cannot use it to gain leverage because the threat to walk away is not credible—they would be "dealing themselves out" of a better arrangement.20  
2. **Binding Options**: If the outside option is greater than the standard equilibrium share, it becomes a "floor." The player receives exactly the value of their outside option, and their opponent takes the remainder of the pie.11

This principle explains the "deal-me-out" behavior observed in laboratory settings. In many legal and economic contexts, threats to perform inefficiently or walk away do not allow a party to extract a "split" of the joint surplus; they merely allow that party to secure their best alternative elsewhere while the other party captures the entire remaining surplus created by the agreement.11

| Concept | Status in Negotiation | Leveraged Result |
| :---- | :---- | :---- |
| **Inside Option** | Active/Ongoing.11 | "Split-the-Difference".9 |
| **Outside Option** | Terminal/Exit.9 | "Outside Option Principle" (The Floor).9 |
| **Threat Point** | Guaranteed autarky.10 | Baseline for individual rationality.5 |
| **Reservation Value** | Hidden limit.22 | Target of informational screening.19 |

## **Coalition Pressure and Two-Level Games: The "Janus-Faced" Negotiator**

Strategic settlement is frequently complicated by the presence of a "coalition principal"—a domestic constituency or a set of internal stakeholders whose approval is required for a deal to be finalized.23 Robert Putnam’s theory of **Two-Level Games** (1988) provides the canonical framework for analyzing this pressure.4

### **The Two Tables of Negotiation**

In a two-level game, a "chief negotiator" sits at two tables simultaneously.23

* **Level I (International/Inter-group)**: The negotiator bargains with their foreign or external counterpart to reach a tentative agreement.4  
* **Level II (National/Intra-group)**: The negotiator must satisfy domestic interest groups, legislatures, and public opinion to "ratify" the agreement.4

The central strategic dilemma is that moves that are rational at the Level I table (e.g., conceding territory for peace) may be "impolitic" or "unratifiable" at the Level II table.23 The negotiator is "Janus-faced," absorbing the concerns of societal actors while attempting to maximize domestic concerns and minimize the impact of external concessions.4

### **Win-Set Dynamics and the Logic of Ratification**

A **Win-Set** is defined as the set of all possible Level I agreements that would gain the necessary majority among Level II constituents.4

* **Overlap Requirement**: An international agreement is only possible if the win-sets of all participating parties overlap. If there is no overlap, the negotiations result in a "deadlock".4  
* **Size Determinants**: The size of a win-set is influenced by domestic power distributions (hawks vs. doves), political institutions (e.g., a 2/3rds vote requirement for treaties), and the strategies of the chief negotiator.23

### **The Paradox of Weakness (The Schelling Conjecture)**

The most counter-intuitive insight of two-level bargaining is that **domestic constraints can be a source of international strength**.4 This "Paradox of Weakness" suggests that a negotiator with a smaller domestic win-set can extract greater concessions from their counterpart.23

A leader who can credibly claim, "I’d like to accept your proposal, but I could never get it ratified at home," forces the other side to move closer to the leader's preferred position to ensure the deal doesn't collapse.23 Conversely, a "strong" state with total autonomy from domestic pressure (a large win-set) occupies a weaker relative bargaining position because it cannot use internal constraints as a reason to reject disadvantageous terms.23

| Actor Type | Win-Set Size | International Bargaining Leverage | Risk Profile |
| :---- | :---- | :---- | :---- |
| **Democracy (Hard Ratification)** | Small.23 | High (Tied-hands Advantage).27 | High risk of involuntary defection.23 |
| **Autocracy (Soft Ratification)** | Large.27 | Low (Flexible but Vulnerable).23 | Higher likelihood of agreement.4 |
| **Vulnerable Leader** | Small.23 | High (Leveraging weakness).23 | Risk of "upsetting the board".26 |
| **Stable Leader** | Large.23 | Low (Expected to concede).30 | "Pushed around" by counterparts.23 |

## **Multidimensional Bargaining: Issue Linkage and Surplus Expansion**

In real-world systems, parties rarely bargain over a single "pie." They negotiate over multiple issues (e.g., trade, environment, and security) where their valuations are often asymmetric.31 This multidimensionality creates opportunities for "log-rolling"—exchanging concessions on issues of low priority to gain ground on issues of high priority.33

### **Issue Linkage vs. Ringfencing**

**Issue Linkage** involves the simultaneous discussion of two or more issues for joint settlement.35 **Ringfencing** refers to the practice of dealing with issues separately through individual agreements.37

* **Surplus Expansion**: Linkage can support cooperation by allowing countries to trade gains across different policy areas. For example, a country might accept a loss on an environmental policy in exchange for a substantial gain in market access.34  
* **Enforcement and Participation**: Linking a high-stakes issue (trade) to a low-compliance issue (environmental standards) can "borrow" the enforcement power of the former to stabilize the latter. If you violate the environmental deal, you lose the trade benefits.33  
* **Complexity-Flexibility Dilemma**: While multiple issues provide flexibility for win-win outcomes, they increase the "structural complexity" of the negotiation.39 Negotiators may use **Nested Bracketing**—organizing issues into subordinate subsets to manage complexity before integrating them into a superordinate structure.39

### **The Impact of Common Shocks**

Recent analysis highlights that the preference for linkage or ringfencing depends on the correlation of exogenous "shocks".37

1. **Ringfencing for Common Shocks**: If countries are prone to shared negative events (e.g., a global recession), ringfencing is superior. It allows them to efficiently terminate cooperation on the "bad" issue while maintaining it on others. Linkage would force them to either suffer through the bad outcome or abandon the entire relationship.37  
2. **Linkage for Non-Aligned Realizations**: When countries face different risks (one has a trade shock, the other an environmental shock), linkage acts as an insurance mechanism. The collective gain allows them to stay in the agreement despite individual losses.37

| Strategy | Definition | Strategic Objective | Risk |
| :---- | :---- | :---- | :---- |
| **Issue Linkage** | Comprehensive agreements spanning multiple domains.37 | Trading concessions across priorities.34 | "Contagion" of failure across issues.37 |
| **Ringfencing** | Separate agreements for each issue.37 | Preventing total collapse from specific shocks.37 | Missed opportunities for "win-win" trades.37 |
| **Issue Tie-In** | Exogenous constraint requiring multidimensional agreement.34 | Limiting feasible objections to cooperation.34 | Removing counter-objections that support trades.34 |
| **Side Payments** | Transfers used to satisfy participation constraints.35 | Facilitating cooperation across asymmetric gains.35 | Requires credible binding mechanisms.35 |

## **The Pathologies of Bargaining: Failure and Strategic Delay**

The central puzzle of bargaining theory is the "inefficiency of war" or conflict: why do rational actors suffer from strikes, lawsuits, or military engagements when a negotiated settlement always exists that both would prefer over the costs of fighting?40 Non-cooperative theory identifies structural features that prevent agents from reaching the efficient frontier.

### **Incomplete Information and the Incentive to Misrepresent**

The leading explanation for bargaining failure is **Asymmetric Information**.7

* **Posturing and Signaling**: Bargainers have private information about their reservation values, capabilities, or resolve.40 To extract a better share, a bargainer has an incentive to "misrepresent" their strength, claiming they can endure more delay than they actually can.7  
* **Strategic Delay as a Screen**: In models like Admati and Perry (1987), delay is an endogenous strategic variable used to signal strength.44 A "tough" player can signal their type by "disappearing" from communication or refusing an offer for a long period.44 This delay does not vanish even as the time between offers becomes small, as the delay is the only way to prove resolve.44  
* **Response Times (RT)**: Behavioral data indicates that RT reveals private information. Both buyers and sellers take hours longer to accept "bad" offers than to reject "good" ones.46 Interestingly, while slow rejections signal a high valuation, they often discourage buyers, who interpret the delay as a lack of interest rather than a strategic stance.46

### **The Commitment Problem: Power Shifts and Preemption**

A second structural cause of failure is the **Commitment Problem**.40 This occurs when actors cannot credibly commit to abiding by an agreement in the future, even if it is mutually beneficial today.

* **Power Transitions**: Large and rapid shifts in the distribution of power make agreements unstable. A rising power cannot credibly commit not to use its future strength to demand better terms.40 This can force a declining power to preemptively attack (preventive war) rather than accept a settlement that will inevitably be overturned.40  
* **Indivisibility**: Some issues—such as holy sites or political sovereignty—are "indivisible." If the parties cannot find a way to split the value (perhaps through side payments or linkage), no negotiated settlement is possible.40

### **The Holdout Problem in Multilateral Contexts**

The **Holdout Problem** is a specific bargaining pathology that arises in "complementary exchanges" involving multiple independent parties.48

* **Mechanism**: In land assembly for urban renewal, a project’s value V is realized only if all N parcels are acquired. Each owner knows that their parcel is essential, giving them "monopoly" leverage.48  
* **Strategic Stance**: Owners strategically delay agreement to extract a larger share of the surplus.48 This "holdout externality" imposes costs on the other owners and the developer, potentially shrinking the total pie.48  
* **Systemic Consequences**: The holdout problem frequently leads to inefficiently low investment or project abandonment. This is cited as a primary justification for "Eminent Domain"—the state’s power to expropriate property with just compensation to prevent individual holdouts from destroying collective gains.48

| Pathology | Trigger | Resulting Inefficiency | Diagnostic Tool |
| :---- | :---- | :---- | :---- |
| **Strategic Delay** | Information asymmetry; signaling.45 | Costly time waste; pie shrinking.44 | Signaling games; RT analysis.19 |
| **Commitment Problem** | Power transitions; rising powers.40 | Preventive war; preemptive attack.40 | Bargaining model of war.41 |
| **Holdout Pathology** | Complementary multi-party assets.48 | Stalled development; urban sprawl.49 | Multilateral bargaining games.48 |
| **Hold-up Problem** | Ex-post exploitation of ex-ante investment.48 | Inefficiently low initial investment.48 | Transaction cost economics.48 |

## **The Procedure of Settlement: Agenda Control and Procedural Leverage**

Bargaining power is not just a product of patience or fallback positions; it is also a function of the **Bargaining Protocol**—the rules governing who speaks when and what is discussed in what order.15

### **The Power of the Agenda**

In multi-issue negotiations, the "agenda" determines the relationship between the issues and the final outcome.31

* **Sequential vs. Simultaneous**: When issues are negotiated sequentially, the outcome of the first issue affects the "threat point" and "impatience rate" for the second issue. For example, if shares of a first "cake" are only distributed after the second "cake" is divided, a player's eagerness for the first influences their stance on the second.31  
* **Optimal Agenda Selection**: Players with conflicting evaluations of issues prefer different agendas. A player generally prefers an agenda that discusses their least important issue first. This allows them to use that issue as a "signal" or a "side payment" to secure their priority on more important issues later in the sequence.31

### **First-Mover Advantage vs. Reactivity**

As established in the Rubinstein model, the party moving first sets the "anchor" or reference point for the negotiation.13 In a one-buyer, multiple-supplier environment, the buyer can determine an optimal sequence of negotiations to maximize their expected gain, playing suppliers off one another by leveraging their respective outside options.50 This "negotiation sequencing" is a vital tool for supply chain coordination and institutional design.50

## **Behavioral and Cognitive Limits: The Reality of Strategic Settlement**

While non-cooperative theory provides rigorous benchmarks like Subgame Perfect Equilibrium (SPE), laboratory evidence often shows that human subjects focus on "fairness" or "focal points" rather than pure backward induction.3

### **Fairness Norms and Evolutionary Stability**

Experimental studies frequently find that participants reach a 50/50 split even when the strategic environment (e.g., asymmetric outside options) suggests they shouldn't.3

* **Evolutionary Justice**: Kenneth Binmore uses evolutionary game theory to explain how 50/50 splits emerge as human attitudes toward "distributive justice." Such splits may be "focal points" that simplify the cognitive burden of coordination.3  
* **Battle of Norms**: Bargaining can reduce to a "battle between rival fairness norms." A subject with a high outside option may argue for "splitting the difference" (cooperative theory), while the subject with the lower option argues for "deal-me-out" (strategic theory).20

### **Cognitive Hierarchies and Sunk Costs**

The ability to "see" the future (backward induction) is bounded by cognitive depth.

* **Limited Backward Induction**: In games like the "Centipede Game," players rarely reason to the very end of the tree, instead focusing on "close-by nodes".51 This "Limited Backward Induction" allows for cooperation to persist even in finitely repeated games where SPE predicts immediate defection.51  
* **The Sunk Cost Fallacy as a Commitment Device**: Evolutionary logic suggests that "honoring sunk costs"—investments that cannot be recovered—may be a hard-wired commitment device.51 By becoming "irrationally" aggressive in defending outputs they have already worked for, producers signal resolve, deterring others from attempting to "hold them up" or steal their gains.51

## **Conclusion: The Architecture of Agreement**

The division of cooperative surplus is the central governing problem of strategic systems. This report has demonstrated that settlement is not a product of spontaneous goodwill, but of a rigorous architecture of constraints and incentives.

Strategic settlement is structured by:

1. **The Shadow of Time**: Impatience acts as a friction that forces the responder to accept less than an equal split, establishing the first-mover advantage.12  
2. **The Credibility of Exit**: Fallback positions only matter when they are "binding." Small improvements in alternatives are strategically invisible, while large ones act as a hard floor for the negotiation.9  
3. **The Janus-Faced Negotiator**: Coalition pressure transforms bargaining into a two-level game, where domestic "weakness" becomes international "strength" through the manipulation of win-sets.4  
4. **The Logic of Linkage**: Multidimensionality expands the pie but risks contagion, requiring careful management of issue-dependent shocks.37  
5. **The Price of Certainty**: Bargaining failure, delay, and conflict are the "costs of information." They are the inefficient mechanisms by which players reveal private information, prove commitment, and overcome the holdout problem.40

For the strategist, understanding this "geometry of settlement" is the prerequisite for institutional design. Whether in climate policy, labor contracts, or military deterrence, the goal is to architect the environment—through rules, signals, and commitment devices—so that the unique Nash equilibrium aligns with the Pareto frontier. Strategic systems analysis thus moves from merely observing conflict to engineering the conditions under which cooperation becomes the dominant strategy.1

This document completes the trunk layer of the bargaining canon. Subsequent reports will deepen these insights into the "Folk Theorem" of repeated interaction and the formal blueprints of Mechanism Design, where the strategist becomes the game designer, crafting the rules that ensure the "cost of no deal" remains high enough to sustain the stability of the deal.1

#### **Works cited**

1. Game Theory 1 - The Geometry of Strategic Conflict — An Ontology of Incentives, Interdependence, and Equilibrium  
2. 6.254 : Game Theory with Engineering Applications Lecture 14: Nash Bargaining Solution - MIT OpenCourseWare, accessed April 18, 2026, [https://ocw.mit.edu/courses/6-254-game-theory-with-engineering-applications-spring-2010/837a6dbd4edfe215c710dd0cf0649021_MIT6_254S10_lec14.pdf](https://ocw.mit.edu/courses/6-254-game-theory-with-engineering-applications-spring-2010/837a6dbd4edfe215c710dd0cf0649021_MIT6_254S10_lec14.pdf)  
3. Cooperative bargaining - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Cooperative_bargaining](https://en.wikipedia.org/wiki/Cooperative_bargaining)  
4. Two-level game theory - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Two-level_game_theory](https://en.wikipedia.org/wiki/Two-level_game_theory)  
5. The Two Person Bargaining Problem - Game Theory - Indian Institute of Science, accessed April 18, 2026, [https://gtl.csa.iisc.ac.in/gametheory/ln/web-cp2-bargaining.pdf](https://gtl.csa.iisc.ac.in/gametheory/ln/web-cp2-bargaining.pdf)  
6. Game-theoretic models of bargaining, accessed April 18, 2026, [https://library.fa.ru/files/Roth1.pdf](https://library.fa.ru/files/Roth1.pdf)  
7. Bargaining 101 (#22): Uncertainty and Bargaining Failure - YouTube, accessed April 18, 2026, [https://www.youtube.com/watch?v=Ps7ogtq_izQ](https://www.youtube.com/watch?v=Ps7ogtq_izQ)  
8. ADVANCES IN NEGOTIATION THEORY: BARGAINING, COALITIONS, AND FAIRNESS - World Bank Document, accessed April 18, 2026, [https://openknowledge.worldbank.org/server/api/core/bitstreams/4c527766-34ab-5035-b997-1d77f4f76198/content](https://openknowledge.worldbank.org/server/api/core/bitstreams/4c527766-34ab-5035-b997-1d77f4f76198/content)  
9. Strategic Negotiations and Outside Options, accessed April 18, 2026, [https://www.uv.es/~acunat/surveyengl.PDF](https://www.uv.es/~acunat/surveyengl.PDF)  
10. ECON 522 - SECTION 2-THREAT POINTS, COASE THEOREM AND TRANSAC- TION COSTS, accessed April 18, 2026, [https://www.ssc.wisc.edu/~dquint/econ522%20fall%202011/522section2.pdf](https://www.ssc.wisc.edu/~dquint/econ522%20fall%202011/522section2.pdf)  
11. On the Misuse of the Nash Bargaining Solution in Law and Economics - bepress Legal Repository, accessed April 18, 2026, [https://law.bepress.com/cgi/viewcontent.cgi?article=1805&context=expresso](https://law.bepress.com/cgi/viewcontent.cgi?article=1805&context=expresso)  
12. Bargaining and Repeated Games, accessed April 18, 2026, [https://web.stanford.edu/~jdlevin/Econ%20203/RepeatedGames.pdf](https://web.stanford.edu/~jdlevin/Econ%20203/RepeatedGames.pdf)  
13. Rubinstein bargaining model - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Rubinstein_bargaining_model](https://en.wikipedia.org/wiki/Rubinstein_bargaining_model)  
14. The Nash bargaining solution in economic ... - Ariel Rubinstein, accessed April 18, 2026, [https://arielrubinstein.tau.ac.il/papers/24.pdf](https://arielrubinstein.tau.ac.il/papers/24.pdf)  
15. G5212: Game Theory Mark Dean Spring 2017, accessed April 18, 2026, [http://www.columbia.edu/~md3405/GT_Game_8_17.pdf](http://www.columbia.edu/~md3405/GT_Game_8_17.pdf)  
16. Introduction to Game Theory Lecture 6: Bargaining - Sites@Duke Express, accessed April 18, 2026, [https://sites.duke.edu/collardwexler/files/2015/01/Lecture-6-Bargaining.pdf](https://sites.duke.edu/collardwexler/files/2015/01/Lecture-6-Bargaining.pdf)  
17. Sequential Bargaining: Game Theory & Examples | Vaia, accessed April 18, 2026, [https://www.vaia.com/en-us/explanations/business-studies/managerial-economics/sequential-bargaining/](https://www.vaia.com/en-us/explanations/business-studies/managerial-economics/sequential-bargaining/)  
18. Game-theoretic models of bargaining - eClass, accessed April 18, 2026, [https://eclass.aueb.gr/modules/document/file.php/DEOS428/Lecture%20handouts/08_bargaining_handout.pdf](https://eclass.aueb.gr/modules/document/file.php/DEOS428/Lecture%20handouts/08_bargaining_handout.pdf)  
19. Game Theory, Lecture 12: Bargaining with Incomplete Information or Reputation - MIT OpenCourseWare, accessed April 18, 2026, [https://ocw.mit.edu/courses/14.126-game-theory-spring-2024/mit14_126_s24_lecture_12_bargaining.pdf](https://ocw.mit.edu/courses/14.126-game-theory-spring-2024/mit14_126_s24_lecture_12_bargaining.pdf)  
20. 5 Outside Options - MIT Press Direct, accessed April 18, 2026, [https://direct.mit.edu/books/edited-volume/chapter-pdf/2316522/c011002_9780262268554.pdf](https://direct.mit.edu/books/edited-volume/chapter-pdf/2316522/c011002_9780262268554.pdf)  
21. (PDF) An Outside Option Experiment - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/24091213_An_Outside_Option_Experiment](https://www.researchgate.net/publication/24091213_An_Outside_Option_Experiment)  
22. Reservation Point in Negotiation: Reach Negotiated Agreements by Asking the Right Questions - PON, accessed April 18, 2026, [https://www.pon.harvard.edu/daily/negotiation-skills-daily/resolve-conflict-by-asking-the-right-questions/](https://www.pon.harvard.edu/daily/negotiation-skills-daily/resolve-conflict-by-asking-the-right-questions/)  
23. 2 level game theory (Putnam) - Guillaume Nicaise, accessed April 18, 2026, [http://www.guillaumenicaise.com/wp-content/uploads/2014/09/resum%C3%A9-du-cours_techniques-de-negociation.pdf](http://www.guillaumenicaise.com/wp-content/uploads/2014/09/resum%C3%A9-du-cours_techniques-de-negociation.pdf)  
24. (PDF) Two-Level Games in Foreign Policy Analysis - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/315698803_Two-Level_Games_in_Foreign_Policy_Analysis](https://www.researchgate.net/publication/315698803_Two-Level_Games_in_Foreign_Policy_Analysis)  
25. Integrating International and Domestic Theories of International Bargaining - Princeton University, accessed April 18, 2026, [https://www.princeton.edu/~amoravcs/library/double.pdf](https://www.princeton.edu/~amoravcs/library/double.pdf)  
26. Two- Level Role Theory and EU Migration - OAPEN Library, accessed April 18, 2026, [https://library.oapen.org/bitstream/handle/20.500.12657/95741/1/9781003582656_10.4324_9781003582656-4.pdf](https://library.oapen.org/bitstream/handle/20.500.12657/95741/1/9781003582656_10.4324_9781003582656-4.pdf)  
27. Two-Level-Games in Seattle and Doha: Domestic Influences on WTO Negotiations - GRIN, accessed April 18, 2026, [https://www.grin.com/document/208460](https://www.grin.com/document/208460)  
28. (PDF) Explanatory Power of the Two level Game Approach - Academia.edu, accessed April 18, 2026, [https://www.academia.edu/36599672/Explanatory_Power_of_the_Two_level_Game_Approach](https://www.academia.edu/36599672/Explanatory_Power_of_the_Two_level_Game_Approach)  
29. The Two-Level Game of Transnational Networks: The Case of the Access to Medicines Campaign, accessed April 18, 2026, [https://www.chaire-epi.ulaval.ca/sites/chaire-epi.ulaval.ca/files/publications/morin_two_level_game_of_networks.pdf](https://www.chaire-epi.ulaval.ca/sites/chaire-epi.ulaval.ca/files/publications/morin_two_level_game_of_networks.pdf)  
30. Two-level games and trade cooperation: What do we now know? - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/263327360_Two-level_games_and_trade_cooperation_What_do_we_now_know](https://www.researchgate.net/publication/263327360_Two-level_games_and_trade_cooperation_What_do_we_now_know)  
31. Discussion Paper No. 689 - THE IMPORTANCE OF THE AGENDA IN BARGAINING - Kellogg School of Management, accessed April 18, 2026, [https://www.kellogg.northwestern.edu/research/math/papers/689.pdf](https://www.kellogg.northwestern.edu/research/math/papers/689.pdf)  
32. Delays and Partial Agreements in Multi-Issue Bargaining, accessed April 18, 2026, [https://people.bu.edu/jortner/static/bargaining.pdf](https://people.bu.edu/jortner/static/bargaining.pdf)  
33. Issue Linkage∗ - Yale Department of Economics, accessed April 18, 2026, [https://economics.yale.edu/sites/default/files/2022-10/IssueLinkageDraft_041216.pdf](https://economics.yale.edu/sites/default/files/2022-10/IssueLinkageDraft_041216.pdf)  
34. Issue Linkage and Issue Tie-in in Multilateral Negotiations, accessed April 18, 2026, [https://feem-media.s3.eu-central-1.amazonaws.com/wp-content/uploads/NDL2000-057.pdf](https://feem-media.s3.eu-central-1.amazonaws.com/wp-content/uploads/NDL2000-057.pdf)  
35. Issue linkage and international cooperation: An empirical investigation - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/258129407_Issue_linkage_and_international_cooperation_An_empirical_investigation](https://www.researchgate.net/publication/258129407_Issue_linkage_and_international_cooperation_An_empirical_investigation)  
36. Issue linkage and international cooperation: An empirical investigation - IDEAS/RePEc, accessed April 18, 2026, [https://ideas.repec.org/a/sae/compsc/v30y2013i3p286-303.html](https://ideas.repec.org/a/sae/compsc/v30y2013i3p286-303.html)  
37. Economics Bulletin - Volume 45, Issue 1, accessed April 18, 2026, [http://www.accessecon.com/Pubs/EB/2025/Volume45/EB-25-V45-I1-P27.pdf](http://www.accessecon.com/Pubs/EB/2025/Volume45/EB-25-V45-I1-P27.pdf)  
38. Issue Linkage and Issue Tie-In in Multilateral Negotiations | Request PDF - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/222299860_Issue_Linkage_and_Issue_Tie-In_in_Multilateral_Negotiations](https://www.researchgate.net/publication/222299860_Issue_Linkage_and_Issue_Tie-In_in_Multilateral_Negotiations)  
39. (PDF) Resolving the Complexity–Flexibility Dilemma in Multi-Issue Negotiations: Nested Bracketing as a Strategy to Enhance Negotiation Outcomes - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/398456764_Resolving_the_complexity-flexibility_dilemma_in_multi-issue_negotiations_Nested_bracketing_as_a_strategy_to_enhance_negotiation_outcomes](https://www.researchgate.net/publication/398456764_Resolving_the_complexity-flexibility_dilemma_in_multi-issue_negotiations_Nested_bracketing_as_a_strategy_to_enhance_negotiation_outcomes)  
40. Bargaining model of war - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Bargaining_model_of_war](https://en.wikipedia.org/wiki/Bargaining_model_of_war)  
41. War as a Failure of Bargaining: A Paradigm Shift in International Relations, accessed April 18, 2026, [https://policycommons.net/artifacts/19494813/paradigm-shift/20395348/](https://policycommons.net/artifacts/19494813/paradigm-shift/20395348/)  
42. Chapter ??? Commitment Problems and Shifting Power as a Cause of Conflict Robert Powell Decades ahead of his time, Thomas Schell, accessed April 18, 2026, [https://sites.socsci.uci.edu/~mrgarfin/OUP/papers/Powell.pdf](https://sites.socsci.uci.edu/~mrgarfin/OUP/papers/Powell.pdf)  
43. 7.4: Conflict | AI Safety, Ethics, and Society Textbook, accessed April 18, 2026, [https://www.aisafetybook.com/textbook/conflict](https://www.aisafetybook.com/textbook/conflict)  
44. Strategic Delay in Bargaining - kyle woodward, accessed April 18, 2026, [https://kylewoodward.com/blog-data/pdfs/references/admati+perry-the-review-of-economic-studies-1987A.pdf](https://kylewoodward.com/blog-data/pdfs/references/admati+perry-the-review-of-economic-studies-1987A.pdf)  
45. Strategic Delay in Bargaining | Stanford Graduate School of Business, accessed April 18, 2026, [https://www.gsb.stanford.edu/faculty-research/publications/strategic-delay-bargaining](https://www.gsb.stanford.edu/faculty-research/publications/strategic-delay-bargaining)  
46. Deliberation during online bargaining reveals strategic information - PubMed, accessed April 18, 2026, [https://pubmed.ncbi.nlm.nih.gov/39937849/](https://pubmed.ncbi.nlm.nih.gov/39937849/)  
47. Credibility and Commitment in Crisis Bargaining - University of Rochester, accessed April 18, 2026, [https://www.rochester.edu/college/faculty/markfey/papers/commitmentR3Merg.pdf](https://www.rochester.edu/college/faculty/markfey/papers/commitmentR3Merg.pdf)  
48. An Experimental Study of the Holdout Problem in a Multilateral ..., accessed April 18, 2026, [https://cupola.gettysburg.edu/context/econfac/article/1009/viewcontent/An_Experimental_Study_of_the_Holdout_Problem_in_a_Multilateral_Bargaining_Game.pdf](https://cupola.gettysburg.edu/context/econfac/article/1009/viewcontent/An_Experimental_Study_of_the_Holdout_Problem_in_a_Multilateral_Bargaining_Game.pdf)  
49. An Experimental Study of the Holdout Problem in a Multilateral Bargaining Game, accessed April 18, 2026, [https://ideas.repec.org/p/usn/usnawp/21.html](https://ideas.repec.org/p/usn/usnawp/21.html)  
50. A Bargaining Game for Supply Chain Contracting - P.C. Rossin College of Engineering & Applied Science - Lehigh University, accessed April 18, 2026, [https://engineering.lehigh.edu/sites/engineering.lehigh.edu/files/_DEPARTMENTS/ise/pdf/tech-papers/01/01t_002.pdf](https://engineering.lehigh.edu/sites/engineering.lehigh.edu/files/_DEPARTMENTS/ise/pdf/tech-papers/01/01t_002.pdf)  
51. Game Theory 4 - Sequential Strategy and Dynamic Commitment — Timing, Credibility, and Subgame Structure

---