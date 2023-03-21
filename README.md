# Can recurrent neural networks learn process model structure?

This repository contains all process models, code and resutls concerning the paper "Can recurrent neural networks learn process model structure?"

If using any of the code/data presented here please cite:
Peeperkorn, J., vanden Broucke, S. & De Weerdt, J. Can recurrent neural networks learn process model structure?. J Intell Inf Syst (2022). https://doi.org/10.1007/s10844-022-00765-x

The folder "Designed Models" contains the artificially generated models used (set 1).

The folder "Process Tree Generation" contains the notebooks used to generate and check the process trees (using the Process Tree generation tool of pm4py). Together with a folder containing both the trees and the converted petri nets.

The folder notebooks contains notebooks with code to do following tasks: playing out the process model and splitting the training and test logs, doing the hyperparameter search, training the LSTM and generating the simulated log and for evaluating (using our proposed metrics). Anther notebok contains the code used in Appendix B, the experiment which uses the inductive miner. 

The other folders contain the results for both hyper parameter searches.

You can find the csv's of all training, test and simulated (simple) event logs here: https://data.mendeley.com/datasets/g4mybythn3/1
