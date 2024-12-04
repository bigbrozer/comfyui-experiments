# Outpainting

Outpainting in ComfyUI refers to a feature that allows users to extend beyond the boundaries of an image or canvas while editing. It enables seamless rendering and display of content beyond the visible area, providing a more comprehensive view of the entire composition. This feature is particularly useful for designers and artists who need to see the full context of their work.

## Requirements

### Checkpoints

* Base: [Juggernaut XL](https://civitai.com/models/133005/juggernaut-xl)
  * Inpaint: [Inpaint_SDXL_Pony (Jugger_inpaint_v8)](https://civitai.com/models/245423?modelVersionId=288402)

## Usage

1. Upload or select an image in **Load Image #3** node.
2. Adapt **🔧 Image Resize #19** to define the target image resolution.
3. Increase the picture in any desired directions from **Pad Image for Outpainting #4**.
4. Optionnaly, in **Tests** group, you can enable **Upscale Image By #21** node to quickly test (it will reduce the final resolution).
