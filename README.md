# spiking-network-decoding

Izhikevich network with 1000 neurons (800 exc / 200 inh). We give it different input stimuli and try to decode
which one it was from the population firing rate with a simple Bayesian decoder, then play around with
connectivity, weights and how many neurons get the input. Everything is in the notebook, the report is
`report.pdf`.

Biggest effect was how many neurons receive the input. With 1% you can barely tell a sine from a delayed sine,
from 10% on it works perfectly in sparse networks. Denser connectivity actually made it worse.

No data needed, just `pip install -r requirements.txt` and run the notebook.
