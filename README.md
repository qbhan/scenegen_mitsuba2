<img src="https://github.com/mitsuba-renderer/mitsuba2/raw/master/docs/images/logo_plain.png" width="120" height="120" alt="Mitsuba logo">

# Data Generator based on Mitsuba Renderer 2
Mitsuba 2 is one of the few of research-oriented rendering system that supports GPU. In the past creating rendered data for deep learning was the bottelneck since path-tracing with ten-thousands of samples consumes a lot of time on CPU. Mitsuba 2 allows to render scenes using CUDA and Optix which reduces the rendering time. 

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
