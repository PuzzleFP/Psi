# Psi

_Rust-based numerical solver for quantum mechanical systems_

---

## Table of Contents
- [The Schrödinger Equation](#the-schrödinger-equation)
  - [The Time-Independent Schrödinger Equation](#the-time-independent-schrödinger-equation)
  - [The Time-Dependent Schrödinger Equation](#the-time-dependent-schrödinger-equation)
- [The Dirac Equation](#the-dirac-equation)
- [Idealized Cases of the Schrödinger Equation](#idealized-cases-of-the-schrödinger-equation)
  - [The Infinite Potential Well](#the-infinite-potential-well)
  - [The Harmonic Oscillator](#the-harmonic-oscillator)
- [Computing Arbitrary Hamiltonians](#computing-arbitrary-hamiltonians)

---

## The Schrödinger Equation

### The Time-Independent Schrödinger Equation
The time-independent Schrödinger equation is given by:

### Example 1: The Infinite Potential Well

In this model, the particle is free except at the two ends, x = 0 and x = a. The potential is described as the following

The Hamiltonian can then be constructed as the following

``

### Example 2: An

$$
\hat{H} \, \psi(x) = E \, \psi(x)
$$

where \( \hat{H} \) is the Hamiltonian operator, \( E \) is the energy, and \( \psi(x) \) is the wavefunction.

---

### The Time-Dependent Schrödinger Equation
The time-dependent Schrödinger equation is:

$$
i \hbar \frac{\partial \psi(x, t)}{\partial t} = \hat{H} \, \psi(x, t)
$$

This describes the evolution of the wavefunction \( \psi(x, t) \) over time.

---

## The Dirac Equation

The Dirac equation, which combines quantum mechanics and special relativity, is:

$$
(i \gamma^\mu \partial_\mu - m) \psi = 0
$$

where \( \gamma^\mu \) are the Dirac matrices, \( m \) is the particle's mass, and \( \psi \) is the spinor field.

---

## Idealized Cases of the Schrödinger Equation

### The Infinite Potential Well
In this case, the potential \( V(x) \) is zero inside a box and infinite outside, resulting in quantized energy levels.

---

### The Harmonic Oscillator
For a particle in a harmonic oscillator potential \( V(x) = \frac{1}{2} m \omega^2 x^2 \), the solutions are quantized energy states based on Hermite polynomials.

---

## Computing Arbitrary Hamiltonians

This section covers numerical methods for computing solutions to arbitrary Hamiltonians in quantum systems, including techniques like matrix diagonalization and time-evolution methods.
