# lstm-assisted-pri-tracking

## Introduction

The predictive capability of RNN-based machine learning models can be leveraged to predict the pulse time of arrivals of pulsed radars that utilise fixed, staggered, sliding or jittered pulse repetition intervals when transmitting signals.

## Hypothesis

If PRI patterns are correctly modelled, RNN-assisted PRI tracking can be a suitable basis for online pulse deinterleaving. Additionally, if sufficient training pulse TOA
data is available, an RNN-based ML model can be trained and used to improve the TOA prediction process during PRI tracking. This will be especially useful for pulsed signals
using staggered or jittered PRI patterns because the PRI between pulse TOAs constantly changes.
