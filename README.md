# You can refer to the code here: [**https://github.com/binyisu/food**](https://github.com/binyisu/food)

# FSOSOD
[2023-01-16]: One of the key challenges for **few-shot open-set object detection** is that **limited training samples induce the model to overfit on the few-shot known classes**, thereby resulting in a poor open-set performance. To alleviate the above problem, **we propose to decouple training a virtual unknown class and sparse the prediction weights for unknown detection in few-shot scenes**. We compare our method with several state-of-the-art OSOD methods in few-shot scenes and observe that our method improves the recall of unknown classes by **5%-9%** across all shots in VOC-COCO dataset setting.

[2022-12-09]: Code is coming soon!

[2022-10-31]: Binyi Su, Hua Zhang, Jingzhi Li, Zhong Zhou. Towards Few-Shot Open-Set Object Detection,
https://arxiv.org/abs/2210.15996.

### Citation

If you find this repo useful, please consider citing our paper:

```
@inproceedings{foodv2,
  title={HSIC-based Moving WeightAveraging for Few-Shot Open-Set Object Detection},
  author={Binyi Su, Hua Zhang, and Zhong Zhou},
  booktitle={Proceedings of the31st ACM International Conference on Multimedia (MM 23)},
  page={5358--5369},
  year={2023},
  doi={https://doi.org/10.1145/3581783.3611850}
}

@ARTICLE{foodv1,
  author={Binyi Su, Hua Zhang, Jingzhi Li, Zhong Zhou},
  journal={IEEE Transactions on Image Processing}, 
  title={Toward Generalized Few-Shot Open-Set Object Detection}, 
  year={2024},
  volume={33},
  number={},
  pages={1389-1402},
  doi={10.1109/TIP.2024.3364495}}
```
