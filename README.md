# ImageFiltering
Smoothing of noisy images.

Objective: Selects an n by n window size, switches the middle pixel of the window with the median value of the window.

To find the median value, we make use of the following algorithms:
  - Quickselect
  - Median of medians to avoid the worst case of Quickselect (which would be O(n^2))
  
To manipulate the images, we use the opencv library.
