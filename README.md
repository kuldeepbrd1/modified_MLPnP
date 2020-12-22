# Modified MLPnP
MLPnP solver modified for accurate scale recovery at large ranges

This is a modified implementation of the original [Maximum Likelihood Perspective-n-Points](https://github.com/urbste/MLPnP_matlab) solver. For details on the orginal algorithm, please refer to [MLPnP - A Real-Time Maximum Likelihood Solution to the Perspective-n-Point Problem](https://arxiv.org/abs/1607.08112)

##Modification:
Scale recovery for linear system solution is done with the intermediate singular value rather than a coarse three column norm that breaks down at larger relative ranges.

## Usage

To use the modified MLPnP, use `MLPnP_mod(points3D, v, cov)`
For original MLPnP, use `MLPnP(points3D, v, cov)`

### NOTE: Currently the modification is only for non-planar case.


...
Description for modification, and Monte-Carlo analysis coming soon...

If it is after November 2020 and I still haven't updated, please raise an issue and I will quickly update everything. I'm just in normal circumstances, lazy :)
