[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vYQ4W4rf)
# MiniTorch Module 3

<img src="https://minitorch.github.io/minitorch.svg" width="50%">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module3.html


You will need to modify `tensor_functions.py` slightly in this assignment.

* Tests:

```
python run_tests.py
```

* Note:

Several of the tests for this assignment will only run if you are on a GPU machine and will not
run on github's test infrastructure. Please follow the instructions to setup up a colab machine
to run these tests.

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/tensor_data.py minitorch/tensor_functions.py minitorch/tensor_ops.py minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/module.py project/run_manual.py project/run_scalar.py project/run_tensor.py

# Task 3.1 and 3.2
Parallel Check Results

<img width="1028" alt="parallel_check_1" src="https://github.com/Cornell-Tech-ML/mle-module-3-liuyi215/assets/100000764/26ab5887-474f-453c-bd64-59ac4d8deb8f">
<img width="1039" alt="parallel_check_2" src="https://github.com/Cornell-Tech-ML/mle-module-3-liuyi215/assets/100000764/eb97d478-9852-4f55-9fc2-6bfebafe3565">
<img width="1081" alt="parallel_check_3" src="https://github.com/Cornell-Tech-ML/mle-module-3-liuyi215/assets/100000764/b7db5f0f-6747-4a7a-aa06-bfb5395b2e7b">
<img width="1082" alt="parallel_check_4" src="https://github.com/Cornell-Tech-ML/mle-module-3-liuyi215/assets/100000764/6885bebf-8f57-4380-83d5-6997013c2ecf">
<img width="1033" alt="parallel_check_5" src="https://github.com/Cornell-Tech-ML/mle-module-3-liuyi215/assets/100000764/67bd75a4-3509-4007-ba21-07f7349220a7">
<img width="983" alt="parallel_check_6" src="https://github.com/Cornell-Tech-ML/mle-module-3-liuyi215/assets/100000764/4c5c66f7-57d3-4ea5-a2bf-2750afed7a33">


# Task 3.4
Graph
![graph1](https://github.com/Cornell-Tech-ML/mle-module-3-liuyi215/assets/100000764/c791cf40-dfe7-4de6-80e9-49d7708f8f48)


# Task 3.5
**Small Models (CPU)**

Dataset = Simple    Hidden Layers = 100    Learning Rate = 0.05 

<img width="1063" alt="cpu_simple_100_0 05" src="https://github.com/Cornell-Tech-ML/mle-module-3-liuyi215/assets/100000764/a4c5a473-f877-445b-aaad-0c479737cb58">


Dataset = Split    Hidden Layers = 100    Learning Rate = 0.05 

<img width="1059" alt="cpu_split_100_0 05" src="https://github.com/Cornell-Tech-ML/mle-module-3-liuyi215/assets/100000764/f51df2d7-64c3-4511-972c-fba3dd60160d">


Dataset = Xor  Hidden Layers = 100  Learning Rate = 0.05

<img width="1044" alt="cpu_xor_100_0 05" src="https://github.com/Cornell-Tech-ML/mle-module-3-liuyi215/assets/100000764/93396cf9-5e26-4da3-9998-9769d720af09">




**Small Models (GPU)**

Dataset = Simple  Hidden Layers = 100  Learning Rate = 0.05 

<img width="798" alt="gpu_simple" src="https://github.com/Cornell-Tech-ML/mle-module-3-liuyi215/assets/100000764/8244d0bc-a14f-4f3e-9204-ae42c58eaed5">


Dataset = Split  Hidden Layers = 100  Learning Rate = 0.05 

<img width="840" alt="gpu_split_second" src="https://github.com/Cornell-Tech-ML/mle-module-3-liuyi215/assets/100000764/26d9110c-4774-4f07-a656-a62219bad84c">



Dataset = Xor  Hidden Layers = 100  Learning Rate = 0.05

<img width="795" alt="gpu_xor" src="https://github.com/Cornell-Tech-ML/mle-module-3-liuyi215/assets/100000764/e97ff864-5811-4f29-83e5-20f5408aed33">




**Large Models (CPU)**

Dataset = Simple  Hidden Layers = 200  Learning Rate = 0.05 

<img width="1065" alt="cpu_simple_200_0 05" src="https://github.com/Cornell-Tech-ML/mle-module-3-liuyi215/assets/100000764/277d5313-1b06-4136-afae-0c75233b3502">




**Large Models (GPU)**

Dataset = Simple  Hidden Layers = 200  Learning Rate = 0.05 

<img width="855" alt="gpu_simple_large_second" src="https://github.com/Cornell-Tech-ML/mle-module-3-liuyi215/assets/100000764/8c778732-cf60-4845-98a7-be81d883cb0c">





