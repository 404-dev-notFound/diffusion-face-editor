# 🎨 Face Generation & Editing with Stable Diffusion

An interactive **Streamlit** app for **generating** and **editing** human faces using **Stable Diffusion models**!  
Customize features like **age**, **smile intensity**, **eye color**, and **hair color** — all in a beautiful web UI.

The project explores **controllable image editing** with diffusion models: create a realistic base face from a text prompt, then adjust individual attributes (age, smile, eye colour, hair colour) while keeping the rest of the face consistent.

> Faces are fully synthetic. Generated faces should not be used to identify or represent real people.

---

## 🚀 Features

- Generate photorealistic portraits from simple text prompts.
- Edit the generated image dynamically:
  - Change **Age**
  - Adjust **Smile** intensity
  - Modify **Eye Color**
  - Alter **Hair Color**
- CUDA GPU acceleration supported (falls back to CPU if unavailable).
- Modern dark-themed UI with smooth user interactions.
- State management for reverting to the original image anytime.
- Expose your app to the web easily using **ngrok**.

---

## 🛠 Tech Stack

- [Streamlit](https://streamlit.io/) — For the interactive UI
- [Diffusers (Hugging Face)](https://huggingface.co/docs/diffusers/index) — Stable Diffusion model
- [PyTorch](https://pytorch.org/) — Backend deep learning engine
- [Pillow (PIL)](https://pypi.org/project/Pillow/) — Image processing
- [ngrok](https://ngrok.com/) — Publicly share your local Streamlit app

---
## ⚡ Quick Overview
- Select a prompt and generate an initial face.
- Use sidebar sliders and dropdowns to tweak attributes.
- Click "Edit Image" to apply changes.
- Click "Revert" anytime to return to the original generation.

---
## ✨ Custom CSS Styling
- The app features customized Streamlit CSS to enhance aesthetics:
- Dark mode background
- Styled buttons
- Highlighted sliders and image borders

---
## 🤝 Contributing
- Pull requests are welcome! Feel free to open an issue if you find a bug or want a new feature.

---
## 📄 License
- This project is licensed under the MIT License.
- Feel free to use, modify, and share!

---
| Generate Base Image | Edit Features |

![Base Image](Assets/image.webp) ![Edited Image](Assets/image(1).webp) ![Edited Image](Assets/image(2).webp) ![Edited Image](Assets/image(3).webp) 
