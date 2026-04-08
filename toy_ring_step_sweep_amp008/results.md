# Step Sweep: ring_ramp01_amp008 (distilled flowmap, 50 steps)

Configuration: `reward_ramp_end=0.1`, `ring_cycloid_amplitude=0.08`, `ring_cycloid_freq=12`, `flowmap_steps=50` (distilled), `ess_threshold=0.9`, `stochasticity_scale=0.1`

| Steps | Method | MMD | SW2 | Mean Reward | Resamples |
|-------|--------|-----|-----|-------------|-----------|
| **50** | No lookahead | 0.996 | 0.578 | 0.911 | 46 |
| | Denoiser | 3.973 | 0.988 | 0.917 | 47 |
| | **Flow-map** | **0.043** | **0.060** | 0.621 | 5 |
| **100** | No lookahead | 0.460 | 0.443 | 0.958 | 64 |
| | Denoiser | 4.131 | 0.979 | 0.949 | 81 |
| | **Flow-map** | **0.065** | **0.083** | 0.925 | 10 |
| **200** | No lookahead | 4.332 | 0.902 | 0.977 | 84 |
| | Denoiser | 3.016 | 0.942 | 0.964 | 135 |
| | **Flow-map** | **0.065** | **0.126** | 0.967 | 9 |
| **500** | No lookahead | 3.459 | 0.857 | 0.972 | 155 |
| | Denoiser | 3.717 | 0.977 | 0.976 | 198 |
| | **Flow-map** | **0.031** | **0.089** | 0.971 | 6 |
