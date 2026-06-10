# Quantum Fields as Frames: Aspect-Selective Binding and Particle Decay in Frames Theory

William J. House

## Abstract

Quantum field theory replaces a particle-first ontology with a field-first formalism. What appears experimentally as a particle is, in the standard account, an excitation of an underlying quantum field. Frames Theory can use this fact to extend its ontology from finite measurement chains and frame neighborhoods into relativistic quantum physics. This paper proposes that a quantum field may be modeled as a persistent informational frame: a structured physical domain with admissible excitations, coupling channels, symmetries, conservation constraints, and state representations. A particle is then a localized or mode-like excitation-aspect of a field-frame, while an interaction vertex is an admissible binding channel between field-frames.

On this view, particle decay is a measurement-like event in the broad Frames Theory sense. It is not necessarily a laboratory measurement or a completed classical record. Rather, it is a local field-frame interaction in which excitation-aspects are redistributed into receiving field-frames according to allowed couplings, quantum numbers, conservation laws, phase space, and transition amplitudes. A Higgs boson decay, for example, is interpreted as an excitation of the Higgs field becoming bound into admissible excitations of other fields. Branching ratios then play a role analogous to frame-binding measures over allowed decay channels. The paper connects this account to Hilbert and Fock spaces, Minkowski causal structure, aspect-selective frame-binding, detector records, and the limits imposed by gauge redundancy and interacting quantum field theory.

## 1. Introduction

Frames Theory begins with bounded informational frames rather than detached objects viewed from nowhere. A frame is a physical informational context with an internal state, accessible relations, constraints, and possible records. Observation is directed information transfer between frames. Measurement is a special case in which a receiving frame becomes stably bound to outcome-relative information.

The earlier papers in this sequence developed the basic frame ontology, Born weights as frame-binding measures, frame-relative state update, decoherence, redundant objectivity, entanglement, causal boundaries, records, aspect-selective binding, and Hilbert space as frame-neighborhood state space. The present paper moves toward quantum field theory.

The motivating question is simple:

> If particles are excitations of fields, can a quantum field be modeled as a frame?

This paper argues that the answer is yes, with care. A quantum field should not be treated as a classical substance filling space, nor as a conscious observer, nor as a macroscopic measuring apparatus. Rather, it may be treated as a persistent frame-like structure: a domain of admissible excitations and interactions whose coupling rules determine what it can receive, bind, transform, or propagate.

This lets Frames Theory reinterpret particle interactions without returning to a naive particle ontology. A Higgs boson is not a tiny object that contains future decay particles inside it. It is an excitation of the Higgs field. Its decay is an interaction process in which the excitation's energy, momentum, quantum numbers, and coupling-relevant aspects become redistributed into excitations of other fields.

In Frames Theory language:

$$
\text{quantum field} = \text{persistent field-frame},
$$

$$
\text{particle} = \text{localized or mode-like excitation-aspect},
$$

$$
\text{interaction vertex} = \text{admissible field-frame binding channel},
$$

$$
\text{decay} = \text{redistribution of excitation-aspects into receiving field-frames}.
$$

The central thesis is:

> A quantum field is a persistent frame whose excitations become particle-like events, and particle decay is a measurement-like redistribution of excitation-aspects into receiving field-frames according to coupling, symmetry, conservation, phase-space, and amplitude constraints.

This paper does not propose a replacement for quantum field theory. It does not derive the Standard Model or modify scattering amplitudes. It offers an interpretive mapping between Frames Theory and the field-theoretic picture already used in modern physics.

## 2. From Particle Ontology to Field-Frame Ontology

Classical intuition often begins with particles as small objects moving through space. Quantum field theory changes that picture. The basic dynamical entities are fields. Particles are excitations of those fields, often defined relative to asymptotic states, detector interactions, or approximate regimes where particle-number descriptions make sense.

Frames Theory should take this seriously. If it treats particles as primary objects, it risks importing an older ontology into a field-theoretic setting. A better move is to treat quantum fields as the persistent structures and particles as field-relative excitation events.

A field-frame is not a frame because it has an opinion or a perspective. It is a frame because it has:

- admissible states or excitations;
- coupling relations to other fields;
- constraints imposed by symmetries and conservation laws;
- causal support in spacetime;
- a quantum state representation;
- possible records through downstream interactions.

For example, the electromagnetic field can bind and propagate electromagnetic aspects associated with charge and current. The gluon field binds color aspects. Fermion fields support spinor excitations with charge, flavor, and mass properties. The Higgs field couples according to the electroweak structure and Yukawa couplings, making some decay channels much more available than others.

This suggests a field-frame ontology:

$$
\text{field-frame ontology}
\ne
\text{particle-first ontology}.
$$

A particle is not denied. It is reinterpreted as a stable or detectable excitation pattern within a field-frame and its associated Hilbert or Fock representation.

## 3. Quantum Fields as Persistent Frames

Define a quantum field-frame schematically as

$$
\mathcal{F}_a=(\Phi_a,\mathcal{H}_a,\mathcal{O}_a,C_a,V_a,\mathcal{D}_a),
$$

where:

- $\Phi_a$ is the field or field operator structure.
- $\mathcal{H}_a$ is the associated state space or sector of a larger Hilbert/Fock space.
- $\mathcal{O}_a$ is the algebra of admissible observables or field operators.
- $C_a$ is the set of constraints, including symmetries and conservation laws.
- $V_a$ is the set of interaction vertices or coupling channels involving the field.
- $\mathcal{D}_a$ is the causal or spacetime support relevant to the field-frame description.

In a full interacting quantum field theory, these ingredients are not always cleanly separable. The Hilbert space may not factor neatly into independent field components, gauge redundancy may obscure naive subsystem boundaries, and interacting fields may not admit a simple particle-number basis at all times. The definition above is therefore a conceptual scaffold, not a final mathematical construction.

Still, it captures the Frames Theory role of a field. A field-frame is a persistent domain that determines which excitation-aspects are admissible, how those aspects propagate, and how interactions with other field-frames may occur.

A software-like sketch would be:

```ts
FieldFrame = {
  fieldType,
  vacuumState,
  allowedExcitations,
  couplingConstants,
  quantumNumbers,
  symmetries,
  conservationConstraints,
  accessibleModes,
  interactionVertices,
  causalSupport
}
```

The phrase "persistent" matters. A particle may be created or annihilated relative to a field-theoretic description. The field-frame remains the structured domain in which such excitations are possible.

## 4. Particles as Excitations and Event-Aspects

In quantum field theory, a particle is often represented as an excitation of a field mode. In simple free-field settings, creation and annihilation operators make this intuitive:

$$
a_k^\dagger|0\rangle = |1_k\rangle,
$$

where $|0\rangle$ is the vacuum state and $|1_k\rangle$ is a one-particle excitation of mode $k$.

Frames Theory interprets such an excitation as an event-aspect of a field-frame. It is not an isolated object with absolute identity independent of the field. It is a field-relative pattern with energy, momentum, spin, charge, and other quantum numbers.

Thus:

$$
\text{particle} = \text{field excitation with frame-bindable aspects}.
$$

The aspects of an excitation may include:

- energy and momentum;
- mass or effective mass;
- spin and helicity;
- electric charge;
- color charge;
- weak isospin or hypercharge;
- flavor;
- lifetime or decay width;
- phase-space accessibility;
- detector-coupling signatures.

Different receiving field-frames can bind different aspects. A charged particle excitation couples to the electromagnetic field. A colored excitation couples to the gluon field. A massive fermion couples to the Higgs field through Yukawa structure. A detector later binds only those aspects that its material, electronics, geometry, and reconstruction algorithms can stabilize into records.

This is the QFT analogue of aspect-selective frame-binding.

## 5. Interaction Vertices as Binding Channels

In perturbative quantum field theory, Feynman diagrams encode possible interaction processes. Vertices represent allowed interactions among fields. The detailed mathematical content depends on the Lagrangian, coupling constants, symmetries, and gauge structure.

Frames Theory interprets an interaction vertex as an admissible binding channel between field-frames. A vertex is not merely a drawing convention. It encodes the possibility that excitation-aspects in one field-frame can be redistributed into excitation-aspects of others.

Schematically, if fields $\Phi_a$, $\Phi_b$, and $\Phi_c$ interact through a term in the Lagrangian, one may write:

$$
\Phi_a \leftrightarrow \Phi_b + \Phi_c
$$

as a possible field-frame binding channel, provided all relevant constraints are satisfied.

More generally:

$$
V_{a\to bc}\in C_{\mathrm{admissible}}
$$

only when the interaction is allowed by the theory's symmetries, charges, conservation laws, and available phase space.

This can be summarized as:

```text
interaction vertex = admissible field-frame binding channel
```

The binding is not necessarily classical. It may be virtual, coherent, reversible, or part of an amplitude sum over histories. It becomes a classical event only when later interactions create stable records in detector, environment, or memory frames.

## 6. Particle Decay as Measurement-Like Field Binding

A particle decay occurs when an unstable excitation evolves into other excitations. In standard language, an initial state $|i\rangle$ can transition into possible final states $|f\rangle$ with amplitudes determined by the interaction Hamiltonian or S-matrix:

$$
\mathcal{A}_{i\to f}=\langle f|S|i\rangle.
$$

The decay rate is determined by the amplitude, phase space, and normalization factors. In a simplified expression:

$$
\Gamma_{i\to f}\propto |\mathcal{M}_{i\to f}|^2\,d\Pi_f,
$$

where $\mathcal{M}_{i\to f}$ is the invariant matrix element and $d\Pi_f$ is the final-state phase-space measure.

Frames Theory interprets this as a field-frame binding process. The initial excitation makes several possible final excitation-aspects available. Receiving field-frames bind only those aspects allowed by their coupling structure and constraints.

A schematic admissibility function is:

```text
canBind(fieldFrame, excitationAspect) =
  hasAllowedCoupling(fieldFrame, excitationAspect)
  && satisfiesConservationLaws(excitationAspect)
  && matchesQuantumNumbers(fieldFrame, excitationAspect)
  && hasAvailableModes(fieldFrame, excitationAspect)
  && hasNonzeroTransitionAmplitude(fieldFrame, excitationAspect)
```

Calling decay "measurement-like" requires care. A decay is not automatically a laboratory measurement. It may produce no durable classical record by itself. It is measurement-like in the broader Frames Theory sense because it is an interaction that redistributes information-bearing aspects into receiving frames and constrains future states. It becomes a measurement in the stronger sense when the decay products couple into detector and environment frames that form records.

Thus:

$$
\text{decay event}
=
\text{field-frame binding},
$$

while

$$
\text{detected decay event}
=
\text{field-frame binding plus record-forming amplification}.
$$

This distinction avoids treating every microscopic interaction as a completed classical observation.

## 7. Higgs Decay as a Field-Frame Example

The Higgs boson is an excitation of the Higgs field. In the Standard Model, the Higgs field couples to massive particles in ways determined by electroweak symmetry breaking and Yukawa couplings. The Higgs boson can decay through several channels, including channels such as

$$
H\to b\bar{b},
$$

$$
H\to \tau^+\tau^-,
$$

$$
H\to W W^*,
$$

$$
H\to Z Z^*,
$$

$$
H\to \gamma\gamma,
$$

and

$$
H\to gg.
$$

Some channels occur at tree level, others through loop processes, and their relative rates depend on coupling strengths, masses, phase space, and the structure of the Standard Model.

In Frames Theory language, the initial Higgs excitation is an event-aspect of the Higgs field-frame. The possible decay products correspond to receiving field-frames or composite final-state sectors. The decay is admissible only where the relevant field-frames can bind the excitation-aspects under the theory's constraints.

For example, in the $H\to b\bar{b}$ channel, the bottom quark field and antibottom excitation sector are receiving frames for the Higgs excitation's energy-momentum and coupling-relevant aspects. In the $H\to \gamma\gamma$ channel, the electromagnetic field receives photon excitations through loop-mediated coupling. The channel is possible not because the Higgs excitation contains photons as hidden classical parts, but because the field-frame interaction structure admits a transition amplitude into that final state.

This is exactly the kind of situation aspect-selective frame-binding is meant to describe. The field characteristics determine which aspects can bind where.

## 8. Branching Ratios as Frame-Binding Measures

For an unstable particle, the total decay width is the sum over partial widths:

$$
\Gamma_{\mathrm{total}}=\sum_i \Gamma_i.
$$

The branching ratio for channel $i$ is

$$
B_i=\frac{\Gamma_i}{\Gamma_{\mathrm{total}}}.
$$

Frames Theory can interpret $B_i$ as a field-frame binding measure over admissible decay channels. It is not a new prediction. It is a reinterpretation of what the existing quantity means in a frame-theoretic ontology.

The analogy with Born weights is suggestive:

$$
\mu_F(k)=|c_k|^2
$$

measures possible binding of a receiving frame to outcome $k$ in ordinary quantum measurement contexts, while

$$
B_i=\frac{\Gamma_i}{\Gamma_{\mathrm{total}}}
$$

measures relative binding into decay channel $i$ among allowed field-frame channels.

The analogy should not be overstated. Born probabilities and branching ratios arise in different formal settings. A branching ratio includes dynamics, matrix elements, and phase-space factors. But both quantities can be read as normalized measures over possible frame-relative actualizations.

In this sense:

$$
\text{branching ratio}
=
\text{normalized field-frame binding measure over decay channels}.
$$

This gives Frames Theory a clean bridge from measurement probabilities to relativistic interaction probabilities.

## 9. Conservation Laws as Admissibility Constraints

Conservation laws are central to particle interactions. Energy and momentum must be conserved. Electric charge must be conserved. Angular momentum, color charge, baryon number, lepton number, and other quantum numbers may impose exact or approximate restrictions depending on the process and theory.

Frames Theory interprets these laws as admissibility constraints on field-frame binding.

Let an initial excitation have conserved quantities $Q_i$, and a possible final channel have total conserved quantities $Q_f$. A channel is admissible only if

$$
Q_i=Q_f
$$

for the conserved quantities relevant to the interaction.

More generally:

$$
a_k\in\mathcal{A}_{\mathrm{bindable}}
\quad\text{only if}\quad
C_{\mathrm{field}}(a_k)=\mathrm{true}.
$$

Here $a_k$ is a candidate excitation-aspect and $C_{\mathrm{field}}$ represents the conservation, symmetry, and coupling constraints of the receiving field-frame network.

This connects directly to aspect-selective binding. A field may be exposed to a process in the sense that a formal diagram can be imagined, but it cannot bind the process unless the corresponding interaction is allowed. Exposure is not binding. A nonzero transition amplitude requires admissibility.

## 10. Aspect-Selective Binding Across Field Types

Different quantum fields bind different aspects of physical processes. This is one of the strongest bridges between aspect-selective frame-binding and quantum field theory.

The electromagnetic field binds charge-current aspects and supports photon excitations. The gluon field binds color aspects and mediates strong interactions. Fermion fields support spinor excitations with charge, flavor, and mass structure. The Higgs field binds mass-generating and Yukawa-coupling-related aspects in the electroweak theory. Weak gauge fields bind charged-current and neutral-current weak interaction aspects.

This can be written schematically:

$$
\mathcal{A}_{\Phi_a}(E)
\subseteq
\mathcal{A}(E),
$$

where $\mathcal{A}(E)$ is the total aspect bundle associated with an interaction event $E$, and $\mathcal{A}_{\Phi_a}(E)$ is the subset bindable by field-frame $\Phi_a$.

For a decay event,

$$
\mathcal{A}(E_{\mathrm{decay}})
=
\{\text{energy-momentum},\text{spin},\text{charges},\text{flavor},\text{color},\text{mass},\text{phase-space mode},\ldots\}.
$$

Each receiving field-frame binds only the aspects compatible with its operator structure and couplings. This is not subjective selection. It is physical admissibility.

The result is a field-theoretic version of the chair-and-person example from aspect-selective binding. The same event can propagate multiple aspects, but each receiving frame binds only what it is structured to receive.

## 11. Detector Records and Macroscopic Measurement

In high-energy physics, particles are not usually observed directly as little objects. They are reconstructed from detector records: tracks, calorimeter deposits, Cherenkov light, displaced vertices, timing signals, missing transverse momentum, and other correlated traces.

Frames Theory can describe the full chain:

```text
field-frame interaction
-> outgoing field excitations
-> detector material coupling
-> electronic signal
-> reconstructed object
-> analysis-level record
```

A Higgs decay, for example, is not observed as an isolated microscopic transition. It is inferred from a network of records produced by the decay products and their interactions with detector frames.

Thus, there are at least two layers:

1. **Field-frame binding:** the microscopic QFT process by which excitation-aspects redistribute into final field excitations.
2. **Record-frame binding:** the macroscopic measurement process by which detector, apparatus, software, and observer frames stabilize evidence of the event.

This distinction helps Frames Theory avoid a common ambiguity. The decay itself is measurement-like, but the experimental measurement is the record-forming amplification and reconstruction of the decay.

Objectivity arises when many detector subsystems and analysis frames redundantly stabilize compatible records of the same underlying event.

## 12. Minkowski Space, Fock Space, and Causal Support

Paper 11 argued that a Hilbert space is the formal state space associated with a frame neighborhood, not the neighborhood itself. Quantum field theory sharpens this point.

In relativistic QFT, fields are defined over spacetime, often idealized as Minkowski space in flat-background settings. The relevant state representation is typically a Hilbert space or Fock space, while the causal structure of Minkowski space constrains which interactions can influence which others.

Frames Theory can distinguish these layers:

$$
\text{Minkowski space}
=
\text{causal-geometric support},
$$

$$
\text{Hilbert/Fock space}
=
\text{quantum state representation},
$$

$$
\text{quantum field}
=
\text{operator-valued field-frame structure},
$$

$$
\text{particle}
=
\text{excitation mode or detected event-aspect}.
$$

This distinction is important. Minkowski space is not itself the field-frame. It is the causal-geometric support within which relativistic field-frame interactions are defined. Hilbert or Fock space is not itself the field-frame either. It is the state representation associated with field configurations, excitations, and observables.

Microcausality can then be interpreted as a causal admissibility condition. For spacelike separated regions $x$ and $y$, appropriate field operators commute or anticommute:

$$
[\mathcal{O}(x),\mathcal{O}(y)]=0
$$

for observables at spacelike separation, in the bosonic schematic case. This expresses the fact that spacelike separated operations cannot be used for causal signaling. In Frames Theory terms, field-frame binding is constrained by causal accessibility.

This prepares a later paper on Minkowski spaces, Fock spaces, and relativistic frame neighborhoods. The present paper uses Minkowski structure as support, not as the main object of study.

## 13. Relation to Previous Frames Theory Papers

The present paper connects several earlier strands.

From Paper 2, it inherits the idea that probability-like quantities can be interpreted as frame-binding measures. Branching ratios are not Born weights in the narrow measurement sense, but they can be read as normalized binding measures over allowed field-frame decay channels.

From Paper 3, it inherits the interpretation of state update as frame-relative. A field interaction may update the state representation available to downstream frames without imposing a universal collapse across all descriptions.

From Paper 5, it inherits the idea that objectivity requires redundant record stabilization. A microscopic decay becomes an experimental fact only when detector and analysis frames stabilize compatible records.

From Paper 6, it inherits the distinction between nonseparable quantum structure and usable causal information. Field interactions may generate correlations, but record comparison remains causally constrained.

From Paper 7, it inherits relativistic causal boundaries. Field-frame binding must respect light cones and causal support.

From Paper 10, it inherits aspect-selective frame-binding. Different fields bind different interaction aspects because their coupling structures differ.

From Paper 11, it inherits the distinction between frame neighborhoods, Hilbert spaces, and state representations. QFT adds field-frames and Fock-space sectors to this picture.

Thus Paper 12 is not a detour. It is a bridge from Frames Theory's quantum-measurement vocabulary into relativistic field ontology.

## 14. Limitations and Open Problems

This paper is interpretive and programmatic. It does not derive quantum field theory from Frames Theory. It does not derive the Standard Model. It does not modify S-matrix elements, decay widths, cross sections, or branching ratios. Its purpose is to provide a disciplined Frames Theory reading of existing QFT structures.

Several limitations are important.

First, interacting quantum field theory does not always permit a simple particle ontology. Particle number can be observer-dependent, approximate, or only cleanly defined for asymptotic states. Frames Theory must avoid treating particles as too fundamental.

Second, gauge theories introduce redundancy. Gauge potentials contain descriptive structure that is not directly physical. A mature frame theory of gauge fields must distinguish physical field-frame content from representational gauge freedom.

Third, Hilbert-space factorization is subtle in QFT, especially in gauge theories and gravitational settings. The idea of separate receiving field-frames must be handled with algebraic and constraint-aware care.

Fourth, localization is difficult. Fields are local in the operator sense, but particles are not always sharply localizable. A field-frame account must respect these subtleties.

Fifth, the relation between microscopic field-frame binding and macroscopic record formation requires more formal development. Detector physics, environmental decoherence, and reconstruction algorithms are part of the frame network, not mere afterthoughts.

These open problems are not reasons to avoid the field-frame proposal. They are where it becomes technically serious.

## 15. Conclusion

Quantum field theory suggests that fields, not particles, are the persistent structures of relativistic quantum physics. Frames Theory can absorb this lesson by treating quantum fields as persistent frames and particles as excitation-aspects of those field-frames.

On this view, particle decay is not a small object splitting into smaller objects. It is a field-frame process in which an unstable excitation redistributes its bindable aspects into admissible receiving field-frames. The allowed channels are determined by coupling structure, quantum numbers, conservation laws, phase space, and transition amplitudes. The resulting branching ratios can be interpreted as normalized field-frame binding measures over the allowed channels.

This gives a compact mapping:

$$
\text{quantum field}
=
\text{persistent informational frame},
$$

$$
\text{particle}
=
\text{field excitation or event-aspect},
$$

$$
\text{interaction vertex}
=
\text{admissible binding channel},
$$

$$
\text{decay}
=
\text{aspect redistribution into receiving field-frames},
$$

$$
\text{branching ratio}
=
\text{field-frame binding measure},
$$

$$
\text{detector record}
=
\text{macroscopic stabilization of field-frame traces}.
$$

The proposal is deliberately conservative about physics and ambitious about ontology. It preserves the formal authority of quantum field theory while offering a Frames Theory reading of what field interactions mean: not detached particles moving through empty space, but structured field-frames binding, transforming, and recording aspects of physical events under causal and symmetry constraints.

## Attribution and License

Author: William J. House.

This paper is part of the Frames Theory project and is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

You are free to share, copy, redistribute, remix, transform, and build upon this work for any purpose, including commercial purposes, provided appropriate attribution is given, a link to the license is provided, and changes are indicated where applicable.

Full license text: https://creativecommons.org/licenses/by/4.0/legalcode

## References and Influences

This paper is an original Frames Theory development, but it is informed by several existing areas of quantum field theory, particle physics, quantum foundations, and information-centered physics.

- Paul Dirac, early quantum field theory and the quantum theory of radiation. Creation and annihilation operators and field-mediated particle processes.
- Richard Feynman, Julian Schwinger, Sin-Itiro Tomonaga, and Freeman Dyson, covariant quantum electrodynamics and perturbative quantum field theory. Scattering amplitudes, diagrams, renormalization, and interaction vertices.
- Steven Weinberg, *The Quantum Theory of Fields* (1995-2000). Relativistic quantum fields, particle states, symmetries, and the S-matrix framework.
- Michael Peskin and Daniel Schroeder, *An Introduction to Quantum Field Theory* (1995). Perturbative QFT, Feynman rules, decay rates, and scattering processes.
- Mark Srednicki, *Quantum Field Theory* (2007). Field quantization, amplitudes, symmetries, and Standard Model structures.
- Claude Itzykson and Jean-Bernard Zuber, *Quantum Field Theory* (1980). Relativistic field theory, perturbation theory, and gauge fields.
- Peter Higgs, Francois Englert, Robert Brout, Gerald Guralnik, C. R. Hagen, and Tom Kibble, electroweak symmetry breaking and the Higgs mechanism.
- Sheldon Glashow, Abdus Salam, Steven Weinberg, and later Standard Model work. Electroweak unification, gauge fields, and particle interactions.
- Murray Gell-Mann and George Zweig, quark model; Harald Fritzsch, Murray Gell-Mann, Heinrich Leutwyler, and quantum chromodynamics. Color, gluons, and strong-interaction fields.
- Rudolf Haag, *Local Quantum Physics* (1992). Algebraic quantum field theory, local observable algebras, and the importance of locality.
- Arthur Wightman and the Wightman axioms. Field locality, relativistic covariance, and operator-valued distributions.
- Huzihiro Araki and algebraic approaches to quantum statistical mechanics and quantum field theory.
- Wojciech H. Zurek and decoherence/quantum Darwinism. Environmental stabilization and redundant records in the emergence of classical objectivity.
- Carlo Rovelli, relational quantum mechanics. Relational state assignment and observer-relative physical facts.
- John Archibald Wheeler, information-centered approaches to physics and the role of observation in physical meaning.

These references should be read as intellectual context rather than claims of equivalence. Frames Theory uses its own vocabulary of frames, field-frames, excitation-aspects, binding, records, accessibility, and consistency while drawing on established QFT structures such as fields, Fock spaces, amplitudes, interaction vertices, conservation laws, causal locality, and detector records.
