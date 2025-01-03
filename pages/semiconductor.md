---
layout: default
title: Semiconductor
permalink: /semiconductor
---

## Fermi Function

$$
f(E) = \frac{1}{1 + e^{\frac{E - E_{\rm F}}{k T}}}
$$

Where
- $E_{\rm F}$ is the Fermi energy, $\rm eV$
- $k$ is the Boltzmann constant, $8.63 \times 10^{-5}\ \rm eV/K$
- $T$ is the temperature, $\rm K$

Note that $f(E) = 0.5$ when $E = E_{\rm F}$ regradless the value of $T$. This implies that 50\% of states are occupied when $E = E_{\rm F}$.

---

## Effective Density of States $N_{\rm c}$ and $N_{\rm v}$

$$
\begin{equation*}
    \begin{split}
        N_{\rm c} &= 2 \left( \frac{2 \pi \cdot m_{\rm n}^* \cdot k \cdot T}{h^2} \right)^{\frac{3}{2}} \\[2ex]
        N_{\rm v} &= 2 \left( \frac{2 \pi \cdot m_{\rm p}^* \cdot k \cdot T}{h^2} \right)^{\frac{3}{2}}
    \end{split}
\end{equation*}
$$

Where
- $N_{\rm c}$ is the effective density of states of conduction band, $\rm cm^{-3}$
- $N_{\rm v}$ is the effective density of states of valence band, $\rm cm^{-3}$
- $m_{\rm n}^*$ is the effective mass of electrons
- $m_{\rm p}^*$ is the effective mass of holes
- $h$ is the Plank constant, $4.14 \times 10^{-15}\ \rm eV \cdot s$

---

## Intrinsic Carrier Concentration $n_{\rm i}$

$$
n_{\rm i} = \sqrt{N_{\rm c} N_{\rm v}} \cdot e^{-\frac{E_{\rm g}}{2 k T}}
$$

Where
- $E_{\rm g}$ is the band gap energy, $\rm eV$

## Carrier Concentration $n$ and $p$

$$
\begin{equation*}
    \begin{split}
        n &= N_{\rm c} \cdot e^{-\frac{E_{\rm c} - E_{\rm F}}{k T}} \\[2ex]
        p &= N_{\rm v} \cdot e^{-\frac{E_{\rm F} - E_{\rm v}}{k T}}
    \end{split}
\end{equation*}
$$

Where
- $n$ is the concentration of electrons, $\rm cm^{-3}$
- $p$ is the concentration of holes, $\rm cm^{-3}$
- $E_{\rm c}$ is the conduction band energy, $\rm eV$
- $E_{\rm v}$ is the valence band energy, $\rm eV$

---

## Fermi Level of Intrinsic Semiconductor $E_{\rm i}$

$$
E_{\rm i} = \frac{1}{2} (E_{\rm c} + E_{\rm v}) + \frac{3}{4} k \cdot T \cdot \ln \left( \frac{m_{\rm p}^*}{m_{\rm n}^*} \right)
$$

## Fermi Level of Extrinsic Semiconductors $E_{\rm F}$

For *n*-type material

$$
\begin{equation*}
    \begin{split}
        E_{\rm F} - E_{\rm i} = k \cdot T \cdot \ln \left( \frac{n}{n_{\rm i}} \right) \approx k \cdot T \cdot \ln \left( \frac{N_{\rm D}}{n_{\rm i}} \right) \\[2ex]
        E_{\rm F} - E_{\rm c} = k \cdot T \cdot \ln \left( \frac{N_{\rm D}}{N_{\rm c}} \right)
    \end{split}
\end{equation*}
$$

For *p*-type material

$$
\begin{equation*}
    \begin{split}
        E_{\rm i} - E_{\rm F} = k \cdot T \cdot \ln \left( \frac{p}{n_{\rm i}} \right) \approx k \cdot T \cdot \ln \left( \frac{N_{\rm A}}{n_{\rm i}} \right) \\[2ex]
        E_{\rm v} - E_{\rm F} = k \cdot T \cdot \ln \left( \frac{N_{\rm A}}{N_{\rm v}} \right)
    \end{split}
\end{equation*}
$$

Where
- $N_{\rm D}$ is the electron (donor) concentration, $\rm cm^{-3}$
- $N_{\rm A}$ is the hole (acceptor) concentration, $\rm cm^{-3}$
