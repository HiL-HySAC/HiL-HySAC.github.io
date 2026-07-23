# Project information

## Title

**Real-World RL with Hybrid Action Spaces and Multi-head Critic via Centralized
Training with Decentralized Execution for Robot Manipulation**

## Authors

1. Changhao Li — HHCM, Istituto Italiano di Tecnologia; DIBRIS, University of
   Genoa — [ORCID](https://orcid.org/0009-0006-1754-0283)
2. Yifang Zhang — HHCM, Istituto Italiano di Tecnologia; DIBRIS, University of
   Genoa — [ORCID](https://orcid.org/0000-0002-7639-4232)
3. Heng Zhang — Human-Robot Interfaces and Interaction Lab, Istituto Italiano
   di Tecnologia; DRIM and University of Genoa —
   [ORCID](https://orcid.org/0000-0003-4832-9668)
4. Arash Ajoudani — Human-Robot Interfaces and Interaction Lab, Istituto
   Italiano di Tecnologia —
   [ORCID](https://orcid.org/0000-0002-1261-737X)
5. Nikos Tsagarakis — DIBRIS, University of Genoa —
   [ORCID](https://orcid.org/0000-0002-9877-8237)

Contact: `changhao.li@papercept.net`

## Method summary

The method applies centralized training with decentralized execution (CTDE) to
hybrid-action reinforcement learning. Cartesian pose control and gripper control
are decoupled into two actor-agents. An omniscient joint critic coordinates
training, while a multi-head hybrid reward architecture decomposes the value
target into simpler sub-tasks. The grasp-head Q-value reshapes the policy loss,
and a worst-case constraint promotes safe exploration.

## Evaluation

The framework is evaluated on a robotic arm and a humanoid robot in four
real-world manipulation tasks:

- tennis-ball pick-and-place;
- banana pick-and-place;
- pot resetting; and
- lid covering.

The experiments use randomization zones approximately ten times larger than
prior work.

## Headline results

- Tennis-ball picking improves from 60% to 80% success: **+20 percentage
  points**, or approximately **33% relative improvement**.
- Banana picking improves from 60% to 90% success: **+30 percentage points**,
  or **50% relative improvement**.
- CTDE succeeds on manipulation tasks where the baseline entirely fails.

## Links

- Live site: <https://hil-hysac.github.io/>
- Videos and additional details: <https://ctderl.github.io/CTDE.github.io/>
- Website source: <https://github.com/HiL-HySAC/HiL-HySAC.github.io>

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
