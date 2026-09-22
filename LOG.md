# Research log

## 2026-09-21

**Context:** Starting a project on how prior expectations shape visual perception, and wether a person's priors can be recovered from their behaviour alone. Starting point: a Bayesian ideal observer for speed estimation, built around the slow-speed prior that explains why low-contrasy stimuli look slower than they are (Weiss et al. 2002; Stocker & Simoncelli 2006).

**Goal for this week:** A working Bayesian observer for a speed estimation task, with tests that check its behaviour (estimates biased toward slow speeds, bias growing with sensory noise) and a figure of perceived vs true speed at high and low contrast.

**Open questions:**
- Which priot shape? Gaussian is easy to reason about, but empirical estimates look closer to a power law, which is harder to handle near 0.
- Grid-based posterior or analytical solution? A grid is more flexible if the prior changes later; an analytical form is easier to fit.
- With a prior truncated at 0, the posterior mean may overshoot the true speed at very slow speeds. Is that a real prediction or an artefact of the model?
- What tests would actually convince me the observer behaves correctly?