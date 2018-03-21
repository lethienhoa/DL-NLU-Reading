### Deep Learning and Natural Language Understanding Reading Group at Synalp team, Loria

Presenters: [Hoa Le](https://lethienhoablog.wordpress.com/), [Claire Gardent](https://members.loria.fr/CGardent/)

| Date | Presenter | Paper |
|-------------|-------------|-----------------|
| 01/03/2018 | Hoa | Adams Wei Yu, Hongrae Lee, Quoc V. Le. **Learning to Skim Text**. ACL 2017 |
| 08/03/2018 | Claire | Abigail See, Peter J. Liu, Christopher D. Manning. **Get To The Point: Summarization with Pointer-Generator Networks**. ACL 2017 |
| 15/03/2018 | Hoa | `Limitations of Neural Machine Translation (NMT):` |
| | | Philipp Koehn and Rebecca Knowles. **Six Challenges for Neural Machine Translation**. First Workshop on Neural Machine Translation 2017 |
| | | Christopher Manning, Kyunghuyn Cho, Thang Luong. **Neural Machine Translation - Tutorial**. ACL 2016 |
| | | `Advancing NMT:` |
| | | `- On Vocabulary aspect` |
| | | `by Softmax scaling`: Sébastien Jean, Kyunghyun Cho, Roland Memisevic, Yoshua Bengio. **On Using Very Large Target Vocabulary for Neural Machine Translation**. ACL 2015 |
| | | `by Copy Mechanism`: Thang Luong, Ilya Sutskever, Quoc Le, Oriol Vinyals, Wojciech Zaremba. **Addressing the Rare Word Problem in Neural Machine Translation**. ACL 2015 |
| | | `by byte-pair encoding`: Rico Sennrich, Barry Haddow, Alexandra Birch. **Neural Machine Translation of Rare Words with Subword Units**. ACL 2016 |
| | | `- On Memory aspect` |
| | | `by Global and Local Attention`: Thang Luong, Hieu Pham, and Chris Manning. **Effective Approaches to Attention-based Neural Machine Translation**. EMNLP 2015 |
| | | `by Coverage mechanism`: Zhaopeng Tu, Zhengdong Lu, Yang Liu, Xiaohua Liu and Hang Li. **Modeling coverage for neural machine translation**. ACL 2016 |
| | | `- On Language Complexity aspect` |
| | | `by Sub-word modeling`: Thang Luong and Chris Manning. **Achieving Open Vocabulary Neural Machine Translation with Hybrid Word-Character Models**. ACL 2016 |
| | | `- On Data aspect` |
| | | `by using Monolingual data`: Rico Sennrich, Barry Haddow, and Alexandra Birch. **Improving Neural Machine Translation Models with Monolingual Data**. ACL 2016 |
| | | `by learning Multi-lingual and combining Multi-task`: Thang Luong, Quoc Le, Ilya Sutskever, Oriol Vinyals, Lukasz Kaiser. **Multi-task sequence to sequence learning**. ICLR 2016 |
| 22/03/2018 | Hoa | Hassan et al., **Achieving Human Parity on Automatic Chinese to English News Translation**. Microsoft research preprint 2018. [[Summary slides]]() |
| | | `3 major components/techniques:` |
| | | `Dual learning`: He et al., **Dual Learning for Machine Translation**. NIPS 2016 |
| | | `Deliberation Networks`: Xia et al., **Deliberation Networks: Sequence Generation Beyond One-Pass Decoding**. NIPS 2017 |
| | | `Joint training`: Zhang et al., **Joint Training for Neural Machine Translation Models with Monolingual Data**. AAAI 2018 |
| 29/03/2018 | | `Learning language representation with Autoencoders (AEs):` |
| | | `(CNN-DCNN) Autoencoder (AE)`: Yizhe Zhang, Dinghan Shen, Guoyin Wang, Zhe Gan, Ricardo Henao, Lawrence Carin. **Deconvolutional Paragraph Representation Learning**. NIPS 2017 |
| | | `(Sequential) Denoising Autoencoder (DAE)`: Felix Hill, Kyunghyun Cho, Anna Korhonen. **Learning Distributed Representations of Sentences from Unlabelled Data**. NAACL-HLT 2016 |
| | | `Variational Autoencoder (VAE)`: Samuel R. Bowman, Luke Vilnis, Oriol Vinyals, Andrew M. Dai, Rafal Jozefowicz, Samy Bengio. **Generating Sentences from a Continuous Space**. CoNLL 2016 |
| | | `Adversarial Autoencoder (AAE)`: |
| | | Alireza Makhzani, Jonathon Shlens, Navdeep Jaitly, Ian Goodfellow. **Adversarial Autoencoders**. ICLR 2016 |
| | | Takeru Miyato, Andrew M. Dai, Ian Goodfellow. **Adversarial Training Methods for Semi-Supervised Text Classification**. ICLR 2017 |
| 05/04/2018 | | `Neural Abstractive Text Summarization` |
| | | `Deterministic vector:` |
| | | Romain Paulus, Caiming Xiong, Richard Socher. **A Deep Reinforced Model for Abstractive Summarization**. Arxiv 2017 |
| | | Qingyu Zhou, Nan Yang, Furu Wei, Ming Zhou. **Selective Encoding for Abstractive Sentence Summarization**. ACL 2017 |
| | | Noah Weber, Leena Shekhar, Niranjan Balasubramanian, Kyunghyun Cho. **Controlling Decoding for More Abstractive Summaries with Copy-Based Networks**. Arxiv 2018 |
| | | `Stochastic vector:` |
| | | Yishu Miao, Phil Blunsom. **Language as a Latent Variable: Discrete Generative Models for Sentence Compression**. EMNLP 2016 |
| | | Piji Li, Wai Lam, Lidong Bing, Zihao Wang. **Deep Recurrent Generative Decoder for Abstractive Text Summarization**. EMNLP 2017 |
| 12/04/2018 | | `Next frontiers of NMT:` |
| | | `- Larger context` |
| | | `by Tracking states over time`: Iulian Vlad Serban, Alessandro Sordoni, Ryan Lowe, Laurent Charlin, Joelle Pineau, Aaron Courville, Yoshua Bengio. **A Hierarchical Latent Variable Encoder-Decoder Model for Generating Dialogues**. AAAI 2015 |
| | | `- Mobile devices` |
| | | `by Knowledge Distillation`: Yoon Kim, Alexander M. Rush. **Sequence-level knowledge distillation**. EMNLP 2016 |
| | | `- Beyond Maximum Likelihood` |
| | | `Scheduled sampling (Curriculum Learning)`: Samy Bengio, Oriol Vinyals, Navdeep Jaitly, Noam Shazeer. **Scheduled sampling for sequence prediction with recurrent Neural networks**. NIPS 2015 |
| | | `Professor Forcing (GAN)`: Alex Lamb, Anirudh Goyal, Ying Zhang, Saizheng Zhang, Aaron Courville, Yoshua Bengio. **Professor Forcing: A New Algorithm for Training Recurrent Networks**. NIPS 2016 |
| | | `MIXER (REINFORCE)`: Marc'Aurelio Ranzato, Sumit Chopra, Michael Auli, Wojciech Zaremba. **Sequence Level Training with Recurrent Neural Networks**. ICLR 2016 |
