[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ptrick/synther-examples/master?urlpath=lab/tree/notebooks)

# Synther Examples

The main repository for synther is located [here](https://github.com/ptrick/synther).

This repository is for sharing some music production techniques using Synther.

## References

Check out the [docs](https://ptrick.github.io/synther-ref/).

## Getting Started (In Browser)

Click on the "Launch binder" button at the top.

## Getting Started (Locally)

Install [Anaconda](https://www.anaconda.com/). Then, to install the requirements, use:

```bash
conda env create
conda activate synther-examples
```

Then, to run the tutorials:

```bash
cd notebooks
jupyter lab
```

Happy hacking!

## The 'mysynthermods' library

Included with the examples is a python library that includes many helpful things as a starting point. Upon enviornment creation, this library is automatically installed with `pip install .` (per Binder requirements).

*Modules:*

* `arrangement` - A module useful for inputting musical pitches and timings according to music theory
* `displaywave` - A module useful for examining waveforms in charts