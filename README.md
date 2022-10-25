# roche-darwin-radau
Assessing Roche &amp; Darwin-Radau formulae of rotating stars

data for *Yoshida,S., Res. Notes AAS, 6, 27 (2022)*

paraN10.d: N=1 polytrope; paraN15.d: N=1.5; paraN30.d: N=3.0

 1st col. oblateness $f_{\rm obl}$;
 2nd col. rotational frequency $\omega$;
 3rd col. mass $M$;
 4th col. moment of inertia w.r.t the rotational axis $I_{zz}$
 
Note: 
  - $f_{\rm obl} = 1-R_p/R_e$, where $R_p$ and $R_e$ are the polar and the equatorial radius.
  - $M$ is normalized by $R_e^3\rho_c$ where $\rho_c$ is the central mass density.
  - $\omega$ is normalized by $\sqrt{4\pi G\rho_c}$.
  - $I_{zz}$ is normalized by $R_e^5\rho_c$.

In our normalization, the rotational frequencies are computed by the approximations as follows.

Roche approximation:
  
  $\omega_R = \sqrt{2f_{\rm obl}/(1-f_{\rm obl})}$.
    

Darwin-Radau apprpoximation:

  $\omega_{DR} = \sqrt{f_{\rm obl}\left(116 - 300C + 225C^2\right)/40}$,
  
  where $C=I_{zz}/MR_e^2$.
