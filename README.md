# Phrase → Story → Image (with CLIPScore & BERTScore)

This project builds a tiny end-to-end **generative AI pipeline**:

1. **Text model** (Hugging Face) generates a **story** from a short phrase  
2. The **story** is fed to an **image generator** to produce an image  
3. The image–story alignment is evaluated with:
   - **CLIPScore** (vision–language similarity)
   - **BERTScore** between a **BLIP** auto-caption of the image and the story

You get:
- Three Jupyter notebooks (prep, pipeline, UI)
- Simple cloud hosting via **Hugging Face Hub** for the text model 

---



