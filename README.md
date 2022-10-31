What is this project ?
----------------------

This project is **NOT** the official LookingGlassVTKModule repository.

It is a fork of LookingGlassVTKModule sources hosted at https://github.com/Kitware/LookingGlassVTKModule

It is used as staging area to maintain topics specific to Kitware projects like [Slicer Custom Application](https://github.com/KitwareMedical/SlicerCustomAppTemplate#readme) or Extension that will eventually be contributed back to the official repository.


What is the branch naming convention ?
--------------------------------------

Each branch is named following the pattern `kitware-custom-app-YYYYMMDD-SHA{N}`

where:

* `kitware-custom-app` is the name of the custom application or extension. Two cases:
  * can be publicly disclosed: replace with the name of the application or extension (e.g `slicer`)
  * can **NOT** be publicly disclosed: use the literal prefix `kitware-custom-app` or `k12345-custom-app` where `12345` is the internal Kitware ID)
* `YYYYMMDD` is the date of the last official commit associated with the branch.
* `SHA{N}` are the first N characters of the last official commit associated with the branch.


Transfer from jcfr user to KitwareMedical organization
------------------------------------------------------

On 2022.10.31, the repository was transferred from the `jcfr` user to the `KitwareMedical` GitHub organization. This ensures that existing forks reference a project maintained by an organization. 

Note that prior to the transition, the following branches specific to the [SlicerLookingGlass](https://github.com/KitwareMedical/SlicerLookingGlass) extension were available at [jcfr/LookingGlassVTKModule](https://github.com/jcfr/LookingGlassVTKModule). Thanks to the automatic redirects setup by GitHub, existing references to `jcfr/LookingGlassVTKModule` are still valid.

| Branch | Historical Alias |
|--|--|
| [slicer-20200922-c0fe32e](https://github.com/jcfr/LookingGlassVTKModule/tree/slicer-20200922-c0fe32e) | `limit-clipping-range-to-limit-parallax` integrated upstream through [PR#10](https://github.com/Kitware/LookingGlassVTKModule/pull/10). |
| [slicer-20201002-f3b4c89](https://github.com/jcfr/LookingGlassVTKModule/tree/slicer-20201002-f3b4c89) | `support-building-as-external-module` associated with upstream [PR#9](https://github.com/Kitware/LookingGlassVTKModule/pull/9). |
