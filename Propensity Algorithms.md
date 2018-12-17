### Propensity Score Matching (PSM)
  - A method used to mitigate bias problems
  - When an experiment is conducted, test subjects should be drawn randomly. As such, Randomized Control Trial (RCT) is the best way to get reliable results.
  - This is unviable in the real world, such as in clinical trials where subject distribution are bound to be biased. We cannot, for example, assgin random treatments to patients with varying conditions and degrees.
  - Thus we use PSM to alleviate possible convariances with Y (the independent variable) and \[ X_1..n \] (dependent variables)
 
 Consider the following example:
  A study on whether smoking has influence on lung cancer
  Subject A - age 24, smokes, 2 hours of exercise per week, 1 hours of exposure to asbestos daily
  Subject B - age 26, doesn't smoke, 0 hours of exercise per week, 3 hours of exposure to asbestos daily
  
  We attempt to explain the chance of lung cancer (independent variable) with smoking (dependent variable).In this case, however, many other
  factors may have covariance with lung cancer. To properly explain the causality of our independent variable, Propensity scores are used to
  better balance our data.
