===========
nvidia-cuda
===========
Forked from: https://github.com/stackhpc/stackhpc-image-elements/tree/master/elements/nvidia-cuda

Install NVidia CUDA packages.

* ``DIB_NVIDIA_CUDA_REPO`` Path to the CUDA RPM/Deb repo.
  Default is ``https://developer.download.nvidia.com/compute/cuda/repos/$distro/x86_64``

* ``DIB_NVIDIA_CUDA_VERSION`` Version of CUDA to install
  Possible values include: ``8.0.44-1``, ``8.0.61-1``, ``9.0.176-1``, ``9.1.85-1``, ``9.2.88-1``,
  ``9.2.148-1``, ``10.0.130-1``, ``10.1.105-1``.
  Default is ``9.0.176-1``

* ``DIB_NVIDIA_CUDA_DELETE_REPO`` Delete the repo after building the image.
  Default is ``y``
