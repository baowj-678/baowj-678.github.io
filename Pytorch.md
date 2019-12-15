# Pytorch

### background

Torch是一个使用Lua语言的神经网络



## torch

### import

~~~python
import torch
from torch.autograd import Variable

~~~





### tansformation

~~~python
# numpy to torch
torch_data = torch.from_numpy(np_data)

# torch to numpy
np_data = torch_data.numpy()

# int to torch
torch_data = torch.IntTensor(data)

# float to torch
torch_data = torch.FloatTensor(data)
~~~



### basic math method

~~~python
# matrix multiplication
data = [[1,2], [3,4]]
tensor = torch.FloatTensor(data)
ans = torch.mm(tensor, tensor)

# calculate mean
mean = torch.mean(tensor)
~~~



### activation function

~~~python
# relu
torch.relu(tensor)

# sigmoid
torch.sigmoid(tensor)

# tanh
torch.tanh(tensor)

# softmax
torch.softmax(tensor)
~~~



