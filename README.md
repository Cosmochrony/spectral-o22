# O22 Cosmochrony README

This repository contains the source of the **O22 Cosmochrony paper**  
[*Shell-Alignment from Projection Locking: A Discrete Admissibility Theorem under Born–Infeld
Saturation*](out/SpectralO22.pdf).

This work extends the **spectral admissibility sub-programme** by resolving
the first central open problem left by **O21**:

> Is shell-alignment an independent geometric hypothesis, or does it follow
> necessarily from the Born–Infeld admissibility structure and the
> non-injective projection $\Pi$?

## Context

**O21** established that:

- the physically relevant observable is the canonical fibre-level quantity
  $
  \sigma_{\mathrm{pair}}^{\mathrm{can}}(n)
  $
- the admissibility criterion can be reformulated intrinsically through the
  observable rank
  $
  n^{\mathrm{obs}}_3
  $
- the external amplitude parameter and the external threshold can be
  eliminated from the persistence criterion

However:

- shell-alignment remained a conjecture
- the geometric matching between continuous decay and discrete BFS structure
  was not yet derived
- the transfer
  $
  \delta_{\mathrm{pair}} \to \beta^*
  $
  therefore still depended on an open structural hypothesis

This defines the scope of **O22**.

## Core Result

The paper proves that **shell-alignment is a theorem, not a conjecture**.

The key mechanism is **projection locking**:

- the Born–Infeld condition defines a continuous saturation locus
- the non-injective projection $\Pi$ only realises observable states on
  admissible BFS-shell depths
- physical saturation can therefore occur only at the intersection
  $
  L_{\mathrm{BI}} \cap \mathbb{N}_q
  $

Central result:

- the saturation depth is not freely continuous
- it is discretely selected by admissible realisation under $\Pi$

Thus, the discreteness of the saturation rank is derived, not assumed.

## Main Structural Results

### 1. Discrete admissibility support

The observable space decomposes as

$
O = \bigsqcup_{n \in \mathbb{N}_q} O_n
$

where $\mathbb{N}_q$ is the set of projectively admissible shell depths.

This means that $\Pi$ cannot encode a saturation event at an arbitrary real
depth.

### 2. Continuous saturation locus

The fibre-level observable is treated as a discrete sampling of a continuous
effective decay law

$
\tilde{\sigma}(t) \sim C\, t^{-\delta_{\mathrm{pair}}}
$

inherited from the underlying $\chi$-relaxation dynamics.

The Born–Infeld admissibility constraint

$
A_n \leq \frac{c_\chi}{\sqrt{\lambda_n}}
$

therefore defines a saturation locus in continuous depth, with no intrinsic
reason to land on an integer.

### 3. Projection locking theorem

The central theorem shows that:

- Born–Infeld saturation alone gives a continuous candidate locus
- $\Pi$ acts as a discrete admissibility filter
- admissible saturation is therefore realised only when the continuous locus
  meets the shell support

Hence the physical saturation depth satisfies

$
n_{\mathrm{sat}} \in \mathbb{N}
$

because it belongs to

$
L_{\mathrm{BI}} \cap \mathbb{N}_q
$

### 4. Shell-alignment as a derived consequence

The shell-alignment condition of **O21** is recovered as a corollary.

This changes its logical status:

- **O21**: shell-alignment as a structural conjecture
- **O22**: shell-alignment as the observable signature of projection locking

The apparent resonance between continuous decay and discrete shell geometry is
no longer a primitive principle.

### 5. Foundational chain from the substrate

The derivation is fully internal to the framework:

$
c_\chi
\;\to\;
A_n^{\max} = \frac{c_\chi}{\sqrt{\lambda_n}}
\;\to\;
L_{\mathrm{BI}}
\;\to\;
L_{\mathrm{BI}} \cap \mathbb{N}_q
\;\to\;
n_{\mathrm{sat}} \in \mathbb{N}
$

No external parameter is introduced.

### 6. Separation from the next open problem

**O22** proves that saturation must occur on a shell.

It does not yet derive **which shell** is selected.

That remaining problem is precisely the scope of **O23**, where the target is
to explain the emergence of the threshold

$
\Sigma_c(n_3) = 3
$

and the privileged role of the three-dimensional stable sector.

## Mathematical Role of O22

**O22** performs the first foundational closure of the fibre-level
admissibility programme:

It replaces shell-alignment as a conjectured geometric match by
shell-alignment as a theorem of discrete admissible realisation.

More precisely, the paper:

- defines projectively admissible depths $\mathbb{N}_q$
- defines admissible realisation of saturation events
- proves that the support of $\Pi$ is discrete
- proves that the Born–Infeld saturation locus is continuous
- derives locking from the incompatibility between these two structures
- recovers shell-alignment as a corollary

## Epistemic Structure of the Paper

### Established input

- canonical fibre-level observable from **O19** and **O21**
- pair-level observable class from **O16** to **O18**
- non-injective projection $\Pi$
- Born–Infeld amplitude bound
- continuous $\chi$-relaxation dynamics

### New results

- definition of the admissible shell support $\mathbb{N}_q$
- definition of admissible realisation for saturation
- projection locking theorem
- derivation of shell-alignment
- reformulation of the **O21** geometric condition as a consequence

### Remaining open problems

- determine which shell is selected
- derive
  $
  \Sigma_c(n_3) = 3
  $
  from the substrate
- establish large-$q$ asymptotics of the locking mechanism
- extend the theorem beyond Heisenberg graphs

## Interpretation of the Result

The conceptual shift is decisive:

- **O21**: shell-alignment is required
- **O22**: shell-alignment is explained

This transforms the programme:

- from geometric matching
- to projection-induced discrete selection
- from conjectured resonance
- to derived locking

The core insight is that saturation is not merely a continuous threshold
crossing. It is a physically admissible realisation event, and such events are
constrained by the support of $\Pi$.

## Structural Role of O22

**O22** continues the sequence:

- **O16**: pair observable identified
- **O17**: pair dynamics derived
- **O18**: fibre structure derived
- **O19**: canonical amplitude normalisation
- **O20**: persistence criterion
- **O21**: intrinsic observable saturation rank
- **O22**: shell-alignment derived from projection locking

Thus:

- the observable is fixed
- the amplitude is canonical
- the saturation rank is intrinsic
- the shell condition is now derived

This is the first fully theorem-level closure of the shell-alignment problem.

## What O22 Adds

- projection locking as a new structural mechanism
- discrete admissibility support $\mathbb{N}_q$
- continuous Born–Infeld saturation locus $L_{\mathrm{BI}}$
- theorem:
  $
  L_{\mathrm{BI}} \cap \mathbb{N}_q \neq \varnothing
  \;\Rightarrow\;
  n_{\mathrm{sat}} \in \mathbb{N}
  $
- shell-alignment as a corollary
- foundational closure of the first open problem of **O21**

## Outcome

The spectral admissibility framework is now:

- fibre-level grounded (**O18**)
- amplitude-level canonical (**O19**)
- saturation-level intrinsic (**O21**)
- shell-level derived (**O22**)

The admissibility condition is now:

- physically meaningful
- structurally internal
- discretely realised
- theorem-level established

## Residual Open Problems

### Which shell is selected?

Derive the specific shell-selection rule rather than only shell-level locking.

### Threshold $3$

Explain why the relevant closure occurs at

$
\Sigma_c(n_3) = 3
$

and whether this follows necessarily from the stable directions selected by
$\Pi$.

### Large-$q$ asymptotics

Determine how the locking residual behaves as $q$ increases and whether
exact alignment emerges asymptotically.

### Universality

Test whether projection locking extends beyond Heisenberg Cayley graphs.

### Full transfer closure

Complete the unconditional derivation of

$
\delta_{\mathrm{pair}} \to \beta^*
$

once shell selection itself is derived.

## Status

The programme is now:

- structurally complete at the shell-alignment level
- theorem-level established at the locking level
- ready for shell-selection derivation in **O23**

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
Shell-Alignment from Projection Locking:
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
