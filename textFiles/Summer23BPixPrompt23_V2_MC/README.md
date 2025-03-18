These are the jet energy correction text files for the `Summer23BPixPrompt23_V2` correction campaign
for 2024 samples.

The corrections should be applied to `Summer23BPix` MC simulation and `Prompt23`
prompt-reconstructed DATA.

The simulated response (MC truth) corrections for DATA and MC (`L2Relative`) are identical to
the previous release (`Summer23BPixPrompt23_V1`) and are based on the studies presented in [1].

The residual corrections for DATA (`L2Residual` and `L2L3Residual`) are based on `V2` from [2]
and are identical to the previous release, except for the pseudorapidity region with
(1.305 < $|\eta|$ < 2.5), where the `L2L3Residual` corrections have been clipped to a constant
value for $p_{T} < 30$ as a result of data/MC checks. The $|\eta|$ bins for the $p_{T}$
clipping are given by: [1.305, 1.479, 1.653, 1.930, 2.172, 2.322, 2.500]

[1] https://indico.cern.ch/event/1384092/#5-mctruth-for-ak8puppi-summer2
[2] https://indico.cern.ch/event/1389009/#4-virtual-l2l3res-for-summer23

