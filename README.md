# Awesome-GANs
## Generative Adversarial Networks (GANs) Variants

Generative Adversarial Networks (GANs) are machine learning frameworks where two neural networks—a generator and a discriminator—compete against each other to create realistic synthetic data. Since their inception, various specialized types of GANs have been developed to tackle specific generation challenges across different industries.

---

## 🏗️ Foundational & Basic GANs

* **Vanilla GAN:** The simplest and original GAN architecture. It utilizes basic Multi-Layer Perceptrons (MLPs) for both networks. Highly foundational but notoriously unstable during training.
* **Deep Convolutional GAN (DCGAN):** A massive improvement over the vanilla GAN. This architecture replaces fully connected layers with Convolutional Neural Networks (CNNs) to stabilize training. Primarily used for high-quality image generation.

## 🎯 Controlled & Labeled Generation

* **Conditional GAN (cGAN):** Introduces conditional parameters (like class labels or text descriptions) into both the generator and discriminator. This allows the user to explicitly dictate *what* gets generated (e.g., generating an image of a specific object based on a label).
* **Information Maximizing GAN (InfoGAN):** An extension of cGAN that learns disentangled representations in an unsupervised manner. It separates latent variables to independently control specific features like object angles, stroke widths, or facial emotions.

## 🔄 Image-to-Image Translation

* **CycleGAN:** A specialized network used for translating an image from one domain to another without needing paired, corresponding examples. Famous for "unpaired style transfer" tasks, such as turning a photograph of a horse into a zebra.
* **Pix2Pix:** Operates on paired datasets to transform one image into another. For instance, turning a sketch of a building into a photorealistic architectural rendering.

## 💎 High-Resolution & Quality Enhancements

* **Super-Resolution GAN (SRGAN):** Designed specifically to take a low-resolution or blurry image and reconstruct it into a high-resolution version by hallucinating realistic finer details.
* **StyleGAN:** Focuses on creating extremely realistic, high-quality images (especially human faces). It allows users to separate features, providing fine-grained control over the "style" of the image (e.g., controlling hair, freckles, age, or expression).


## 📈 Star History

<div align="center">
	<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-GANs&type=date&legend=bottom-right">
	 <picture>
	   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-GANs&type=date&theme=dark&legend=bottom-right" />
	   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-GANs&type=date&legend=bottom-right" />
	   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-GANs&type=date&legend=bottom-right" />
	 </picture>
	</a>
</div>


---

## 📚 External Resources

* [Google for Developers GAN Variations Guide](https://google.com)
* [AWS What is a GAN? Explanation](https://amazon.com)

