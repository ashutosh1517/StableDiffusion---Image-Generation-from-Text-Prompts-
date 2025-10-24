Image generation from Text-prompts using SD-Turbo.

In this work, Text-prompts are loaded from a Google-doc file, and using SD-Turbo model, images are generated from those Text-prompts. Below is a quick description of the model. Info from original website.

Note: Due to updated Github configuration the Notebook's cell-outputs are cleared. So, to see the generated images look at the 'final_outputs' folder.

# Details - https://huggingface.co/stabilityai/sd-turbo
" SD-Turbo is a distilled version of Stable Diffusion 2.1, trained for real-time synthesis. 
SD-Turbo is based on a novel training method called Adversarial Diffusion Distillation (ADD), 
which allows sampling large-scale foundational image diffusion models in 1 to 4 steps at high image quality. 
This approach uses score distillation to leverage large-scale off-the-shelf image diffusion models as a teacher signal and combines this with an adversarial loss to ensure high image fidelity even in the low-step regime of one or two sampling steps.

Developed by: Stability AI
Funded by: Stability AI
Model type: Generative text-to-image model
Finetuned from model: Stable Diffusion 2.1 "
