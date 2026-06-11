### Hi, I'm Zixuan 👋

I like taking apart big, intimidating models until I understand exactly why they work — then putting the smallest runnable version back together so other people can too.

These days that means **embodied AI**: vision-language-action policies, diffusion / flow matching, and 3D vision. I'm a direct-PhD student at Peking University, but most of what I actually *do* lives in the repos below.

---

**A recurring theme in my work:** complex papers shouldn't stay locked inside their original codebases.

- 🤖 **[pi-zero-minimal](https://github.com/PKUJZX/pi-zero-minimal)** — Physical Intelligence's π0, stripped down to a minimal runnable VLA. No engineering scaffolding, just the core idea you can read in one sitting.
- 🧩 **[CV_Milestones](https://github.com/PKUJZX/CV_Milestones)** — clean-room re-implementations of landmark papers (DiT, 3DGS, …) — the version I wish existed when I was first reading them.

And when re-implementing isn't enough, I write things down:

- 🌊 **[Flow-Diffusion](https://pkujzx.github.io/Flow-Diffusion/)** — diffusion, score matching, and SDEs, all derived from one flow-matching lens. The unified picture I wanted but couldn't find.
- 📐 **[3D_Vision](https://pkujzx.github.io/3D_Vision/)** — camera models → epipolar geometry → SfM, built from the ground up.

---

**On the research side**, I've spent time on:

- a diffusion **foundation model** unifying five image-restoration tasks — and rebuilding its sampler with flow matching for a ~30× speedup *(co-first author, Nature Communications)*
- using a **VLM as a reward signal** to make few-step text-to-image models actually follow instructions, trained end-to-end and differentiable
- **feed-forward 3D reconstruction** with Transformers, self-supervised where ground truth doesn't exist

---

I'm always up for a good conversation about generative models, embodied agents, or why your sampler is slow.

📫 jzx417889065@stu.pku.edu.cn
