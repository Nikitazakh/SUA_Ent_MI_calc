# SUA_Ent_MI_calc

All package versions necessary for running entropy and mutual information of spike train are available in the file requirements.txt.

The files must be launched strictly in the following sequence:
1. NEX to CSV.ipynb
2. CSV to ENCODED ISI.ipynb
3. ENCODED ISI to ENTROPY.ipynb
4. FINAL FILE PREP.ipynb

Each subsequent script uses results from the previous one. The first file NEX to CSV.ipynb works with the folder where .nex files are stored.

If you have any problems running the program or have questions about the approaches used, do not hesitate to contact us by email at zaharov.ni@phystech.edu.
