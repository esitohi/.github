# [Project Esitohi]

Project Esitohi is a Github organization for the development of interactive, accessible, reproducible, and cutting-edge astrophotographic processing tools in Julia, oriented towards the technically inclined amateur astronomer.
We aim to combine existing Julia packages to create an environment that allows for the straightforward construction and execution of image processing pipelines, but also facilitates the development of new image processing tools that are designed to work with the tremendous amount of image information we generate on a good night.

## What's in our scope?

Any [free (as in freedom)](https://en.wikipedia.org/wiki/Free_software) Julia package intended for use by astrophotographers can be part of this organization.
This includes tools for obtaining image statistics (including image stacking), denoisers that can use more information than a final stack provides, spectrophotometric color calibration, continuum subtraction, sequence management, image registration, sensor calibration and characterization, aberration correction, machine learning tools, and free datasets for developers to work with.
We are also interested in tooling for processing other kinds of astronomical data (such as radio datasets; really anything an amateur astronomer can feasibly acquire), tooling that accomplishes common tasks in unusual ways (such as the use of geometric algebra), and tooling that makes astronomy accessible to those who have historically been left out (such as methods for producing audio or tactile data representations for the visually impaired).

Some kinds of general-purpose image and astonomical data processing tools may be better suited for the [JuliaImages] or [JuliaAstro] organization.
Packages of broad interest are open for transfer to suitable organizations who have a larger capacity for package maintenance than we do; just inquire if you're part of an organization that is interested in stewardship.

We would rather contribute to existing packages with functionality we desire than create new ones unless there is good technical reason to do so.
For example, Richardson-Lucy deconvolution implementations with regularizers already exist in Julia (like [DeconvOptim.jl]), so we have no need to create our own package for this purpose.
Instead, we encourage you to contribute directly to these projects if you want to provide extended functionality.

While we primarily aim to write Julia tools, tooling which can interoperate with Julia is also welcome and encouraged here, such as GUIs and other kinds of interfaces.
We'd also like to encourage the publication of educational guides explaining the technical details of astrophotography.
These guides do not have to be specific to Project Esitohi software; we would especially like to encourage educational materials that show how to accomplish the same task using multiple different software packages.

## FAQ

### How can I contribute my image data to this project?
Hold onto your data for now. Git isn't really made for committing huge FITS files, so we'll need an alternative hosting solution for that.
In the meantime, if you want to share processed images for free use, consider uploading them to [Wikimedia Commons].

### What other kinds of data would be useful for this project?
While we still need to figure out a file hosting solution for large data, we could use:
* Specifications of the transmittance of various astronomical filters, ideally taken with a spectrophotometer.
* Specifications of the optical designs of common amateur telescopes and ancillary optics other than Newtonians, with special attention given to designs that use aspheric surfaces.
* Error characterization (periodic error, nonperiodic error, backlash behavior) for guided mounts, especially strain wave mounts.

### What does Esitohi mean?
It's the Nʉmʉ Tekwapʉ̲ (Comanche) word for the Milky Way.

[Project Esitohi]: https://github.com/esitohi
[JuliaImages]: https://github.com/JuliaImages
[JuliaAstro]: https://github.com/JuliaAstro
[DeconvOptim.jl]: https://github.com/roflmaostc/DeconvOptim.jl
[Wikimedia Commons]: https://commons.wikimedia.org/
