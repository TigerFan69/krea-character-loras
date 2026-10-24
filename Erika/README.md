These character downloads are free. Optional [Ko-fi support and $5/month private-community membership](https://ko-fi.com/tigerfan69/tiers) supports development. Follow [Civitai releases](https://civitai.red/user/TigerFan69) and [Hugging Face models](https://huggingface.co/TigerFan69); no membership is required to download these models. Community: LoRA Studio Beta Community on Discord (connect through Ko-fi for member areas).

# Krea 2 Erika v1

Erika is a fictional SFW character LoRA by TigerFan69. This release is free; it is not a paid early-access release.

![Erika clothed creator preview](Erika-preview.png)

## Download and terms

Read [LICENSE.pdf](LICENSE.pdf), [NOTICE.txt](NOTICE.txt), and [CREATOR-TERMS.md](CREATOR-TERMS.md) before downloading or using this derivative. By downloading, accessing, copying, using or distributing it, you agree to be bound by the Krea 2 Community License Agreement and applicable creator terms. If you do not agree, do not download or use it.

- [Civitai model and example gallery](https://civitai.red/models/3017341/krea-2-erika-fictional-character-lora) — version 3425433.
- [Hugging Face model page](https://huggingface.co/TigerFan69/Krea-2-Erika-v1).
- [Free Ko-fi download](https://ko-fi.com/s/280f8a4300).
- GitHub Release package: `Krea-2-Erika-v1.zip`; includes the original weights, this guide, license, notice, creator permissions, and checksums. GitHub's automatic source archives contain documentation only.

## Model details

| Field | Value |
| --- | --- |
| Creator | TigerFan69 |
| Base family | Krea 2 |
| Inference workflow | Compatible Krea 2 / Krea 2 Turbo workflow |
| Training steps | 2,000 |
| Trigger (case-sensitive) | `Erika-v1` |
| Original run | `krea2_erika-v1_cd93955d9edb` |
| Format | Safetensors, fp16, 512 tensors |
| File size | 114,324,760 bytes |
| SHA-256 | `1a9bd81c39b531dbecaf0a6a5bb22acb7046ff7eefcf2f6f8b13c66b746e5d0d` |

This is an adapter only. Obtain the base model, text encoder, and VAE separately under their licenses. Do not use a FLUX.1 Schnell or FLUX.1 Dev workflow for this adapter.

## ComfyUI installation

1. Extract the release ZIP and read its license and creator permissions.
2. Copy `krea2_erika-v1_cd93955d9edb.safetensors` to `ComfyUI/models/loras/`, then refresh or restart ComfyUI.
3. In your working Krea 2 Turbo workflow, insert **Load LoRA (Model Only)** between the base-model loader and sampler; choose this adapter.
4. Include `Erika-v1` in the prompt. Start with your working Krea 2 workflow and adjust LoRA strength, prompt and seed. No numeric settings have been independently tested for this release.

Example: `Erika-v1, a fictional adult woman wearing a casual jacket, standing in a sunlit garden, natural lighting, portrait photograph`.

## Validation and feedback

The local source checksum and Safetensors metadata were checked before packaging. Metadata identifies Krea 2 and 2,000 training steps. No fresh visual generation benchmark is claimed by this packaging check. A clothed creator example is included; training data is not bundled. See the creator's Civitai gallery for more examples. Results depend on the base workflow, seed and prompt.

For feedback, use the model's Civitai discussion or existing Discord installation-help and results-and-feedback channels. Remove secrets and personal information from reports. [Creator on Civitai](https://civitai.red/user/TigerFan69) · [Hugging Face](https://huggingface.co/TigerFan69).

The separate [LoRA Studio software](https://github.com/TigerFan69/lora-studio) is a free public technical preview. Its MIT license does not apply to these character models.
