# DNA-ELMR

DNA-ELMR is a DNA storage coding method based on transformer and reinforcement learning with a novelty low-complex loss function, which consists of hairpin loss, penalty loss, MSE loss, and existing biological loss. 

## ✨ Key Innovations

- 🚀 Novel Low-Complexity Hairpin Loss
We pioneered a hairpin structure loss calculation method using complementary matrix convolution, which dramatically reduces the computational complexity from O(n³) to O(n²). This efficient loss is seamlessly integrated with other critical biological constraints to guide the model towards generating more synthesizable DNA sequences.
- ⚡ RL-Driven Error Suppression (eMotifs)
We introduce eMotifs, a reinforcement learning framework designed to dynamically suppress error-prone motifs. It consists of two core components:
eformer: A sequencing simulator that injects realistic errors into DNA sequences.
ePenalty: A penalty loss generator that uses eformer's output to guide the Transformer autoencoder away from generating problematic motifs.
