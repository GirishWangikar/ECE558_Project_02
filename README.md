# ECE558_Project_02
1. Two-dimensional convolution : 
Write a function to implement π = ππππ£2(π,π€, πππ), where
π is an input image (grey, or RGB), π€ is a 2-D kernel (e.g., 3 Γ 3 box
filter), and πππ represents the 4 padding type (see page 17 in the handout
notes of lecture 8): clip/zero-padding, wrap around, copy edge, and
reflect across edge, as illustrated in the following example (2nd to 5th
row).

2. Implementing and testing the 2-D FFT and its inverse using a built-in 1-D FFT algorithm : 
obtain a built-in routine that computes the 1-D FFT. For example, if you know how to integrate c/c++ functions to Matlab or Python. Use the built-in 1-D FFT to implement πΉ =
π·πΉπ2(π) from scratch, where π is an input grey image. Visualize the spectrum and phase angle image. When visualizing them,
apply the transform π  = log (1 + πππ (πΉ)) or others as you see fit. Using your DFT2 to implement the inverse FFT of an input
transform πΉ, π = πΌπ·πΉπ2(πΉ) from scratch.
