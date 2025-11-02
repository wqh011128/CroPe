# Cross-Modal Semantic Compensation for All Adverse Scene Segmentation
Cross-Modal Semantic Compensation for All Adverse Scene Segmentation


Accepted by NeurIPS 2025 (Conference on Neural Information Processing Systems)

1. Project Overview
Scene understanding in adverse conditions, such as fog, snow, and night, is challenging due to the visual appearance degeneration. In this context, we propose a
Cross-modal Semantic Compensation Adaptation method (CroPe) for scene understanding. Distinct from the existing methods, which only use the visual information
to learn the domain-invariant features, CroPe establishes a visual-textual paradigm
which provides textual semantic compensation for visual features, enabling the
model to learn more consistent representations. We propose the Complementary
Perceptual Text Generation (CPTG) module which generates a set of multi-level
complementary-perceptive text embeddings incorporating both generalization and
domain awareness. To achieve cross-modal semantic compensation, the Reverse
Chain Text-Visual Fusion (RCTVF) module is developed. By the unified attention
and reverse decoding chain, compensation information is successively fused to the
visual features from the deep (semantic dense) to shallow (semantic sparse) features,
maximizing compensation gain. CroPe yields competitive results under all adverse
conditions and significantly improves the state-of-the-art performance by 6.5 mIoU
for ACDC-Night dataset and 1.2 mIoU for ACDC-All dataset, respectively
