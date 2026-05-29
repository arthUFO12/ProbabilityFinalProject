# Ensemble vs Mixed-Distortion Model Accuracy

The ensemble averages softmax outputs from the Gaussian-trained, salt-and-pepper-trained, and blur-trained models. The mixed model is the single model trained on mixed distortions.

| tested_on   |   ensemble_accuracy |   mixed_model_accuracy |   ensemble_minus_mixed | winner   |
|:------------|--------------------:|-----------------------:|-----------------------:|:---------|
| clean       |              0.7448 |                 0.6912 |                 0.0536 | ensemble |
| gaussian    |              0.7132 |                 0.6768 |                 0.0364 | ensemble |
| salt_pepper |              0.6132 |                 0.6758 |                -0.0626 | mixed    |
| blur        |              0.6968 |                 0.6749 |                 0.0219 | ensemble |
| mixed       |              0.6783 |                 0.6748 |                 0.0035 | ensemble |