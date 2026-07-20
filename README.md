# noxpix-models

Public hosting for the ONNX model weights that [NoxPix](https://noxframe.com.mx)
downloads on demand at runtime. The models are **not** bundled in the NoxPix
installer; the app fetches them from the release assets here on first use.

Each model is redistributed under its own original open-source license.

## Real-ESRGAN x4plus (`real_esrgan_x4plus.onnx`)
ONNX export of Real-ESRGAN x4plus, self-exported from the original weights.

## Background-removal models (`rembg-models-v1`)

Byte-identical mirrors of the ONNX models rembg downloads at first use,
re-hosted here so NoxPix does not depend on third-party release URLs staying
alive. Provenance and licenses are listed in the release notes; all are
free for commercial use with attribution (Apache-2.0 / MIT).

Copyright (c) 2021, Xintao Wang
Licensed under the BSD 3-Clause License.
Source: https://github.com/xinntao/Real-ESRGAN

See LICENSE for the full BSD-3-Clause text.
