
<div align="center">
    <br>
    <img src="https://github.com/Djdefrag/QualityScaler/blob/main/Assets/logo.png" width="175"> </a> 
    <br><br> QualityScaler - image/video AI upscaler app (BSRGAN) <br><br>
    <a href="https://jangystudio.itch.io/qualityscaler">
         <img src="https://user-images.githubusercontent.com/86362423/162710522-c40c4f39-a6b9-48bc-84bc-1c6b78319f01.png" width="200">
    </a>
</div>
<br>
<div align="center">
    <img src="https://user-images.githubusercontent.com/32263112/220398451-6945d091-cdf1-4c9d-ba1d-ce0aeba24268.PNG"> </a> 
</div>

## What is QualityScaler?
Qualityscaler is a Windows app that uses BSRGAN Artificial Intelligence to enhance, enlarge and reduce noise in photographs and videos.

## Other AI projects.🤓

https://github.com/Djdefrag/RealESRScaler / RealESRScaler - image/video AI upscaler app (Real-ESRGAN)

https://github.com/Djdefrag/FluidFrames.RIFE / FluidFrames.RIFE - video AI interpolation app (RIFE-HDv3)


## Citations. ❤

https://80.lv/articles/80-level-digest-great-ai-powered-tools-for-upscaling-images/

https://timesavervfx.com/ai-upscale/

## Credits.

BSRGAN - https://github.com/cszn/BSRGAN | https://arxiv.org/abs/2103.14006

## How is made. 🛠

QualityScaler is completely written in Python, from backend to frontend. 
External packages are:
- AI  -> torch / torch-directml
- GUI -> tkinter / tkdnd / sv_ttk
- Image/video -> openCV / moviepy
- Packaging   -> pyinstaller
- Miscellaneous -> pywin32 / win32mica

## Requirements. 🤓
- Windows 11 / Windows 10
- RAM >= 8Gb
- Directx12 compatible GPU:
    - any AMD >= Radeon HD 7000 series
    - any Intel HD Integrated >= 4th-gen core
    - any NVIDIA >=  GTX 600 series

## Features.
- [x] Easy to use GUI
- [x] Image/list of images upscale
- [x] Video upscale
- [x] Drag&drop files [image / multiple images / video]
- [x] Automatic image tiling and merging to avoid gpu VRAM limitation
- [x] Resize image/video before upscaling
- [x] Multiple Gpu support
- [x] Compatible images - png, jpeg, bmp, webp, tif  
- [x] Compatible video  - mp4, wemb, gif, mkv, flv, avi, mov, qt 

## Next steps. 🤫

- [ ] Update 2.0 (now under development)
    - [ ] Python 3.11 (expecting ~30% more performance)
    - [ ] torch/torch-directml 2.0 (more performance)
    - [ ] a new completely redesigned graphical interface, with many more options for the user
    - [ ] upscaling of images and videos at once (currently it is possible to upscale a single image, a list of images or a single video)
    - [ ] upscale multiple videos at once
- [x] Switch to Pytorch-directml to support all Directx12 compatible gpu (AMD, Intel, Nvidia)
- [x] New GUI with Windows 11 style
- [x] Include audio for upscaled video
- [x] Optimizing video frame resize and extraction speed
- [x] Multi GPU support (for pc with double GPU, integrated + dedicated)
- [x] Python 3.10 (expecting ~10% more performance)


## Known bugs.
- [ ] When running QualityScaler as Administrator, drag&drop is not working

## Some Example.

#### Videos

![original](https://user-images.githubusercontent.com/32263112/209139620-bdd028f8-d5fc-40de-8f3d-6b80a14f8aab.gif)

https://user-images.githubusercontent.com/32263112/209139639-2b123b83-ac6e-4681-b94a-954ed0aea78c.mp4

#### Images

![test](https://user-images.githubusercontent.com/32263112/166690007-f1601487-7b94-4f2c-b4e2-436bc189a26e.png)

![Bsrgan x4](https://user-images.githubusercontent.com/32263112/168884625-c869baee-4cca-4a33-bdad-b65d9c29889d.png)

![Bsrgan x4 (2)](https://user-images.githubusercontent.com/32263112/197983965-40785dbd-78c6-48a0-a1eb-39d9c3278f42.png)

![Bsrgan x4 (3)](https://user-images.githubusercontent.com/32263112/197983979-5857a855-d402-4fab-9217-ee5bd057bd01.png)

![Bsrgan x4](https://user-images.githubusercontent.com/32263112/198290909-277e176e-ccb4-4a4b-8531-b182a18d566a.png)


