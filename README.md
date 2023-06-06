# Project-on-Deblur-NeRF
Study Deblur-NeRF's mechanism and think.

The results are produced by the code [Deblur-NeRF](https://github.com/limacv/Deblur-NeRF)

[logs_exp](https://github.com/get-through/Project-on-Deblur-NeRF/tree/main/logs_exp) contains the videos, params and testsets (reconstruct from original view) after 200000 iterations, also metrics. The ones labelled full is the result of Deblur-NeRF, and the ones labelled naive is the result of pure NeRF.
Blur5grass is its original dataset, while blurtea and defocus drinks are shot by our own.
The original data we shot, run after COLMAP, and with resize to 25% of the size for quicker training, is [here]()

[tensorboard_exp](https://github.com/get-through/Project-on-Deblur-NeRF/tree/main/tensorborad_exp) contains the visualization of training loss, training PSNR, and four metrics on testset.

Videos are too big to be shown here, but viewing the defocus_full example, we can see that the background defocus blur has no enhancement, as the data we shot are always focused on one or more of the cans, but not the background. Also, it demonstrates an artifact possibly due to inconsistent light field.
