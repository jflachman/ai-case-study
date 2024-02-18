# A New Age of ML Software

## Overview and Origin
Modular AI was founded in 2022 by Chris Lattner and Tim Davis.  The two met at google.  They found that AI is impeded by the many disparate languages and technologies required between research and deployment.  They founded Modular AI to bring next-generation AI developer platform unifying the development and deployment of AI with production-quality AI software.

Modular received $100M from private investors in its latest rounded of funding in August 2023.  These AI investors include General Catalyst, Greylock, SVAngel, GV and Factory.

## Business Activities

The core problem Modular is solving is lifting the AI industry to run on production quality software. Modular is targeting the AI Industry as a whole, providing a supercharged AI language based on Python and fully integrated infrastructure capabilities.  

The AI industry has grown from research with python and adding performance with specialized solutions in C, C++ or Rust.  Moving to production often requires porting python solution and writing additional custom frameworks in more performant languages.  Modular is solving this complex workflow and deployment problem.  Instead of cobbling together all these disparate technologies, AI developers can easily move their solutions to a single unified stack.

In this approach Modular is unique in the industry.  There are many niche competitors providing AI frameworks, stacks, virtualization solutions, etc that are based on legacy technologies.  Modular is designed to easily work with all these technologies.  However, are the industry moves forward with Mojo and MAX, many of these solutions may wain or be replaced.  For example, Mojo will have more native support for C, thus reducing the need for solutions like Cython.

## Unique Product offerings

AI started in statistics and research using python, a flexible, but relatively slow interpreter language.  As AI concepts and models mature and move to production, it often requires porting the design to more performant languages like C, C++, Rust, etc.  Additional custom code is required to interface with the many GPUs and TPUs supporting massive speed and parallelization.

Chris was the cofounder of LLVM 20+ years ago.  LLVM is the compiler infrastructure under almost all modern programming languages.

Together Chris and Tim developed the MLIR compiler infrastructure.  Where LLVM only supports one dimensional vectors, MLIR can support multi-dimensional vectors.  MLIR is designed from the ground up to work on any CPU, GPU or TPU eliminating the need to import additional libraries to work with the many disparate hardware solutions.

For a programming syntax they chose python and call this new language Mojo.  Mojo will be fully backward compatible with python in the next 12-18 months.  They are being careful eliminate the migration issues caused by the python 2 to python 3 upgrade.  Because Mojo is written on MLIR, it is much more performant allowing python code to run at the speed of C.

Mojo is a superset of python providing advanced machine learning functionality.  It supports multi-dimensional vectors natively, the ability to do low level functions like SIMD and alloc.  Mojo extends python with advanced ML language features like vectorize, parallelize, tile, unrolling and others.  Mojo even provides autotuning features to optimize parameters.

Utilizing these advanced features or Mojo’s in existing python ML routines can result in up to a 35,000 times increase in execution speed.

The result is that researchers and developers will be able to use the same python and enhanced mojo code to do research and move directly to production without developing C, C++ or Rust for performance.  Using Mojo, Machine Learning code can easily target CPUs, GPUs or TPUs.

Modular is also releasing MAX, the Modular Accelerated Execution platform.  MAX is the next generation of AI infrastructure. These provide an integrated suite of products powering your full ML pipeline.  Developers can now replace all the disparate technologies in their ML pipeline with a single suite.

MAX is an inference engine.  
>*In the field of artificial intelligence, an inference engine is a component of an intelligent system that applies logical rules to the knowledge base to deduce new information.* (1)

>*The MAX Engine provides drop-in compatibility with all AI Frameworks like pytorch and tensorflow.  This includes full compatibility with all the framework operators, quantized types, and dynamic shapes.  It can easily support all your existing customized operations.  The max engine is up to 5x faster than existing infrastructure.  It supports execution across all your hardware architectures.  It is fully extensible via Mojo.  Max supports all the important genAI workloads like Llama2, Stable Diffusion, Wisper, and many others.  It also supports all traditional AI use cases like recommenders, image classification, object detection and more*(2)

>*Max adds a serving module to the Mojo language and the Max Engine.  Max Serving is a set of APIs that integrate with existing serving stack making it easy to server models with the Max Engine.  It provides drop in compatibility with NVIDIA Triton, TF Serving and Torch Serve.  Integrates into any existing container orchestration services such as Kubernetes. (2)

Modulars integrated suite with Max Engine, Max Serving, and Mojo is poised to accelerate the AI industry, increasing performance, simplifying development, and reducing operating costs.  Their current offering does not have a direct competitor in the market.  There is no other competitor rewriting the entire AI Toolchain from the ground up. 

## Landscape

Modular provides solutions to the entire AI pipeline from research to developers, ML Ops and more.  Over the last decade, other providers have tried to fix niche gaps in the AI Pipeline.  They have provided more performant algorithms and frameworks writing in C, C++ or Rust while attempting to make them work with python.  These solutions have been a bandaid to the underlying problem that the existing LLVM compiler and python are not designed to support multi-dimensional vectors, the core structure of AI/ML.

Other major vendors in the fields include Google, Facebook, NVIDIA, among others.  Each of these have advanced AI in a significant way.  Modular with MAX and Mojo is set to increase their impact on the AI industry.

## Results

Modular is still rolling out their solutions.  Initial releases of MAX Engine, MAX Server and Mojo are available.  Word is still getting out on Modular.  They also have some work left to fully implement python in Mojo.   However, the AI industry is driven by model performance (both in inference results and computation speed) and model deployment complexity.  Modular has directly targeted these areas with its product offering.

The final measure of success is adoption.  With their thoughtful approach to technology development and python backward compatibility, they focus on making Mojo very easy to adopt.  Modular is moving to open source Mojo, accelerating development of this key capability.  Adoption is a metric that will become visible in the next 12-18 months.

## Recommendations

It is difficult to make recommendations for products or services to modular. They have a board made of AI strategic investors.  Modular or building a new AI Architecture base.  Therefore, I might recommend the following:
- A partnership with AWS or Google to make Mojo & MAX easily available in the cloud.  This would accelerate early adoption.
- A partnership with NVIDIA to could provide a new compute cloud offering now that this could be require fewer players to build and deploy.

These offerings could help accelerate early adoption of MAX and Mojo in the AI Industry.  They would also give Modular and use based income stream.  In an industry dependent of compute power and ease of deployment, this is where the majority of the revenue could be earned.

References:

1. Inference Engine. (2023, February 17) In Wikipedia. https://en.wikipedia.org/wiki/Inference_engine

2. Eric Johnson, Eric. (2023, December 4) *ModCon 2023: Introducing MAX Modular Xecution Platform*.  YouTube.  https://www.youtube.com/watch?v=w708BaebI48
