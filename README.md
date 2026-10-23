# GWDataAnalysisSummerSchool

My course in gravitational wave data analysis at a summer school in
Copenhagen in 2017.

You can find video of my lectures (and others!) at
https://www.youtube.com/playlist?list=PL3oNS3JrakNBkY_bB2JZbUchKxXjWKlBh 


## Running the Notebooks (Potatoasad has ported these lectures to numpyro. This section is not by Will Farr!)

The models are written in [NumPyro](https://num.pyro.ai) (originally they
used PyStan).  Install [uv](https://docs.astral.sh/uv/), then from the root of
this repository run

    uv run jupyter lab

which creates an environment with everything needed for all three lectures.
Lecture 2 also needs the GW150914 data files; see the notebook for links.

Download those files (or just the first hdf5 file) and put them inside the lecture2 folder
