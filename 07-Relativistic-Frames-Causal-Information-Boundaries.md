# Relativistic Frames and Causal Information Boundaries in Frames Theory

## Abstract

Relativity teaches that physical description is constrained by causal structure. No observer has access to all events at once, simultaneity is frame-dependent, and horizons can permanently limit information exchange. Frames Theory treats these facts not as secondary complications, but as central clues: a physical frame is always bounded by what it can causally receive, store, transform, and reconcile. This paper develops the relativistic extension of Frames Theory at a conceptual level. It interprets relativistic frames as bounded informational domains embedded in spacetime, with causal light cones, horizons, and finite propagation speeds defining the limits of frame accessibility. State update, objectivity, and record reconciliation are therefore constrained by causal information boundaries. The paper does not derive special or general relativity, nor does it formulate a complete relativistic quantum field theory. Its aim is narrower: to show how Frames Theory can incorporate relativistic causality without requiring a global present, preferred simultaneity slice, or superluminal information transfer.

## 1. Introduction

The previous paper considered entanglement, Bell nonlocality, and no-signaling. It argued that quantum correlations can be nonseparable without becoming usable faster-than-light signals. That conclusion points directly toward a broader question:

> What is a frame when causal structure itself limits what information can be received?

In nonrelativistic discussions of quantum measurement, it is tempting to speak as if all frames could be arranged on a single universal time slice. A detector measures, an observer reads, a record forms, and a broader frame eventually reconciles the descriptions. This is often useful as an approximation. But relativity denies that there is a physically privileged global present shared by all observers.

Special relativity constrains information transfer by light cones. General relativity adds curvature, horizons, and observer-dependent causal domains. A theory of informational frames must therefore make causal boundedness explicit. Frames are not merely abstract perspectives. They are physical systems embedded in a causal structure that determines which records can reach them.

The central thesis of this paper is:

> A relativistic frame is a bounded informational domain whose accessible state is constrained by causal information boundaries.

This thesis extends the existing Frames Theory vocabulary. A frame is still a bounded informational context. Observation is still directed information transfer. Binding is still local actualization relative to a receiving frame. Objectivity is still redundant frame-binding across a network. But in relativistic settings, the edges of that network are constrained by light cones, causal diamonds, horizons, and finite signal propagation.

This paper is intentionally modest. It does not claim to derive Lorentz invariance, Einstein's field equations, or quantum field theory. It develops a conceptual bridge: Frames Theory must be causal-domain aware.

## 2. From Informational Frames to Relativistic Frames

In the first Frames Theory paper, a frame was introduced as a bounded informational context:

$$
F_i=(\rho_i,N_i,C_i),
$$

where $\rho_i$ is the frame's informational state, $N_i$ is the set of accessible neighboring frames, and $C_i$ is the set of consistency constraints governing admissible relations.

For relativistic settings, this definition needs an additional emphasis. The accessibility neighborhood $N_i$ cannot be arbitrary. It must be constrained by causal structure.

A relativistic frame can therefore be written schematically as

$$
F_i=(\rho_i,N_i,C_i,\mathcal{D}_i),
$$

where $\mathcal{D}_i$ is the causal domain associated with the frame. This domain represents the spacetime region from which the frame can receive information, to which it can send information, or over which it can reconcile records, depending on the physical question being asked.

This addition does not replace the earlier definition. It refines it. In ordinary laboratory settings, $\mathcal{D}_i$ may be implicit because causal delays are small relative to the timescales of interest. In relativistic or cosmological settings, $\mathcal{D}_i$ becomes central.

The accessible neighborhood of a frame should therefore satisfy a causal constraint:

$$
F_j\in N_i
\quad\Rightarrow\quad
F_j \text{ is causally accessible to } F_i
\text{ within the relevant domain } \mathcal{D}_i.
$$

The phrase "causally accessible" can mean different things depending on context. It may mean that a signal from $F_j$ can reach $F_i$, that $F_i$ can influence $F_j$, or that both can enter a common comparison frame. Frames Theory must track these distinctions rather than treating accessibility as a single undifferentiated relation.

## 3. Light Cones as Information Boundaries

In special relativity, the light cone at an event separates possible causal relations from impossible ones. Events inside the past light cone can influence the event. Events inside the future light cone can be influenced by the event. Events outside both are spacelike separated and cannot exchange signals without exceeding the speed of light.

Frames Theory interprets light cones as information boundaries. If an event $p$ lies outside the past light cone of a frame event $q$, then information from $p$ is not available at $q$.

This can be written schematically as

$$
p\notin J^-(q)
\quad\Rightarrow\quad
p\notin \mathrm{Access}(q),
$$

where $J^-(q)$ is the causal past of $q$.

Similarly, if an event $r$ lies outside the future light cone of $q$, then the frame at $q$ cannot send information to $r$ by ordinary causal means:

$$
r\notin J^+(q)
\quad\Rightarrow\quad
q\not\rightarrow r.
$$

This gives a relativistic grounding to earlier Frames Theory language. An information-transfer edge

$$
O_{ij}:F_i\rightarrow F_j
$$

is admissible only when the relevant portion of $F_i$ lies in the causal past of the relevant portion of $F_j$.

Thus the directed information graph of Frames Theory is not merely an abstract graph. In relativistic settings, it must be embedded in causal structure. Edges are constrained by spacetime.

## 4. No Global Present

One of the most important consequences of relativity is the relativity of simultaneity. Events that are simultaneous in one inertial frame need not be simultaneous in another. This undercuts any ontology that requires a single universal present in which all facts update at once.

Frames Theory already avoids universal collapse. Relativistic causality strengthens that choice. If state update is frame-relative, then there is no need to specify a global time at which all frames update. A receiving frame updates when information enters its causal domain and becomes bound or stabilized.

Suppose two spacelike separated measurement events occur at $A$ and $B$. One inertial coordinate system may place $A$ before $B$, while another places $B$ before $A$. Frames Theory does not need to decide which event really happened first in an absolute sense. Each local receiving frame undergoes local binding in its own causal context. A later comparison frame reconciles their records only when both records enter a shared causal domain.

This matches the structure developed in the no-signaling paper:

$$
F_A:\quad (x,a),
$$

$$
F_B:\quad (y,b),
$$

$$
F_C:\quad (x,a;y,b).
$$

The comparison frame $F_C$ is not an instantaneous global view. It is a physical frame whose access depends on receiving records from $F_A$ and $F_B$ through causal channels.

Thus, Frames Theory replaces global simultaneity with causal record availability.

## 5. Causal Diamonds and Local Description

A useful relativistic notion is the causal diamond. Given two events $p$ and $q$ with $p$ in the causal past of $q$, the causal diamond is the intersection of the future of $p$ and the past of $q$:

$$
\mathcal{D}(p,q)=J^+(p)\cap J^-(q).
$$

This region contains the events that can be influenced by $p$ and can also influence $q$. It is a natural candidate for a bounded relativistic informational domain.

Frames Theory can treat a causal diamond as the spacetime support of a frame-relative description. A laboratory frame over a finite duration, for example, does not occupy all spacetime. It occupies a finite causal domain containing the events and records that can participate in its internal informational state.

In this language, a frame state $\rho_i$ is not simply associated with an abstract time parameter. It is associated with the information available within a causal domain:

$$
\rho_i = \rho(\mathcal{D}_i).
$$

This notation is schematic, but it marks an important shift. The state of a relativistic frame is not a God's-eye state of the universe at a time. It is an information state supported by a bounded causal region.

This interpretation is especially useful for finite observers. Any real observer has a finite worldline, finite memory, finite signal access, and finite measurement apparatus. The relevant frame is not all of spacetime, but the causal domain over which that observer can receive and reconcile information.

## 6. Horizons and Permanently Inaccessible Information

Light cones define local causal boundaries. Horizons define stronger limitations. A horizon may prevent information from ever reaching a frame, even in principle.

Examples include black hole event horizons, cosmological event horizons, and Rindler horizons for accelerated observers. In each case, some degrees of freedom are inaccessible to a given frame.

Frames Theory interprets horizons as causal information boundaries. If information cannot cross a horizon into a frame's accessible domain, then that information cannot contribute to the frame's state except indirectly through boundary effects or correlations already present in accessible degrees of freedom.

A horizon can therefore be represented as a boundary on the frame's accessible neighborhood:

$$
N_i^{\mathrm{accessible}}
\subset
N_i^{\mathrm{global}}.
$$

The distinction between accessible and global neighborhoods is important. A mathematical model may include regions beyond a horizon, but an embedded frame cannot operationally access them. The frame's physical state description must therefore be restricted.

This connects directly to partial trace. If a frame cannot access degrees of freedom beyond a horizon, then its effective state may be represented by tracing over inaccessible degrees of freedom:

$$
\rho_{\mathrm{accessible}}=\operatorname{Tr}_{\mathrm{beyond\ horizon}}(\rho_{\mathrm{global}}).
$$

This expression should be read cautiously. It is a schematic bridge, not a full theory of quantum fields in curved spacetime. Its purpose is to show the continuity between earlier Frames Theory treatment of partial trace and relativistic causal boundaries.

A reduced state is what a broader entangled structure looks like from a frame that lacks access to the purifying degrees of freedom. Horizons make that lack of access physically fundamental rather than merely practical.

## 7. Relativistic State Update

In nonrelativistic language, one often speaks of state update after measurement as if it occurs instantaneously. Relativity makes this language dangerous. Instantaneous across which time slice? Relative to which inertial frame?

Frames Theory avoids this problem by treating update as local and frame-relative. A frame updates when information enters its causal domain and becomes part of its accessible state.

For a receiving frame $F_i$, an update may be written schematically as

$$
\rho_i \longrightarrow \rho_i'
$$

when an information-transfer event enters $\mathcal{D}_i$ and satisfies the relevant compatibility and binding conditions.

For another frame $F_j$ outside the causal future of that event, no corresponding update is required. Its accessible state remains unchanged until a causal record arrives.

This principle can be stated as:

> State update propagates with records, not with a universal simultaneity surface.

This is the relativistic version of frame-relative state update. Projection, conditioning, partial trace, and decoherence are not global operations imposed across all spacetime. They are operations used by frames whose accessible information has changed.

This does not deny the usefulness of global state assignments in calculations. Physicists often choose spacelike hypersurfaces, foliations, or coordinate systems for computation. Frames Theory treats such global assignments as representational tools, not as ontologically privileged update surfaces.

## 8. Objectivity Under Causal Constraints

The fifth paper described classical objectivity as redundant frame-binding across a recursive information network. Relativity adds an important condition: redundancy must be causally available.

A record may be redundantly encoded in many environmental degrees of freedom, but a frame can access only the parts of that redundancy that lie within its causal domain. Objectivity is therefore not just redundancy in an abstract global environment. It is accessible redundancy.

For a frame $F_i$, one might write:

$$
\mathcal{O}_{F_i}(k)
\sim
\text{redundancy of records for } k
\text{ inside } \mathcal{D}_i.
$$

This is not proposed as a final quantitative definition. It is a reminder that objectivity is indexed to causal access. A fact can be highly objective within one causal domain and unavailable within another.

For example, a laboratory record may be objective within the future light cone of the experiment. It may be inaccessible to a spacelike separated frame until a signal arrives. It may be permanently inaccessible to a frame beyond a cosmological horizon.

Thus classical objectivity spreads causally. It does not appear everywhere at once.

This gives Frames Theory a relativistic account of public facthood:

1. A local event becomes bound in a receiving frame.
2. The record is redundantly stabilized in nearby environmental frames.
3. The record propagates outward through causal channels.
4. Other frames become able to bind to the record only when it enters their causal domains.
5. A broader public fact emerges across the connected region of the frame network.

Objectivity is therefore networked, redundant, and causally bounded.

## 9. Cosmological Patches and Partial Reality

Cosmology intensifies the problem. In an expanding universe with horizons, no embedded observer can access all events. Different observers may have different cosmic event horizons. Some regions may never enter one another's causal domains.

Frames Theory suggests that cosmological reality may be patch-relative in an operational sense. This does not mean that inaccessible regions do not exist mathematically. It means that no embedded frame can convert the entire global structure into accessible record, observation, or reconciliation.

A cosmological causal patch can be treated as a large-scale frame:

$$
F_{\mathrm{patch}}=(\rho_{\mathrm{patch}},N_{\mathrm{patch}},C_{\mathrm{patch}},\mathcal{D}_{\mathrm{patch}}).
$$

The state $\rho_{\mathrm{patch}}$ represents what can be described from within that causal patch, including records, fields, horizons, and accessible correlations. Degrees of freedom outside the patch may enter only through boundary conditions, correlations, or theoretical extrapolation.

This picture is compatible with a cautious attitude toward global cosmological descriptions. A global model may be mathematically useful, but no internal frame can occupy the model's external viewpoint. The physically available descriptions are patch-based and consistency-constrained.

This is not a denial of cosmology. It is a reminder that cosmology is practiced by embedded frames with finite causal access.

## 10. Relation to Quantum Field Theory

A full relativistic treatment of quantum frames should eventually connect with quantum field theory. QFT already respects locality in a sophisticated way. Observables are associated with spacetime regions, and operators associated with spacelike separated regions commute in local relativistic theories:

$$
[\mathcal{O}(x),\mathcal{O}(y)]=0
\quad\text{for spacelike separated } x,y.
$$

This microcausality condition expresses the impossibility of using spacelike separated operations for controllable signaling.

Frames Theory can interpret microcausality as a constraint on admissible information-transfer edges between frames. If two operations are spacelike separated, neither can serve as an ordinary causal update channel for the other. Their correlations may still be constrained by the joint state, but usable information must enter a common future frame through causal propagation.

This aligns QFT with the no-signaling account developed in the previous paper. Nonlocal correlations may appear in joint records, but local operations in spacelike separated regions cannot transmit controllable messages.

At this stage, Frames Theory does not replace algebraic QFT, local quantum field dynamics, or curved-spacetime field theory. Rather, it offers an interpretive layer: local algebras, causal diamonds, and horizon-limited states are natural candidates for relativistic frame domains.

## 11. Relation to the Prior Papers

This paper extends the sequence into relativistic causal structure.

The first paper introduced frames, observation, information transfer, containment, and cosmological horizons.

The second paper interpreted the Born rule as a frame-binding measure.

The third paper interpreted projection, partial trace, and decoherence as frame-relative state-update operations.

The fourth paper developed a conditional derivational pathway for the Born rule from frame-consistency constraints.

The fifth paper interpreted classical objectivity as redundant frame-binding across a recursive information network.

The sixth paper interpreted entanglement as distributed binding constraint and no-signaling as causal limitation on frame-accessible records.

The present paper adds causal information boundaries: the claim that frame accessibility, update, and objectivity must be constrained by light cones, horizons, and finite record propagation.

The resulting sequence is:

$$
\text{frames}
\longrightarrow
\text{binding measure}
\longrightarrow
\text{state update}
\longrightarrow
\text{measure derivation}
\longrightarrow
\text{classical objectivity}
\longrightarrow
\text{entanglement and no-signaling}
\longrightarrow
\text{causal information boundaries}.
$$

## 12. Relation to Existing Approaches

### 12.1 Special Relativity

Special relativity constrains causal access through invariant light cones and denies a preferred simultaneity relation. Frames Theory accepts these constraints. Its contribution is to interpret them as boundaries on information transfer, state update, and record reconciliation.

### 12.2 General Relativity

General relativity makes causal structure dynamical through spacetime geometry. Frames Theory does not derive this geometry. It treats relativistic causal domains as the physical background within which frame accessibility is defined. A future theory would need to clarify whether frame-network structure can illuminate the emergence or dynamics of spacetime geometry itself.

### 12.3 Algebraic Quantum Field Theory

Algebraic QFT assigns observables to spacetime regions and enforces locality through commutation relations for spacelike separated regions. Frames Theory is naturally compatible with this regional logic. It interprets local algebras as candidate formal representations of frame-accessible observables.

### 12.4 Relational Quantum Mechanics

Relational Quantum Mechanics treats facts as relative to interacting systems. Frames Theory agrees, but adds causal-domain structure. A fact is not merely relative to a system; it is also bounded by the causal region through which records can reach and be reconciled by that system.

### 12.5 Black Hole Complementarity and Holography

Black hole complementarity and holography emphasize that information accessible to different observers may be organized by horizons and boundaries. Frames Theory resonates with this idea but does not yet supply a holographic principle. It treats horizons as strong examples of causal information boundaries.

## 13. Limitations and Open Problems

This paper is conceptual. It does not derive special relativity, general relativity, Lorentz invariance, Einstein's field equations, or quantum field theory.

It does not provide a complete mathematical definition of $\mathcal{D}_i$ for arbitrary frames. Future work should formalize causal domains using worldlines, worldtubes, causal diamonds, local algebras, or other physically precise structures.

It does not solve the problem of relativistic collapse, because Frames Theory rejects universal collapse as the wrong target. It instead reframes the issue as local update and causal record propagation.

It does not address in detail the Unruh effect, Hawking radiation, black hole information, de Sitter horizons, or holographic entropy bounds. These are natural later topics.

It does not claim that all spacetime geometry emerges from frame relations. That is a possible research direction, not a result established here.

Finally, it does not make new empirical predictions. The contribution is interpretive and structural: it shows how Frames Theory can respect relativistic causal boundaries while preserving frame-relative state update and objectivity.

## 14. Conclusion

Frames Theory begins from bounded informational contexts. Relativity makes such boundedness unavoidable. No frame has access to all events, no global present is physically privileged, and horizons can permanently restrict information flow.

This paper has argued that relativistic frames should be understood as causal informational domains. A frame's accessible state is bounded by light cones, causal diamonds, horizons, and finite signal propagation. State update occurs when records enter a frame's causal domain, not when a universal simultaneity surface is globally rewritten. Objectivity spreads through causal propagation of redundant records, not through instantaneous global fact creation.

The compact statement is:

$$
\text{relativistic frame}=\text{bounded information state within a causal domain}.
$$

This preserves the core commitments of Frames Theory while bringing them into contact with relativistic causality. The next step is to apply this causal-domain view to black holes, horizons, holography, and cosmological patches in greater detail.
