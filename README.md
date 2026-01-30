# advanced-gen-ai-capstone-2

## Workflow

### Image Generation Model
- **Model name:** FLUX.1-dev FP8  
- **Format:** `.safetensors`  
- **Source:** https://huggingface.co/black-forest-labs/FLUX.1-dev  

### Interface / Pipeline
- **Tool:** ComfyUI
- **Execution mode:** Fully local (self-hosted)
- **Pipeline type:** Node-based workflow (Checkpoint → CLIP → Sampler → VAE → Image)
<img width="1397" height="987" alt="image" src="https://github.com/user-attachments/assets/28040b39-f949-45d2-b55a-5c1b869a168e" />

---

<img width="1383" height="983" alt="image" src="https://github.com/user-attachments/assets/277041e1-197f-4522-9bd3-abbb6df6c7c2" />

---

<img width="1914" height="938" alt="image" src="https://github.com/user-attachments/assets/b4baec82-006d-454f-8929-ba367031d499" />

---

### Hardware Used
- **OS:** Windows
- **GPU:** NVIDIA GeForce RTX 4060 Ti (8GB VRAM)
- **CPU:** x64 desktop processor
- **RAM:** 16 GB
- **CUDA:** Enabled (PyTorch CUDA build)

### Result
I used self-hosted model. Run on machine. But can't get desired results. I got black pictures everytime. I tried two different models, but nothing changed
