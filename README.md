# Machine Failure Prevention with Predictive Maintenance  

## Introduction  

FOSS Proprietary, Inc is gathering several types of data for its fleet of servers.  These servers have three operating modes: *normal*, *faulty* and *failed*.   The servers run all the time, and usually they are in normal mode.  However, in the event that the server enters faulty mode, the company would like to be aware of this as soon as possible.  This way they can take preventative action to avoid entering failed mode.

They collect four kinds of timeseries data for each server.  When a server is operating in *normal* mode the data behaves in a fairly predictable way, but with a moderate amount of noise.  Before a server fails it will ramp into *faulty* mode, during which the data appears visibly quite different.  Finally, when a server fails it enters a third, and distinctly different, *failed* mode where all signals are very close to 0.

## Process  

Machine_Failure_Prevention_with_Predictive_Maintenance.ipynb demonstrates the use of Fast Fourier Transformation (FFT) to obtain signature frequency and amplitude patterns in timeseries for use in prediction of operating modes.
