# Hilbert Space as Frame-Neighborhood State Space in Frames Theory

William J. House

## Abstract

Quantum mechanics represents physical systems by states in Hilbert spaces. In standard presentations, this is often treated as if there were a single universal Hilbert space whose state is primary, with observers and measurements appearing later as special subsystems or update rules. Frames Theory reverses the emphasis. It begins with bounded informational frames, their accessible neighborhoods, their admissible observables, and their record structures. From this point of view, a Hilbert space is not identical to a frame neighborhood. Rather, it is the quantum state space representable within, or relative to, a frame neighborhood. The neighborhood supplies the relational and causal domain: which frames are accessible, which channels connect them, which degrees of freedom can be bound, and which records can be reconciled. The Hilbert space supplies the formal quantum representation of possible states, superpositions, amplitudes, observables, and outcome bases available in that domain.

This paper develops the idea of Hilbert space as frame-neighborhood state space. It distinguishes neighborhoods from state spaces, relates accessible degrees of freedom to tensor-product decompositions, interprets observable algebras as admissibility structures, and clarifies how projection, partial trace, decoherence, and Wigner's Friend appear when Hilbert spaces are indexed to frames. The central claim is not that ordinary Hilbert-space quantum mechanics is wrong, but that its ontology should be made frame-relative: different frames may legitimately use different Hilbert representations or different decompositions of a larger representation, provided their descriptions reconcile over shared informational neighborhoods.

## 1. Introduction

Frames Theory treats physical description as situated within bounded informational contexts. A frame is not merely a viewpoint in a psychological sense. It is a physical system or domain capable of receiving, storing, transforming, constraining, or propagating information. A detector, apparatus, laboratory, organism, notebook, environment, black hole exterior, or cosmological causal patch may all function as frames when their informational boundaries matter.

Earlier papers in this sequence developed the basic frame ontology, the Born rule as a frame-binding measure, frame-relative state update, redundant objectivity, entanglement without superluminal signaling, causal information boundaries, records, and aspect-selective binding. These papers all used standard quantum structures when needed: state vectors, density matrices, projectors, partial traces, tensor products, and decoherence. But they left partly implicit a foundational question:

> What is the status of Hilbert space itself in Frames Theory?

In standard quantum mechanics, one begins with a Hilbert space $\mathcal{H}$. Pure states are vectors or rays in $\mathcal{H}$, mixed states are density operators on $\mathcal{H}$, and observables are represented by operators acting on $\mathcal{H}$. Composite systems are represented by tensor products, and measurement updates are represented by projection or more general quantum operations.

Frames Theory does not reject this formalism. The question is how to interpret it. Is there one universal Hilbert space whose state is the primary object of reality? Or are Hilbert spaces formal state spaces associated with bounded domains of accessibility, interaction, and record formation?

This paper takes the second route. A Hilbert space is best understood as a representation space associated with a frame or frame neighborhood. A frame neighborhood determines what can be accessed, coupled to, bound, measured, or reconciled. The associated Hilbert space represents the possible quantum states and observables available within that domain.

The central thesis is:

> A Hilbert space is the formal quantum state space associated with a frame neighborhood, not the neighborhood itself.

This distinction is small but important. A frame neighborhood is relational, causal, and informational. It consists of frames, channels, constraints, records, and accessibility relations. A Hilbert space is representational and algebraic. It encodes possible quantum states, amplitudes, superpositions, measurement bases, and operators relative to that accessible domain.

The payoff is a cleaner interpretation of frame-relative quantum description. Different frames may assign different Hilbert spaces, different factorizations, or different effective states without contradiction, as long as these descriptions are connected by restriction, embedding, conditioning, or reconciliation maps where their domains overlap.

## 2. Frame Neighborhoods

In the first Frames Theory paper, a frame was written schematically as

$$
F_i=(\rho_i,N_i,C_i),
$$

where $\rho_i$ is the informational state of the frame, $N_i$ is its accessible neighborhood, and $C_i$ is the set of constraints governing admissible relations. Later papers added records, causal domains, and type profiles where needed.

For the present paper, it is useful to make the neighborhood structure explicit. Define a frame neighborhood centered on $F_i$ as

$$
\mathcal{N}_i=(F_i,\mathrm{Acc}_i,E_i,C_i,R_i,\mathcal{D}_i),
$$

where:

- $F_i$ is the central or reference frame.
- $\mathrm{Acc}_i$ is the set of frames, degrees of freedom, and records accessible to $F_i$.
- $E_i$ is the set of information-transfer channels available within the neighborhood.
- $C_i$ is the set of admissibility and consistency constraints.
- $R_i$ is the record structure available to the frame.
- $\mathcal{D}_i$ is the causal domain supporting the neighborhood, when relativistic structure matters.

This definition is intentionally broad. In a simple nonrelativistic laboratory model, $\mathcal{D}_i$ may be suppressed. In a relativistic or cosmological model, it becomes essential. In a quantum measurement model, $\mathrm{Acc}_i$ may include only a system and apparatus. In a larger objectivity model, it may include environmental records, observers, notebooks, and databases.

A neighborhood is not simply a spatial region. It is an accessibility structure. Two systems may be nearby in coordinate space but informationally isolated by shielding, decoherence, horizon structure, or incompatible coupling channels. Conversely, two records may be spatially separated but informationally connected by reliable causal channels.

Thus, a frame neighborhood is best understood as the local domain over which a frame can form, use, or reconcile state descriptions.

## 3. Hilbert Space Associated With a Neighborhood

Given a frame neighborhood $\mathcal{N}_i$, define the associated Hilbert space as

$$
\mathcal{H}_i = \mathcal{H}(\mathcal{N}_i).
$$

This notation means that $\mathcal{H}_i$ is the quantum state space generated by the degrees of freedom accessible within $\mathcal{N}_i$, subject to the admissibility constraints of that neighborhood.

Equivalently,

$$
\mathcal{H}_i = \text{the Hilbert space of possible quantum states representable from frame }F_i.
$$

For a neighborhood $\mathcal{N}$ not centered on a single frame, one may write

$$
\mathcal{H}_{\mathcal{N}} = \text{the Hilbert space generated by the degrees of freedom accessible in }\mathcal{N}.
$$

The important point is that $\mathcal{H}_i$ is not the same object as $\mathcal{N}_i$. The neighborhood contains frames, edges, causal relations, records, and constraints. The Hilbert space is the formal quantum state space used to represent possible states within that neighborhood.

For example, a simple detector frame with access to a spin-\(1/2\) system may use

$$
\mathcal{H}_{\mathrm{detector}}=\mathrm{span}\{|\uparrow\rangle,|\downarrow\rangle\}.
$$

If the detector is embedded in an apparatus and local environment, the relevant neighborhood may support a larger representation:

$$
\mathcal{H}_{\mathrm{neighborhood}}=\mathcal{H}_{\mathrm{spin}}
\otimes
\mathcal{H}_{\mathrm{detector}}
\otimes
\mathcal{H}_{\mathrm{apparatus}}
\otimes
\mathcal{H}_{\mathrm{environment}}.
$$

Frames Theory does not deny that larger tensor products can be written. It denies that every such tensor product is automatically the physically primary state space for every frame. A Hilbert space becomes physically meaningful relative to a frame when its degrees of freedom are accessible, dynamically relevant, or capable of entering records for that frame.

## 4. Neighborhoods Are Access Domains, Not State Spaces

The distinction between a neighborhood and its Hilbert representation can be summarized as follows:

$$
\text{frame neighborhood}=\text{accessible relational domain},
$$

while

$$
\text{Hilbert space}=\text{quantum state space representable over that domain}.
$$

The neighborhood answers questions such as:

- Which frames can exchange information?
- Which channels are available?
- Which records can be accessed?
- Which degrees of freedom are causally or operationally reachable?
- Which constraints govern admissible binding?

The Hilbert space answers questions such as:

- Which quantum states can be represented?
- Which observables can be defined?
- Which superpositions are meaningful?
- Which outcome bases are available?
- Which amplitudes and density operators describe the accessible system?

Confusing these two levels leads to ontological mistakes. If the Hilbert space is treated as the neighborhood itself, then the relational, causal, and record-based structure of Frames Theory disappears into an abstract state space. If the neighborhood is treated as enough by itself, then the specifically quantum structure of amplitudes, inner products, operators, and noncommuting observables is lost.

The right relation is association, not identity:

$$
\mathcal{N}_i \mapsto \mathcal{H}_i.
$$

A neighborhood supports a Hilbert representation. The representation depends on what the neighborhood makes accessible.

This gives Frames Theory a natural way to use ordinary quantum mechanics while avoiding a prematurely global ontology. One may write a Hilbert space for the domain under study, but the physical meaning of that space is indexed to the frame-neighborhood that supports it.

## 5. Admissible Observables and Operator Algebras

A Hilbert space alone does not determine what a frame can actually observe or bind. A formal state space may contain many possible operators, but a physical frame has access only to observables compatible with its couplings, records, and constraints.

For a frame neighborhood $\mathcal{N}_i$, let

$$
\mathcal{O}_i
$$

be the set or algebra of admissible observables available to $F_i$. Then a more precise frame-neighborhood representation is

$$
\mathfrak{Q}_i=(\mathcal{H}_i,\mathcal{O}_i,\rho_i,C_i,R_i),
$$

where:

- $\mathcal{H}_i$ is the associated Hilbert space.
- $\mathcal{O}_i$ is the admissible observable algebra.
- $\rho_i$ is the frame-relative quantum state.
- $C_i$ is the set of compatibility and consistency constraints.
- $R_i$ is the record structure available to the frame.

This formulation connects directly to aspect-selective frame-binding. Exposure to a degree of freedom is not enough. A frame must have admissible observables through which the relevant distinction can be registered.

For an observable $A$ to be physically available to $F_i$, one may require schematically that

$$
A\in\mathcal{O}_i
\quad\text{only if}\quad
A\text{ is supported by couplings, records, and constraints in }\mathcal{N}_i.
$$

In more algebraic language, different frames may have different subalgebras of a larger operator algebra. A broader frame may have access to correlations represented by operators on a composite space, while a local frame may have access only to operators acting on a restricted subsystem.

This matters for measurement. A frame does not bind to every formal distinction in $\mathcal{H}_i$. It binds to distinctions represented by admissible observables that its structure can couple to and stabilize.

Thus, in Frames Theory, the observable algebra is the bridge between formal Hilbert space and physical frame capacity.

## 6. Tensor Products, Containment, and Decomposition

Composite quantum systems are represented by tensor products. If frames $A$ and $B$ are jointly accessible within a neighborhood, then a composite representation may take the form

$$
\mathcal{H}_{AB}=\mathcal{H}_A\otimes\mathcal{H}_B.
$$

In ordinary quantum mechanics this is standard. Frames Theory adds a question:

> Relative to which frame neighborhood is this decomposition meaningful?

A tensor-product decomposition is not merely a mathematical convenience. It reflects a choice of subsystem structure, accessibility, and interaction. A detector may decompose a situation into system and apparatus. A broader laboratory frame may decompose it into particle, detector, apparatus, observer, and environment. Another frame may treat the entire laboratory as one coherent composite system.

If $F_i$ is contained in or embedded within $F_j$, written

$$
F_i\preceq F_j,
$$

then the Hilbert representation associated with $F_i$ may be related to that of $F_j$ by embedding, tensor extension, restriction, or coarse-graining. Schematically,

$$
\mathcal{H}_i
\longrightarrow
\mathcal{H}_j
$$

when the containing frame includes the degrees of freedom of the contained frame together with additional accessible structure.

But containment is not always simple. Frames may overlap without one fully containing the other. In such cases, their Hilbert spaces may share a common subrepresentation:

$$
\mathcal{H}_{i\cap j}
\subseteq
\mathcal{H}_i,
\mathcal{H}_j.
$$

The consistency problem is then to reconcile descriptions over the shared informational domain. If two frames assign states $\rho_i$ and $\rho_j$, their restrictions to the overlap should be compatible where the frames have access to the same records or observables.

This is the Hilbert-space version of the general Frames Theory consistency functional:

$$
\mathcal{K}(i,j)=\exp\left(-D(\rho_i^{\Omega},\rho_j^{\Omega})\right),
$$

where $\Omega$ is the shared informational neighborhood and $D$ is an appropriate information distance.

## 7. Projection, Partial Trace, and Frame-Relative State Spaces

The third Frames Theory paper interpreted projection, partial trace, and decoherence as frame-relative state-update operations. The present paper clarifies the Hilbert-space background for that claim.

A projection update such as

$$
\rho^{\mathrm{post}}=\frac{P_k\rho P_k}{\mathrm{Tr}(P_k\rho)}
$$

is not an update to all Hilbert-space descriptions everywhere. It is an update within the Hilbert representation available to a frame that has bound to outcome $k$. More explicitly,

$$
\rho_i^{\mathrm{post}}=\frac{P_{i,k}\rho_iP_{i,k}}{\mathrm{Tr}(P_{i,k}\rho_i)},
$$

where $P_{i,k}\in\mathcal{O}_i$ is an admissible projector for frame $F_i$.

The condition $P_{i,k}\in\mathcal{O}_i$ matters. A formal projector may exist in some larger Hilbert space, but if the receiving frame cannot couple to, resolve, or stabilize the associated distinction, then it is not an available measurement outcome for that frame.

Similarly, partial trace is the operation by which a frame restricts a broader Hilbert representation to accessible degrees of freedom. If a broader frame uses

$$
\rho_{SE}\quad\text{on}\quad\mathcal{H}_S\otimes\mathcal{H}_E,
$$

then a frame with access only to $S$ uses

$$
\rho_S=\mathrm{Tr}_E(\rho_{SE}).
$$

Frames Theory reads this as:

> The reduced state is the state available in the Hilbert space associated with the smaller frame neighborhood.

The trace operation is therefore a map between frame-neighborhood state spaces:

$$
\mathrm{Tr}_E:
\mathcal{D}(\mathcal{H}_S\otimes\mathcal{H}_E)
\rightarrow
\mathcal{D}(\mathcal{H}_S),
$$

where $\mathcal{D}(\mathcal{H})$ denotes density operators on $\mathcal{H}$.

This explains how the same situation can be pure relative to one frame and mixed relative to another. A broader frame may use a pure state in a larger Hilbert space. A local frame may use a mixed state in a smaller Hilbert space. These are not contradictory claims about an absolute state. They are different descriptions indexed to different accessibility domains.

## 8. Wigner's Friend as Hilbert-Space Relativity

Wigner's Friend is a natural example of frame-indexed Hilbert representations.

Inside the laboratory, the friend measures a particle and binds to a definite outcome. The friend/lab neighborhood supports a Hilbert representation in which the outcome has become actual relative to that frame:

$$
\mathcal{H}_{\mathrm{friend}}
\quad\text{with}\quad
\rho_{\mathrm{friend}}^{(k)}.
$$

From Wigner's external frame, before interaction with the lab record, the laboratory may be represented as a coherent composite system:

$$
|\Psi\rangle_{SFL}=\sum_k c_k|k\rangle_S|F_k\rangle|L_k\rangle.
$$

Here Wigner's neighborhood supports a different Hilbert representation:

$$
\mathcal{H}_{\mathrm{Wigner}}=\mathcal{H}_S\otimes\mathcal{H}_F\otimes\mathcal{H}_L,
$$

at least in the idealized model where Wigner can coherently describe the closed lab.

The apparent conflict arises if one demands that the friend's actualized Hilbert-space description and Wigner's coherent Hilbert-space description must be the same absolute state description. Frames Theory denies that demand. The two descriptions are indexed to different neighborhoods:

$$
\mathcal{N}_{\mathrm{friend}}
\ne
\mathcal{N}_{\mathrm{Wigner}}.
$$

The friend has access to the internal measurement record. Wigner, before opening or interacting with the lab, has access to the lab as an external composite system. The descriptions must reconcile only when a comparison neighborhood forms:

$$
\mathcal{N}_{\mathrm{comparison}}
$$

with access to both Wigner's later record and the friend's record.

At that point, consistency constraints require the records to be compatible. If the friend recorded \(k\), Wigner's later interaction must bind to records consistent with that outcome in ordinary conditions. The comparison frame does not retroactively require that Wigner's earlier external Hilbert description was identical to the friend's internal one. It requires that their accessible records reconcile when brought into a common neighborhood.

Thus Wigner's Friend becomes an example of Hilbert-space relativity:

> Different frame neighborhoods may support different Hilbert representations of the same broader physical situation, and those representations become jointly constrained when records enter a common comparison frame.

## 9. Entanglement, Nonseparability, and Shared Neighborhoods

Entanglement shows why Hilbert spaces cannot always be reduced to independent frame-local state spaces. If two systems \(A\) and \(B\) are prepared in an entangled state,

$$
|\Phi^+\rangle_{AB}=\frac{1}{\sqrt{2}}(|0\rangle_A|0\rangle_B+|1\rangle_A|1\rangle_B),
$$

then the joint Hilbert space

$$
\mathcal{H}_{AB}=\mathcal{H}_A\otimes\mathcal{H}_B
$$

contains states that are not products of states in $\mathcal{H}_A$ and $\mathcal{H}_B$. The correlation structure belongs to the joint representation.

Frames Theory interprets this as a nonseparable constraint associated with a shared generating or comparison neighborhood. Local frames $F_A$ and $F_B$ may each use reduced states:

$$
\rho_A=\mathrm{Tr}_B(|\Phi^+\rangle\langle\Phi^+|),
$$

$$
\rho_B=\mathrm{Tr}_A(|\Phi^+\rangle\langle\Phi^+|).
$$

These local states do not contain the full correlation. The correlation becomes directly available only in a broader frame that can access and compare both records.

This reinforces the distinction between local Hilbert spaces and joint Hilbert spaces. A local frame's Hilbert space may be adequate for local outcome statistics. A joint comparison frame may require a larger Hilbert space to represent correlations. Neither representation alone should be mistaken for an unrestricted God's-eye description.

No-signaling also fits naturally here. A local frame cannot use operators or records outside its accessible neighborhood. Even if the joint Hilbert space contains nonseparable correlations, usable information remains constrained by causal record propagation.

## 10. The Universal Hilbert Space Question

A natural objection is that quantum cosmology, Everettian mechanics, and many formulations of quantum field theory speak of a universal Hilbert space. Does Frames Theory deny the usefulness of such a space?

No. Frames Theory denies only that a universal Hilbert space should be treated as automatically operationally available or ontologically primary for embedded frames.

One may formally write

$$
\mathcal{H}_{\mathrm{global}}
$$

as a mathematical representation of all degrees of freedom in a model. Such a representation may be useful for calculation, symmetry analysis, or theoretical unification. But no embedded frame has direct access to all of $\mathcal{H}_{\mathrm{global}}$. Every physical frame occupies a bounded accessibility domain.

For a frame $F_i$, the physically available Hilbert representation is some restriction, subspace, factor, effective algebra, or coarse-graining of the global representation:

$$
\mathcal{H}_i
\sim
\mathrm{Restrict}_{\mathcal{N}_i}(\mathcal{H}_{\mathrm{global}}).
$$

This schematic expression should not be treated as a final mathematical definition. It marks the intended relation: the frame-relative state space is derived from what the frame can access, not from a view from nowhere.

This point is especially important in cosmology. A cosmic horizon may place degrees of freedom permanently outside a frame's accessible domain. A formal global Hilbert space may include those degrees of freedom, but the frame's operational state must be restricted. The corresponding reduced state may be mixed because the inaccessible degrees of freedom purify it only from a larger perspective.

Frames Theory therefore treats universal Hilbert spaces as possible formal envelopes, not as the basic unit of physical actuality. Physical actuality begins with frame-relative binding, record formation, and consistency across accessible neighborhoods.

## 11. Software and Simulation Implications

The interpretation developed here also clarifies how a Frames Theory simulator should represent quantum state spaces.

A simulation should not treat the network graph and the Hilbert space as the same object. It should represent them as related layers:

```ts
FrameNeighborhood = {
  centerFrame,
  accessibleFrames,
  channels,
  causalDomain,
  records,
  constraints
}

QuantumRepresentation = {
  neighborhoodId,
  hilbertSpace,
  observableAlgebra,
  state,
  basis,
  updateRules
}
```

The frame graph determines accessibility, propagation, containment, and record sharing. The Hilbert representation determines quantum states, amplitudes, admissible observables, and measurement updates within that accessible domain.

A measurement-chain scenario might therefore begin with

$$
\mathcal{H}_{\mathrm{detector}}=\mathcal{H}_{\mathrm{spin}}\otimes\mathcal{H}_{\mathrm{detector}},
$$

then extend to

$$
\mathcal{H}_{\mathrm{lab}}=\mathcal{H}_{\mathrm{spin}}\otimes\mathcal{H}_{\mathrm{detector}}\otimes\mathcal{H}_{\mathrm{apparatus}}\otimes\mathcal{H}_{\mathrm{environment}},
$$

as additional frames enter the accessible neighborhood.

The simulator should make visible four distinct operations:

1. Expanding or restricting a frame neighborhood.
2. Constructing the Hilbert representation supported by that neighborhood.
3. Selecting admissible observables for the receiving frame.
4. Updating the frame-relative state through binding, projection, trace, or decoherence operations.

This design prevents a subtle mistake: animating a single global state and merely labeling parts of it as frames. Frames Theory requires the accessibility graph and the quantum representation to co-determine what each frame can actually describe.

## 12. Open Problems

The frame-neighborhood interpretation of Hilbert space is a scaffold, not a completed mathematical theory. Several problems remain open.

First, Frames Theory needs a precise rule for assigning $\mathcal{H}_i$ to $\mathcal{N}_i$. In simple models this is straightforward, but in interacting quantum field theory, gauge theories, gravity, and cosmology, subsystem decomposition is subtle.

Second, the relation between observable algebras and frame admissibility should be formalized. Algebraic quantum theory may be especially useful here, since it already treats local regions through associated operator algebras.

Third, overlap maps between Hilbert representations need to be specified. If two frames have overlapping but non-identical neighborhoods, Frames Theory must define how their states restrict to the overlap and how consistency should be measured.

Fourth, tensor-product factorization must be treated carefully. In gauge theories and quantum gravity, Hilbert spaces may not factorize cleanly across spatial regions. Frames Theory should not assume simple tensor products where the underlying physics forbids them.

Fifth, the role of a global Hilbert space in quantum cosmology remains delicate. A global representation may be mathematically useful, but Frames Theory must explain how embedded frame-relative descriptions arise from it without smuggling in an impossible external observer.

These are not defects of the framework. They are the places where the framework becomes mathematically serious.

## 13. Conclusion

A Hilbert space can be modeled as a frame-neighborhood state space, but only if the phrase is understood carefully. The frame neighborhood is not itself the Hilbert space. The neighborhood is the relational and causal domain of accessibility. The Hilbert space is the formal quantum state space associated with that domain.

This gives Frames Theory a disciplined bridge to standard quantum mechanics:

$$
\text{Frame}=\text{bounded informational context},
$$

$$
\text{Frame neighborhood}=\text{accessible relational domain},
$$

$$
\text{Hilbert space}=\text{quantum state space representable within that domain},
$$

$$
\text{Observable algebra}=\text{admissible distinctions bindable by the frame},
$$

$$
\text{Measurement}=\text{local binding and update inside this accessible structure}.
$$

On this view, quantum states are not descriptions from nowhere. They are state descriptions supported by bounded domains of accessibility, coupling, and record formation. Different frames may use different Hilbert spaces, different decompositions, or different reduced states because they occupy different informational neighborhoods. Their descriptions are not arbitrary, because they must reconcile where their records, observables, and causal domains overlap.

The result is a frame-relative interpretation of Hilbert space: not a rejection of quantum formalism, but a relocation of its ontology. Instead of beginning with a universal Hilbert space and asking where observers fit, Frames Theory begins with bounded frames and asks what Hilbert representation each frame neighborhood can legitimately support.

## Attribution and License

Author: William J. House.

This paper is part of the Frames Theory project and is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

You are free to share, copy, redistribute, remix, transform, and build upon this work for any purpose, including commercial purposes, provided appropriate attribution is given, a link to the license is provided, and changes are indicated where applicable.

Full license text: https://creativecommons.org/licenses/by/4.0/legalcode

## References and Influences

This paper is an original Frames Theory development, but it is informed by several existing areas of physics, mathematics, and philosophy of science.

- John von Neumann, *Mathematical Foundations of Quantum Mechanics* (1932). Foundational Hilbert-space formalism, measurement theory, and projection.
- Paul Dirac, *The Principles of Quantum Mechanics* (1930). State vectors, observables, and the algebraic structure of quantum theory.
- Hugh Everett III, "Relative State" Formulation of Quantum Mechanics (1957). Relative-state descriptions and no-collapse quantum interpretation.
- Bryce DeWitt and Neill Graham, eds., *The Many-Worlds Interpretation of Quantum Mechanics* (1973). Development and interpretation of Everettian quantum mechanics.
- Carlo Rovelli, "Relational Quantum Mechanics" (1996). Relational state assignment and observer-relative physical facts.
- Wojciech H. Zurek, decoherence, pointer states, envariance, and quantum Darwinism. Environmental stabilization, redundant records, and emergence of classical objectivity.
- H. Dieter Zeh, decoherence and the emergence of classicality. Early work on environment-induced suppression of interference.
- Robert B. Griffiths, Roland Omnes, Murray Gell-Mann, and James Hartle, consistent/decoherent histories approaches. Histories, records, and consistency conditions in quantum theory.
- George Mackey and Andrew Gleason, mathematical probability measures on Hilbert spaces. Hilbert-space structure and constraints on quantum probability.
- Rudolf Haag, *Local Quantum Physics* (1992). Algebraic quantum field theory and local observable algebras.
- John Archibald Wheeler, information-centered and participatory approaches to physics. The role of information, observation, and physical meaning.
- Jacob Bekenstein, Stephen Hawking, Gerard 't Hooft, Leonard Susskind, and later holographic-principle work. Horizons, information bounds, and observer-accessible domains.
- Ted Jacobson, Erik Verlinde, Mark Van Raamsdonk, and tensor-network/holographic programs relating information, entanglement, and geometry.
- Gregory Bateson, *Steps to an Ecology of Mind* (1972). Systems, information, and relational epistemology.

These references should be read as intellectual context rather than claims of equivalence. Frames Theory uses its own vocabulary of frames, neighborhoods, binding, records, accessibility, and consistency, while drawing on established structures from quantum theory, decoherence, relational interpretation, algebraic locality, information theory, and horizon-bounded physics.
