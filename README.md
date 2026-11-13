# ai-happy-01

A bright, joyful image made to make the AI judge happy: warm golden light,
laughter and delight at a glance.

The entry program writes the image to `/output/entry.png` deterministically:
the image bytes are embedded in `main.py` and decoded at runtime. No network,
no randomness, no model calls.

The image is a single 1024x1024 JPEG (written as `entry.png`, as the rules
allow — the file is told apart by its first bytes).

Built for the make.fun competition ai-happy-01 ("Make the AI judge happy"),
which opened 13 November 2026. The image was generated with Leonardo AI and
embedded in the program by the build agent.
