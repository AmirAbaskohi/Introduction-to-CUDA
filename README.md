# Introduction to CUDA
This repo is for learning CUDA using C/C++.

## What is CUDA?
CUDA is a parallel computing platform and application programming interface model created by Nvidia. It allows software developers and software engineers to use a CUDA-enabled graphics processing unit for general purpose processing – an approach termed GPGPU.

The CUDA platform is designed to work with programming languages such as C, C++, and Fortran. This accessibility makes it easier for specialists in parallel programming to use GPU resources, in contrast to prior APIs like Direct3D and OpenGL, which required advanced skills in graphics programming. CUDA-powered GPUs also support programming frameworks such as OpenMP, OpenACC and OpenCL; and HIP by compiling such code to CUDA. 

![image](https://user-images.githubusercontent.com/50926437/128422031-fa5226a0-f665-45a2-b456-b3339e3ceada.png)


## Advantages
CUDA has several advantages over traditional general-purpose computation on GPUs (GPGPU) using graphics APIs: 
* Scattered reads – code can read from arbitrary addresses in memory.
* Unified virtual memory (CUDA 4.0 and above)
* Unified memory (CUDA 6.0 and above)
* Shared memory – CUDA exposes a fast shared memory region that can be shared among threads. This can be used as a user-managed cache, enabling higher bandwidth than is possible using texture lookups.
* Faster downloads and readbacks to and from the GPU
* Full support for integer and bitwise operations, including integer texture lookups
* On RTX 20 and 30 series cards, the CUDA cores are used for a feature called "RTX IO" Which is where the CUDA cores dramatically decrease game-loading times.

## Why should we learn CUDA?
With CUDA, you can leverage a GPU's parallel computing power for a range of high-performance computing applications in the fields of science, healthcare, and deep learning. Learn CUDA Programming will help you learn GPU parallel programming and understand its modern applications.

Also CUDA is the basis of most of the important DeepLearning frameworks such as `PyTorch` and `Tensorflow`.

*Amirhossein Abaskohi*
