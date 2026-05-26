# Toward a Frames-Theoretic Derivation of the Born Rule

## Abstract

The Born rule states that if a quantum system is prepared in the state $|\psi\rangle=\sum_k c_k|k\rangle$, then the probability of outcome $k$ is $|c_k|^2$. A prior Frames Theory interpretation identifies this quantity as a frame-binding measure: the measure by which a receiving frame becomes informationally bound to an outcome-relative state. At the quantum level, such binding begins as entangling correlation between a system and a receiving frame, then becomes stable through decoherence, accessibility, and recursive consistency across frames. The present paper asks why that measure should take the quadratic Born form rather than some other function of amplitude. The argument developed here is conditional rather than absolute: if frame-binding measures must satisfy normalization, phase insensitivity, coarse-graining additivity, refinement invariance, and recursive frame-containment consistency, then the admissible measure is forced toward the quadratic form. The distinctive Frames Theory contribution is recursive frame-containment consistency: binding measures must reconcile across nested frames that resolve outcome structure at different levels of informational detail. This paper therefore offers a derivational pathway rather than a derivation from no assumptions. It aims to show how the Born rule can be understood as the unique stable measure compatible with frame-relative binding across a recursive informational network.

## 1. Introduction

The Born rule is one of the central mathematical facts of quantum theory. If a system is represented in a measurement basis as

$$
|\psi\rangle=\sum_k c_k|k\rangle,
$$

then the probability assigned to outcome $k$ is

$$
P(k)=|c_k|^2.
$$

The empirical success of this rule is not in dispute. The deeper question is why this rule has the form it does. Why should the relevant measure be $|c_k|^2$ rather than $|c_k|$, $|c_k|^4$, or some other function of the amplitude?

In the frame-binding interpretation of the Born rule, the quantity $|c_k|^2$ is not treated as the probability that one globally real outcome is selected from unreal alternatives. It is treated as the measure by which a receiving frame becomes informationally bound to an outcome-relative state. More precisely, $\mu_F(k)$ weights possible stabilized bindings arising from entangling correlations between a system and a receiving frame. In that interpretation, the Born rule is written as

$$
\mu_F(k)=|c_k|^2,
$$

where $\mu_F(k)$ is the binding measure for outcome $k$ relative to receiving frame $F$.

That interpretive move answers one question: what does Born probability mean? It does not yet answer a second question: why must the binding measure be quadratic?

This paper develops a conditional derivational program. It does not claim to derive the Born rule from no assumptions. Instead, it asks what constraints a frame-binding measure must satisfy if it is to remain stable under the informational operations that Frames Theory takes to be physically meaningful: phase changes that carry no accessible binding distinction, coarse-graining across frames of different resolution, unitary refinement of outcome channels, and reconciliation across recursive containment relations.

The central claim is:

> If a frame-binding measure is normalized, phase-insensitive, additive under coarse-graining, invariant under informational refinement, and consistent across recursive frame containment, then the quadratic Born form is selected as the admissible measure.

This claim should be read carefully. It is not a replacement for Gleason's theorem, decision-theoretic derivations, or envariance-based arguments. Rather, it gives a Frames Theory interpretation of why the assumptions behind Born-rule derivations are physically natural. It also adds a distinctively Frames-theoretic principle: recursive frame-containment consistency.

The structure of the paper is as follows. Section 2 reviews the minimal Frames Theory background. Section 3 defines a general frame-binding measure without assuming the Born form. Section 4 states five axioms for such measures. Section 5 formulates the Frame-Binding Measure Proposition. Section 6 gives a proof outline and non-circularity check. Section 7 compares the argument with existing Born-rule derivations. Section 8 discusses limitations and open problems. Section 9 concludes.

## 2. Frames Theory Recap

Frames Theory begins with the idea that physical description is always situated within a bounded informational context. A frame is a physical or informational system capable of carrying a state, entering relations with other frames, and preserving or propagating distinctions. A frame may be a detector, a laboratory, an observer, an environment, a data record, or any system capable of receiving and stabilizing information.

Observation is not identified with consciousness. It is directed information transfer. If one frame becomes correlated with another in a way that constrains its future state, an observation-like relation has occurred. Measurement is a special case in which a receiving frame becomes correlated with a quantum system in an outcome-resolving way.

For the purposes of this paper, five ideas from Frames Theory are needed.

**Receiving frame.** A receiving frame $F$ is a frame capable of becoming informationally correlated with a quantum system or outcome-relative state.

**Entangling correlation.** At the quantum level, the initial substrate of binding is an interaction in which the system and receiving frame become non-factorizably correlated.

**Binding.** Binding is the process by which a receiving frame becomes correlated with an outcome-relative state.

**Decoherent frame-binding.** Decoherent frame-binding is the stabilized form of binding in which environmental propagation and accessibility make an entangling correlation robust enough to support a frame-relative outcome.

**Actualization.** Actualization is the result of successful binding from the perspective of the receiving frame.

**Containment.** Frames may be recursively nested. A detector frame may be contained within an apparatus frame, which is contained within a laboratory frame, which is contained within a broader environmental or observer frame.

**Consistency.** Frames that describe overlapping informational content must be able to reconcile their descriptions where their domains overlap. In earlier Frames Theory notation, this can be represented by consistency functionals over shared informational neighborhoods, but the present paper requires only the conceptual point: frame-relative descriptions cannot assign incompatible measures to the same resolved outcome structure when one description is a refinement of another.

Paper 2 used these ideas to reinterpret the Born rule as a binding measure. Paper 3 asks whether the quadratic form can be motivated from the consistency requirements imposed by this frame network. The derivation concerns the measure over outcome channels produced by system-frame entangling interactions, not a measure over amplitudes considered apart from their role in possible bindings.

The present paper works in a restricted setting: pure states, a fixed outcome context, and idealized outcome channels. It does not solve the preferred-basis problem. It assumes that a relevant measurement context has already been specified by the interaction between the quantum system and the receiving frame.

## 3. General Frame-Binding Measures

Let a quantum system be represented in a fixed outcome context as

$$
|\psi\rangle=\sum_k c_k|k\rangle.
$$

In a measurement-like interaction with a receiving frame initially in state $|F_0\rangle$, the relevant binding channels are represented by

$$
|\psi\rangle_S|F_0\rangle
\longrightarrow
\sum_k c_k |k\rangle_S|F_k\rangle.
$$

The derivational question is why the measure over these possible system-frame binding channels must be quadratic in the amplitudes $c_k$.

In the Born rule, the outcome measure is

$$
P(k)=|c_k|^2.
$$

But a derivational argument should not assume this form at the beginning. Instead, define a general frame-binding measure

$$
\mu_F(k)=g_F(c_k),
$$

where $\mu_F(k)$ is the measure associated with receiving frame $F$ becoming bound to outcome-relative state $k$.

If the measure is insensitive to arbitrary phase, then it can be written as a function of the amplitude magnitude:

$$
\mu_F(k)=f(|c_k|).
$$

The question is then whether the function $f$ is constrained by frame-theoretic consistency requirements. The goal is not merely to choose a convenient function, but to determine what kind of function can survive changes in frame resolution, outcome refinement, and containment relations.

The derivational target is the quadratic form:

$$
\mu_F(k)=|c_k|^2.
$$

The rest of the paper asks how this form follows from five constraints.

## 4. Five Frame-Consistency Axioms

### 4.1 Axiom 1: Normalization

For an exhaustive outcome context, the binding measures must sum to one:

$$
\sum_k \mu_F(k)=1.
$$

This axiom states that if a receiving frame is placed in an outcome-resolving relation with a quantum system, then the possible outcome-relative bindings form a complete set for that context. The frame binds to some admissible outcome-relative state.

Normalization is not unique to Frames Theory. Any probability or measure-like account needs it. Its role here is to ensure that the total measure assigned to the admissible binding space is fixed.

### 4.2 Axiom 2: Phase Insensitivity

The binding measure for a resolved outcome cannot depend on an arbitrary phase convention:

$$
\mu_F(e^{i\theta}c_k)=\mu_F(c_k).
$$

Therefore the measure depends only on the magnitude of the amplitude:

$$
\mu_F(k)=f(|c_k|).
$$

The Frames Theory justification is direct. A receiving frame binds to informational distinctions that are physically available in the interaction. A phase convention that does not alter the outcome structure available to the receiving frame cannot alter the binding measure. If two descriptions differ only by such a phase, they cannot correspond to different frame-binding weights.

This does not mean that phase is never physically relevant. Relative phases can be observed through interference when the measurement context makes them available. The axiom is narrower: once a resolved outcome channel has been specified, arbitrary phase convention alone cannot change the measure assigned to binding to that channel.

### 4.3 Axiom 3: Coarse-Graining Additivity

If a receiving frame does not distinguish two mutually exclusive outcome channels $a$ and $b$, then the measure of the coarse-grained alternative is the sum of the measures of the fine alternatives:

$$
\mu_F(a\lor b)=\mu_F(a)+\mu_F(b).
$$

This expresses consistency between fine-grained and coarse-grained descriptions. A frame with higher resolution may distinguish two sub-outcomes. A coarser frame may register only their union. If both frames are describing the same underlying outcome structure at different resolutions, their binding measures must reconcile.

The Frames Theory justification is that a coarser frame cannot lose or gain total binding measure merely by failing to distinguish internal alternatives. If the alternatives are mutually exclusive and jointly represented as one outcome class at the coarser level, then the coarse measure must equal the sum of the fine measures.

This axiom must be handled carefully. Additivity is one of the places where Born-rule derivations can appear to import probability assumptions. The present paper makes the assumption explicit. It does not pretend that additivity is derived from nothing. Instead, it argues that additivity is physically motivated by frame-resolution consistency.

### 4.4 Axiom 4: Refinement Invariance

Suppose an outcome channel with amplitude $c$ is refined into $n$ equal-amplitude subchannels:

$$
c|k\rangle
\longrightarrow
\sum_{j=1}^{n}\frac{c}{\sqrt n}|k,j\rangle.
$$

In a frame-binding context, this can be read more concretely as a refinement of possible system-frame binding channels:

$$
c|k\rangle_S|F_k\rangle
\longrightarrow
\sum_{j=1}^{n}\frac{c}{\sqrt n}|k,j\rangle_S|F_{k,j}\rangle.
$$

This refinement changes the informational resolution of the channel, but it should not change the total binding measure associated with the original outcome class. Therefore

$$
\mu(c)=n\,\mu\left(\frac{c}{\sqrt n}\right).
$$

This condition is naturally satisfied by the quadratic measure:

$$
|c|^2
=
n\left|\frac{c}{\sqrt n}\right|^2.
$$

The Frames Theory justification is that refinement introduces additional distinguishable substructure inside an outcome channel, but does not create new total binding weight for the original channel. If a child frame resolves the subchannels $|k,j\rangle$ while a parent frame registers only $k$, then their measures must agree when the fine distinctions are summed.

Axiom 4 is powerful, and it is also where the derivation is most vulnerable to circularity objections. The paper therefore treats it as an explicit physical constraint: unitary informational refinement of a binding channel should not alter the total measure assigned to that channel.

### 4.5 Axiom 5: Recursive Frame-Containment Consistency

The preceding axioms constrain a measure within a fixed outcome context. Frames Theory adds a further requirement: measures must remain consistent across recursively nested frames.

Let $F_i$ be a finer-grained or child frame, and let $F_P$ be a parent or containing frame. Suppose the child frame distinguishes outcomes $\alpha$, while the parent frame registers only the coarser outcome class $k$. Let

$$
\pi: \alpha \mapsto k
$$

be the map from fine-grained distinctions to parent-frame outcome classes. Then the parent-frame measure must equal the sum of the child-frame measures over all fine outcomes that map to $k$:

$$
\mu_{F_P}(k)
=
\sum_{\alpha\in\pi^{-1}(k)}\mu_{F_i}(\alpha).
$$

This is recursive frame-containment consistency.

It is the distinctively Frames-theoretic axiom. Standard Born-rule derivations constrain probability measures over Hilbert-space structures, branch weights, or rational expectations. Recursive frame-containment consistency constrains measures across a physical network of frames. It says that the measure assigned to an outcome must be stable under changes of frame resolution.

For example, a detector may distinguish several microscopic entangling interaction channels that all correspond to the same macroscopic pointer state. Decoherence may then stabilize those channels into redundant records across the apparatus, laboratory, observer, and environment. The apparatus frame may register only the pointer state. The observer frame may register only the displayed result. If these are nested descriptions of the same measurement chain, then the measure assigned at the observer level must reconcile with the summed measures of the finer detector-level channels.

Without such a constraint, frame-relative actualization would become unstable across containment levels. A child frame could assign one total measure to a set of distinctions while the parent frame assigned another measure to the corresponding coarse outcome. That would undermine the coherence of the frame network.

## 5. The Frame-Binding Measure Proposition

The preceding axioms motivate the following proposition.

> **Frame-Binding Measure Proposition.** Let $\mu_F$ be a normalized measure over mutually exclusive outcome-bindings available to a receiving frame $F$ for a quantum system in the pure state
>
> $$
> |\psi\rangle=\sum_k c_k|k\rangle.
> $$
>
> Suppose the measurement context is fixed and the outcomes $|k\rangle$ are resolvable by the receiving frame. If $\mu_F$ satisfies normalization, phase insensitivity, coarse-graining additivity, refinement invariance, and recursive frame-containment consistency, then the admissible binding measure is the quadratic Born measure:
>
> $$
> \mu_F(k)=|c_k|^2.
> $$

This proposition should be read as a conditional result. It says that if the stated consistency requirements are imposed on frame-binding measures, then the quadratic form is selected. It does not claim that the axioms themselves are forced without physical assumptions. The work of the paper is to show that the assumptions are natural in a frame-theoretic ontology.

## 6. Proof Outline and Non-Circularity Check

### 6.1 Proof Outline

The proof begins by refusing to assume the Born form. Let the binding measure be

$$
\mu_F(k)=g_F(c_k).
$$

By phase insensitivity,

$$
\mu_F(e^{i\theta}c_k)=\mu_F(c_k),
$$

so the measure depends only on amplitude magnitude:

$$
\mu_F(k)=f(|c_k|).
$$

Now consider a channel of amplitude $c$ refined into $n$ equal-amplitude subchannels:

$$
c|k\rangle
\longrightarrow
\sum_{j=1}^{n}\frac{c}{\sqrt n}|k,j\rangle.
$$

By refinement invariance, the total measure assigned to the original channel must equal the sum of the measures assigned to the refined subchannels:

$$
f(|c|)=n f\left(\frac{|c|}{\sqrt n}\right).
$$

The quadratic function satisfies this equation:

$$
f(x)=x^2.
$$

Indeed,

$$
x^2=n\left(\frac{x}{\sqrt n}\right)^2.
$$

A broader functional argument can be sketched as follows. If refinement invariance holds for arbitrary equal refinements, then $f$ must scale under transformations $x\mapsto x/\sqrt n$ as

$$
f\left(\frac{x}{\sqrt n}\right)=\frac{1}{n}f(x).
$$

This is equivalent to scaling quadratically under amplitude magnitude:

$$
f(\lambda x)=\lambda^2 f(x)
$$

for refinement-compatible scaling factors $\lambda=1/\sqrt n$, and by continuity or regularity extension for the relevant domain. Thus

$$
f(x)=C x^2
$$

for some constant $C$.

Normalization fixes $C=1$ for normalized quantum states:

$$
\sum_k |c_k|^2=1.
$$

Therefore

$$
\mu_F(k)=|c_k|^2.
$$

Coarse-graining additivity ensures that this measure behaves correctly when fine alternatives are grouped:

$$
\mu_F(a\lor b)=\mu_F(a)+\mu_F(b).
$$

Recursive frame-containment consistency then ensures that the same measure survives changes of frame resolution:

$$
\mu_{F_P}(k)
=
\sum_{\alpha\in\pi^{-1}(k)}\mu_{F_i}(\alpha).
$$

Thus the Born measure is not only selected within a single outcome context; it is stable across a recursive network of frames.

### 6.2 What Is Rigorous and What Remains Heuristic

The proof outline contains both rigorous and heuristic elements.

The scaling argument from refinement invariance to quadratic dependence is mathematically sharp if sufficient regularity conditions are assumed for $f$, such as continuity or appropriate measurability. Without such conditions, pathological functions may need to be excluded explicitly.

The normalization step is standard once the state is normalized and the outcome context is exhaustive.

The most heuristic element is Axiom 5. Recursive frame-containment consistency is physically motivated by Frames Theory, but its full mathematical treatment requires a more precise account of frame maps, containment relations, and outcome-resolution morphisms. In this paper, Axiom 5 functions as a principled constraint rather than a fully developed theorem of frame topology.

### 6.3 Non-Circularity Check

A derivation of the Born rule must avoid assuming the rule in disguised form. The present argument does not begin with $\mu_F(k)=|c_k|^2$. It begins with a general measure $f(|c_k|)$.

Still, two assumptions do significant work.

First, coarse-graining additivity assumes that mutually exclusive alternatives contribute additively to the measure of their union. This is a probability-like assumption. The Frames Theory justification is that it expresses consistency between fine and coarse frame descriptions.

Second, refinement invariance assumes that splitting a channel into equal-amplitude subchannels should not alter the total measure of the original channel. This is the step that most directly selects the quadratic form. The Frames Theory justification is that informational refinement should alter resolution, not total binding weight. When the channel is a system-frame binding channel, refinement changes how the possible entangling correlations are resolved; it should not create additional total measure for the coarse binding that the parent frame records.

Thus the correct claim is not that the Born rule has been derived from no assumptions. The correct claim is that once the physically motivated consistency requirements of frame-binding are made explicit, the quadratic Born measure is the stable candidate.

## 7. Relation to Existing Born-Rule Derivations

### 7.1 Gleason's Theorem

Gleason's theorem shows that, for Hilbert spaces of dimension greater than two, any suitable noncontextual probability measure over projectors must take the trace form

$$
\mu(P)=\operatorname{Tr}(\rho P).
$$

For a pure state and rank-one outcome projector, this yields the Born rule.

Frames Theory does not need to dismiss or replace Gleason's theorem. Instead, it can treat Gleason as a mathematical constraint on admissible measures. The Frames Theory contribution is interpretive and structural: it identifies what the measure measures. The measure is not merely a formal probability assignment over projectors; it is a measure of possible frame-bindings.

Gleason constrains the form. Frames Theory supplies the ontology.

### 7.2 Deutsch-Wallace Decision Theory

Deutsch-Wallace arguments derive Born weights in Everettian quantum mechanics from rational decision-theoretic constraints. The central idea is that rational agents in a branching universe should weight future branches according to the Born measure.

Frames Theory differs in emphasis. It does not ground the Born rule primarily in rational preference, subjective uncertainty, or agent-centered decision theory. Its object is physical and informational: the binding of receiving frames to outcome-relative states.

This does not make decision-theoretic arguments irrelevant. They may describe how agents embedded in frame networks should reason once the binding measure is in place. But they are not the foundation of the measure in Frames Theory.

### 7.3 Zurek's Envariance

Zurek's envariance program derives Born weights from symmetries of entangled quantum states, especially environment-assisted invariance. It emphasizes that certain phase and amplitude relations are inaccessible to subsystems because of entanglement structure.

Frames Theory is sympathetic to this strategy. Phase insensitivity is closely related to the idea that inaccessible distinctions cannot alter locally available outcome weights. Decoherence and envariance may also help explain why certain frame states become stable outcome records.

The difference is that Frames Theory makes the receiving frame and containment network explicit. Envariance constrains weights through symmetry. Frames Theory adds the requirement that binding measures reconcile across nested frames with different informational resolutions.

### 7.4 Everettian Branch Weights

Everettian interpretations retain global unitary evolution and treat measurement as branching. Born probabilities are then understood as branch weights, rational credences, or measures over observer-relative futures.

Frames Theory also rejects universal collapse, but it does not make branch ontology the central explanatory object. The central object is the receiving frame and its binding relation to outcome-relative states. The quadratic measure weights possible frame-bindings rather than free-standing branches.

This allows Frames Theory to remain close to the unitary structure of Everettian quantum mechanics while giving probability a different ontological role.

## 8. Limitations and Open Problems

The present paper is intentionally limited.

First, the argument applies to pure states in a fixed outcome context. It does not solve the preferred-basis problem. Frames Theory suggests that basis selection is frame-relative and depends on the receiving frame's capacity to resolve and stabilize distinctions, but that is not a complete solution.

Second, the proof relies on explicit axioms. It is a conditional derivation, not a derivation from no assumptions. Additivity and refinement invariance must be defended physically rather than hidden.

Third, recursive frame-containment consistency is introduced here as a physically motivated principle, not as a fully formalized mathematical theory. A more rigorous treatment may require graph-theoretic, topological, or categorical methods for mapping fine frame distinctions to coarse frame outcomes.

Fourth, the argument has not yet been extended to mixed states, POVMs, weak measurements, noisy measurements, open-system dynamics, or quantum field theory.

Fifth, the paper does not propose new empirical predictions. Its contribution is conceptual and structural: it explains why the Born measure is the stable candidate for frame-binding in a recursively organized informational ontology.

These limitations are not incidental. They define the next stage of the research program.

## 9. Conclusion

Paper 2 interpreted the Born rule as a frame-binding measure. Paper 3 has asked why that measure should be quadratic.

The proposed answer is that a frame-binding measure must remain stable under the operations that Frames Theory treats as physically meaningful: phase changes that do not alter accessible outcome distinctions, coarse-graining across frame resolutions, unitary refinement of system-frame binding channels, and recursive containment between child and parent frames.

The resulting proposition is conditional:

> A normalized, phase-insensitive frame-binding measure that is additive under coarse-graining, invariant under informational refinement, and consistent across recursive frame containment is forced toward the quadratic Born form.

In symbols:

$$
\mu_F(k)=|c_k|^2.
$$

The distinctive contribution of Frames Theory is not merely to repeat standard probability axioms. It is to give those axioms a physical interpretation in terms of frame-binding and to add a recursive consistency condition across nested informational contexts.

This does not end the Born-rule problem. It sharpens it. It shows where the real assumptions lie, why they are natural within Frames Theory, and how the quadratic measure emerges as the only stable candidate for frame-relative actualization across a recursive frame network.
