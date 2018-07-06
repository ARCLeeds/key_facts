As requested, over the next 12 months we will (probably) be losing:
  1/8th of Polaris (5312/8 = 664 cores, plus 192 private cores)
  Arc2: (3040 cores, plus 2352 private cores)
  Marc1: (1236 private cores, including a couple of 3TB RAM nodes)

  => 7484 cores (3704 public, 3780 private)

Arc4 will probably replace the 3040 we're losing from A2, but until we know how 
much we can spend we can't really estimate that core count.

Phi/KNL is a bit of a dead-end tech.
GPU is useful but we might want to consider spending in a similar way to A3, ie:
  First tranche of funding we buy a few GPUs and mostly general purpose nodes
  2nd tranche we take a greater look at novel architectures, should the community 
  wish.

That's assuming we alter the way we schedule cluster purchases. We currently
buy a completely new cluster every 2 years and retire after 4 (or so)
years. This has the advantage of always having two machines so that WHEN one
breaks, the other can be used.

The existing model probably remains the best practical option with biennial
procurements after all, as a new -> upgrade -> new -> upgrade cadence implies
running compute for much longer than 4 years to maintain this resilience.

