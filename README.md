<img src="https://github.com/mitsuba-renderer/mitsuba2/raw/master/docs/images/logo_plain.png" width="120" height="120" alt="Mitsuba logo">

# Data Generator based on Mitsuba Renderer 2
Mitsuba 2 is one of the few of research-oriented rendering system that supports GPU. In the past creating rendered data for deep learning was the bottelneck since path-tracing with ten-thousands of samples consumes a lot of time on CPU. Mitsuba 2 allows to render scenes using CUDA and Optix which reduces the rendering time. 

# Added Features & Fixes
To render scenes with various camara settings and materials, I managed to add and fix some parts of mitsuba2. Modifications and additions might be based on my onwn implementations, or other people's pull requests. I will mention the original implementations. Please see the issues and pull requests for more informations.
## Plugins Missing
- [x] Sunsky
- [x] Coating
- [ ] Hair
- [ ] Cube

## Plugin Errors
- [ ] Envmap
- [ ] SRGBReflectance

# Why do we need a data generator for graphics?

## About Mitsuba 2

Please see the [documentation](http://mitsuba2.readthedocs.org/en/latest) for
details on how to compile, use, and extend Mitsuba 2.


Mitsuba2 was created by [Wenzel Jakob](http://rgl.epfl.ch/people/wjakob).
Significant features and/or improvements to the code were contributed by
[Merlin Nimier-David](https://merlin.nimierdavid.fr/),
[Guillaume Loubet](https://maverick.inria.fr/Membres/Guillaume.Loubet/),
[Benoît Ruiz](https://github.com/4str0m),
[Sébastien Speierer](https://github.com/Speierers),
[Delio Vicini](https://dvicini.github.io/),
and [Tizian Zeltner](https://tizianzeltner.com/).
