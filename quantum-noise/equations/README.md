$$E=mc^2$$

$$
\left\{\frac{1}{2}\right\}
$$

$$P = G\left\( k_B T_{N} + \frac{k_B T}{2}\left[\left( \frac{eV_{audio}(t) + hf_{RF}}{2k_B T}\right)\coth{\left( \frac{eV_{audio}(t) + hf_{RF}}{2k_B T}\right)} + \left( \frac{eV_{audio}(t) - hf_{RF}}{2k_B T}\right)\coth{\left( \frac{eV_{audio}(t) - hf_{RF}}{2k_B T}\right)}\right]\right\)$$


$$P = G\left\{k_B T_{N} + \frac{k_B T}{2}\left[\left( \frac{e V_{peak}\sin{(2\pi f_{audio} t  + \psi_{audio})} + hf_{RF}}{2k_B T}\right)\coth{\left( \frac{eV_{peak}\sin{(2\pi f_{audio} t  + \psi_{audio})} + hf_{RF}}{2k_B T}\right)} + \left( \frac{eV_{peak}\sin{(2\pi f_{audio} t  + \psi_{audio})} - hf_{RF}}{2k_B T}\right)\coth{\left( \frac{eV_{peak}\sin{(2\pi f_{audio} t  + \psi_{audio})} - hf_{RF}}{2k_B T}\right)}\right]\right\}$$

$$P = G\left\{k_B T_{N} + \frac{k_B T}{2}\left[\textbf{xcothx}{\left( \frac{eV_{peak}\sin{(2\pi f_{audio} t  + \psi_{audio})} + hf_{RF}}{2k_B T}\right)} + \textbf{xcothx}{\left( \frac{eV_{peak}\sin{(2\pi f_{audio} t  + \psi_{audio})} - hf_{RF}}{2k_B T}\right)}\right]\right\}$$

$$P(t,\phi,\eta,\theta,\psi,\theta_N,G) = G\left\{\theta_N + \frac{\theta}{2}\left[\textbf{xcothx}{\left( \frac{\eta\sin{(2\pi f_{audio} t  + \psi_{audio})} + \phi}{2\theta}\right)} + \textbf{xcothx}{\left( \frac{\eta\sin{(2\pi f_{audio} t  + \psi_{audio})} - \phi}{2\theta}\right)}\right]\right\}$$

$k_B T$ is in units of pixels. P is in units of pixels. G is dimensionless linear gain. $eV_{audio}$ is in units of pixels. hf is in units of pixels.  In reduced form, $\theta = k_B T$, $\phi = hf_{RF}$, and $\eta = eV^{audio}_{peak}$, all measured in units of pixels with the same conversion between pixels and yoctojoules.


