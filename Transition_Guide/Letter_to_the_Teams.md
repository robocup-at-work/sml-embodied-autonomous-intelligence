# Letter to the Teams

## Embracing the Challenge

We are aware that the structural changes introduced with the Smart Manufacturing League (SML) will require teams to adapt their robots and software stacks.
As with any major transition, this may temporarily affect competitiveness, especially for established systems.
At the same time, the vast majority of required core skills remain familiar to the RoboCup Industrial community:
localization, navigation, manipulation, planning, and coordination and robust hardware control.

We therefore encourage teams to approach the upcoming seasons with confidence and curiosity.
The SML is designed to evolve existing strengths into a new, exciting benchmark that bridges real-world industrial demands, current research objectives, and an engaging competition format.
We are excited to shape this next chapter of RoboCup Industrial together with the community, advancing robotic research for Industry 5.0 and beyond.

## Playful Analogies

To illustrate the core idea of the proposed *Embodied-Autonomous-Intelligence-Workshop (EAI-WS)* format, the cooperative game **Overcooked** serves as a useful analogy.
In the *EAI-WS*, robotic agents take the role of the cooks: retrieving materials from storage, performing processing and assembly steps, and delivering finished products to customers.
Recognizable products composed of clearly distinguishable raw materials allow task requirements and action sequences to become intuitive at a glance.
This results in a competition format that is easy to understand for spectators, yet challenging to master, while retaining scientific depth across perception, manipulation, planning, and coordination.

## Retaining Legacy

By explicitly supporting both ground-level systems from RoboCup@Work and human-level platforms from the former RCLL, teams may continue to use their existing robots with limited hardware changes.
In many cases, only software adaptations will be required.
Elevation structures for static workbench setups enable collaboration across operating heights and encourage novel hardware concepts.
Humanoid robots, while not yet mature enough to consistently outperform specialized systems, are included as an optional platform.
This allows teams to explore their potential early and benchmark them against established solutions under identical task conditions.

## Polymer Bricks and Toy Products

One of the most visible technical changes is the introduction of colored polymer bricks as standardized target objects.
This requires new perception pipelines for most teams; however, given recent advances in AI-based vision methods, this is considered a reasonable and future-oriented adaptation.
We encourage the use of synthetic data generation, 6-DoF pose estimation networks, and publicly available CAD models, for example via tools such as BlenderProc.
Open-source releases and shared datasets may further accelerate knowledge exchange and collective progress across the league.

At the same time, the use of standardized lightweight objects simplifies manipulation compared to previous industrial parts with large variability in size, weight, and material.
This ensures that most existing manipulators remain viable, particularly in the early seasons.
Standardized components also improve global availability, reduce cost, and enable a wide range of product combinations, supporting the vision of adaptive on-demand manufacturing.
Future challenges may gradually introduce more realistic components (e.g., wheels, drivetrains) or tools (e.g., drills, screwdrivers), seamlessly extending the workbench tasks.

## Advancing high-dexterity Manipulation

The workbench track introduces a new focus area: precise object handling and assembly.
These tasks reflect key challenges in modern production environments and remain difficult for current robotic systems.
To ensure broad participation, multiple strategies are supported.
Human--Robot Interaction (HRI) may be used to compensate for missing manipulation capabilities, reflecting common industrial practice where robots supply parts and humans perform fine assembly.
In addition, partnerships across teams and tracks allow groups to combine complementary strengths, enabling higher levels of autonomy than individual teams might achieve alone.
This structure encourages collaboration, international exchange, and long-term research progress.

## Giving planners a home

Planning has always been a central element of RoboCup Industrial.
However, differences in hardware capabilities and execution reliability have often limited the practical impact of optimized plans.
To address this, the EAI-WS introduces a simulation-based planning benchmark that allows fair comparison of planning strategies on a common baseline, independent of physical hardware.
Fleet size, arena complexity, and task load can be scaled without additional cost.
Until a shared simulation environment is finalized, planning evaluation may remain limited in early events.
We explicitly invite teams to contribute to its development, as even simple 2D environments can already enable meaningful benchmarking.

Ultimately, planning solutions are expected to interface with real robots.
Community-driven communication standards and collaboration interfaces will therefore play a key role in future seasons.
Teams with existing systems may continue to use their custom interfaces during the transition phase.

## Skill-based Track Designs

The new track structure and scoring system are designed to reward both specialization and complete system autonomy.
By introducing multiple tiers with gradually increasing complexity, the SML welcomes participants at all career stages.
Beginner teams can learn in controlled environments, while advanced teams are challenged with large-scale coordination and throughput optimization.
RoboCup thrives on its community, and the SML aims to remain open, inclusive, and ambitious in this spirit.

## Explore the new league

The 2026 season will serve as a transition phase.
Warehouse and planning capabilities from existing @Work and RCLL systems are expected to perform well, while workbench tasks may initially rely more heavily on HRI and partnerships.
The expert tier will be treated as a technical challenge in early events, focusing on exploration rather than strict ranking.
We strongly encourage teams to form collaborations and contribute to shared interfaces and benchmarks.
Such collective efforts are essential for realizing interconnected autonomous factories and preparing individual robotic agents to operate as part of larger, intelligent fleets.
