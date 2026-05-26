# Frame-Relative State Update: Projection, Partial Trace, and Decoherence in Frames Theory

## Abstract

Standard quantum mechanics uses several state-update operations whose ontological status remains contested. Projection appears to replace a superposition with a definite outcome. The partial trace replaces a pure joint state with a reduced state for a subsystem. Decoherence suppresses interference between environmental records and yields an effectively classical mixture. These operations are empirically successful, but they are often described in ways that suggest either universal collapse, subjective ignorance, or an unresolved transition from quantum possibility to classical fact. Frames Theory offers a different interpretation. Projection, partial trace, and decoherence are not universal state changes imposed on reality as a whole. They are frame-relative update operations: rules for describing the informational state available to a receiving frame, given what that frame can access, bind to, and stabilize. On this view, entanglement supplies the microscopic substrate of quantum frame-binding, while decoherence determines which correlations become stable and accessible to receiving frames. This paper reinterprets projection as frame-relative conditionalization, partial trace as restriction to a frame's accessible degrees of freedom, and decoherence as the loss of frame-accessible coherence together with stabilization of pointer-like bindings. The formalism of quantum mechanics is preserved. What changes is the ontology of state update.

## 1. Introduction

Quantum mechanics contains several formal operations that work extremely well in practice but raise deep interpretive questions. When a measurement yields an outcome, the state is often said to project onto the corresponding eigenspace. When a subsystem is entangled with an inaccessible environment, the state of the subsystem is obtained by taking a partial trace. When a system interacts with a large environment, interference between macroscopic alternatives becomes practically inaccessible through decoherence.

These operations are standard. The difficulty is not their use, but their interpretation. Are they physical changes in the universe as a whole? Are they bookkeeping rules for observers? Are they approximations to some deeper mechanism? Or are they different descriptions available to different physical frames?

Frames Theory takes the last option seriously. Physical description is always situated within a frame: a bounded informational context capable of receiving, preserving, and propagating distinctions. A detector, apparatus, observer, environment, or record can all function as frames. A frame need not be conscious. It need only have an informational state and physical relations to other frames.

In this setting, state update is not a universal event. It is a frame-relative change in accessible information. Projection describes how a receiving frame updates after binding to an outcome. Partial trace describes what state is available when a frame lacks access to environmental degrees of freedom. Decoherence describes how environmental propagation makes some coherences inaccessible and some outcome channels stable.

The central thesis of this paper is:

> Projection, partial trace, and decoherence are frame-relative state-update operations, not universal collapse processes.

This thesis does not change quantum predictions. It changes what the state-update rules are taken to mean. A broader frame may describe a system plus apparatus or environment by a joint unitary state. A local receiving frame may describe the same situation by a reduced or conditioned state. A bound frame may describe one outcome as actualized. These descriptions need not contradict one another, because they belong to different levels of frame-relative access.

This paper sits between two other Frames Theory papers. The prior paper, *The Born Rule as a Frame-Binding Measure in Frames Theory*, interpreted Born probabilities as measures of successful informational binding between quantum phenomena and receiving frames. A later paper, *Toward a Frames-Theoretic Derivation of the Born Rule*, asks why that binding measure must take the quadratic Born form. The present paper fills the middle step: it explains how standard quantum state-update rules function once states are understood as frame-relative informational descriptions.

## 2. Minimal Frames Theory Recap

Frames Theory begins with the claim that physical descriptions are always made from within bounded informational contexts. A frame is a system with an internal informational state, relations to neighboring frames, and constraints governing which distinctions it can access or stabilize.

For the present paper, the following terms are central.

**Frame.** A bounded informational context. A frame may be microscopic or macroscopic, simple or complex. Detectors, apparatuses, organisms, laboratories, environments, and written records may all serve as frames.

**Receiving frame.** A frame that becomes informationally correlated with a quantum system or outcome-relative state.

**Generating frame.** The frame or interaction context from which a relevant informational structure originates.

**Propagation.** The process by which an informational structure becomes available to candidate receiving frames.

**Candidate binding site.** A frame whose state-space, coupling, and contextual constraints make it capable of receiving and stabilizing a propagated informational structure.

**Entangling correlation.** The microscopic quantum correlation by which a system and receiving frame become non-factorizably related. At the quantum level, frame-binding typically begins as entangling correlation.

**Binding.** The process by which a receiving frame becomes informationally correlated with an outcome-relative state.

**Decoherent frame-binding.** A binding relation that has become stable through environmental propagation, decoherence, and loss of accessible interference between alternatives.

**Redundant frame-binding.** Stabilization of the same outcome-relative information across multiple nested or neighboring frames. This is the frame-theoretic analogue of the redundancy emphasized in quantum Darwinism.

**Actualization.** The stabilized result of binding from the receiving frame's perspective. An outcome is actual for a frame when that frame has become bound to the corresponding outcome-relative state.

**Accessibility.** The set of degrees of freedom, distinctions, and correlations available to a frame. A frame may be physically correlated with a larger system while lacking access to many details of that system.

**Consistency.** The requirement that frame-relative descriptions reconcile where their informational domains overlap. Different frames may have different descriptions, but these descriptions must cohere when one frame's accessible content maps into another's.

These definitions allow three levels of description to be separated.

First, there is a **global or joint description**. A broader frame may describe a system, apparatus, and environment together as a unitary entangled state.

Second, there is a **frame-relative description**. A receiving frame may have access only to a reduced or conditioned state, because its informational boundary excludes some degrees of freedom.

Third, there is an **actualized or bound description**. Once a receiving frame is bound to outcome $k$, that outcome is definite relative to that frame.

Much confusion in the measurement problem comes from treating these three descriptions as if they had to be the same description. Frames Theory denies this. The broader joint state, the local reduced state, and the actualized bound state may all be valid, but they are valid relative to different frames and different accessibility domains.

## 3. Projection and Lüders Update

In the standard projective measurement formalism, an outcome $k$ is associated with a projector $P_k$. Given an initial density matrix $\rho$, the probability of outcome $k$ is

$$
p_k=\operatorname{Tr}(P_k\rho).
$$

After outcome $k$ is obtained, the state is updated by the Lüders rule:

$$
\rho^{\mathrm{post}}
=
\frac{P_k\rho P_k}{\operatorname{Tr}(P_k\rho)}.
$$

In collapse language, this is often described as if the physical state of the world has jumped into the $k$ subspace. Frames Theory gives a different interpretation.

Projection is frame-relative conditionalization. It is the rule by which a receiving frame updates its accessible state description after binding to outcome $k$. The projector $P_k$ does not need to represent a universal event that erases all other terms from every possible frame of description. It represents the constraint imposed on the receiving frame's future descriptions once the frame has stabilized the outcome-relative information associated with $k$.

For a receiving frame $F$, write the post-binding update as

$$
\rho_F^{\mathrm{post}}
=
\frac{P_k\rho P_k}{\operatorname{Tr}(P_k\rho)}.
$$

The denominator is the binding weight associated with that possible update:

$$
\mu_F(k)=\operatorname{Tr}(P_k\rho).
$$

In the pure-state case, if

$$
|\psi\rangle=\sum_k c_k|k\rangle,
$$

and $P_k=|k\rangle\langle k|$, this reduces to

$$
\mu_F(k)=|c_k|^2.
$$

This connects projection directly to the frame-binding interpretation of the Born rule. The Born weight measures the possible successful binding of frame $F$ to outcome $k$. The Lüders update gives the state description available to $F$ after that binding has occurred.

The entangling interaction creates the system-frame correlation. The Lüders rule is not the creation of that correlation; it is the conditioned description available to the receiving frame once the correlation has stabilized as outcome $k$. In this sense, projection is downstream from entanglement and stabilization. It is the local update rule for a frame that has become bound.

This distinction matters. A detector frame may become bound to outcome $k$ and use the projected state as its effective state for subsequent interactions. A broader laboratory frame, not yet correlated with the detector reading, may still represent the detector-system pair as an entangled state. Both descriptions can be correct relative to their frames.

For example, before the detector reading is propagated to a broader frame, a larger frame may write

$$
|\Psi\rangle_{SD}
=
\sum_k c_k |k\rangle_S |D_k\rangle.
$$

The detector frame $D_k$, however, is locally stabilized with respect to outcome $k$. From within that detector frame, subsequent same-basis interactions are constrained as though the state has projected. Projection is therefore not a universal physical rupture. It is the formal expression of local stabilization in a receiving frame.

This also avoids a common ambiguity: when did collapse happen? In Frames Theory, there is no single universal collapse time. There are binding events and propagation events. Different frames update when they receive and stabilize the relevant information.

## 4. Partial Trace and Reduced Density Matrices

Projection describes state update after outcome-resolving information has been received. The partial trace describes a different kind of frame-relative state: a reduced description available when a frame lacks access to part of a larger joint system.

Suppose a system $S$ is entangled with an environment $E$ and the joint state is represented by $\rho_{SE}$. A frame with access only to $S$ uses the reduced state

$$
\rho_S=\operatorname{Tr}_E(\rho_{SE}).
$$

This operation is often described as tracing out the environment. Frames Theory interprets this not as physical deletion or subjective forgetting, but as restriction to a frame's accessible degrees of freedom. The reduced state is the effective state available within the informational boundary of the frame.

If the joint state is pure,

$$
\rho_{SE}=|\Psi\rangle_{SE}\langle\Psi|,
$$

then the local reduced state may be mixed:

$$
\rho_S=\operatorname{Tr}_E\left(|\Psi\rangle_{SE}\langle\Psi|\right).
$$

This raises a familiar question. How can the same physical situation be pure and mixed? Frames Theory answers: pure relative to which frame, and mixed relative to which frame?

A broader frame with access to both $S$ and $E$ may describe the joint state as pure. A local frame with access only to $S$ must use the reduced state. The mixedness of $\rho_S$ reflects inaccessible environmental information relative to that local frame. It is not necessarily a universal fact that the system has become objectively mixed in every possible description.

This interpretation is especially natural in Frames Theory because frames are defined by informational boundaries. A frame's state is not a God's-eye inventory of all correlations in the universe. It is the state available within that frame's accessible neighborhood.

Thus the partial trace is a frame-relative operation:

> To trace out $E$ is to construct the state available to a frame that lacks access to the distinctions carried by $E$.

This allows pure and mixed descriptions to coexist without contradiction. They are not competing absolute claims. They are descriptions indexed to different accessibility domains.

Partial trace also helps clarify the status of ignorance. In classical probability, a mixed state is often treated as ignorance about which definite state actually obtains. In quantum mechanics, reduced mixed states can arise from entanglement even when the joint state is pure. Frames Theory interprets this as frame-relative inaccessibility rather than mere subjective ignorance. The local frame lacks access to the environmental correlations that would purify its description.

Put compactly: a reduced density matrix is what entanglement looks like from a frame that lacks access to the purifying degrees of freedom. The mixed state is not a failure of the formalism. It is the correct frame-relative state for a bounded informational context.

## 5. Decoherence and Pointer-Basis Stabilization

Decoherence occurs when a system becomes entangled with environmental degrees of freedom in a way that suppresses interference between certain alternatives. A typical schematic interaction is

$$
\sum_k c_k |k\rangle|E_0\rangle
\longrightarrow
\sum_k c_k |k\rangle|E_k\rangle.
$$

If the environmental states become effectively orthogonal,

$$
\langle E_j|E_k\rangle\approx 0
\quad\text{for}\quad j\ne k,
$$

then a frame without access to the detailed environmental correlations describes the system by an approximately diagonal reduced state:

$$
\rho_{\mathrm{eff}}
\approx
\sum_k |c_k|^2 |k\rangle\langle k|.
$$

This formula is often said to explain why quantum superpositions appear classical. Frames Theory agrees that decoherence is central, but it interprets the process carefully.

Decoherence is not universal collapse. It is the loss of frame-relative accessibility to coherence terms. The off-diagonal terms are not necessarily destroyed in an absolute sense. They become inaccessible to frames whose coupling to the system is mediated through environmental records that distinguish the $k$ alternatives.

This gives a frame-theoretic interpretation of pointer states. Pointer states are not selected because nature has an absolute preference for one basis. They are stabilization points for frames coupled through a particular environment. A receiving frame stabilizes in the basis that its coupling can register, preserve, and propagate.

Decoherence does not create collapse. It turns microscopic entangling correlations into stable, accessible, redundantly propagated frame-bindings. Entanglement supplies the quantum correlation; decoherence makes that correlation robust enough to function as a frame-relative record.

In frame language, decoherence has four stages.

1. **Generation:** a quantum event produces an informational structure with multiple outcome-relative channels.
2. **Propagation:** that structure spreads into environmental degrees of freedom.
3. **Filtering:** candidate receiving frames can access only some distinctions and not others.
4. **Stabilization:** bindings become stable in the channels that the environment redundantly records.

The pointer basis is therefore a frame-relative stabilization basis. It is the basis in which a particular class of receiving frames can form stable, repeatable bindings given their environmental coupling.

This should not be overstated. Frames Theory does not provide, in this paper, a complete first-principles solution to the preferred-basis problem. It reframes the problem. The relevant question is not simply, "Which basis does the universe prefer?" but rather, "Which basis is stabilized for which receiving frames, given their coupling and accessibility?"

Different frames with different coupling pathways may stabilize different effective bases. In ordinary macroscopic measurements, environmental redundancy makes some pointer-like bases overwhelmingly stable for many frames at once. This explains the practical objectivity of measurement records without requiring a universal collapse event.

### 5.1 Objectivity as Redundant Frame-Binding

An outcome appears objective when many frames can independently access stable records of the same outcome-relative information. A detector, apparatus, laboratory environment, observer, written record, and broader thermal environment need not be a single monolithic observer. They form a network of overlapping frames in which the same binding has become redundantly stabilized.

In this sense, objectivity is redundant frame-binding across a recursive information network. This is close to the logic of quantum Darwinism, where classical objectivity emerges because many observers can access redundant environmental records. Frames Theory generalizes the point: the record is objective to the extent that it is stably available across many compatible frames.

## 6. Consistency and Reconciliation Across Frames

If quantum state updates are frame-relative, a natural worry arises. Does Frames Theory allow arbitrary incompatible descriptions? It does not. Frame-relative does not mean unconstrained. Descriptions must reconcile where frames overlap, interact, or stand in containment relations.

Consider three descriptions of a measurement chain.

A broad frame $G$ may describe the system, apparatus, and environment by a joint state:

$$
\rho_{SAE}.
$$

A local frame $F$ with access only to the system may use a reduced state:

$$
\rho_F=\operatorname{Tr}_{AE}(\rho_{SAE}).
$$

A detector frame $D_k$ that has bound to outcome $k$ may use a conditioned state:

$$
\rho_{D_k}^{\mathrm{post}}
=
\frac{P_k\rho P_k}{\operatorname{Tr}(P_k\rho)}.
$$

These descriptions differ, but they are not arbitrary. The reduced state must be obtainable from the broader state by restricting access. The conditioned state must be tied to a binding event with a definite outcome-relative channel. The binding measures must agree when fine-grained distinctions are grouped into coarser outcomes.

A useful consistency relation, developed more fully in the Born-rule derivation paper, is

$$
\mu_{F_P}(k)
=
\sum_{\alpha\in\pi^{-1}(k)}\mu_{F_i}(\alpha).
$$

Here $F_i$ is a finer-grained or child frame, $F_P$ is a parent or containing frame, and $\pi$ maps fine distinctions $\alpha$ to coarse outcome classes $k$. This relation says that the measure assigned to a coarse outcome must reconcile with the summed measures assigned to the finer outcomes that realize it.

In the present paper, this relation is not used to derive the Born rule. It is used to clarify why frame-relative state updates do not lead to chaos. Different frames may use different states because they have different access. But their descriptions must still connect through trace operations, conditioning operations, propagation histories, and containment maps.

This gives Frames Theory a middle path. It avoids universal collapse, but it also avoids unrestricted perspectivalism. Frames are local, but not isolated. Their descriptions are relative, but consistency-constrained.

## 7. Comparison With Existing Approaches

### 7.1 Copenhagen and Collapse-Based Views

In collapse-based language, projection is often treated as a real physical transition from a superposition to a definite state. Frames Theory keeps the projection rule but changes its status. Projection is a frame-relative update after binding, not a universal physical event.

This preserves local definiteness. A receiving frame really does stabilize to outcome $k$. What Frames Theory denies is that this local stabilization must be represented as an instantaneous transformation of the state for all frames.

### 7.2 Everettian or Many-Worlds Views

Everettian interpretations retain global unitarity and deny universal collapse. Frames Theory shares this no-universal-collapse orientation. A broader frame may describe measurement by a unitary entangled state.

The difference is emphasis. Everettian language often centers on branches. Frames Theory centers on receiving frames, accessibility, binding, and consistency. The question is not primarily which branch is real, but what state description is available to which frame, and how frame-relative updates reconcile across a network.

### 7.3 Decoherence Theory

Decoherence theory explains why interference between macroscopic alternatives becomes inaccessible and why pointer states become stable. Frames Theory is compatible with this account. Its contribution is to clarify whose state has decohered and relative to which accessibility boundary.

Decoherence is not treated as a hidden collapse mechanism. It is the environmental propagation and filtering of information such that certain coherences become inaccessible to particular receiving frames.

### 7.4 Relational Quantum Mechanics

Relational Quantum Mechanics holds that physical properties are relative to interacting systems. Frames Theory is close in spirit, but it adds additional vocabulary and structure: propagation, candidate binding sites, binding, actualization, and recursive consistency across frame networks.

This lets Frames Theory distinguish exposure from binding, binding from actualization, and local update from reconciliation across nested frames.

### 7.5 QBism

QBism interprets the quantum state as an agent's personal degrees of belief about future experience. Frames Theory also rejects observer-independent collapse, but it does not reduce frames to agents or beliefs. A frame may be a detector, environment, apparatus, record, or observer.

State update is therefore not merely personal belief revision. It is a physical informational update within a frame that has received or lost access to certain distinctions.

### 7.6 Objective Collapse Theories

Objective collapse theories modify quantum dynamics so that collapses occur under specified physical conditions. Frames Theory does not add such dynamics. It keeps standard quantum state-update rules and interprets them as frame-relative operations.

On this view, no new collapse mechanism is required. What is required is a careful indexing of state descriptions to frames and their accessibility conditions.

## 8. Limitations and Open Problems

This paper is intentionally limited.

It addresses projective measurements, Lüders updates, partial traces, reduced density matrices, and idealized decoherence in finite-dimensional or effectively finite-dimensional contexts.

It does not yet provide a full treatment of POVMs, weak measurements, continuous measurement, noisy measurements, quantum channels, error correction, entanglement swapping, relativistic quantum field theory, or quantum gravity.

It does not claim to solve the preferred-basis problem in an absolute sense. It reinterprets basis selection as frame-relative stabilization determined by coupling and accessibility. A fuller theory would need to specify the dynamics by which different frames acquire different stable bases.

It also does not claim new empirical predictions beyond standard quantum mechanics. The paper's contribution is interpretive and structural. It clarifies what the standard update operations mean if quantum states are understood as frame-relative informational descriptions.

Finally, no-signaling must be handled carefully. Frame-relative update does not imply controllable superluminal signal propagation. A frame may update its local state description after receiving binding information, but this does not allow it to transmit usable information outside the constraints of standard quantum theory.

These limitations mark the next steps for the research program.

## 9. Conclusion

Projection, partial trace, and decoherence are often treated as if they describe puzzling changes in the state of reality as a whole. Frames Theory offers a different interpretation. They are frame-relative state-update operations.

Projection is the update rule for a receiving frame after it binds to outcome-resolving information:

$$
\rho_F^{\mathrm{post}}
=
\frac{P_k\rho P_k}{\operatorname{Tr}(P_k\rho)}.
$$

Partial trace is the construction of the state available within a frame's informational boundary:

$$
\rho_S=\operatorname{Tr}_E(\rho_{SE}).
$$

Decoherence is the propagation and environmental stabilization of outcome-relevant information together with the loss of frame-accessible coherence:

$$
\rho_{\mathrm{eff}}
\approx
\sum_k |c_k|^2 |k\rangle\langle k|.
$$

These operations do not need to be read as universal collapse. They are rules for relating global or joint descriptions, frame-relative reduced descriptions, and actualized bound descriptions.

This completes the bridge between the Born-rule interpretation and the Born-rule derivation program. The Born-rule paper explains what probability measures: successful frame-binding. The present paper explains how state descriptions update relative to frames. The derivation paper then asks why the binding measure must take the quadratic form.

Together, these papers suggest a coherent frame-theoretic reading of quantum measurement: outcomes are locally definite, state updates are frame-relative, and consistency across frames replaces the need for universal collapse.
