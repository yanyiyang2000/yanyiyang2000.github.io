---
layout: default
title: Semiconductor
permalink: /semiconductor
---

## Effective Density of States $N_{\rm c}$ and $N_{\rm v}$

$$
N_{\rm c} = 2 \left( \frac{2 \pi m_{\rm n}^* k T}{h^2} \right)^{\frac{3}{2}}
$$

$$
N_{\rm v} = 2 \left( \frac{2 \pi m_{\rm p}^* k T}{h^2} \right)^{\frac{3}{2}}
$$

Where
- $N_{\rm c}$ is the effective density of states of conduction band$, $\rm cm^{-3}$
- $N_{\rm v}$ is the effective density of states of valence band$, $\rm cm^{-3}$
- $m_{\rm n}^*$ is the effective mass of electrons
- $m_{\rm p}^*$ is the effective mass of holes
- $k$ is the Boltzmann constant, $8.63 \times 10^{-5}\ \rm eV/K$
- $T$ is the temperature, $\rm K$
- $h$ is the Plank constant, $4.14 \times 10^{-15}\ \rm eV \cdot s$

## Intrinsic Carrier Concentration $n_{\rm i}$

$$
n_{\rm i} = \sqrt{N_{\rm c} N_{\rm v}} e^{-\frac{E_{\rm g}}{2 k T}}
$$

Where
- $E_{\rm g}$ is the band gap energy, $\rm eV$

## Carrier Concentration $n$ and $p$

$$
n = N_{\rm c} e^{-\frac{E_{\rm c} - E_{\rm F}}{k T}}
$$

$$
p = N_{\rm v} e^{-\frac{E_{\rm F} - E_{\rm v}}{k T}}
$$

Where
- $n$ is the concentration of electrons, $\rm cm^{-3}$
- $p$ is the concentration of holes, $\rm cm^{-3}$
- $E_{\rm c}$ is the conduction band energy, $\rm eV$
- $E_{\rm v}$ is the valence band energy, $\rm eV$
- $E_{\rm F}$ is the Fermi energy, $\rm eV$

## Fermi Level of Intrinsic Semiconductor $E_{\rm i}$

$$
E_{\rm i} = \frac{1}{2} (E_{\rm c} + E_{\rm v}) + \frac{3}{4} k T \ln \left( \frac{m_{\rm p}^*}{m_{\rm n}^*} \right)
$$

## Fermi Level of Extrinsic Semiconductors $E_{\rm F}$

For n-type semiconductor

$$
E_{\rm F} - E_{\rm i} = k T \ln \left( \frac{n}{n_{\rm i}} \right) \approx k T \ln \left( \frac{N_{\rm D}}{n_{\rm i}} \right)
$$

$$
E_{\rm F} - E_{\rm c} = k T \ln \left( \frac{N_{\rm D}}{N_{\rm c}} \right)
$$

For p-type semiconductor

$$
E_{\rm i} - E_{\rm F} = k T \ln \left( \frac{p}{n_{\rm i}} \right) \approx k T \ln \left( \frac{N_{\rm A}}{n_{\rm i}} \right)
$$

$$
E_{\rm v} - E_{\rm F} = k T \ln \left( \frac{N_{\rm A}}{N_{\rm v}} \right)
$$

Where
- $N_{\rm D}$ is the donor concentration, $\rm cm^{-3}$
- $N_{\rm A}$ is the acceptor concentration, $\rm cm^{-3}$
