# Central Force Notes

## Definition
A **central force** is a force that:
- Acts on a particle along the line joining the particle to a fixed point (the center).
- Depends only on the distance $\( r \)$ from the center, i.e., $\( \vec{F} = F(r) \hat{r} \)$, where $\( \hat{r} \)$ is the radial unit vector.

Examples:
- Gravitational force: \( F(r) = -\frac{G M m}{r^2} \)
- Electrostatic force (Coulomb): \( F(r) = \frac{k q_1 q_2}{r^2} \)

## Key Properties
1. **Conservative Nature**:
   - Central forces are conservative if \( F(r) \) depends only on distance \( r \).
   - Implies the existence of a potential energy \( V(r) \), where \( \vec{F} = -\nabla V(r) \).
   - Work done is path-independent.

2. **Angular Momentum Conservation**:
   - Central forces produce no torque (\( \vec{\tau} = \vec{r} \times \vec{F} = 0 \)), since \( \vec{F} \) is parallel to \( \vec{r} \).
   - Angular momentum \( \vec{L} = \vec{r} \times \vec{p} \) is conserved (\( \frac{d\vec{L}}{dt} = 0 \)).

3. **Motion in a Plane**:
   - Due to angular momentum conservation, the particle’s motion is confined to a plane perpendicular to \( \vec{L} \).

## Equations of Motion
- In polar coordinates (\( r, \theta \)), the Lagrangian for a particle under a central force is:
  \[
  L = \frac{1}{2} m (\dot{r}^2 + r^2 \dot{\theta}^2) - V(r)
  \]
- Lagrange’s equations yield:
  - Radial equation: \( m \ddot{r} = m r \dot{\theta}^2 - \frac{dV}{dr} \)
  - Angular equation: \( \frac{d}{dt} (m r^2 \dot{\theta}) = 0 \), implying \( m r^2 \dot{\theta} = l \) (constant angular momentum).

- Effective potential: 
  \[
  V_{\text{eff}}(r) = V(r) + \frac{l^2}{2 m r^2}
  \]
  The term \( \frac{l^2}{2 m r^2} \) is the centrifugal potential.

## Kepler’s Laws (for Gravitational Force)
For an inverse-square force (\( F = -\frac{k}{r^2} \)):
1. **Law of Orbits**: Orbits are conic sections (e.g., ellipses for bound orbits).
2. **Law of Areas**: Equal areas are swept in equal times (\( \frac{dA}{dt} = \frac{l}{2m} \)).
3. **Law of Periods**: For elliptical orbits, the period \( T \) satisfies \( T^2 \propto a^3 \), where \( a \) is the semi-major axis.

## Orbit Equation
- The orbit equation for a central force is derived using the substitution \( u = \frac{1}{r} \):
  \[
  \frac{d^2 u}{d\theta^2} + u = -\frac{m}{l^2} \frac{dV}{du}
  \]
- For inverse-square law (\( V(r) = -\frac{k}{r} \)):
  \[
  r = \frac{l^2 / (m k)}{1 + e \cos\theta}
  \]
  where \( e \) is the eccentricity (determines orbit shape: \( e = 0 \) for circle, \( 0 < e < 1 \) for ellipse, etc.).

## Stability of Orbits
- Circular orbits are stable if the effective potential \( V_{\text{eff}}(r) \) has a minimum.
- Condition for stability: \( \frac{d^2 V_{\text{eff}}}{dr^2} > 0 \) at the equilibrium radius.

## Applications
- Planetary motion (e.g., Earth around Sun).
- Satellite orbits.
- Atomic systems (e.g., electron orbiting nucleus in Bohr model).
- Scattering problems (e.g., Rutherford scattering).

## Notes
- Central forces simplify analysis due to symmetry and conservation laws.
- Non-central forces (e.g., magnetic forces) do not conserve angular momentum in the same way.
- For inverse-square forces, bound orbits are closed (ellipses), but other power-law forces (e.g., \( F \propto r^{-3} \)) may lead to non-closed orbits.

