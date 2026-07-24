# Project information

## Title

**Efficient Real-World Online Reinforcement Learning for Robot Manipulation via
Hybrid Actions and Reward-Decomposed Critics**

## Authors

1. Changhao Li — HHCM, Istituto Italiano di Tecnologia; DIBRIS, University of
   Genova — [ORCID](https://orcid.org/0009-0006-1754-0283)
2. Yifang Zhang — HHCM, Istituto Italiano di Tecnologia; DIBRIS, University of
   Genova — [ORCID](https://orcid.org/0000-0002-7639-4232)
3. Heng Zhang — Human-Robot Interfaces and Interaction Lab, Istituto Italiano
   di Tecnologia; DRIM and University of Genova —
   [ORCID](https://orcid.org/0000-0003-4832-9668)
4. Davide Torielli — HHCM, Istituto Italiano di Tecnologia; DIBRIS, University
   of Genova — [ORCID](https://orcid.org/0000-0002-7639-4232)
5. Damiano Gasperini — HHCM, Istituto Italiano di Tecnologia; DIBRIS,
   University of Genova —
   [ORCID](https://orcid.org/0000-0002-7639-4232)
6. Luca Muratore — DIBRIS, University of Genova —
   [ORCID](https://orcid.org/0000-0002-1265-3370)
7. Arash Ajoudani — Human-Robot Interfaces and Interaction Lab, Istituto
   Italiano di Tecnologia —
   [ORCID](https://orcid.org/0000-0002-1261-737X)
8. Nikos Tsagarakis — DIBRIS, University of Genova —
   [ORCID](https://orcid.org/0000-0002-9877-8237)

Contact: `changhao.li@papercept.net`

## Method summary

The method combines an RLPD-based human-in-the-loop online RL pipeline with
centralized training and decentralized execution (CTDE) and Hybrid Reward
Architecture (HRA). A continuous SAC actor controls 6-DoF Cartesian motion,
while a discrete SAC actor selects open, close, or stay for the gripper. Both
actors share a centralized critic decomposed into sparse task-reward and
potential-based grasp-reward Q-value heads. The decomposed Q-values are used to
reformulate the actor objectives for more stable and sample-efficient learning.

## Evaluation

The framework is evaluated on the Inail arm and Franka Emika Panda arm in three
real-world manipulation tasks:

- tennis-ball pick-and-place;
- banana pick-and-place;
- pot resetting.

The experiments use randomization zones approximately ten times larger than
prior work. Evaluation uses 20 episodes per task.

## Headline results

- Tennis-ball picking improves from 60% to 80% success: **+20 percentage
  points**, or approximately **33% relative improvement**.
- Banana picking improves from 60% to 90% success: **+30 percentage points**,
  or **50% relative improvement**.
- Pot resetting improves from 0% to **55%**.
- The average absolute improvement across the evaluated tasks is **35 percentage
  points**.
- The maximum absolute improvement is **55 percentage points** on pot reset.

## Links

- Live site: <https://hil-hysac.github.io/>

## Publication items still required

- official paper or preprint URL;
- final venue and publication year;
- official BibTeX;
- code, model, and dataset URLs, if they will be released;
- final method and results figures; and
- social preview image.

## Social preview guidance

Create a 1200 × 630 px preview image containing the project title, short
description, and one recognizable visual. Save it as
`assets/social-card.png` and add the `og:image` tag described in the README.

## Accessibility and release review

- All meaningful images have accurate `alt` text.
- Decorative images use empty `alt=""` or are hidden from assistive technology.
- Heading levels remain sequential.
- Text is understandable without relying on color alone.
- Links describe their destination.
- The page is usable with a keyboard.
- Reduced-motion preferences are respected.
- Content has been reviewed by at least one project author.
