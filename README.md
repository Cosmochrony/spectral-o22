This repository contains the source of the **O22 Cosmochrony paper**  
*Projection Locking of the Saturation Depth: A Discrete Admissibility Theorem under Born–Infeld
Saturation* (titled *Shell-Alignment from Projection Locking* up to version 1.18).

**Version 1.20.** Follows O19 1.3: §2.2 describes the O19 canonical observable as a case-dependent
proposal whose own residual factor is trivial ($r\equiv1$, O19 Lemma 2.4), no longer as a pipeline-independent combination
(O19's former Proposition 7.2 is now Open Problem 7.2); the reported values $r(c,q)\in\{1,2,3,4\}$
are a historical hypothesis, $r\equiv1$ on the real pipeline within O16's contract, and O17's
normalisation statement is internal to its toy model. Theorem 4.8 is unchanged.

**Version 1.19.** Withdraws the former Corollary 5.1, which recovered the shell-alignment conjecture of
**O21**. Its proof identified the O21 rank $n^{\mathrm{obs}}_3$ with the Born–Infeld saturation depth
$n_{\mathrm{sat}}$ by citing O21 Proposition 3.2, which only shows that $n^{\mathrm{obs}}_3$ does not
depend on the choice of reference shells under an exact power law. Nothing relates the threshold $9/q^2$
to the Born–Infeld saturation value, and $n^{\mathrm{obs}}_3$ scales as $\lambda^{1/\delta}$ under
$\sigma\mapsto\lambda\sigma$ (O21 1.3). The O21 conjecture remains open; Theorem 4.8 is unchanged and
concerns $n_{\mathrm{sat}}$ only. Labels and numbering are kept: Remark 5.1 records the withdrawal.
The abstract no longer states that the pair observable governs the charged-lepton mass hierarchy: that
comparison is a research motivation, and none of O16–O21 establishes it. The threshold
$\Sigma_c(n_3)=3$ is a supplied selection rule (**O24**).

## Question

> Within a model of physical realisation under the non-injective projection $\Pi$, can the Born–Infeld
> saturation depth fall between two BFS shells?

## Core result

Theorem 4.8 (projection locking):

- the Born–Infeld condition defines a continuous saturation locus $L_{\mathrm{BI}}$
- a saturation event counts as physically realisable only if it is encoded on a BFS shell (condition (R2)),
  and the observable space is taken to decompose as $O = \bigsqcup_{n \in \mathbb{N}_q} O_n$
- a realisable saturation depth therefore lies in $L_{\mathrm{BI}} \cap \mathbb{N}_q$, hence
  $n_{\mathrm{sat}} \in \mathbb{N}$

The integer value follows from that definition of realisability together with the shell decomposition.
Theorem 4.8 does not establish that such a depth exists. Conditional on the supplied saturation scale, the chain

$c_{\mathrm{BI}} \;\to\; A_n^{\max} = \frac{c_{\mathrm{BI}}}{\sqrt{\lambda_n}} \;\to\; L_{\mathrm{BI}} \;\to\; L_{\mathrm{BI}} \cap \mathbb{N}_q \;\to\; n_{\mathrm{sat}} \in \mathbb{N}$

introduces no further parameter; [A-cap] fixes neither the value of the scale nor its identification with
the spectral amplitude scale.

## What the paper does not establish

- the shell-alignment conjecture of **O21**, which concerns $n^{\mathrm{obs}}_3$, not $n_{\mathrm{sat}}$
- the logarithmic commensurability condition of O21 as a signature of locking
- which shell the saturation depth selects
- the threshold $\Sigma_c(n_3)=3$, which stays a supplied selection rule; reading it as three physically
  stable directions is an interpretive hypothesis
- any link between the pair observable and the physical lepton mass hierarchy
- a native growth carrier: shell selection alone cannot repair the refuted cross-substrate prescription
  $\beta^*=1/(\delta_{\mathrm{pair}}+1/2)$

## Epistemic structure

### Inputs

- canonical fibre-level observable proposed in **O19** (not established as pipeline independent) and the crossing rank of **O21**
- pair-level observable class from **O16** to **O18**
- non-injective projection $\Pi$ and the shell decomposition of its observable space
- Born–Infeld amplitude bound with a supplied saturation scale
- continuous $\chi$-relaxation dynamics (sketch-level continuous decay law)

### Results

- definition of the admissible shell support $\mathbb{N}_q$ and of admissible realisation
- projection locking theorem for the saturation depth (Theorem 4.8)
- withdrawal of the former shell-alignment corollary (Remark 5.1)

### Open problems

- the O21 shell-alignment conjecture and any relation between $n^{\mathrm{obs}}_3$ and $n_{\mathrm{sat}}$;
  a large-$q$ campaign over many conjugate pairs would test that conjecture, not Theorem 4.8
- which shell is selected
- the threshold $\Sigma_c(n_3)=3$
- extension beyond Heisenberg graphs

## Position in the sequence

- **O16**: pair observable identified
- **O17**: pair dynamics derived
- **O18**: Born–Infeld parity established as a covariance of the response family; the fibre identification
  stated as an open problem
- **O19**: canonical amplitude normalisation proposed, not established as pipeline independent
- **O20**: persistence criterion
- **O21**: crossing rank free of fitted parameters, for a fixed normalisation
- **O22**: projection locking of the saturation depth

## Repository Structure

```text
paper/
├── out/      # Compiled O22 PDF
├── tex/      # LaTeX sources
└── README.md
```

# Citation

If you reference this work, please cite:

J. Beau
Projection Locking of the Saturation Depth:
A Discrete Admissibility Theorem under Born–Infeld Saturation
Zenodo, 2026.

# Acknowledgements

Portions of the derivations, conceptual synthesis, structural organisation,
and editorial refinement benefited from iterative interactions with large
language models used as analytical assistants.

All theoretical results, computations, and interpretations remain the sole
responsibility of the author.

# Contributions

This repository is intended as a research reference.

Critical feedback, independent verification, and further analysis of:

- projection locking
- shell-level admissibility
- Born–Infeld saturation
- fibre-level observables
- shell-selection mechanisms

are welcome.

Please open an issue to discuss conceptual points, technical details, or
possible extensions.
