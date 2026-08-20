# Pill

Live viewer: https://oscarbrendonn.github.io/pill/

Capsule built from pole-free icosphere topology (20k triangles, smooth shaded) with a hand-authored base colour texture matching the source icon exactly.

Colours sampled from the source: green `#5FCB88`, divider `#1D3934`, body `#FFFFFF`.

Clean-up applied: no lathe pole at the tips, constant-V mapping so there is no UV wrap seam, and clamp-to-edge sampling with an inset UV range so the tips never pick up colour from the far end of the texture.

- `pill_full.glb` -- full model, 4096 x 2048 texture
- `pill.glb` -- compressed copy used by the viewer

Artwork by @oscarbrencyrpto.
