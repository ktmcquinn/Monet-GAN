# Monet Style Transfer using CycleGAN 🎨

This project applies Monet’s artistic style to photographs using CycleGANs trained on the "I’m Something of a Painter Myself" Kaggle dataset.

##  Dataset
- 300 Monet paintings (JPEG)
- 7028 real-world photos (JPEG)

##  Model
- CycleGAN with ResNet-style generators
- PatchGAN discriminators
- Losses: adversarial, cycle-consistency, identity

##  Evaluation
- MiFID score: `XXXXXXXXXXXX`
- Visual inspection confirms style transfer fidelity

##  Usage
1. Train model (`train_step`)
2. Export predictions (`images.zip`)
3. Submit to Kaggle
