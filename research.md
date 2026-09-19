---
layout: default
title: Research
bodyClass: research
---

<div class="research-container">
  <div class="research-text">
    <p>
      Gravitational waves (GWs) are propagating perturbations in the spacetime metric driven by the rapid time evolution of an asymmetric mass distribution. Among the various sources of GWs, compact binary coalescences (CBCs) are of primary observational importance. In fact, all GW events detected by the LIGO-Virgo-KAGRA (LVK) network of detectors so far have originated from these merging pairs. My research focuses on the GWs emanating from CBCs. I mainly construct waveforms for waltzing binaries by studying their center-of-mass kinematics and the resulting waveform distortions to determine their formation channels and profile the environments that nurture them. 
    </p>
    <p>
      Broadly, my work revolves around three main directions: 
    </p>
    <ul>
      <li>Probing the merger environments on a single-event basis.</li>
      <li>Developing model-independent tests to characterize the GW signals.</li>
      <li>Probing the early Universe using GW astronomy and 21-cm cosmology.</li>
    </ul>
    <p>
      Below, I briefly describe these research directions:
    </p>
    <h3><span style="color: gold;">Waltzing Binaries and reconstructing the potential profile of their environment</span></h3>
    <p>
      The astrophysical processes that govern CBCs are at best partially understood, if at all. Several models have been proposed to explain their origin, but ascertaining the provenance and evolution mechanism of a given CBC is very challenging because these cannot generally be localized to their positions in the sky and, most of the time, lack additional electromagnetic signatures. While information about putative formation channels on a population level can still be speculated based on the intrinsic properties of the objects, such as mass ratios, eccentricities, and spins, one cannot, in general, pinpoint a formation channel on a single-event basis. A direct, event-by-event probe of the merger environment using GWs alone is therefore of great importance.
    </p>
    <p>
      Unlike a constant redshift (e.g., cosmological redshift), which is degenerate with the masses of CBCs, a time-varying Doppler shift of a CBC's centre-of-mass (CoM), such as one produced by a constant line-of-sight acceleration (LOSA), will modulate the GW signal it emits with respect to the one produced by an isolated CBC. In fact, any higher-order derivative of the line-of-sight velocity (LOSV) will do so. Specifically, the $n^{th}$-order derivative of the LOSV leads to modulations in GW signals at $-4n$ post-Newtonian (PN) order; e.g., LOSA modulates the GW signal at $-4$ PN order. Since the environments hosting these binaries have characteristic properties such as mass and potential profiles that govern the kinematics of the CoM of these binaries, they imprint themselves on the emitted GWs (see Figure below). Therefore, by studying the kinematics of the CBC's CoM, one can profile the environment and determine its formation channel at the level of an individual binary. This technique reveals the CBC formation channel as a byproduct and can also be used to profile dark matter (DM) spikes and probe the nature of DM. See the relevant papers in <a href="https://avinash-tiwari-at.github.io/assets/Pub_list.pdf" target="_blank">Publications</a>.
      <figure style="text-align: center;">
        <img src="/assets/Research/Profiling_Depict.jpg" alt="Project 1 figure" style="max-width:95%; border-radius:8px;">
        <figcaption style="font-size:0.975rem; color:gray; margin-top:5px;">
        A cartoon comparing the waveforms of GWs emitted from a binary in the absence of external gravitational fields (orange) and a binary under the influence of an external gravitational field (blue) sourced by a supermassive black hole (SMBH) and surrounding mass distribution. 
        </figcaption>
      </figure>
    </p>
    <p>
      In the context of a circular or eccentric outer orbit of the CBC's CoM, in the above scenario, we approximate the LOSV by its Taylor expansion in the limit where the observation duration is much shorter than the outer orbital period. However, this is not always satisfied. When the observation duration is comparable to or greater than the outer orbital period, a periodic non-relativistic LOSV in these orbits leads to modulations at 4PN order. In such scenarios, the modulated and unmodulated waveforms go in and out of phase repeatedly. The GIF below shows the evolution of the modulated and unmodulated GW strains for a fiducial $10-10 \, M_{\odot}$ BBH perturbed by an $8 \, M_{\odot}$ BH at a distance of 53158.5 km in a circular orbit.  
      <figure style="text-align: center;">
        <img src="/assets/Research/gw_insp_BH_as_third_dop_compressed.gif" alt="Project 1 figure" style="max-width:95%; border-radius:8px;">
        <figcaption style="font-size:0.975rem; color:gray; margin-top:5px;">
        A GIF depicting a three-body system consisting of a BBH and a BH orbiting their barycentre (top panel) and corresponding waveforms for the isolated BBH and BBH-BH scenario, accounting for the Doppler shift due to a time-varying line-of-sight velocity. 
        </figcaption>
      </figure>
      These modulations become particularly important for such three-body systems and CBCs in close outer orbits around SMBHs. In addition, these modulations can also be used to detect and characterize the circum-CBC exoplanets.
    </p>
    <h3><span style="color: gold;">Eccentricity Evolution Consistency Test (EECT)</span></h3>
    <p>
  Eccentric CBC detections are valuable as they can provide insights into the environments that nurture CBCs. However, a number of physical and <em>beyond-GR</em> effects could imitate, or be mimicked by, eccentric CBCs. The standard approach to ascertain that a detected CBC is eccentric is to employ Bayesian model selection, where the eccentric CBC hypothesis is compared against other hypotheses. Such an approach is not only computationally intensive and time-consuming, but could also be misleading if none of the models under consideration represents the true model. Alternatively, one can use a simple but powerful method, the <strong>eccentricity evolution consistency test (EECT)</strong>, to directly confirm or reject the eccentric hypothesis without needing to compare it against a plethora of other possible hypotheses. The key idea is that while spurious nonzero values of eccentricity at some reference frequency could be acquired when a non-eccentric CBC with additional effects is recovered with an eccentric CBC waveform model, the evolution of eccentricity with frequency will in general not be mimicked. The method compares the eccentricity recovered at a low reference frequency (e.g., 10 Hz), evolved to higher frequencies assuming GR, with eccentricities recovered at those same higher frequencies. A discrepancy between the two eccentricities at any reference frequency would violate the EECT and indicate the presence of a mimicker. The figure below shows an example of a truly eccentric signal (<strong>left panel</strong>) and a mimicker (<strong>right panel</strong>), demonstrating that this test can distinguish between the two. Specifically, if the eccentricity deviation &delta;<sub>e</sub> is consistent with zero within the 68% credible interval at all reference frequencies, the signal is truly eccentric; otherwise, it is a mimicker.
      <figure style="text-align: center;">
        <img src="/assets/Research/EECT_Example.jpg" alt="Project 1 figure" style="max-width:95%; border-radius:8px;">
        <figcaption style="font-size:0.975rem; color:gray; margin-top:5px;">
        <strong>LEFT PANEL</strong>: top panel shows violins representing eccentricity deviation $\delta_e$ plotted as a function of GW frequency for a null test wherein we inject an eccentric GW signal using the TaylorF2Ecc waveform model in zero noise and recover the binary parameters of the GW signal using the same waveform model, while the bottom panel shows the individual GR-predicted (left-half) and observed (right-half) eccentricity half-violins plotted as a function of GW frequency. <strong>RIGHT PANEL</strong>: violins representing  $\delta_e$ plotted against GW frequency for the case of non-spinning quasi-circular zero-noise injection corrected for the LOSA effect, with LOSA $= - 2.25 \times 10^{-4} \, \rm s^{-1}$. 
        </figcaption>
      </figure>
    </p>
    <p>
      The Figure below shows the application of EECT to GW200105, a CBC event consisting of a neutron star and a BH, observed in LVK's third observing run. Notice that it satisfies EECT within 68% confidence and therefore lends complementary support in favor of the eccentricity hypothesis, while also providing a novel test of the consistency of $e(f)$ with GR.
      <figure style="text-align: center;">
        <img src="/assets/Research/EECT_GW200105.jpg" alt="Project 1 figure" style="max-width:95%; border-radius:8px;">
        <figcaption style="font-size:0.975rem; color:gray; margin-top:5px;">
        <strong>LEFT PANEL</strong>: violins of the eccentricity deviation $\delta_e$ at different reference frequencies. The horizontal line at $\delta_e = 0$ represents zero deviation from GR. <strong>RIGHT PANEL</strong>: individual $e_{\rm obs}$ (right side) and $e_{\rm GR}$ (left side) posteriors at different reference frequencies for the same. In both panels, the dashed and the dotted lines represent the 90\% and 68\% credible intervals, respectively. 
        </figcaption>
      </figure>
    </p>
    <h3><span style="color: gold;">Gravitational Wave Informed Inference of 21-cm Global Signal Parameters</span></h3>
    <p>
  Understanding how and when the first stars and galaxies formed remains one of the central challenges in modern cosmology. These structures emerged during the transition from the Dark Ages to the Cosmic Dawn, a period that remains observationally unconstrained despite strong theoretical progress. During this epoch, neutral hydrogen absorbed a fraction of cosmic microwave background photons through its 21-cm hyperfine transition, producing a 21-cm absorption signal whose evolution encodes the early Universe’s thermal and ionization history. However, extracting the underlying astrophysical parameters from this signal is limited by severe parameter degeneracies, which cannot be resolved without independent observational probes. The next-generation GW detectors, such as Cosmic Explorer (CE), will observe BBH mergers up to very large redshifts and hence will detect a fraction of them formed within the redshift range $\sim 13-25$. The merger rate of these BBHs will depend on the star formation rate density (SFRD) at these redshifts, together with the BBH formation efficiency and a time delay distribution. Therefore, the merger rate of these BBHs can serve as a tracer of the SFRD in the redshift range $\sim 13-25$ and hence can improve the inference of parameters generating the 21-cm cosmic hydrogen signal, and help break degeneracies between them. 
    </p>
    <p>
      The Figure below shows the modeled 21-cm global signal for the fiducial SFRD: $\Psi = \Psi_0 e^{-\beta (z - z_0)}$.
      <figure style="text-align: center;">
        <img src="/assets/Research/21_cm_global_signal.jpg" alt="Project 1 figure" style="max-width:95%; border-radius:8px;">
        <figcaption style="font-size:0.975rem; color:gray; margin-top:5px;">
        The 21-cm global signal for a fiducial SFRD of the form $\Psi = \Psi_0 e^{-\beta (z - z_0)}$. The redshift range is taken to be $z\sim13-25$. Other parameters are set to $\Psi_0 = 0.0066 \, M_{\odot} \rm  Mpc^{-3} yr^{-1}$, $\beta = 4/5$, $z_0 = 17$, $f_{\alpha} = 6 \times 10^{37}$, $f_{Xh} = 3 \times 10^{-2}$. A Gaussian instrumental noise with standard deviation $\Delta T_b = 10 \, \rm mK $ has been added to the signal. 
        </figcaption>
      </figure>
    </p>
    <p>
      The Figure below shows the $1d$-posteriors of the 21-cm global signal parameters inferred without and with GW observations. The top panel shows that none of the parameters except $\beta$ are measured, even at a 90% credible level, while the bottom panel shows that when we use the GW posteriors on $\Psi_0$ and $\beta$  as priors while inferring the other 21-cm global signal parameters, the inference on these parameters improves significantly.
      <figure style="text-align: center;">
        <img src="/assets/Research/21_cm_post_noGW.jpg" alt="Project 1 figure" style="max-width:95%; border-radius:8px;">
        <img src="/assets/Research/21_cm_post_GW.jpg" alt="Project 1 figure" style="max-width:95%; border-radius:8px;">
        <figcaption style="font-size:0.975rem; color:gray; margin-top:5px;">
        <strong>TOP PANEL </strong>: The $1d$-posteriors of the 21-cm global signal parameters using only the data from the 21cm observation, with no complementary GW information. <strong>BOTTOM PANEL </strong>: The inferred posteriors of 21-cm global signal parameters obtained using both the 21-cm signal observation as well as the GW hierarchical inference results. Blue histograms correspond to inference involving 100 GW events, while the brown histograms correspond to 1000 GW events. The black dashed lines represent the true values, while the light blue and brown shaded regions represent the 90% credible intervals.
        </figcaption>
      </figure>
    </p>
  </div>
</div>

