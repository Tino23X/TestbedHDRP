TestbedHDRP
===========

![gif](https://i.imgur.com/2qlNtFC.gif)
![gif](https://i.imgur.com/K3k5ffi.gif)

![gif](https://i.imgur.com/RQHKvIc.gif)
![gif](https://i.imgur.com/89atwYZ.gif)

This is a testbed project for [Unity HDRP] (High Definition Render Pipeline).
It contains several scenes that aim to try out the new functionalities of HDRP.
Please note that they're not necessarily useful nor showing right use of the
functionalities. I'm just trying to explore the possibilities of the new
features.

[Unity HDRP]: https://github.com/Unity-Technologies/ScriptableRenderPipeline/wiki/High-Definition-Render-Pipeline-overview

System requirements
-------------------

- Unity 2018.2 or later

How to use the project
----------------------

This repository includes some [submodules]. Before opening the project with
Unity, not only the repository itself but also these submodules have to be
synced up.

If you're using Git from the command line, please run `git submodule init` and
`git submodule update` in the project directory to sync the submodules. Or you
can just use the `--recursive` option when initially cloning the repository.

[submodules]: https://git-scm.com/book/en/v2/Git-Tools-Submodules

Acknowledgements
----------------

- The statues models used in the examples were scanned by Geoffrey Marchal. See
  the following page for further information.

  https://github.com/keijiro/DanishStatues

- The "Sponza" scene model was originally created by Marko Dabrovic and
  retouched by Kenzie Lamar and Morgan McGuire. See the following page for
  further information.

  https://github.com/keijiro/DabrovicSponza

- The photogrammetric textures used in displacement mapping examples were
  created by StruffelProductions. See the CC0Textures project page for further
  information.

  https://cc0textures.com

- The animation data used in the motion blur examples were captured by the
  Carnegie Mellon University Motion Capture Database project. See the following
  page for further information.

  https://github.com/keijiro/CMUMocap
