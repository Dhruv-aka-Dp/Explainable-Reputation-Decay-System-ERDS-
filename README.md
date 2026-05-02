Reputation systems play a foundational role in enabling trust across digital platforms, from e-
commerce marketplaces and knowledge-sharing communities to decentralised applications.
Despite their prevalence, most existing systems treat trust as a static or endlessly accumulating
metric, one that fails to reflect the temporal nature of real-world trustworthiness. A user who has
been inactive for months may still carry a high score built on historical interactions, creating a
misleading impression of current reliability.
A second and equally important limitation is the near-total absence of explainability. Users observe
that their scores change, but the system rarely, if ever, tells them why. In blockchain-based
implementations, this gap is particularly jarring: the entire premise of a distributed ledger is
transparency, yet the reasoning behind state changes remains opaque.
This project proposes an Explainable Reputation Decay System implemented using blockchain
smart contracts. The system introduces a deterministic reputation model in which reputation values
evolve based on two factors → interaction based updates and time based decay. The decay
mechanism reflects the real-life scenario that trustworthiness should diminish if a participant
remains inactive for extended periods. To improve transparency, the system also incorporates an
explainability layer. Each reputation update generates a structured explanation describing the cause
of the change.
