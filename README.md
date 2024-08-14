# Δx
Δx is a collection of ml paper summaries of the form: 'it's just x but with y'.

| Paper title                                                                        | Model name           | Summary                                                                                             |
|------------------------------------------------------------------------------------|----------------------|-----------------------------------------------------------------------------------------------------|
| Semi-supervised Learning by Entropy Minimization                                   | Entropy Minimisation | Supervision but with the additional goal of maximising prediction confidencen on the unlabeled data |
| Fast R-CNN                                                                         | Fast R-CNN           | R-CNN but with RoI pooling                                                                          |
| Faster R-CNN                                                                       | Faster R-CNN         | Fast R-CNN but with a region proposal network                                                       |
| Focal Loss for Dense Object Detection                                              | RetinaNet            | FPN but with a one-stage detector                                                                   |
| Leveraging Pre-trained Checkpoints for Sequence Generation Tasks                   | -                    | Encoder-Decoder Transformer, but with pre-trained BERT/GPT-style encoder/decoder checkpoints        |
| Swin Transformer: Hierarchical Vision Transformer using Shifted Windows            | Swin Transformer     | ViT but with a patch size hierarchy                                                                 |
| Per-Pixel Classification is Not All You Need for Semantic Segmentation             | MaskFormer           | DETR but with per-instance binary masks                                                             |
| Masked-attention Mask Transformer for Universal Image Segmentation                 | Mask2Former          | MaskFormer but with masked attention around objects/regions and multi-scale pixel decoder features  |
| Momentum Contrast for Unsupervised Visual Representation Learning                  | MoCo                 | Contrastive learning but with one momentum-updated encoder                                          |
| Training Transitive and Commutative Multimodal Transformers with LoReTTa           | LoReTTa              | ImageBind but with Transformers                                                                     |
| ProtST: Multi-Modality Learning of Protein Sequences and Biomedical Texts          | ProtST               | CLIP but with proteins and functional annotations                                                   |
| When Scaling Meets LLM Finetuning: The Effect of Data, Model and Finetuning Method | -                    | Chinchilla scaling laws but for finetuning                                                          |
| Scaling Data-Constrained Language Models                                           | Datablation          | Chinchilla scaling laws but for the data-constrained regime                                         |
| Online normalizer calculation for softmax                                          | -                    | Softmax calculation but online/ streaming/ blockwise                                                |
| FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness        | FlashAttention       | Online softmax but with attention checkpointing                                                     |
| Blockwise Parallel Transformer for Large Context Models                            | BPT                  | FlashAttention but fusing blockwise attention with FFN                                              |
| Ring Attention with Blockwise Transformers for Near-Infinite Context               | Ring Attention       | BPT but distribute blocks across devices & overlap computation and communication                    |

