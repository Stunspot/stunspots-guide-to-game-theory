# D. Sequential Strategy and Dynamic Commitment — Timing, Credibility, and Subgame Structure

The geometry of strategic conflict is transformed the moment interaction is no longer viewed as a static collision of incentives but as a cinematic progression through time. In the foundational layers of this canon, strategic interdependence was defined by the recursive anticipation of moves in a simultaneous field.1 However, the introduction of sequence—the realization that players move at different points on a temporal axis and can observe the actions of their predecessors—fundamentally redefines the nature of strategic power.2 In a sequential world, time is not a neutral backdrop; it is a critical resource. Commitment is not merely a statement of intent; it is a weaponized architectural intervention.3 Flexibility is no longer an unalloyed virtue but a costly tradeoff against the power of resolve.5 This report, the fourth in a 12-part canon, serves as the definitive account of how time changes power, shifting the analytical focus from the static alignment of incentives to the dynamic ability to shape the future game before it actually arrives.6

## **The Ontology of the Sequential Shift**

The transition from simultaneous interaction to sequential interaction represents a phase shift in strategic logic. In a simultaneous-move game, the primary burden of the agent is to stabilize expectations in an informational vacuum.1 Once sequence is introduced, the game is governed by a time axis, where later movers can condition their behavior on the observable commitments of earlier movers.2 This turn-based structure, represented formally through the extensive-form game tree, makes the "geometry of contingency" visible.8

### **Inherited Primitives and the Temporal Camera Angle**

To maintain modular consistency within this canon, we inherit the core primitives of players, actions, and utilities established in the first report.1 A player remains an autonomous unit of agency, but in the sequential register, their "strategy" becomes a comprehensive "program" for every possible information set they might encounter across the timeline.1 The extensive-form representation functions as a "cinematic sequence," highlighting the order of play and the flow of information.8

| Representational Feature | Normal Form (Matrix) | Extensive Form (Tree) |
| :---- | :---- | :---- |
| **Primary Visual** | Matrix (Payoff Table) 8 | Tree (Nodes and Edges) 8 |
| **Temporal Focus** | Simultaneous/Collapsed 2 | Sequential/Temporal Sequence 2 |
| **Information Unit** | Strategic Profile 1 | Information Set 8 |
| **Strategic Burden** | Finding fixed points (Nash) 1 | Identifying credible threats 9 |
| **Loss of Detail** | Erases timing/observability 8 | Becomes unwieldy for large sets 8 |

The most significant "controlled loss" in the simultaneous matrix is the distinction between a credible commitment and an idle bluff.8 By collapsing the timeline, the matrix treats a threat made before the game as equivalent to an action taken during the game. The extensive form preserves this distinction, allowing the analyst to apply "sequential rationality"—the demand that a player’s behavior be optimal at every decision point, given what they know and what they expect others to do in the future.10

### **The Information Set as a Boundary of Hindsight**

In sequential analysis, the "information set" is the formal unit that captures observability.8 It partitions decision nodes into collections that are indistinguishable to the player at the moment of choice.8 If a player moves without knowing exactly what the predecessor did, they are modeled within a non-singleton information set. This formalization prevents the error of assuming that just because time has passed, information has necessarily been revealed.8 Power in a sequential game often flows from the manipulation of these information sets—either through "signaling" (the informed player moving first to reveal their type) or "screening" (the uninformed player moving first to force the other to reveal their type).10

## **The Grammar of Sequential Rationality**

The fundamental solution concept for simultaneous games is the Nash equilibrium, a state of mutual strategic fit where expectations are consistent.1 However, in sequential games, the Nash equilibrium concept is often too weak, as it can be sustained by "incredible threats"—actions that a rational player would never actually carry out if the relevant subgame were reached.11 To resolve this, Reinhard Selten (1965) introduced the concept of Subgame Perfect Equilibrium (SPE), which requires that strategies constitute a Nash equilibrium in every possible subgame of the original game.13

### **Subgame Perfection and the Logic of Backward Induction**

A subgame is a portion of a game tree that starts at a single-vertex information set and is fully self-contained.14 To find a subgame perfect equilibrium in a finite game of perfect information, the analyst utilizes "backward induction".16 This process begins at the terminal nodes of the tree, identifying the optimal action for the last player to move in each final subgame. These optimal payoffs are then "rolled back" to the previous decision node, treating them as the "continuation value" for the next player up the tree.17

Mathematically, for each decision node h and action a, the player chooses the action that maximizes their utility u_i given the reaction function R_j(h,a) of all subsequent players j. If A_i(h) is the set of actions available to player i at node h, the subgame perfect action a* satisfies:

a* = arg max_{a in A_i(h)} u_i(a, R_j(h, a))

This procedure ensures that every move in the equilibrium path is "sequentially rational," meaning it is a best response to the actual choices that will be made later in the sequence.10

### **The Selten Revolution: Cleaning the Equilibrium Landscape**

The power of subgame perfection is most visible in the "Entry-Deterrence" game.11 Imagine a potential entrant and an incumbent monopolist. In a simultaneous matrix, there are two Nash equilibria: (Enter, Accommodate) and (Stay Out, Fight). The second equilibrium is sustained by the incumbent's threat to launch a price war if the entrant appears.19 However, the extensive-form rendering reveals that once entry has occurred, the incumbent faces a choice between "Accommodating" (earning moderate profits) and "Fighting" (earning zero or negative profits).11 Because the incumbent is rational, they will accommodate. The threat to fight is "incredible"—it is a psychological bluff that is exposed by the subgame structure.16 SPE eliminates such bluffs, selecting (Enter, Accommodate) as the unique rational prediction.11

| Concept | Definition | Strategic Consequence |
| :---- | :---- | :---- |
| **Nash Equilibrium** | Mutually consistent strategies. | Can include non-credible threats.11 |
| **Subgame Perfect (SPE)** | Nash equilibrium in every subgame. | Eliminates bluffs; demands local rationality.13 |
| **Backward Induction** | Reasoning from end to start. | Solves for the "continuation value".16 |
| **Incredible Threat** | Pledged suboptimal action if reached. | Fails to influence rational opponents.12 |

## **The Paradox of Commitment: Power via Self-Deprivation**

The most profound realization of sequential strategy is that power often derives from a manifest inability to act. In *The Strategy of Conflict* (1960), Thomas Schelling established that in a strategic environment, "more choices" can actually be a liability.3 This "paradox of commitment" posits that a player can improve their outcome by deliberately and visibly relinquishing options, thereby forcing the adversary to bear the full burden of avoiding a mutually catastrophic outcome.20

### **The Architecture of Self-Binding**

A commitment device is a mechanism that makes a specific future action irreversible or prohibitively expensive.23 For a commitment to change the game, it must be observable by the opponent and it must be credible.24 Credibility is the social and epistemic property of a commitment; it is the degree to which an opponent believes that the committed player will actually follow through when the time comes.16

The legendary example of Hernan Cortes scuttling his own ships upon landing in Mexico serves as the canonical illustration of this logic.23 By destroying his means of retreat, Cortes communicated to his men—and his enemies—that he could not be induced to flee. The "weakness" of having no escape route became a "strength" by making the commitment to fight absolute.21 In modern contexts, this translates into "burning bridges" behind oneself, such as a firm building massive production capacity that is non-recoverable, which functions as a credible threat to remain in the market even during a price war.16

### **A Taxonomy of Strategic Moves: Threats, Promises, and Warnings**

Schelling’s analysis provides a rigorous taxonomy of the moves used to manipulate an adversary's expectations. These moves are not merely communicative; they are architectural interventions that change the payoffs of future subgames.21

1. **Threats:** A pledge to impose a cost on the opponent if they act contrary to the player's wishes.26 A threat is "costly if it fails"—meaning if the opponent defies the threat, the player must execute the punishment, which is often painful for both parties. A successful threat is one that never has to be carried out.26  
2. **Promises:** A pledge to provide a benefit to the opponent if they act in accordance with the player's wishes.26 Unlike a threat, a promise is "costly if it succeeds"—meaning if the opponent complies, the player must actually deliver the reward.27 Promises are used when an agreement leaves a player with an incentive to "cheat" or "renege" after the other has performed.3  
3. **Warnings:** A statement that an action by the opponent will result in a negative outcome due to factors *external* to the player's choice.21 A warning carries no cost to the speaker because the consequence is automatic or driven by a third party.30

| Strategic Move | Definition | Cost Mechanism | Primary Objective |
| :---- | :---- | :---- | :---- |
| **Threat** | "If you do X, I will punish you." | Costly when it fails.28 | Deterrence (Stability) |
| **Promise** | "If you do X, I will reward you." | Costly when it succeeds.28 | Compellence (Change) |
| **Warning** | "If you do X, Nature punishes you." | Cost-neutral to speaker.30 | Info Revelation |
| **Commitment** | "I have made it so I must do Y." | Irreversible structural change.21 | Expectation Shaping |

## **Timing as a Resource: The Structural Advantages of Sequence**

The order of play is not a mere procedural detail; it determines whether power flows to the initiator or the responder. Game theory identifies specific structural conditions that favor moving first (the commitment advantage) or moving second (the informational advantage).31

### **First-Mover Advantage: The Power of the Stackelberg Leader**

In competitions where strategies are "strategic substitutes," there is a powerful first-mover advantage.32 Strategic substitutes occur when an increase in the action of one player causes the optimal response of the other player to decrease.33 The canonical model is the Stackelberg quantity duopoly. If Firm 1 moves first and commits to producing a large quantity of a good, Firm 2—observing this commitment—must best-respond by producing a smaller quantity to avoid a market-wide price collapse.24 By acting first, Firm 1 "captures" a larger share of the market's capacity, earning higher profits than it would in a simultaneous Cournot game.32

### **Second-Mover Advantage: The Power of Information and Flexibility**

Conversely, when strategies are "strategic complements," power often shifts to the second-mover.32 Strategic complements occur when an increase in one player's action makes the other player want to increase their own action accordingly.33 The classic example is price competition with differentiated goods (Sequentialized Hotelling).33 A firm that sets its price first is vulnerable; the second-mover can observe that price and slightly undercut it to capture the most profitable segment of the market.32 Here, the "power of the second move" lies in the flexibility to react to the leader's observable and irreversible commitment.

### **The Theorem of Gal-Or and the Role of Uncertainty**

The Theorem of Gal-Or (1985) establishes that under conditions of perfect and complete information, timing advantages are strictly a function of the sign of the cross-derivatives of the payoff functions.33 However, the analysis undergoes a significant shift when information is incomplete. Gal-Or later proved (1987) that if there is uncertainty about market demand, the informational advantage of waiting to see the first-mover's choice (which functions as a signal of their private info) can create a second-mover advantage even in quantity-based games.33 This shows that the value of timing is a coupled system involving both commitment power and information extraction.

| Competitive Model | Strategic Relationship | Advantageous Position | Logic of Power |
| :---- | :---- | :---- | :---- |
| **Stackelberg Cournot** | Strategic Substitutes | First-Mover 33 | Commitment forces accommodation.32 |
| **Stackelberg Bertrand** | Strategic Complements | Second-Mover 33 | Reactivity allows exploitation.32 |
| **Bayesian Stackelberg** | Informational Asymmetry | Second-Mover 33 | Observation reveals hidden types.33 |

## **Dynamic Inconsistency: The Intertemporal Bargaining of the Self**

Sequential strategy is not limited to interpersonal conflict; it provides a rigorous framework for understanding the "divided self." Dynamic inconsistency (or time inconsistency) occurs when an agent’s preferences over future outcomes change as time passes, leading them to revise plans that were optimal from an earlier perspective.34 This transforms an individual optimization problem into a non-cooperative game between successive incarnations of the same person.35

### **Naivete vs. Sophistication**

The formal study of dynamic inconsistency, pioneered by Robert Strotz (1956), typically models agents using non-constant (hyperbolic) discounting.36 This captures the empirical observation that people are more impulsive in the short run than in the long run.35

* **Naive Agents:** These individuals are unaware of their future preference reversals. They make ambitious plans today assuming their future self will follow through, only to find themselves "surprised" by their own lack of willpower when the moment of choice arrives.37  
* **Sophisticated Agents:** These individuals recognize their own dynamic inconsistency. They treat their future selves as independent players in a non-cooperative game and act strategically today to bind their future actions.37

### **The Tradeoff between Commitment and Flexibility**

Sophisticated agents face a fundamental dilemma between the "value of commitment" and the "value of flexibility".5 Commitment is valued because it removes "temptation" or "self-control" problems—for instance, by investing in illiquid assets that cannot be easily spent today.36 However, flexibility is also valuable because the future is uncertain. An agent expects to receive new information (modeled as "taste shocks") that might make the original plan suboptimal for legitimate reasons.5

The optimal commitment device is rarely a "total binding." Instead, it is often a "minimum-savings rule" or a "soft contract" that restricts the most extreme choices while preserving enough flexibility to respond to unforeseen needs.5 This represents a "principal-agent" formulation where the "present self" (the principal) designs a choice set for the "future self" (the agent).5

| Agent Attribute | Naive Agent | Sophisticated Agent |
| :---- | :---- | :---- |
| **Self-Awareness** | Unaware of preference shifts.37 | Anticipates future temptation.37 |
| **Planning Logic** | "Sliding" plans; revised daily.37 | Seeks commitment devices.38 |
| **Solution Concept** | Myopic best-response.39 | Subgame Perfect (intrapersonal).36 |
| **Typical Failure** | Procrastination/Over-consumption.37 | Over-binding (excessive rigidity).5 |

## **Weaponizing Reputation: Resolved Masquerading in Dynamic Games**

In dynamic environments with many stages, the history of play becomes a signaling mechanism for the construction of reputation. A reputation is not a vague social asset; it is an epistemic link between past behavior and future expectations. In sequential games, reputations allow actors to influence an adversary’s beliefs about their hidden "type".40

### **The Gang of Four and the Masquerade of Resolve**

The seminal research of the "Gang of Four" (Kreps, Wilson, Milgrom, and Roberts, 1982) demonstrated that in dynamic games, even a vanishingly small amount of incomplete information about a player’s payoffs can fundamentally alter the equilibrium.41 If there is a small probability that a player is an "irrational type" who always executes a certain threat (e.g., fighting every market entrant), then a "rational type" has an incentive to masquerade as that irrational type to build a reputation for toughness.41

This provides a rational explanation for the "Chain Store Paradox." While simple backward induction suggests that an incumbent should never fight an entry in a finite game, the reputational model shows that fighting in early rounds is a high-yield investment.19 By fighting early, the incumbent jumps their "posterior reputation" mu—the opponent's belief in their toughness—deterring entry in all subsequent rounds.42 Reputation thus functions as a commitment that is built through action rather than pre-arranged by a device.

### **Reputation Renewal and the Signal Decay**

In environments with imperfect monitoring or "noisy control," reputations are rarely permanent.43 This leads to the phenomenon of "reputation renewal," where a long-lived player must periodically perform costly, resolved actions to "recharge" the signal of their type.44 If an agent’s behavior is not perfectly observable, the "signal" provided by a past action begins to "fade" as the opponent updates their beliefs toward the average.44 Power in these systems belongs to those who can manage the "cyclical rhythm" of resolve-demonstration.

| Reputation Component | Strategic Function | Epistemic Impact |
| :---- | :---- | :---- |
| **Masquerading** | Rational imitation of "crazy" types. | Increases deterrent power.41 |
| **Posterior Belief (mu)** | Opponent’s estimate of your type. | Determined by history of play.40 |
| **Resolve Signaling** | Performing costly, painful actions. | Resets the reputation cycle.44 |
| **Reputation Fading** | Gradual loss of signal clarity. | Requires periodic renewal.45 |

## **Epistemic Refinements: Stability in the Informational Fog**

As a sequence unfolds, the analyst must account for how players update their beliefs about "who" they are playing against. This requires the transition from the Bayesian Nash Equilibrium (BNE) of static games to more sophisticated refinements: Perfect Bayesian Equilibrium (PBE) and Sequential Equilibrium.10

### **Perfect Bayesian Equilibrium (PBE)**

A PBE consists of an assessment (sigma, mu), where sigma is a strategy profile and mu is a "belief system"—a probability distribution over the nodes of every information set in the tree.10 PBE requires two conditions:

1. **Sequential Rationality:** At every information set (even those off the equilibrium path), the player must be maximizing their expected utility given their beliefs mu.10  
2. **Bayesian Consistency:** Beliefs must be updated using Bayes' rule at every information set reached with positive probability in equilibrium.10

The primary weakness of "weak" PBE is that it places no restrictions on "off-path" beliefs—what a player thinks when an opponent makes an impossible or unexpected move.10 This allows for "unreasonable" equilibria where a player is deterred by a threat that would only be rational if the opponent held some unsupported belief about the deviator's type.43

### **Sequential Equilibrium and the "Trembling Hand"**

To provide more discipline, Kreps and Wilson (1982) developed Sequential Equilibrium.10 This refinement requires "Kreps-Wilson Consistency": the assessment must be the limit of a sequence of assessments where every action has at least a tiny probability of being chosen (a "tremble").10 By assuming that every node is reachable through some small error, Sequential Equilibrium forces all off-path beliefs to be derived from a coherent theory of mistakes rather than arbitrary bluffs.10

## **Institutionalizing Resolve: Externalizing Commitment**

The most effective strategic commitments are those that are not dependent on internal willpower but are externalized into institutions or structural constraints.

### **Audience Costs as a Commitment Weapon**

In international crisis bargaining, James Fearon (1994) identified "audience costs" as a primary mechanism of resolve.46 A leader who makes a public threat creates a situation where backing down would be politically costly due to punishment by their own citizens or domestic political opponents. By "going public," the leader ties their own hands, making a threat more credible than it would be in a private channel.

The size and effectiveness of these costs depend on the "dovishness" or "hawkishness" of the electorate. If the audience is hawkish, backing down generates a "signaling audience cost" (a lower payoff after retreat than after not challenging at all). Strategic power involves the leader's ability to "endogenize" their own constraints by manipulating public expectations.47

### **Contract-Enforcement Institutions (CEIs)**

At the economic level, exchange is fundamentally sequential: one party provides a service, and the other pays later.48 This creates a "predation" problem where the second-mover has an incentive to renege. Contract-enforcement institutions (courts, legal systems) serve as third-party commitment devices that link current conduct with future payoffs.

By imposing a fine for breach of contract, the legal system rewrites the utility of the "Defect" action, making it lower than "Cooperate".1 This transforms a sequential "Prisoner's Dilemma" (where the first-mover is vulnerable) into a coordination game where cooperation is the unique Nash equilibrium. Strategic systems analysis shows that the wealth of nations is often a function of these institutions' ability to provide "credible commitment" capacity.48

| Institutional Mechanism | Domain | Strategic Function | Commitment Source |
| :---- | :---- | :---- | :---- |
| **Audience Costs** | Int. Relations | Escalates cost of retreat.46 | Domestic Public.46 |
| **CEIs** | Market Exchange | Penalizes contract breach.48 | Legal State.48 |
| **Central Bank Independence** | Finance | Stabilizes price expectations. | Technocratic Rules. |
| **Constitutions** | Politics | Binds future governments.49 | Rule of Law.49 |

## **Behavioral Realities: The Limits of Sequential Reasoning**

While the mathematical ideals of SPE and Backward Induction provide the theoretical benchmark for sequential power, real-world agents exhibit systematic deviations due to cognitive and computational constraints.18

### **Limited Backward Induction and the Centipede Paradox**

Experiments on the "Centipede Game"—where two players take turns either "Continuing" or "Stopping" (taking the larger share of the current pot)—expose the tension between theory and behavior. Backward induction predicts that a rational player should "Stop" on the very first move.

However, empirical evidence shows that most players continue for several rounds. This "Limited Backward Induction" (LBI) occurs because agents only reason through a few steps of the tree ("close-by nodes") rather than the entire horizon.51 Furthermore, if a player has even a slight doubt that their opponent is perfectly rational, it becomes a "best response" to continue and see if a higher mutual payoff can be achieved.41

### **Cognitive Hierarchies and Level-k Reasoning**

Cognitive Hierarchy Theory (CHT) models players as having different "depths" of reasoning, typically measured by a parameter tau.50

* **Level-0:** Acts instinctively or randomly.  
* **Level-1:** Best-responds to the belief that everyone else is Level-0.  
* **Level-2:** Best-responds to the belief that everyone else is a mixture of Level-0 and Level-1.

Experimental data across games like the "Beauty Contest" often finds that the average reasoning depth is between 1.5 and 2.5.50 This suggests that strategic power in a sequential environment also includes the ability to exploit the limited foresight of others.54

| Reasoning Depth | Characterization | Behavioral Alignment |
| :---- | :---- | :---- |
| **Level-0** | Instinctive | Modeling anchor only.50 |
| **Level-1** | Naive Best-Response | Common in simple games.50 |
| **Level-2** | Sophisticated anticipation | Observed in competitive labs.50 |
| **Infinite** | Subgame Perfect | Benchmark; rarely observed.11 |

### **Computational Complexity as a Temporal Boundary**

The ability to "shape the future" is limited by the computational intractability of the tree itself. Finding a Nash equilibrium for complex games is PPAD-complete, and the verification of SPE in extensive games lies in PSPACE. In vast games like chess or real-time automated markets, no agent can solve for the equilibrium through pure deduction. This justifies the use of "Learning Dynamics," where agents "discover" stable strategies through trial and error over time. Here, power belongs to the agent with the fastest learning rate or most efficient heuristic.

## **Brinkmanship: The Diplomacy of Controlled Risk**

One of the most subtle mechanisms of sequential strategy is "Brinkmanship"—a tactic described by Schelling as "the threat that leaves something to chance".20 If a player cannot credibly threaten an all-out disaster, they can instead create a situation where the disaster becomes a stochastic possibility that neither player can fully control.20

### **The Little Black Box of Stochastic Ruin**

Schelling’s "Little Black Box" thought experiment serves as the foundational model. Ideally, for deterrence, a player would possess a device that has a small, set probability of detonating (causing mutual ruin) every day.20 By initiating a sequence of play that moves toward the "brink," the player delegates the final decision to this "black box" of risk.20 The credibility of the threat is no longer dependent on the player’s willingness to push the button; it is built into the situation’s inherent volatility.57

Brinkmanship is therefore a "war of nerves" where players bargain through the manipulation of risk.20 The goal is to harass and intimidate an adversary by exposing them to a shared risk that becomes "intolerable" to them first.20

## **Sunk Costs and the Biology of Commitment**

Why do rational agents honor "sunk costs"—investments that cannot be recovered and should therefore be ignored according to standard economics? Evolutionary game theory suggests that "honoring bygones" may be a hard-wired commitment device.58

### **The Evolutionary Utility of Persistence**

In the struggle for survival, Nature may have found it expedient to resolve internal conflicts between the "emotional" and "rational" centers of the brain through the salience of sunk costs.58 For instance, in distributional contests over food or territory, a producer who exhibits an "irrational" proclivity to defend their output (treating past effort as a value to be honored) will be more aggressive in defense.58 This aggression acts as a credible signal of resolve, deterring interlopers who would otherwise steal the producer’s gains.58 At the individual level, the sense of "identity"—the psychological investment in one's own history—may be the ultimate sunk cost, serving as a biological commitment device to maintain consistent behavior across a lifetime.58

## **Synthesis: Time as the Ultimate Strategic Lens**

The transition from static interdependence to sequential interaction redefines the strategic field from a set of choices into an architecture of control. Once time is introduced, strategic power is no longer just about the magnitude of payoffs, but about the **topology of the timeline**.

1. **Credibility is the Epistemic Prerequisite:** Power in a sequence is an informational property. A player only has power if their future actions are believed to be certain, which requires alignment of incentives with history.16  
2. **Commitment is an Architectural Act:** By visibly and irreversibly relinquishing choice, a player shifts the "last clear chance" of avoiding disaster onto the opponent.20  
3. **Timing is a Structural Resource:** Moving first provides commitment power; moving second provides informational power. Advantage is determined by whether strategies are substitutes or complements.33  
4. **The Self is a Non-Cooperative System:** Dynamic inconsistency transforms individual decision-making into an intertemporal bargaining process between different "selves".35  
5. **Rationality is Bounded by Horizon:** The theoretical benchmark of SPE is often replaced by Level-k reasoning and limited backward induction, where power flows to the agent who can see one step further.51

Strategic systems analysis must treat time as the variable that "hardens" the strategic field. The "shadow of the future" allows for the construction of trust through repeated interaction, but it also allows for weaponization of resolve through self-binding. As the canon moves into its next modules—Bargaining and Repeated Interaction—the sequential infrastructure established here will serve as the engine for understanding how coordination is sustained or destroyed in a world of rational, time-bound agents.

### ---

**Glossary of Canonical Terms**

* **Assessment (sigma, mu):** A pair consisting of a strategy profile and a belief system.10  
* **Backward Induction:** The process of analyzing a game from the terminal nodes back to the start to identify sequentially rational play.16  
* **Belief System (mu):** A probability distribution over the nodes of an information set.10  
* **Brinkmanship:** The strategic manipulation of risk to create a credible threat of disaster that neither party fully controls.20  
* **Commitment Device:** A mechanism that makes a future action irreversible or costly, thereby increasing credibility.23  
* **Dynamic Inconsistency:** A situation where an agent's optimal plan for the future becomes suboptimal when that future arrives.34  
* **First-Mover Advantage:** The benefit of acting first to commit to a strategy, typically found in games of strategic substitutes.32  
* **Information Set:** A set of decision nodes where a player cannot distinguish their current location in the sequence.8  
* **Second-Mover Advantage:** The benefit of acting second to utilize observational information, typically found in games of strategic complements.32  
* **Subgame Perfect Equilibrium (SPE):** A Nash equilibrium that remains an equilibrium in every possible subgame of the original game.13

### **Inherited from Reports 1–3**

* **Ontological:** Players, Actions vs. Strategies, Utility, Interdependence, Nash Equilibrium.1  
* **Epistemic:** Belief Hierarchies, Common Knowledge, Type Uncertainty, Harsanyi Transformation.10  
* **Representational:** Extensive-Form Game Trees, Nodes, Edges, Terminal Nodes, Non-singleton Information Sets.8

### **Downstream Dependencies**

* **Report 5: Bargaining Systems:** Uses sequential structure to model the division of surplus and the impact of patience.  
* **Report 6: Repeated Interaction:** Deepens sequence into infinite horizons and folk theorems.  
* **Report 7: Mechanism Design:** Architects sequential rules to ensure incentive compatibility.  
* **Report 11: Strategic Failure:** Analyzes how limited backward induction and commitment traps cause systemic collapse.

### **What This Report Does Not Yet Cover**

* **Infinite Horizon Dynamics:** The specific conditions for cooperation in indefinitely repeated games.  
* **Coalitional Bargaining:** The strategic formation of sub-groups in sequential interactions.  
* **Advanced Mechanism Blueprints:** Specific designs for auction sequences or labor matching systems.

#### **Works cited**

1. Game Theory 1 - The Geometry of Strategic Conflict — An Ontology of Incentives, Interdependence, and Equilibrium  
2. Sequential game - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Sequential_game](https://en.wikipedia.org/wiki/Sequential_game)  
3. The Strategy of Conflict - sackett.net, accessed April 18, 2026, [https://www.sackett.net/Strategy-of-Conflict.pdf](https://www.sackett.net/Strategy-of-Conflict.pdf)  
4. Commitment device - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Commitment_device](https://en.wikipedia.org/wiki/Commitment_device)  
5. Commitment vs. Flexibility | MIT Economics, accessed April 18, 2026, [https://economics.mit.edu/sites/default/files/publications/Commitment%20vs%20Flexibility.pdf](https://economics.mit.edu/sites/default/files/publications/Commitment%20vs%20Flexibility.pdf)  
6. Thomas C. Schelling: A Reminiscence - War on the Rocks, accessed April 18, 2026, [https://warontherocks.com/2016/12/thomas-c-schelling-a-reminiscence/](https://warontherocks.com/2016/12/thomas-c-schelling-a-reminiscence/)  
7. Thomas Schelling - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Thomas_Schelling](https://en.wikipedia.org/wiki/Thomas_Schelling)  
8. Game Theory 3 - Strategic Representation and Formalization — Modeling Strategic Reality with Matrices, Trees, Information Sets, and Type Spaces  
9. Why subgame-perfect Nash equilibrium is called perfect rather than just subgame Nash equilibrium? - Quora, accessed April 18, 2026, [https://www.quora.com/Why-subgame-perfect-Nash-equilibrium-is-called-perfect-rather-than-just-subgame-Nash-equilibrium](https://www.quora.com/Why-subgame-perfect-Nash-equilibrium-is-called-perfect-rather-than-just-subgame-Nash-equilibrium)  
10. Game Theory 2 - Equilibrium and Information — Stability, Beliefs, and Strategic Knowledge Systems  
11. Subgame Perfection | Encyclopedia.com, accessed April 18, 2026, [https://www.encyclopedia.com/social-sciences/applied-and-social-sciences-magazines/subgame-perfection](https://www.encyclopedia.com/social-sciences/applied-and-social-sciences-magazines/subgame-perfection)  
12. What is the difference between a Nash Equilibrium and a subgame perfect nash equilibrium? : r/GAMETHEORY - Reddit, accessed April 18, 2026, [https://www.reddit.com/r/GAMETHEORY/comments/2xtfgm/what_is_the_difference_between_a_nash_equilibrium/](https://www.reddit.com/r/GAMETHEORY/comments/2xtfgm/what_is_the_difference_between_a_nash_equilibrium/)  
13. Subgame perfect equilibrium - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Subgame_perfect_equilibrium](https://en.wikipedia.org/wiki/Subgame_perfect_equilibrium)  
14. Subgame Perfection - Game Theory, accessed April 18, 2026, [https://vknight.org/gtb/main-5/](https://vknight.org/gtb/main-5/)  
15. Subgames - Game Theory through Examples, accessed April 18, 2026, [http://www.eprisner.de/MAT109/Subgames.html](http://www.eprisner.de/MAT109/Subgames.html)  
16. Backward induction - Microeconomic Theory Concepts - Umbrex, accessed April 18, 2026, [https://umbrex.com/resources/economics-concepts/microeconomic-theory/backward-induction/](https://umbrex.com/resources/economics-concepts/microeconomic-theory/backward-induction/)  
17. Subgame Perfect Nash Equilibrium and Backward Induction - Moodle@Units, accessed April 18, 2026, [https://moodle2.units.it/pluginfile.php/85593/mod_resource/content/0/lecture%205.pdf](https://moodle2.units.it/pluginfile.php/85593/mod_resource/content/0/lecture%205.pdf)  
18. Backward induction - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Backward_induction](https://en.wikipedia.org/wiki/Backward_induction)  
19. Reinhard Selten - Econlib, accessed April 18, 2026, [https://www.econlib.org/library/Enc/bios/Selten.html](https://www.econlib.org/library/Enc/bios/Selten.html)  
20. 4.2 — Credible Commitments - Game Theory, accessed April 18, 2026, [https://gamef21.classes.ryansafner.com/slides/4.2-slides.pdf](https://gamef21.classes.ryansafner.com/slides/4.2-slides.pdf)  
21. 176 Ethics October 2007 Schelling, Thomas C. Strategies of Commitment and Other Essays. Cambridge, MA - Political Science, accessed April 18, 2026, [https://polisci.osu.edu/sites/polisci.osu.edu/files/_SchellingRev_.pdf](https://polisci.osu.edu/sites/polisci.osu.edu/files/_SchellingRev_.pdf)  
22. Thomas C. Schelling's "Strategy of Conflict" - LessWrong, accessed April 18, 2026, [https://www.lesswrong.com/posts/tJQsxD34maYw2g5E4/thomas-c-schelling-s-strategy-of-conflict](https://www.lesswrong.com/posts/tJQsxD34maYw2g5E4/thomas-c-schelling-s-strategy-of-conflict)  
23. Commitment Devices in Game Theory: Burn the Ships, Win the Market - Amtech, accessed April 18, 2026, [https://buildamtech.com/podcast/commitment-devices-in-game-theory-burn-the-ships-win-the-market/](https://buildamtech.com/podcast/commitment-devices-in-game-theory-burn-the-ships-win-the-market/)  
24. Game Theory: Sequential and Commitment Games | PDF - Scribd, accessed April 18, 2026, [https://www.scribd.com/document/965782597/Lecture-4-5-pdf-5](https://www.scribd.com/document/965782597/Lecture-4-5-pdf-5)  
25. COMMITMENT AND OBSERVABILITY IN GAMES - Northwestern University, accessed April 18, 2026, [https://www.kellogg.northwestern.edu/research/math/papers/1014.pdf](https://www.kellogg.northwestern.edu/research/math/papers/1014.pdf)  
26. The Power of Ambiguity in Threats and Promises - Rob Henderson's Newsletter, accessed April 18, 2026, [https://www.robkhenderson.com/p/the-power-of-ambiguity-in-threats](https://www.robkhenderson.com/p/the-power-of-ambiguity-in-threats)  
27. National Security Strategy: Credible Commitments in Deterrence & Com- pellence - Branislav L. Slantchev (UCSD), accessed April 18, 2026, [http://slantchev.ucsd.edu/courses/ps142j/lectures/credible-commitments.pdf](http://slantchev.ucsd.edu/courses/ps142j/lectures/credible-commitments.pdf)  
28. Randomization of Threats and Promises, accessed April 18, 2026, [https://www.rand.org/content/dam/rand/pubs/papers/2006/P1716.pdf](https://www.rand.org/content/dam/rand/pubs/papers/2006/P1716.pdf)  
29. Game Theory - Stanford Encyclopedia of Philosophy, accessed April 18, 2026, [https://plato.stanford.edu/entries/game-theory/](https://plato.stanford.edu/entries/game-theory/)  
30. Promises and Threats with Conditionals and Disjunctions, accessed April 18, 2026, [https://michael-franke.github.io/heimseite/Papers/joint_PIs2010.pdf](https://michael-franke.github.io/heimseite/Papers/joint_PIs2010.pdf)  
31. Subgame Perfection, accessed April 18, 2026, [https://saylordotorg.github.io/text_introduction-to-economic-analysis/s17-05-subgame-perfection.html](https://saylordotorg.github.io/text_introduction-to-economic-analysis/s17-05-subgame-perfection.html)  
32. When Do First-Movers Have an Advantage? A Stackelberg Classroom Experiment - Economics, accessed April 18, 2026, [https://irving.vassar.edu/faculty/rr/Research/RebeleinTurkay_IO_ClassroomExperiment.pdf](https://irving.vassar.edu/faculty/rr/Research/RebeleinTurkay_IO_ClassroomExperiment.pdf)  
33. First-Mover and Second-Mover Advantage under Uncertainty - mediaTUM, accessed April 18, 2026, [https://mediatum.ub.tum.de/doc/1471052/document.pdf](https://mediatum.ub.tum.de/doc/1471052/document.pdf)  
34. Dynamic inconsistency - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Dynamic_inconsistency](https://en.wikipedia.org/wiki/Dynamic_inconsistency)  
35. Dynamic Inconsistency Theory | Request PDF - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/341229343_Dynamic_Inconsistency_Theory](https://www.researchgate.net/publication/341229343_Dynamic_Inconsistency_Theory)  
36. Commitment Devices under Self-Control Problems: An Overview - Juan D. Carrillo, accessed April 18, 2026, [https://www.jdcarrillo.org/PDFpapers/book2-ch04.pdf](https://www.jdcarrillo.org/PDFpapers/book2-ch04.pdf)  
37. General Equilibrium and Dynamic Inconsistency - EconStor, accessed April 18, 2026, [https://www.econstor.eu/bitstream/10419/263776/1/cesifo1_wp9846.pdf](https://www.econstor.eu/bitstream/10419/263776/1/cesifo1_wp9846.pdf)  
38. Dynamic Inconsistency and Convex Commitment Devices 1 Introduction, accessed April 18, 2026, [https://acsweb.ucsd.edu/~awolansk/pdfs/Dynamic_Inconsistency_and_Convex_Commitment_Devices.pdf](https://acsweb.ucsd.edu/~awolansk/pdfs/Dynamic_Inconsistency_and_Convex_Commitment_Devices.pdf)  
39. Dynamic Inconsistency in Risky Choice: Evidence from the Lab and Field, accessed April 18, 2026, [https://fnce.wharton.upenn.edu/wp-content/uploads/2022/09/Alex_DynamicInconsistencyRisk.pdf](https://fnce.wharton.upenn.edu/wp-content/uploads/2022/09/Alex_DynamicInconsistencyRisk.pdf)  
40. Game Theory, Lecture 9: Reputation Effects in Repeated Games - MIT OpenCourseWare, accessed April 18, 2026, [https://ocw.mit.edu/courses/14.126-game-theory-spring-2024/mit14_126_s24_lecture_9_reputation_effects.pdf](https://ocw.mit.edu/courses/14.126-game-theory-spring-2024/mit14_126_s24_lecture_9_reputation_effects.pdf)  
41. reputation without commitment in finitely-repeated games - MIT Economics, accessed April 18, 2026, [https://economics.mit.edu/sites/default/files/publications/WYreputation-final.pdf](https://economics.mit.edu/sites/default/files/publications/WYreputation-final.pdf)  
42. Chapter 10 Reputation Formation - DSpace@MIT, accessed April 18, 2026, [https://dspace.mit.edu/bitstream/handle/1721.1/99213/14-123-spring-2010/contents/lecture-notes/MIT14_123S10_notes10.pdf](https://dspace.mit.edu/bitstream/handle/1721.1/99213/14-123-spring-2010/contents/lecture-notes/MIT14_123S10_notes10.pdf)  
43. Reputation Effects in Dynamic Games Martin CrippsI Department of Economics University of Warwick No. 329 October 1989 This pape, accessed April 18, 2026, [https://warwick.ac.uk/fac/soc/economics/research/workingpapers/1989-1994/twerp329.pdf](https://warwick.ac.uk/fac/soc/economics/research/workingpapers/1989-1994/twerp329.pdf)  
44. Information Acquisition and Reputation Dynamics, accessed April 18, 2026, [https://siepr.stanford.edu/publications/working-paper/information-acquisition-and-reputation-dynamics](https://siepr.stanford.edu/publications/working-paper/information-acquisition-and-reputation-dynamics)  
45. [2509.09181] Incomplete Reputation Information and Punishment in Indirect Reciprocity, accessed April 18, 2026, [https://arxiv.org/abs/2509.09181](https://arxiv.org/abs/2509.09181)  
46. Audience Costs Theory and Its Audiences - Branislav L. Slantchev (UCSD), accessed April 18, 2026, [http://slantchev.ucsd.edu/published/pdf/TrachtenbergResponse-W061.pdf](http://slantchev.ucsd.edu/published/pdf/TrachtenbergResponse-W061.pdf)  
47. A Behavioral Foundation for Audience Costs - Stanford University, accessed April 18, 2026, [https://stanford.edu/~avidit/audiencecosts.pdf](https://stanford.edu/~avidit/audiencecosts.pdf)  
48. 28. Commitment, Coercion, and Markets: The Nature and Dynamics of Institutions Supporting Exchange - Stanford University, accessed April 18, 2026, [https://web.stanford.edu/~avner/Greif_Papers/Commitment_Coercion_Markets.pdf](https://web.stanford.edu/~avner/Greif_Papers/Commitment_Coercion_Markets.pdf)  
49. (PDF) Institutional Transition and the Problem of Credible Commitment - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/228320248_Institutional_Transition_and_the_Problem_of_Credible_Commitment](https://www.researchgate.net/publication/228320248_Institutional_Transition_and_the_Problem_of_Credible_Commitment)  
50. Neural correlates of depth of strategic reasoning in medial prefrontal cortex - PNAS, accessed April 18, 2026, [https://www.pnas.org/doi/10.1073/pnas.0807721106](https://www.pnas.org/doi/10.1073/pnas.0807721106)  
51. (PDF) Limited backward induction: foresight and behavior in sequential games, accessed April 18, 2026, [https://www.researchgate.net/publication/270493023_Limited_backward_induction_foresight_and_behavior_in_sequential_games](https://www.researchgate.net/publication/270493023_Limited_backward_induction_foresight_and_behavior_in_sequential_games)  
52. Limited backward induction: foresight and behavior in sequential games - IDEAS/RePEc, accessed April 18, 2026, [https://ideas.repec.org/p/mib/wpaper/289.html](https://ideas.repec.org/p/mib/wpaper/289.html)  
53. Limited Depth of Reasoning in Games - Duarte Gonçalves, accessed April 18, 2026, [https://duartegoncalves.com/teaching/phd-experimental/slides/Goncalves,%20PhD%20Experimental.%20Limited%20Depth%20of%20Reasoning%20in%20Games-handout.pdf](https://duartegoncalves.com/teaching/phd-experimental/slides/Goncalves,%20PhD%20Experimental.%20Limited%20Depth%20of%20Reasoning%20in%20Games-handout.pdf)  
54. Cognitive hierarchy theory - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Cognitive_hierarchy_theory](https://en.wikipedia.org/wiki/Cognitive_hierarchy_theory)  
55. LLM Strategic Reasoning: Agentic Study through Behavioral Game Theory - arXiv, accessed April 18, 2026, [https://arxiv.org/html/2502.20432v3](https://arxiv.org/html/2502.20432v3)  
56. The Psychology of Nuclear Brinkmanship | International Security - MIT Press Direct, accessed April 18, 2026, [https://direct.mit.edu/isec/article/47/3/9/114669/The-Psychology-of-Nuclear-Brinkmanship](https://direct.mit.edu/isec/article/47/3/9/114669/The-Psychology-of-Nuclear-Brinkmanship)  
57. Strategic Stability and Its Limits: Reflections on Schelling - Texas ..., accessed April 18, 2026, [https://tnsr.org/roundtable/strategic-stability-and-its-limits-reflections-on-schelling/](https://tnsr.org/roundtable/strategic-stability-and-its-limits-reflections-on-schelling/)  
58. The Evolutionary Logic of Honoring Sunk Costs - The University of British Columbia, accessed April 18, 2026, [https://economics.ubc.ca/wp-content/uploads/sites/38/2013/09/pdf_paper_mukesh-eswaran-honoring-sunk-costs.pdf](https://economics.ubc.ca/wp-content/uploads/sites/38/2013/09/pdf_paper_mukesh-eswaran-honoring-sunk-costs.pdf)  
59. Sunk Cost Fallacy: Escalation of Commitment Explained, accessed April 18, 2026, [https://db.arabpsychology.com/escalation-of-commitment-2/](https://db.arabpsychology.com/escalation-of-commitment-2/)

---