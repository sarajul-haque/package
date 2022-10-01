# Install:
pip install aesthetic-ascii

2. Generate an aesthetic ASCII visual:

from aesthetic_ascii import synthesize

# initialize drive object (to generate visuals)
drive = synthesize.Drive()
# generate a ASCII visual (dark_mode optional)
drive.generate(dark_mode=True)
# save to png
drive.to_png('aesthetic.png')