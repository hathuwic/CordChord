FOLDER CONTENTS:
- _main.pd - the Bela patch for dataset collection
- PC_side.pd - the computer patch for dataset collection
- output_2023-11-13 - the final dataset collected using these patches
- dataset_comprehension subfolder
	- dataset_comprehension.ipynb - a Jupyter Notebook for interpreting and plotting the dataset, helpful for looking for errors or missing values
	- figures subfolder - contains the saved figures showing the normalised sensor values at each position along the string, per displacement amount (30mm, 25mm, 20mm, 15mm, 10mm, 5mm)
- samples_by_pos.xlsx - a guide for how many samples to collect for each position and displacment combination

WHAT DO THESE PATCHES DO?

The PC_side patch sends bangs to the Bela patch to request real-time sensor data from the optical distance sensors, which is received and appended to a textfile object.

HOW TO USE

1. Load _main.pd onto Bela
2. Load PC_side on your PC
3. Use the ~ key on the keyboard to get 10 samples from each sensor at 100ms intervals