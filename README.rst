===================================================================
CAMB Extension for Dark Matter–Dark Energy Momentum Transfer Model
===================================================================

Author: **Florencia Anabella Teppa Pannia**.

This repository contains a modified version of CAMB implementing 
a dark matter–dark energy (DM–DE) momentum transfer model, based on a series of peer-reviewed publications and a doctoral thesis. Any scientific use of this code requires citation of at least the first reference listed in the Citations section below.

Credits and Licence
=================================

This repository is a fork of CAMB (v.1.6.5): Code for Anisotropies in the Microwave Background, developed by Antony Lewis and Anthony Challinor (https://camb.info/).

Original CAMB repository: https://github.com/cmbant/CAMB

All original CAMB licensing, structure, and philosophy are preserved.

Description
==============================
*CAMB DM-DE momentum transfer* is a modified version of CAMB for computing cosmological perturbations with dark matter-dark energy momentum transfer. The physical model describes an elastic scattering (momentum transfer) interaction between Dark Matter and Dark Energy, following the theoretical framework developed in the references listed in the Citations section.

The model assumes a dynamical dark energy component with EoS parameter w≠1. The stregth of the interaction is quantified by the model parameter *alpaDMDE*, which should be specify as an extra cosmological parameter. The interaction modifies the velocity equations of DE and DM components at the level of linear perturbations. 

All modifications are indicated in the code with the flag *DMDE*. Most of the original schemes are kept commented out for ease of comparison.

The results presented in the papers listed in the Citations section below were obtained using `CAMB v.1.0.7 <https://github.com/cmbant/CAMB/releases/tag/1.0.7>`_ (Jul 31, 2019) and `CosmoMC <https://github.com/cmbant/CosmoMC>`_. All the modifications were migrated to the current version v.1.6.5 for better compatibility with `Cobaya <https://cobaya.readthedocs.io/en/latest/index.html>`_. 

A modified CLASS version for the same model by D. Figueruelo is also available at
https://github.com/david-figuer/CLASS_momentum_transfer

Citations (mandatory)
=================================
If you use this code in scientific work, please cite at least the first reference below. Additional citations are strongly encouraged when relevant.

- D\. Figueruelo, M. Aparicio Resco, F. A. Teppa Pannia, et al. , "J-PAS: forecasts for dark matter-dark energy elastic couplings" (`arXiv:2103.01571 <https://arxiv.org/abs/2103.01571>`_).
  
- J\. Beltrán Jiménez, D. Bettoni, D. Figueruelo, F.A. Teppa Pannia & S. Tsujikawa, "Probing elastic interactions in the dark sector and the role of 𝑆8" (`arXiv:2106.11222 <https://arxiv.org/abs/2106.11222>`_).
  
- J\. Beltrán Jiménez, D. Figueruelo, F.A. Teppa Pannia, "Nondegeneracy of massive neutrinos and elastic interactions in the dark sector" (`arXiv:2403.03216 <https://arxiv.org/abs/2403.03216v1>`_).
  
- J\. Beltrán Jiménez, D. Bettoni, D. Figueruelo, F.A. Teppa Pannia, "On evidence for elastic interactions in the dark sector" (`arXiv2410.18645 <https://arxiv.org/abs/2410.18645>`_).
  
- D\. Figueruelo, "Restrictions in the dark sector of the universe and modified gravity with large scale structure and gravitational waves" `PhD Thesis <https://inspirehep.net/literature/2722259>`_ (2023).
  
The model was first introduced in:

- M\. Asghari, J. Beltrán Jiménez, S. Khosravi & D.F. Mota, "On structure formation from a small-scales-interacting dark sector" (`arXiv:1902.05532  <https://arxiv.org/abs/1902.05532>`_). 

Contact
=======

Author: **Florencia Anabella Teppa Pannia**.

For questions, collaborations or issues, please open a GitHub issue 
or contact the author directly to fa.teppa.pannia@upm.es 

     
