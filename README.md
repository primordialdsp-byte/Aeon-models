# AEON models

Model files that AEON downloads on first use.

## stems/

ONNX exports for the stem splitter, mode «Максимум», made with
`tools/stems/export_models.py` in the AEON repository. Each network is a chain
of small files run in order.

- `bsr-vocals-*`: BS-RoFormer (viperx, ep 317), vocals. Weights from the UVR
  model repository (TRvlvr/model_repo).
- `scnet-xl-*`: SCNet XL IHF (ZFTurbo, Music-Source-Separation-Training,
  MIT licence), drums, bass and other.

Weights are stored as fp16.
