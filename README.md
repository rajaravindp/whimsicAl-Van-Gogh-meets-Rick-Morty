# Transformative Image Synthesis using Stable Diffusion

<div style="display: flex; flex-direction: column; align-items: center; text-align: center;">
  <img src="https://github.com/rajaravindp/whimsicAl-VanGoghMeetsRickandMorty/assets/118573661/72a87d67-7dd7-47b2-a6a8-f74bb0dbee57" alt="vanGoghRick Morty_gif" width="45%">
  <img src="https://github.com/rajaravindp/whimsicAl-VanGoghMeetsRickandMorty/assets/118573661/1cfde6a0-7a63-4ae4-93dd-bd36744cd494" alt="VanGoghSimpsons_gif" width="45%">
</div>

The creation of the video involves leveraging Stable Diffusion, a cutting-edge AI technique that combines various models like VAE (Variational Autoencoder), CLIP (Contrastive Language-Image Pre-training), and UNET. Here's a breakdown of the process:

- Text to Embeddings: The chosen prompts, "Van Gogh style Simpsons digital art" and "Van Gogh style Rick & Morty digital art" undergoe transformation into text embeddings using CLIP, representing the semantic essence of the input.

- Latent Generation: UNET is employed to generate latent representations based on the text embeddings. These latents act as a bridge between textual input and visual output.

- Stable Diffusion Process: Through multiple iterations governed by Stable Diffusion, the AI model refines these latents, gradually evolving them while maintaining stability. This involves a careful balance of noise prediction and guidance.

- Image Decoding: The refined latents are then decoded using the VAE model, resulting in a sequence of images that collectively form the video frames.

- Video Assembly: The decoded images are compiled into a video, seamlessly transitioning between frames and creating a coherent visual narrative.

