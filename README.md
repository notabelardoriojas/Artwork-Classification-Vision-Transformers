# Painting-Classification-Vision-Transformers
Classification of Paintings Using Vision Transformers with Shifted Patch Tokenization and Locality Self Attention.

Classified 7,000+ art pieces into five classes: drawing, painting, iconography, engraving, and sculpture.
Used Vision Transformer suitable for training on small datasets by implementing shifted patch tokenization and locality self attention to force the attention module to pay more attention to the inter-token relations.
Reached 82% test accuracy with this method.

Source: https://keras.io/examples/vision/vit_small_ds/

Follow along with the notebook: Painting_Classification_Vision_Transformers.ipynb

| n_observations     | 7,829     |
|--------------------|-----------|
| n_classes          | 5         |
| image_size         | (256,256) |
| PATCH_SIZE         | 32        |
| LEARNING_RATE      | .001      |
| WEIGHT_DECAY       | .0001     |
| epochs             | 50        |
| TRANSFORMER_LAYERS | 16        |
| NUM_HEADS          | 4         |
| train_accuracy     | 88.0%     |
| test_accuracy      | 82.7%     |
