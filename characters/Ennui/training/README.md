# Ennui LoRA Training

## Training Environment

- Training application: Draw Things
- Character: Ennui
- Operating system: macOS
- Hardware: Apple Silicon Mac

## Training Checkpoints

| Training Steps | Filename | Status |
|---|---|---|
| 400 | `lora_001_400_lora_f32.ckpt` | Earlier checkpoint |
| 2200 | `lora_001_2200_lora_f32.ckpt` | Candidate final checkpoint |

## Checkpoint Format

The checkpoint files begin with the SQLite database signature.
They contain a `tensors` table and a `loratrainingconfiguration` table.

Their compatibility with other inference software has not yet been verified.

## Model Evaluation

The checkpoints should be compared using consistent prompts and
generation settings.

Evaluate:
- Facial identity consistency
- Hairstyle consistency
- Outfit consistency
- Performance across different poses
- Performance across different expressions
- Ability to preserve identity across backgrounds

## Final Model

The final checkpoint will be selected after testing.

The exported model format and supported base model will be documented
once compatibility has been confirmed.

## Distribution

Large model files will be distributed separately from the main Git
repository when appropriate.
