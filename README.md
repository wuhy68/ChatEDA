# ChatEDA

ChatEDA: A Large Language Model Powered Autonomous Agent for EDA ([TCAD24](https://ieeexplore.ieee.org/document/10485372))

Divergent Thoughts toward One Goal: LLM-based Multi-Agent Collaboration System for Electronic Design Automation ([NAACL25 Main](https://aclanthology.org/2025.naacl-long.83.pdf))

## EDA Tool Instruction Dataset
We propose some examples of [EDA tool instructions datasets](https://github.com/wuhy68/ChatEDAv1/blob/master/data/train/ChatEDA-train-example.json) for training AutoMage and ChipLlama models, the controllers of ChatEDA and EDAid, respectively.

## ChatEDA-Bench
[ChatEDA-Bench](https://github.com/wuhy68/ChatEDAv1/blob/master/data/test/ChatEDA-Bench.txt) is a comprehensive evaluation benchmark comprising 50 distinct tasks to evaluate the performance of LLMs in automating the EDA flow.

## API Document
To facilitate a better understanding of the Python-EDA interface document, we provide the [API document](https://github.com/wuhy68/ChatEDAv1/blob/master/api_doc/openroad_api.py) and the corresponding [OpenRoad implementation](https://github.com/wuhy68/ChatEDAv1/blob/master/api_doc/openroad_api_impl.py).

## Citation
```bibtex
@article{wu2024chateda,
  title={{ChatEDA: A Large Language Model Powered Autonomous Agent for EDA}},
  author={Wu, Haoyuan and He, Zhuolun and Zhang, Xinyun and Yao, Xufeng and Zheng, Su and Zheng, Haisheng and Yu, Bei},
  journal={IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems},
  year={2024},
  publisher={IEEE}
}

@inproceedings{wu2025EDAid,
  title={{Divergent Thoughts toward One Goal: LLM-based Multi-Agent Collaboration System for Electronic Design Automation}},
  author={Wu, Haoyuan and Zheng, Haisheng and He, Zhuolun and Yu, Bei},
  booktitle={Annual Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics},
  year={2025}
}
```

## License
This repo is licensed under the [Apache 2.0 License](https://github.com/wuhy68/ChatEDAv1/blob/master/LICENSE). 
