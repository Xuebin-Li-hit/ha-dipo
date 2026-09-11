# HA-DiPO

Project page for **HA-DiPO: Sequential Diffusion Policy Optimization for Heterogeneous Cooperative Transport**.

This static website contains the method overview, manuscript Figures 1 and 2, and simulation demonstrations. Figure 2 combines the onboard perception schematic with processing results from one static real-robot LiDAR scan. The featured MuJoCo video shows an 8 kg rod with a 4 kg attached mass and pitch commands clamped to ±0.02 rad. The four Isaac Lab motion clips and the additional MuJoCo rollout use the B2 + B2W policy evaluated on September 11, 2026 (1.5 m rod, native pitch bounds of ±0.04 rad). Two B2 + B2W perturbation clips use a 2 m rod; three B2 + B2 clips remain for illustration. Real-robot videos and paper, arXiv, and code links are forthcoming.

## GitHub Pages

When ready for public release, select **Settings → Pages → Deploy from a branch → main → / (root)**. The entry point is `index.html`; all assets use relative paths so the page works under a repository subdirectory.

No custom domain or build dependencies are required. The page retains a `noindex` directive; this does not make a published page private.
