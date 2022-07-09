# Wave-Function-Collapse
Wave Function Collapse is an algorithm for procedural generation of images.

WFC initializes output bitmap in a completely unobserved state, where each pixel value is in superposition of colors of the input bitmap (so if the input was black & white then the unobserved states are shown in different shades of grey). The coefficients in these superpositions are real numbers, not complex numbers, so it doesn't do the actual quantum mechanics, but it was inspired by QM. Then the program goes into the observation-propagation cycle:

- On each observation step an NxN region is chosen among the unobserved which has the lowest Shannon entropy. This region's state then collapses into a definite state according to its coefficients and the distribution of NxN patterns in the input.
- On each propagation step new information gained from the collapse on the previous step propagates through the output.


## Source of Algorithms and Implementation
<a href="https://github.com/mxgmn/WaveFunctionCollapse">Algorithm and Implementation Source</a>
<a href="https://discourse.processing.org/t/wave-collapse-function-algorithm-in-processing/12983">WFC Algorithm in Processing</a>

## Contribution

Feel free to contribute in the assignments section (which will be updated).

How to Contribute?

- Copy the link from the code button above either it can be SSH or HTTPs.
- Do the git cloning to your local repository
  - For SSH
  ```
  git clone git@github.com:Vishal-sys-code/Wave-Function-Collapse.git
  ```
  - For HTTPS
  ```
  https://github.com/Vishal-sys-code/Wave-Function-Collapse.git
  ```
- Select your Editor and do the PRs(Pull Requests).

Pull request Merging (Privacy Policy):
 - We will merge the pull request when we will check if every-thing is fine or not.
 
 
