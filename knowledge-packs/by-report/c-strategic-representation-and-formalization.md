# C. Strategic Representation and Formalization — Modeling Strategic Reality with Matrices, Trees, Information Sets, and Type Spaces

Formalization in strategic analysis is not a neutral act of notation or a clerical wrapper placed around a problem after the fact. It is the primary theoretical commitment by which an analyst decides what a strategic problem *is*.1 To represent a live conflict as a payoff matrix, an extensive-form tree, or a Bayesian type space is to choose a specific "strategic camera angle" that deliberately highlights certain causal structures while suppressing others.3 This report, the third in a 12-report canon, serves as the definitive guide to modelcraft—the disciplined art of preserving the causal burden of reality under conditions of unavoidable representational loss.2 The governing burden of this document is to teach how to encode strategic situations so that the load-bearing elements—incentives, timing, and information—remain visible without being flattened into elegant but misleading nonsense.1

## **The Inherited Architecture of Strategic Reality**

Strategic modeling does not begin in a vacuum. It inherits a base ontology from the canon’s prior foundational work. The analyst enters the modeling process with a prerequisite understanding of what strategic reality is made of, even before deciding how to draw it.1

### **Inherited Ontology from Report 1**

Report 1 established the "atomic" primitives of the strategic field. A player is understood as an autonomous unit of agency with a set of preferences and the capacity to choose actions to serve those preferences.1 These preferences are mapped into utility functions, which represent numerical orderings over outcomes, accounting for risk, material gain, and normative constraints.1 Crucially, the field distinguishes between an "action"—a discrete choice at a single node—and a "strategy," which is a global program for every possible contingency the player might encounter.1 Strategic interaction is defined by interdependence, where the value of an agent's choice is recursively conditioned by the anticipated choices of others.1 The Nash equilibrium remains the candidate rest-state of this system, where expectations are mutually consistent and no player has a unilateral incentive to deviate.1

### **Epistemic Infrastructure from Report 2**

Report 2 added the informational dimensions necessary for realistic modeling. It introduced the "information set" as the formal unit for capturing observability, preventing the error of assuming that all players know exactly where they are in a sequence of events.6 It established "type uncertainty" as the formal packaging for hidden characteristics, utilizing the Harsanyi transformation to treat uncertainty about "who" a player is as a move by Nature.6 Finally, it mapped the recursive hierarchies of belief—what I think you think I think—and established "common knowledge" as the social glue required for stable coordination, while identifying the fragility of that glue in the face of private signals or "trembles".6

## **Representation as Theory Choice Under Controlled Loss**

The most fundamental truth of modelcraft is that every representation is a "fable"—an abstract simplification that preserves some structure and erases the rest.5 The question for the analyst is never whether a formalization is complete. It is whether it preserves the "strategic burden" that matters for the problem at hand.1

### **The Standard of Controlled Omission**

Choosing a representational form is an act of controlled omission. The analyst must decide what becomes visible, what gets compressed into a utility value, what gets offloaded to the stochastic realm of Nature, and what is elevated into the explicit rules of the game.2 This process is driven by three standards that the analyst must constantly balance:

1. **Descriptive Adequacy:** The model must contain enough institutional and psychological texture to feel recognizable as the target problem.2  
2. **Analytic Tractability:** The model must be simple enough to permit formal reasoning and the identification of equilibria.4  
3. **Intervention Usefulness:** The model must highlight the variables that a decision-maker or game designer can actually influence.1

A model that is "too faithful" to reality often becomes as useless as a 1:1 scale map; a model that is "too clean" produces false clarity by erasing the very friction that determines the outcome.4 The expert analyst treats this tension not as a defect to be solved but as a trade-off to be managed.1

### **Representation as Governance**

Representational choices are not merely aesthetic; they are governance decisions.18 How an analyst frames a problem—whether as a simultaneous matrix or a sequential tree—determines the kind of behavior that will be predicted.16 For example, in large language model (LLM) agent environments, providing agents with "personas" rather than raw payoff information can shift equilibrium attainment by up to 90 percentage points.18 This establishes that representational choices are implicit interventions that shape system-level outcomes.18 Formalization is the act of deciding which "camera angle" will govern the analyst's perception of the game's logic.3

## **The Major Representational Families and Their Strategic Angles**

The strategist typically chooses from four primary representational families. Each provides a different angle on strategic reality, and each carries a specific burden of loss.

### **1. Normal-Form Representation: The Compact Interdependence Mapping**

The normal-form (or strategic-form) representation is the "wide-angle lens" of the field. It is primarily used to model simultaneous interactions where the primary burden is the alignment of incentives rather than the timing of moves.11

A normal-form game is typically represented as an n-dimensional matrix, where each dimension corresponds to a player’s strategy set.11 The cells of the matrix contain utility vectors representing the payoffs for each player under a specific strategy profile. Formally, a normal-form game is a triplet (N, S, u), where N is the set of players, S is the product of all individual strategy spaces S_i, and u is the payoff function mapping S to n-dimensional real space R^n.11

| Feature | Strategic (Normal) Form | Extensive Form |
| :---- | :---- | :---- |
| Primary Visual | Matrix (Payoff Table) | Tree (Nodes and Edges) |
| Temporal Focus | Simultaneous/Collapsed Timing | Sequential/Temporal Sequence |
| Strategy Definition | Complete plan chosen ex-ante | Choices made at decision nodes |
| Key Strength | Identifying dominated strategies | Identifying credible threats |
| Key Loss | Erases observability and timing | Becomes unwieldy for large sets |

The normal form is exceptionally powerful for identifying strictly dominated strategies and finding all possible Nash equilibria.11 However, its "controlled loss" is timing. It collapses a complex sequential process into a single, simultaneous choice.12 This collapse is often a lie: it assumes that players can formulate a "complete contingency plan" before the game begins and that no new information will change their fundamental logic during play.11

### **2. Extensive-Form Representation: The Geometry of Contingency**

The extensive-form representation is the "cinematic sequence" of game theory. It is the tool of choice for modeling games where the order of play, observability, and the credibility of future actions are strategically load-bearing.13

An extensive-form game is defined by a "game tree"—a set of nodes representing choice points, edges representing actions, and terminal nodes representing payoffs.13 The formal structure includes:

* **Players:** N = {1,..., n}, including "Nature" for chance events.15  
* **Game Tree:** A set of histories H and a precedence relation that defines the sequence.19  
* **Information Sets:** A partition of the decision nodes for each player into sets that are indistinguishable to the player at the moment of choice.6

The extensive form makes "subgames" visible, allowing the analyst to use "backward induction" to eliminate equilibria that rely on incredible threats.10 If the normal form is about *what* players want, the extensive form is about *when* they know what they want and whether they can *commit* to it.8

### **3. Bayesian and Type-Space Representation: The Engineering of Hidden Characteristics**

When the primary strategic burden is not "what happened" but "who is my opponent," the analyst moves to Bayesian representations.6 This form utilizes the Harsanyi transformation to convert uncertainty about players' preferences or capabilities into moves by Nature.6

A Bayesian game introduces the concept of a "type" t_i in T_i for each player.6 A player's type packages all their private information: their production costs, their risk tolerance, and even their beliefs about others' beliefs.6 The expected utility for player i with type t_i given a strategy profile s and a common prior P is represented as: EU_i(s_i | t_i) = sum over t_-i in T_-i of [ P(t_-i | t_i) * u_i(s_i(t_i), s_-i(t_-i), t) ]6

The "controlled loss" of the Bayesian rendering is institutional texture. It often obscures the dynamic rhythm of negotiation by focusing on the static distribution of types.6 However, it is the only form capable of surgically analyzing signaling and screening environments.6

### **4. Dynamic and State-Transition Representations: Environmental Evolution**

In cases where the environment itself evolves based on players' moves or exogenous forces, analysts utilize state-based or stochastic games.23 These models treat the "state of the world" as a variable that changes over time. Nature’s moves in these games are not merely "one-shot" reveals of type but continuous transformations of the payoff landscape.23 This form is essential for modeling "controlled loss of control" in complex systems like climate policy or high-frequency automated markets.18

## **Modeling Primitives as Live Acts of Judgment**

A central failure in amateur modeling is treating the primitives—players, actions, payoffs—as inherited givens. In advanced modelcraft, every primitive is a substantive commitment that changes the game’s apparent logic.1

### **Who Counts as a Player?**

The decision of who counts as a player is often the most consequential modeling choice. Analysts must judge when a collective actor (a firm, a state, a family) may be modeled as "unitary" and when internal fragmentation is strategically load-bearing.7

| Actor Type | Modeling Choice | Strategic Implication |
| :---- | :---- | :---- |
| Unitary Actor | Modeled as a single body with coherent preferences.7 | Focuses on external competition; ignores internal agency costs.27 |
| Fractured Actor | Modeled as a coalition of individuals with conflicting goals.28 | Focuses on internal coordination and principal-agent problems.28 |

In strategic management, treating a firm as a monolithic entity misses the reality that firms are often "coalitions of individuals".28 If the strategic burden of a problem lies in internal sabotage or misaligned hierarchical incentives, a unitary model is a representational lie that will produce a failed prediction.28

### **Defining the Action Space: Discrete vs. Continuous**

The analyst must decide the granularity of the action space. Most canonical models use discrete choices (e.g., "Enter" vs. "Stay Out").11 While discrete models are powerful for identifying qualitative tipping points, they often flatten the "adaptive and graded nature" of real decisions.31

Transitioning from discrete to continuous repeated interactions can promote greater cooperation, as synchronous action and real-time visibility foster trust more effectively than turn-based, binary "simultaneous" games.31 Deciding between a discrete and continuous action space is a decision about whether "effort" and "timing" are load-bearing variables.31

### **The Placement of Institutions: Rules vs. Payoffs**

A recurring tension in formalization is whether institutions belong in the "rules of the game" or merely in the "utility landscape".1

* **Burying in Payoffs:** Modeling a legal fine as a subtraction from the utility of the "Defect" action.1 This is elegant but loses sight of the *mechanism* of enforcement.  
* **Elevating to Rules:** Modeling the legal system as a player (or a move by Nature) that observes actions and imposes penalties.18 This preserves the causal chain of observability and adjudication but increases model complexity.1

## **The Engineering of Information and Informational "Fogs"**

If representation is a theory choice, information engineering is the way that choice is implemented. Report 2 introduced information sets and type spaces; this report teaches how to construct them as precision instruments.6

### **Constructing Information Sets: Merging vs. Distinguishing Nodes**

The placement of information sets determines the "informational fog" of the game.6 Merging two nodes into a single information set is a claim that the differences between those nodes are strategically irrelevant to the player.6

* **Strategic Error:** Merging nodes that *could* be distinguished in reality destroys observability distinctions that might be decisive for credibility.6  
* **The "Not Knowing" Burden:** If a player in a sequential game moves without knowing what the previous player did, they *must* be modeled as belonging to a non-singleton information set.6 This formalizes the "imperfect information" without resorting to a simultaneous matrix that erases the timing entirely.15

### **Nature Moves vs. "Junk Drawers"**

Nature nodes should be used to encode exogenous uncertainty (stochastic risk) without becoming a "lazy bucket" for everything the analyst has failed to understand.1

* **Precision:** Nature should be assigned a specific probability distribution for a specific event (e.g., "High demand" vs. "Low demand").6  
* **Pathology:** "Overloading Nature" occurs when analysts use Nature moves to hide unstable preferences or institutional volatility that should have been modeled as strategic choices by players.1 This flattens a "strategic game" into a "game against nature," erasing the recursive reasoning that defines the field.1

### **Type Spaces: Formalizing Hidden Characteristics**

Type spaces can sharpen a model by formally packaging characteristics like "cost structure" or "valuation".6 However, they can also become "bloated junk drawers" for ambiguity.33 A "type" should be the sufficient statistic for a player's strategic reality—containing only what is needed to determine their best response hierarchy.6 Adding irrelevant "character details" to a type space increases noise without adding predictive power.6

## **Translation Across Representations: Changing Camera Angles**

A central feature of modelcraft is the ability to translate the same strategic situation across different forms to see what each rendering reveals or hides.1

### **What is Gained and Lost in Translation?**

* **Matrix Rendering:** Clarifies pure interdependence and identifies all Nash equilibria. It hides the "dynamics of interaction" and makes it impossible to distinguish between credible commitments and idle threats.8  
* **Tree Rendering:** Reveals timing, sequence, and information flow. It makes "subgame perfection" visible but becomes exponentially unwieldy as the number of strategies increases.13  
* **Bayesian Rendering:** Illuminates the role of private information and belief updating. It often obscures institutional texture or the "dynamic rhythm" of a long-term bargaining process.6

### **The "Electronic Mail Game" as a Translation Lesson**

In the Electronic Mail Game (Rubinstein, 1989), two players wish to coordinate on a risky action.6

* **Matrix View:** Suggests that if enough confirmation messages are sent, coordination should be easy.39  
* **Epistemic Tree View:** Reveals that because messages can be lost with a tiny probability, there is *never* common knowledge.6 Coordination remains impossible regardless of how many messages are sent.6  
* **Conclusion:** Only the "camera angle" of the extensive-form epistemic tree reveals the "fragility of common knowledge" that the matrix rendering "smoothes over".6

## **Model Selection: Practical Field Judgment**

The analyst chooses where to start based on the "strategic burden" of the problem, not a classroom decision tree.1

### **When to Start with the Normal Form**

* The problem is a "simultaneous rivalry" where all parties act without observation (e.g., price-setting in a mature market).11  
* The primary goal is to find the "fixed points" of mutual strategic fit.1  
* The analyst needs to identify strictly dominated strategies across a large action space.11

### **When the Extensive Form is Unavoidable**

* Timing is the central mechanism of the game (e.g., a "first-mover advantage" or an "entry-deterrence" scenario).13  
* Credibility, threats, and sequential rationality are the load-bearing pillars of the conflict.8  
* The game involves multiple "subgames" with different equilibrium properties.10

### **When Incomplete Information Forces Bayesian Type Spaces**

* The "hidden type" of the opponent determines the entire payoff landscape (e.g., an auction or a sovereign debt crisis).6  
* Asymmetric information creates incentives for "signaling" or "screening".6

### **The "Second Rendering" Rule**

A serious analyst will deliberately re-represent a problem in a second form to test whether the first formalization has quietly erased something important.1 If a matrix shows a stable Nash equilibrium, drawing it as a tree might reveal it relies on an irrational subgame move. If a tree shows a unique path, collapsing it into a matrix might reveal a hidden coordination dilemma.16

## **Workflow for Strategic Formalization**

Formalization is an iterative process of problem-framing and refinement, not a one-way software checklist.21

1. **Identify the Strategic Question:** What is the specific behavior or outcome the model needs to explain or predict? 1  
2. **Determine the Actors:** Are they unitary or fractured? Who has the power to change the outcome? 7  
3. **Map the Actions and Timing:** Are moves simultaneous or sequential? Are choices discrete or continuous? 11  
4. **Map Observability and Uncertainty:** What do players know when they move? What uncertainty belongs to Nature and what to hidden types? 6  
5. **Choose the "Revealing" Representation:** Select the form (Matrix, Tree, Type Space) that highlights the load-bearing burden.1  
6. **The "Burden" Test:** Does the formalization preserve the real causal friction of the live case, or has it "flattened it into nonsense"? 1  
7. **Revise and Re-represent:** If the first model hides the core conflict, change the "camera angle" and restart.1

## **Representational Failure Modes: Recurring Pathologies**

A bad formalization feels dangerous because it creates an illusion of precision while erasing the game’s actual logic.43

* **Collapsing Sequence into a Matrix:** erases the distinction between credible threats and idle bluffs, leading to a failure to predict "subgame perfect" behavior.8  
* **Burying Institutions inside Payoffs:** loses sight of the *rules* under analysis, making it impossible to see how institutional change (e.g., a change in tax law) would shift the equilibrium.1  
* **Treating Type Uncertainty as Stochastic Risk:** fails to account for the "recursive reasoning" of opponents, turning a strategic game into a mindless gamble.6  
* **Overloading Nature:** occurs when an analyst uses Nature to "hide" everything they haven't formalized, effectively removing the *agency* from the model.1  
* **Brittle Pseudo-Precision:** introducing so much detail that the model becomes computationally intractable or interpretatively silent.4

## **Tractability vs. Fidelity: The Abstraction Trade-off**

Simplification is not a defect; it is a managed sacrifice.4 A "faithful" model that cannot be reasoned with is less useful than a "cleaner" one that preserves the right strategic burden.4

### **The Computational Constraint**

Finding a Nash equilibrium for complex games is "PPAD-complete," meaning that even for computers, finding the "right" answer can be impossible.6 If a model is too complex to be solved, its status as a prediction of human behavior—who must act in real-time—is compromised.3 This justifies the use of "Learning Dynamics" or "Multi-Agent Reinforcement Learning" (MARL) to see if agents can *discover* the equilibrium through trial and error, rather than assuming they "solve" for it instantly.3

### **The Pathology of Refinement**

In large extensive games like poker, "abstracting less" (making the model more detailed) does not always lead to a stronger strategy.19 Refining an abstraction can introduce new "pathologies" where the agent's strategy becomes *weaker* in the full game.37 The lesson is that precision is not a linear climb; it is a fit between the model's complexity and the agent's cognitive or computational limits.6

## **Anchor Cases for Strategic Perception**

Three canonical cases show how representation changes everything.

### **1. Entry-Deterrence: The Logic of Credibility**

* **Matrix Representation:** Shows two Nash equilibria: (Enter, Accommodate) and (Stay Out, Fight). Both look equally "rational".1  
* **Tree Representation:** Reveals that if the entrant actually moves, the incumbent's *best response* at that node is to accommodate. The threat to "Fight" is revealed as an idle threat.1  
* **Lesson:** Only the "camera angle" of the tree makes the logic of credibility visible.8

### **2. Spence’s Labor Market: The Logic of Signaling**

* **Matrix Representation:** Creates a "bloated" payoff table that obscures the *intent* of the workers.6  
* **Type-Space Representation:** Nature draws a "type" (Productivity). The worker observes it and chooses a "costly signal" (Education). The firm observes the signal and updates its beliefs.6  
* **Lesson:** Only the "type-space angle" allows the analyst to understand how private information is converted into a strategic signal.6

### **3. The "Double Bind" Game: The Logic of Pathological Communication**

* **Normal Form:** Collapses the conflicting frames into a simple "No-Win" payoff.46  
* **Bayesian Frame Representation:** Models the Receiver acting under uncertainty about the "operative frame" while the Sender possesses private info and penalizes meta-communication.46  
* **Lesson:** Representing the "frame uncertainty" as a type space reveals how the Receiver's beliefs can become "locked" into pathological states.46

## **Scope Conditions and Failure Conditions of the Framework**

### **Where Representation Illuminates Powerfully**

* **Structured Competition:** Markets, bidding, and adversarial planning where moves and observability are clear.1  
* **Institutional Design:** Engineering rules for auctions, carbon credits, or matching systems.1  
* **Strategic Diagnostics:** Reading hidden incentive traps (Nash Traps) in failing coordination environments.1

### **Where Representation Becomes Thin or Distorted**

* **Unstable Preferences:** Cases where trauma, social contagion, or identity shifts cause mid-game shifts in utility.1  
* **Radically Bounded Cognition:** Environments so noisy or computationally intractable that players cannot "solve" for best responses.1  
* **Endogenous Rule-Making:** Situations where the "rules of the game" are under constant revision by the players themselves, creating a meta-level fluidity that a static equilibrium analysis cannot capture.1

## **Downstream Dependencies**

This report establishes the representational and formal architecture for the remainder of the canon:

* **Report 4 (Sequential Strategy):** Will deepen the logic of the tree to explore "commitment" and the "shadow of the future."  
* **Report 7 (Mechanism Design):** Will use the engineering of type spaces and rules to "architect" outcomes.  
* **Report 11 (Strategic Failure):** Will use "representational failure modes" to diagnose why systems collapse.

This report does not yet cover the deep mechanics of "Bayesian updating," the "Folk Theorem" of repeated games, or the specific "Equilibrium Refinements" catalog (Trembling Hand, Divinity); those are reserved for the technical and dynamic modules of the series.

## **Synthesis: The Craft of Preserving Causal Burden**

Formal strategic representation is the analyst’s way of choosing the right "camera angle" under conditions of unavoidable loss.3 It is not an aesthetic wrapper or a clerical burden. It is the disciplined act of deciding what the game is, what structure must be preserved, and what simplifications can be survived.1

The deeper claim of this analysis is that strategic reality is not "found"—it is "formalized." A successful representation preserves the "causal burden" of the situation: it shows how incentives drive actions, how timing creates or destroys credibility, and how the informational "fog" supports or sabotages coordination.1 The expert analyst uses these tools not to produce "perfect" models, but to produce "useful fables"—the smallest possible formalizations that reveal the core logic of the game without lying about its structure.1 This is the craft of modelcraft: the place where strategic ontology becomes representational judgment, and where the invisible scaffolding of a conflict is finally made visible and actionable.

## **Compact Glossary of Canonical Terms**

* **Action:** A discrete choice available to a player at a specific decision point.1  
* **Assessment (sigma, mu):** A pair consisting of a strategy profile and a belief system.6  
* **Best Response:** The strategy that maximizes a player's utility given the strategies of others.1  
* **Common Knowledge:** A fact X is common knowledge if everyone knows X, everyone knows everyone knows X, and so on.1  
* **Information Set:** A collection of decision nodes that a player cannot distinguish between at the time they act.6  
* **Nature:** A pseudo-player that moves according to a fixed probability distribution to model exogenous uncertainty.6  
* **Strategy:** A comprehensive plan specifying an action for every possible information set in the game.1  
* **Type:** A formal packaging of a player's private information, capabilities, and belief hierarchies.6  
* **Unitary Actor:** An assumption that a collective entity makes decisions as if it were a single body.7

#### **Works cited**

1. Game Theory 1 - The Geometry of Strategic Conflict — An Ontology of Incentives, Interdependence, and Equilibrium  
2. The Epistemic Risk in Representation Forthcoming March 2022 - PhilSci-Archive, accessed April 18, 2026, [https://philsci-archive.pitt.edu/19680/1/The%20Epistemic%20Risk%20in%20Representation%20Forthcoming%20March%202022.pdf](https://philsci-archive.pitt.edu/19680/1/The%20Epistemic%20Risk%20in%20Representation%20Forthcoming%20March%202022.pdf)  
3. Effect of Camera Angle on Perception of Trust and Attractiveness - Uni Mainz, accessed April 18, 2026, [https://experimental.psychologie.uni-mainz.de/files/2024/06/2018BaranowskiHecht_Camera_Angle.pdf](https://experimental.psychologie.uni-mainz.de/files/2024/06/2018BaranowskiHecht_Camera_Angle.pdf)  
4. Game Theory and Economic Modelling - David M. Kreps - Google Books, accessed April 18, 2026, [https://books.google.com/books/about/Game_Theory_and_Economic_Modelling.html?id=qMoTDAAAQBAJ](https://books.google.com/books/about/Game_Theory_and_Economic_Modelling.html?id=qMoTDAAAQBAJ)  
5. Thoughts on Ariel Rubinstein saying Game Theory doesn't have practical application?, accessed April 18, 2026, [https://www.reddit.com/r/GAMETHEORY/comments/1904xyt/thoughts_on_ariel_rubinstein_saying_game_theory/](https://www.reddit.com/r/GAMETHEORY/comments/1904xyt/thoughts_on_ariel_rubinstein_saying_game_theory/)  
6. Game Theory 2 - Equilibrium and Information — Stability, Beliefs, and Strategic Knowledge Systems  
7. 4 negotiating land and property development: a game theoretical approach to value capturing - Radboud Repository, accessed April 18, 2026, [https://repository.ubn.ru.nl/bitstream/handle/2066/111736/111736.pdf](https://repository.ubn.ru.nl/bitstream/handle/2066/111736/111736.pdf)  
8. Game Theory | Internet Encyclopedia of Philosophy, accessed April 18, 2026, [https://iep.utm.edu/game-th/](https://iep.utm.edu/game-th/)  
9. Game Theory - Stanford Encyclopedia of Philosophy, accessed April 18, 2026, [https://plato.stanford.edu/entries/game-theory/](https://plato.stanford.edu/entries/game-theory/)  
10. Advanced Game Theory, accessed April 18, 2026, [https://www.selcukozyurt.com/home/teaching/advanced-game-theory](https://www.selcukozyurt.com/home/teaching/advanced-game-theory)  
11. Normal-form game - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Normal-form_game](https://en.wikipedia.org/wiki/Normal-form_game)  
12. Strategic Form Games - Game Theory - Indian Institute of Science, accessed April 18, 2026, [https://gtl.csa.iisc.ac.in/gametheory/ln/web-ncp3-sfg.pdf](https://gtl.csa.iisc.ac.in/gametheory/ln/web-ncp3-sfg.pdf)  
13. Game theory - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Game_theory](https://en.wikipedia.org/wiki/Game_theory)  
14. UBC ISCI 344 Game Theory - Extensive and normal form, accessed April 18, 2026, [https://www.cs.ubc.ca/~rikblok/teaching/past/isci344/02%20Extensive%20and%20normal%20form%20games.pdf](https://www.cs.ubc.ca/~rikblok/teaching/past/isci344/02%20Extensive%20and%20normal%20form%20games.pdf)  
15. Extensive-form game - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Extensive-form_game](https://en.wikipedia.org/wiki/Extensive-form_game)  
16. When Normal and Extensive Form Decisions Differ - Carnegie Mellon University, accessed April 18, 2026, [https://www.cmu.edu/dietrich/philosophy/docs/seidenfeld/When%20Normal%20and%20Extensive%20Form%20Decisions%20Differ.pdf](https://www.cmu.edu/dietrich/philosophy/docs/seidenfeld/When%20Normal%20and%20Extensive%20Form%20Decisions%20Differ.pdf)  
17. Ariel Rubinstein - Wikipedia, accessed April 18, 2026, [https://en.wikipedia.org/wiki/Ariel_Rubinstein](https://en.wikipedia.org/wiki/Ariel_Rubinstein)  
18. When Identity Overrides Incentives: Representational Choices as Governance Decisions in Multi-Agent LLM Systems - arXiv, accessed April 18, 2026, [https://arxiv.org/html/2601.10102v3](https://arxiv.org/html/2601.10102v3)  
19. Abstraction Pathologies in Extensive Games - Computer Poker Research Group, accessed April 18, 2026, [https://poker.cs.ualberta.ca/publications/AAMAS09-abstraction.pdf](https://poker.cs.ualberta.ca/publications/AAMAS09-abstraction.pdf)  
20. An Introduction to Counterfactual Regret Minimization - Model AI Assignments, accessed April 18, 2026, [https://modelai.gettysburg.edu/2013/cfr/cfr.pdf](https://modelai.gettysburg.edu/2013/cfr/cfr.pdf)  
21. Reprise: A Design Tool for Specifying, Generating, and Customizing 3D Printable Adaptations on Everyday Objects, accessed April 18, 2026, [https://hcied.info/papers/reprise-UIST16.pdf](https://hcied.info/papers/reprise-UIST16.pdf)  
22. ISO/IEC 5259 Artificial intelligence —Data quality for analytics and machine learning (ML) - Management Solutions, accessed April 18, 2026, [https://www.managementsolutions.com/sites/default/files/publicaciones/eng/iso-iec-5259-artificial-intelligence.pdf](https://www.managementsolutions.com/sites/default/files/publicaciones/eng/iso-iec-5259-artificial-intelligence.pdf)  
23. Stochastic Target Games with Controlled Loss - Columbia Math Department, accessed April 18, 2026, [https://www.math.columbia.edu/~mnutz/docs/BMN.pdf](https://www.math.columbia.edu/~mnutz/docs/BMN.pdf)  
24. Stochastic target games with controlled loss - Project Euclid, accessed April 18, 2026, [https://projecteuclid.org/journals/annals-of-applied-probability/volume-24/issue-3/Stochastic-target-games-with-controlled-loss/10.1214/13-AAP938.pdf](https://projecteuclid.org/journals/annals-of-applied-probability/volume-24/issue-3/Stochastic-target-games-with-controlled-loss/10.1214/13-AAP938.pdf)  
25. Designing Fear: Voluntary Control of Involuntary Inputs in Horror Games - DiVA portal, accessed April 18, 2026, [https://www.diva-portal.org/smash/get/diva2:1976389/FULLTEXT01.pdf](https://www.diva-portal.org/smash/get/diva2:1976389/FULLTEXT01.pdf)  
26. of Power - States and Strategies in International Politics - Branislav L. Slantchev (UCSD), accessed April 18, 2026, [http://slantchev.ucsd.edu/courses/pdf/Powell%20-%20States%20and%20Strategies.pdf](http://slantchev.ucsd.edu/courses/pdf/Powell%20-%20States%20and%20Strategies.pdf)  
27. Negotiating land and property development: a game theoretical approach to value capturing, accessed April 18, 2026, [https://www.emerald.com/insight/content/doi/10.1108/17539261211216003/full/html](https://www.emerald.com/insight/content/doi/10.1108/17539261211216003/full/html)  
28. Revisiting the Unitary Actor Assumption: Toward Realistic Aggregation of Individual Preferences in Strategy Research - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/403130022_Revisiting_the_Unitary_Actor_Assumption_Toward_Realistic_Aggregation_of_Individual_Preferences_in_Strategy_Research](https://www.researchgate.net/publication/403130022_Revisiting_the_Unitary_Actor_Assumption_Toward_Realistic_Aggregation_of_Individual_Preferences_in_Strategy_Research)  
29. (PDF) Formalization of multi-level games - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/263869528_Formalization_of_multi-level_games](https://www.researchgate.net/publication/263869528_Formalization_of_multi-level_games)  
30. Autoformalization of Game Descriptions using Large Language Models - arXiv, accessed April 18, 2026, [https://arxiv.org/html/2409.12300v1](https://arxiv.org/html/2409.12300v1)  
31. Continuous dynamics of cooperation and competition in social decision-making - bioRxiv, accessed April 18, 2026, [https://www.biorxiv.org/content/10.1101/2025.05.28.655569v2.full.pdf](https://www.biorxiv.org/content/10.1101/2025.05.28.655569v2.full.pdf)  
32. Mixed Strategy Constraints in Continuous Games - arXiv, accessed April 18, 2026, [https://arxiv.org/html/2402.17874v2](https://arxiv.org/html/2402.17874v2)  
33. Electronic Life Histories: At Home with E-waste Waste Materialities and Meaning, accessed April 18, 2026, [https://www.whp-journals.co.uk/WW/article/view/1038/581](https://www.whp-journals.co.uk/WW/article/view/1038/581)  
34. Alexandra Alvergne Crispin Jenkinson Charlotte Faurie Editors - National Academic Digital Library of Ethiopia, accessed April 18, 2026, [http://ndl.ethernet.edu.et/bitstream/123456789/88639/1/2016_Book_EvolutionaryThinkingInMedicine.pdf](http://ndl.ethernet.edu.et/bitstream/123456789/88639/1/2016_Book_EvolutionaryThinkingInMedicine.pdf)  
35. Subject Student Teachers' Perceptions of Key Environmental Problems and Their Own Role as Environmental Problem Solvers - MDPI, accessed April 18, 2026, [https://www.mdpi.com/2227-7102/13/8/779](https://www.mdpi.com/2227-7102/13/8/779)  
36. Date Everything! and our Parasocial Relationships with Things - Nicolle Lamerichs, accessed April 18, 2026, [https://nicollelamerichs.com/2025/07/06/date-everything-and-our-parasocial-relationships-with-things/](https://nicollelamerichs.com/2025/07/06/date-everything-and-our-parasocial-relationships-with-things/)  
37. Abstraction Pathologies in Extensive Games - Department of Computing Science, accessed April 18, 2026, [https://webdocs.cs.ualberta.ca/~bowling/papers/09aamas-abstraction.pdf](https://webdocs.cs.ualberta.ca/~bowling/papers/09aamas-abstraction.pdf)  
38. CHAPTER 5 - A sequential strategic theory of bargaining - Ariel Rubinstein, accessed April 18, 2026, [https://arielrubinstein.tau.ac.il/papers/25.pdf](https://arielrubinstein.tau.ac.il/papers/25.pdf)  
39. Game Theory and Economic Modelling - David M. Kreps - Oxford ..., accessed April 18, 2026, [https://global.oup.com/academic/product/game-theory-and-economic-modelling-9780198283812](https://global.oup.com/academic/product/game-theory-and-economic-modelling-9780198283812)  
40. Game Theory (Stanford Encyclopedia of Philosophy/Fall 2025 Edition), accessed April 18, 2026, [https://plato.stanford.edu/archives/fall2025/entries/game-theory/](https://plato.stanford.edu/archives/fall2025/entries/game-theory/)  
41. Untitled - Kellogg School of Management - Northwestern University, accessed April 18, 2026, [https://www.kellogg.northwestern.edu/research/math/papers/1041.pdf](https://www.kellogg.northwestern.edu/research/math/papers/1041.pdf)  
42. Computational Support for Sketching in Design: A Review - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/220613481_Computational_Support_for_Sketching_in_Design_A_Review](https://www.researchgate.net/publication/220613481_Computational_Support_for_Sketching_in_Design_A_Review)  
43. Wargame Pathologies, accessed April 18, 2026, [https://www.professionalwargaming.co.uk/WargamePathologies.pdf](https://www.professionalwargaming.co.uk/WargamePathologies.pdf)  
44. Why We Stay Stuck: A Complex Conceptual Systems Theory for Wicked Problems - MDPI, accessed April 18, 2026, [https://www.mdpi.com/2079-8954/14/4/431](https://www.mdpi.com/2079-8954/14/4/431)  
45. Game Theory and Economic Modelling | Stanford Graduate School of Business, accessed April 18, 2026, [https://www.gsb.stanford.edu/faculty-research/books/game-theory-economic-modelling](https://www.gsb.stanford.edu/faculty-research/books/game-theory-economic-modelling)  
46. The Bateson Game: A Model of Strategic Ambiguity, Frame Uncertainty, and Pathological Learning - MDPI, accessed April 18, 2026, [https://www.mdpi.com/2073-4336/16/6/57](https://www.mdpi.com/2073-4336/16/6/57)  
47. De-framing video games from the light of cinema « G|A|M, accessed April 18, 2026, [https://www.gamejournal.it/arsenault_perron_deframing/](https://www.gamejournal.it/arsenault_perron_deframing/)  
48. (PDF) Multi-Value Decision-Making and Games: The Perspective of Generalized Game Theory on Social and Psychological Complexity, Contradiction, and Equilibrium - ResearchGate, accessed April 18, 2026, [https://www.researchgate.net/publication/242177189_Multi-Value_Decision-Making_and_Games_The_Perspective_of_Generalized_Game_Theory_on_Social_and_Psychological_Complexity_Contradiction_and_Equilibrium](https://www.researchgate.net/publication/242177189_Multi-Value_Decision-Making_and_Games_The_Perspective_of_Generalized_Game_Theory_on_Social_and_Psychological_Complexity_Contradiction_and_Equilibrium)  
49. What you see is what you get: webcam placement influences perception and social coordination - Frontiers, accessed April 18, 2026, [https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2015.00306/full](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2015.00306/full)

---