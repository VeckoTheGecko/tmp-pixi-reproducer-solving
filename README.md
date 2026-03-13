## tmp-pixi-reproducer-solving

For some reasons outdated versions of hvplot were being pulled in

https://discord.com/channels/1082332781146800168/1481965828613083309

2f84ccd0cc1f9068885ede76620ef8cc0d072a48 shows that hvplot 0.8.1 was being pulled in, fb326f52e3b3942431f985de903acd8560050b1d shows that you can fix if you lower pin hvplot.

Really strangely, this stepped reproducing Fri Mar 13 around 13:05 Amsterdam time (i.e., solving on 2f84ccd0cc1f9068885ede76620ef8cc0d072a48 caused an updated hvplot to be pulled in).