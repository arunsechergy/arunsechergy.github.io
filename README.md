## Welcome to ArunSechergy's page

### Understanding fundamentals of PyTorch
- CUDA
	 1. To understand CUDA, we need to understand what GPU is.  GPU (Graphics Processing Unit) is a hardware used for specialized computing tasks. As the name suggests, this was initialized developed to process graphics faster than CPU. GPU processes faster due to its parallel computing property that is, GPU can break down an long independent task into smaller tasks and run all those tasks in parallel. 
	 2. Due to this parallel computing nature, GPU found its application in Deep learning, which is embarrassingly parallel. 
	 [placeholder for parallel processing image]
	 3. Nvidia is the industry leader in developing GPUs. With GPU as a hardware, a software layer was needed to optimize the computation for different domain specific tasks. This software layer is CUDA, which was developed by Nvidia. Simply put, CUDA is an API to GPU. There's cuDNN library which can used to work with CUDA to develop further
	 [Architecture flow [hardware (GPU) software(CUDA) library(cuDNN) framework(PyTorch)]]
