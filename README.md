# StyleTransfer
**Neural Style Transfer meets Fashion**  
_A digital art experiment by Melis Yılmaz_

---

## 🧠 What is this?

**Wearing the Canvas** is a creative-technical project that explores what happens when we apply the brushstrokes of iconic female painters — like Tamara de Lempicka — to images of modern women in fashion.

Built using **PyTorch** and **VGG19**, this style transfer pipeline doesn’t just recreate art — it reflects on **how femininity, form, and visual culture** have evolved and intertwined.

---

## 🔍 What’s in this repo?

- `notebooks/style_transfer.ipynb`  
  A fully working pipeline for neural style transfer using content + style loss  
- `data/`  
  Content images (modern fashion) + style images (paintings)
- `outputs/`  
  Generated stylized images — first runs using Lempicka’s works

---

## 🌀 Techniques Used

- Pretrained **VGG19** as a feature extractor  
- **Content loss** from deeper CNN layers  
- **Style loss** via Gram matrix on early layers  
- Image optimization with **LBFGS**  
- Interpretability: understanding activations, visual flow, aesthetic outcomes

---

## 🧵 Why this project?

This isn’t just a neural network task — it’s a personal curiosity:  
> What does it mean to "wear" a painting?  
> Can a machine learn to reinterpret beauty?  
> How does digital style alter our perception of feminine form?

Through code, we explore questions usually reserved for galleries and essays.

---

## 🚧 Next steps

- Compare outputs across multiple painters  
- Apply selective style transfer to clothing only  
- Write interpretive reflections (visual + written)  
- Publish a curated portfolio or visual essay

---

## ✍️ Made with curiosity and PyTorch by [@meliisyyilmaz](https://github.com/meliisyyilmaz)
