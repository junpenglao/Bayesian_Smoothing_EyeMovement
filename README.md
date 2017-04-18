# Eye movement data analysis using Gaussian Process

Code, data and material for my presentation in Bayes@Lund 2017.

--

# Abstract
Statistical Inferences of Eye movement data using Bayesian smoothing  *Junpeng Lao*  Human observer performs rapid ballistic eye movements to sample visual information, with a combination of fixations and saccades. One of the challenges in the analysis of eye gaze is the sparseness of the data, as only one sample is observed at a given time point. One of the solutions is the usage of kernel smoothing. It is first applied as descriptive data representation (i.e., heat map), and later for statistical inference (e.g., *i*Map4, [Lao et al., 2016](https://github.com/iBMLab/iMap4)). However, it is impossible to infer the smoothing parameters (e.g., kernel size), as they are mostly fixed and chosen arbitrarily. A more natural solution is to use Gaussian Process. Bayesian inference on the kernel length scale of the covariance function can capture the actual smooth spatial-temporal effect, whereas the uncertainty of the observed data points is naturally expressed as the kernel variance. Here, I demonstrate the advantage of this approach on an eye movement study using dynamic stimuli.
