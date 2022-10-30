# htmlcolourchart

A minimal but useful colour chart implemented in CSS 

- across the centre of the page we sweep through all possible 100% saturated RGB colours
- this entire "spectrum" fadea to 100% white at the top of the window
- and to Black (0%) at the bottom

Resizes to fit whatever viewport it is in, should fill your devices screen in full screen mode.

Useful for checking linearity and clipping of displays or cameras. I made to it demonstrate the heinous over-saturation of the Android 12 update on the Motorol Edge 20 Fusion

Does NOT care about colour space, perceptual models, gamma, etc. It is a 100% 8-bit RGB thing.

[See it in action here](https://piersg.github.io/htmlcolourchart/)
