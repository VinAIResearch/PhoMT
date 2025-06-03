# PhoMT: A High-Quality and Large-Scale Benchmark Dataset for Vietnamese-English Machine Translation


PhoMT is a high-quality and large-scale Vietnamese-English parallel dataset of 3.02M sentence pairs. The dataset statistics are as follows:

<img width="750" alt="PhoMT statistics" src="https://user-images.githubusercontent.com/2412555/139051008-43966c7c-5ebc-4906-b656-7ac36ade1c52.png">

Details of the dataset construction and experimental results can be found in our [EMNLP 2021 paper](https://aclanthology.org/2021.emnlp-main.369/):

	@inproceedings{PhoMT,
    title     = {{PhoMT: A High-Quality and Large-Scale Benchmark Dataset for Vietnamese-English Machine Translation}},
    author    = {Long Doan and Linh The Nguyen and Nguyen Luong Tran and Thai Hoang and Dat Quoc Nguyen},
    booktitle = {Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing},
    year      = {2021},
    pages     = {4495--4503}
    }
    
Please follow this [**LINK**](https://huggingface.co/datasets/vinai/PhoMT) to download the PhoMT dataset. By downloading this dataset, USER agrees:
-   to use the dataset for research or educational purposes only.
-   to not distribute the dataset or part of the dataset in any original or modified form.
-   and to cite our EMNLP 2021 paper "PhoMT: A High-Quality and Large-Scale Benchmark Dataset for Vietnamese-English Machine Translation" whenever the dataset is used to help produce published results.

Note: We performed Vietnamese tone normalization on the Vietnamese sentences, using a [Python script](https://github.com/VinAIResearch/BARTpho/blob/main/VietnameseToneNormalization.md).

#### Copyright (c) 2021 VinAI

	THE DATA IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
	AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
	LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
	OUT OF OR IN CONNECTION WITH THE DATA OR THE USE OR OTHER DEALINGS IN THE
	DATA.
