# STAR Network
Tensorflow  implementation for STAckable Recurrent (STAR) network based on our Arxiv paper:

Turkoglu, M.O., D'Aronco, S., Wegner, J.D. and Schindler, K., 2019. Gating Revisited: Deep Multi-layer RNNs That Can Be Trained. arXiv preprint arXiv:1911.11033.

# [[Paper]](https://arxiv.org/abs/1911.11033)


<img src="https://raw.githubusercontent.com/0zgur0/STAR_Network/master/imgs/cells.PNG" width="900" height="220">
<img src="https://raw.githubusercontent.com/0zgur0/STAR_Network/master/imgs/img_grad.PNG" width="960" height="540">

## Getting Started

Run the model with 
```bash
python main.py --cell bn-star --stack 4 --data pmnist
```

## Citation
```bash
@article{turkoglu2019gating,
  title={Gating Revisited: Deep Multi-layer RNNs That Can Be Trained},
  author={Turkoglu, Mehmet Ozgur and D'Aronco, Stefano and Wegner, Jan Dirk and Schindler, Konrad},
  journal={arXiv preprint arXiv:1911.11033},
  year={2019}
}
```

The code is mostly based on https://github.com/JosvanderWesthuizen/janet.

