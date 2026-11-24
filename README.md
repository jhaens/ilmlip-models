# ILMlip models

Pretrained models of [ILMlip](https://github.com/jhaens/ilmlip): `<name>.pt` and `models.json`
(sha256, size, training data). Names and the choice of a model: the ILMlip docs.

```python
from ilmlip import load_calculator
atoms.calc = load_calculator("OAM-L-omat")    # ILMLIP_MODELS=<this folder>, or downloaded
```

`ILMLIP_MODELS` points ILMlip at a folder of these files; `ILMLIP_REPO` at a copy of this
repository to download from.

Free for noncommercial use under the PolyForm Noncommercial License 1.0.0; the training data keep
their own licences. See [LICENSE](LICENSE).
