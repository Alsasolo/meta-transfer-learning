Traceback (most recent call last):
  File "main.py", line 81, in <module>
    trainer.train()
  File "/home/xiaocuiping/Projects/mtl/pt/trainer/pre.py", line 178, in train
    data = self.model(data)
  File "/home/xiaocuiping/anaconda3/envs/mtl-pytorch/lib/python3.5/site-packages/torch/nn/modules/module.py", line 550, in __call__
    result = self.forward(*input, **kwargs)
  File "/home/xiaocuiping/Projects/mtl/pt/models/mtl.py", line 70, in forward
    data_shot, label_shot, data_query = inp
ValueError: too many values to unpack (expected 3)
