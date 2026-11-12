# COLLECTIVE
## Can We Build Artificial Intelligence from Programmable Living Units?
**Bridging Biological Computation, Molecular Manufacturing, and Emergent Collective Intelligence**

> **Status: Early-stage speculative research proposal — not an implemented system.** We seek critical interdisciplinary feedback, not confirmation of a predetermined outcome.

### The question
Could an ensemble of programmable biological or biohybrid units, each able to sense, compute, communicate, learn, and potentially manufacture molecular structures, develop forms of **organically embodied artificial intelligence** through learned cooperation?

COLLECTIVE asks two distinct questions:
1. **Engineering:** Which interfaces can current science realistically provide to integrate computation, molecular manufacturing, and learned cooperation within programmable biological units?
2. **Science:** Under what measurable conditions, if any, does a network of such units develop collective capabilities beyond its individual components and prescribed programs?

A successful outcome is **not assumed**. A negative feasibility result, or a useful distributed biohybrid computer without emergent intelligence, would also be informative.

### Proposed architecture (conceptual, not demonstrated)
A unit is envisioned as a cell-like, potentially compartmentalized biohybrid module. Its initial size is deliberately unconstrained (even coin-sized) to separate functional design from miniaturization.

- **Addressable DNA-based archive:** indexed storage for data and encoded instructions, hypothetically read through a molecular/electronic interface.
- **Processor and working memory:** an instruction set and boot logic that can retrieve an encoded routine (for example, FFT), load it into RAM, and execute it.
- **Sensing and feedback:** optical, chemical, electrochemical, mechanical, and environmental measurements (including pH), with calibration and uncertainty estimates.
- **Communication:** a predefined serial interface and common protocol for exchanging tasks, measurements, and results across heterogeneous units.
- **Metabolism and maintenance:** an explicitly provided source of usable chemical energy, precursors, transport, repair, and waste management.
- **Molecular manufacturing:** a hypothetical processor-directed interface capable of specifying and physically producing molecular products, potentially extending beyond conventional ribosomal capabilities. This is a major unsolved subsystem, **not** a conventional electronic output port.

DNA is not assumed to function as a fast random-access hard drive today. Address resolution, access latency, error correction, preservation, transcription/translation alternatives, and physical integration are open research problems. Likewise, storing executable code in DNA requires a deliberately specified encoding, interpreter/ISA, and readout system.

### Collective behavior and learning
Units may have different sensor and computation specializations. They can partition a problem, request calculations from peers, compare measurements, and adapt relationships based on feedback. Their physical topology and hierarchy are **not prescribed**; whether specialization or hierarchy emerges is an observation target.

We propose exploring both individual scores and collective reward, with attention to correctness, speed, computational contribution, and resource efficiency. **An unresolved incentive-design problem:** rewarding raw compute expenditure can encourage wasteful work; rewarding only efficiency can undervalue difficult but essential work. Controlled simulations should compare reward functions and identify gaming, free-riding, and distorted credit assignment.

No explicit objective such as “grow an organ,” “move,” “add hardware,” or “self-replicate” is supplied. The open hypothesis is whether units with suitable *general physical capabilities* could discover new subgoals or useful structures. We must distinguish genuinely novel designs from retrieval of preloaded instructions and from behavior already entailed by an optimizer.

### Example test domain: reactive oxygen species
As a conceptual challenge, units might detect and reason about reactive oxygen species (ROS), **not ordinary molecular oxygen O₂**, using multiple sensors and biochemical feedback. Any candidate intervention must be assessed for both target reduction and potentially harmful reaction products. A harmful measured outcome earns negative feedback and triggers an **independent** production stop. Delayed, unmeasured, or unexpected toxicity remains a key safety limitation. This is an illustration of feedback logic, **not a wet-lab protocol or validated therapy**.

Other challenges can be purely computational, such as signal processing or decomposed mathematical problems, to isolate cooperation from biochemical manufacturing.

### What exists, and what does not
Existing research on DNA data storage, biosensors, bioelectronics, synthetic gene circuits, molecular machinery, distributed learning, and biohybrid systems provides *partial analogies*. None is presented here as proof that the integrated COLLECTIVE architecture is feasible. Particularly speculative components include fast addressable DNA-to-processor access, general processor-controlled molecular synthesis, robust metabolism at the proposed scale, and autonomous discovery of new physical capabilities.

### First falsifiable milestones
1. **Digital baseline:** simulate heterogeneous agents, bounded compute/energy, shared bus, local memory, reward rules, and measurable coordination. Compare against centralized and non-learning baselines.
2. **Interface feasibility review:** independently assess DNA indexing/readout, sensor-electronics coupling, molecular manufacturing, and energy/material budgets; quantify bottlenecks.
3. **Restricted modular prototypes:** only where independently justified and within institutional biosafety oversight, demonstrate one interface at a time rather than attempting an integrated living system immediately.
4. **Emergence tests:** use held-out tasks, ablations, preloaded-knowledge audits, resource accounting, and reproducible controls to distinguish learning, optimization, and genuine novel capability.

### Open invitation
We welcome **skeptical and constructive** contributions from synthetic biology, biochemistry, molecular electronics, microbiology, computer architecture, distributed systems, artificial life, control theory, materials science, bioethics, and database engineering.

Please start a GitHub Issue with: (a) the subsystem or claim, (b) what is already demonstrated in peer-reviewed work, (c) the principal obstacle, and (d) a safe, measurable test or counterexample. See [research questions](docs/RESEARCH_QUESTIONS.md) and [collaboration guide](CONTRIBUTING.md).

**This repository is a proposal and discussion space.** It contains no validated experimental procedure, organism design, working biological device, or claim of artificial general intelligence.
