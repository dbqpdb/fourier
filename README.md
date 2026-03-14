# The Fourier Transform: From Intuition to Computation

An interactive Jupyter notebook that builds up the Fourier transform step by step, with visualizations at every stage.

## Contents

1. **Signals as sums of sinusoids** — visual decomposition of a composite signal
2. **Correlation with complex exponentials** — why the transform works
3. **Discrete Fourier Transform** — implemented from scratch, verified against NumPy
4. **Magnitude and phase** — what each tells you about the signal
5. **Inverse DFT** — perfect reconstruction demo
6. **Key properties** — linearity, time-shift, Parseval's theorem, convolution theorem
7. **Spectral leakage and windowing** — rectangular vs. Hann vs. Blackman
8. **Filtering a noisy signal** — end-to-end denoising in the frequency domain
9. **The DFT matrix** — linear algebra perspective with orthogonality verification
10. **DFT vs. analytical Fourier transform** — comparing the DFT against closed-form solutions (Gaussian, rect, exponential decay) and demonstrating convergence

## Getting started

Requires [uv](https://docs.astral.sh/uv/).

```bash
uv sync
uv run jupyter notebook fourier_transform.ipynb
```

The notebook is pre-executed with all outputs embedded, so you can also [view it directly on GitHub](fourier_transform.ipynb).
