# motifcompetesim_gillespie

Motif Gillespie Compete Simulation 
Grant Kinsler 
Written: 01/03/2016 
Last Update: 01/03/2016

motifcompetesim_gillespie_master.py is the master file of the simulation. 
Options used to indicate the parameters used in the run. Use --help option for more information on parameter options.

Example command line way to run a simulation (consisting of 2 trials of 100 rounds each, with various other parameters. Elongation data is suppressed in default): 
python motifcompetesim_gillespie_master.py --trials=2 --maxStrands=10 --maxStrandLength=7 --numCells=10 --numRounds=100 --elong=0.05 --motiflist=10000,01111 --biaslist=0.9,0.1 (--elongdata=False)

List of other necessary files:
motifcompetesim_gillespie_trial.py; runs a trial of the simulation 
motifcompetesim_gillespie_motifoutput.py; runs simulations and controls motif data csv output 
motifcompetesim_gillespie_allstrandoutput.py; controls all data csv output 
motifcompetesim_gillespie_fulltrialoutput.py; controls full trial 1 data dsv output 
motifcompetesim_gillespie_elongdataoutput.py; controls full trial 1 data dsv output 
motifcompetesim_gillespie_cell.py; defines Cell class 
motifcompetesim_gillespie_population.py; defines Population class
