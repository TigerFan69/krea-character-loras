These character downloads are free. Optional [Ko-fi support and $5/month private-community membership](https://ko-fi.com/tigerfan69/tiers) supports development. Follow [Civitai releases](https://civitai.red/user/TigerFan69) and [Hugging Face models](https://huggingface.co/TigerFan69); no membership is required to download these models. Community: LoRA Studio Beta Community on Discord (connect through Ko-fi for member areas).

# Krea 2 Jessica v1

Jessica is a fictional SFW character LoRA by TigerFan69. This release is free; it is not a paid early-access release.

## Download and terms

Read [LICENSE.pdf](LICENSE.pdf), [NOTICE.txt](NOTICE.txt), and [CREATOR-TERMS.md](CREATOR-TERMS.md) before downloading or using this derivative. By downloading, accessing, copying, using or distributing it, you agree to be bound by the Krea 2 Community License Agreement and applicable creator terms. If you do not agree, do not download or use it.

- Civitai availability: the October 24 version 1a listing was unpublished as a duplicate, as verified October 25. No new weights were trained: its full checksum matches this original v1 file. Use the free mirrors here while Civitai availability is unresolved.
- [Hugging Face model page](https://huggingface.co/TigerFan69/Krea-2-Jessica-v1).
- [Free Ko-fi download](https://ko-fi.com/s/cff4d8ff39).
- GitHub Release package: `Krea-2-Jessica-v1-2026-10-25.zip` (current documentation/preview refresh; older assets are retained for history); includes the original weights, this guide, license, notice, creator permissions, and checksums. GitHub's automatic source archives contain documentation only.

## Model details

| Field | Value |
| --- | --- |
| Creator | TigerFan69 |
| Base family | Krea 2 |
| Inference workflow | Compatible Krea 2 / Krea 2 Turbo workflow |
| Training steps | 2,000 |
| Trigger (case-sensitive) | `JessicaV1` |
| Original run | `krea2_jessicav1_3028a8fecc14` |
| Format | Safetensors, fp16, 512 tensors |
| File size | 114,324,760 bytes |
| SHA-256 | `f0e39d1d3bdad3c4dcec7d45410dc4d453ee2c11cc1de37312a30460d8ee2d80` |

This is an adapter only. Obtain the base model, text encoder, and VAE separately under their licenses. Do not use a FLUX.1 Schnell or FLUX.1 Dev workflow for this adapter.

## ComfyUI installation

1. Extract the release ZIP and read its license and creator permissions.
2. Copy `Krea-2-Jessica-v1.safetensors` to `ComfyUI/models/loras/`, then refresh or restart ComfyUI.
3. In your working Krea 2 Turbo workflow, insert **Load LoRA (Model Only)** between the base-model loader and sampler; choose this adapter.
4. Start at LoRA strength **1.0**, then compare **0.7** with the same prompt and seed. Include `JessicaV1` in the prompt.
5. For a Turbo workflow, start with **8 steps**, **CFG 1**, and **512 × 512** resolution, then adjust for your compatible workflow. These are starting suggestions, not universal requirements or a quality guarantee.

Example: `JessicaV1, a fictional character wearing a casual jacket, standing in a sunlit garden, natural lighting, portrait photograph`.

## Validation and feedback

The local source checksum and Safetensors metadata were checked before packaging. Metadata identifies Krea 2 and 2,000 training steps. No fresh visual generation benchmark is claimed by this packaging check. Example images and training data are not bundled. Results depend on the base workflow, seed and prompt.

For feedback, use the existing Discord installation-help and results-and-feedback channels, or Ko-fi messages. Remove secrets and personal information from reports. [Creator on Civitai](https://civitai.red/user/TigerFan69) · [Hugging Face](https://huggingface.co/TigerFan69).

The separate [LoRA Studio software](https://github.com/TigerFan69/lora-studio) is a free public technical preview. Its MIT license does not apply to these character models.


## Listing revision and SFW scope

The creator identifies Jessica as an adult fictional character. This release remains **SFW-only**. The Civitai version 1a upload used a renamed file with identical weights; it does not represent new training or an improved model. The original v1 release is preserved. No duplicate Civitai upload is being created.
