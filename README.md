The patch modifies Amber source code (including x-ray module) to handle 100000 residues. This is especially useful for supercell simulations. To apply the patch, execute in the the Amber source directory:

```patch -p1 < path/to/adjust_residues_limit.patch```