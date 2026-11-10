**Name:** Maggie Zhang

**Email:** maz007@ucsd.edu

**Section:** D38 Efficient AI: Algorithms and Systems for Foundation Models

**Mentor:** Zhijian Liu

---

**What is the most interesting topic covered in your domain this quarter?** 

The most interesting topic covered in our domain this quarter to me is what speculative decoding actually is and how it can help accelerate LM inference. The idea that we can use probabilistic guidelines to shrink model sizes while retaining the same outputs is very interesting and more than needed in today's current environment.


**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

Currently, I am interested in investigating how different changes in an RL-trained policy affect speculative decoding acceptance rates, and what methods of altering and updating draft model could improve rollout efficiency from speculative decoding. Specifically, I would be interested in incorporating quantization into our pipeline.


**What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

Currently, our Quarter 1 project only has a fixed draft model with the speculative decoding part loaded in. I would like to start implementing and enhancing the RL (GRPO aspect) of our project and looking at what changes happen when the target policy evolves. Also, I would be interested in looking at the effects of dataset and ablation on our results, since this is a data science concept that is sometimes overlooked in ML in order to focus on finetuning hyperparameters or something about the model rather than the original data science setup.


**What other techniques would you be interested in using in your project?**

Some possible techniques that we might implement in the future that I'm interested in include exploring adaptive speculation lengths (in this case specifically for the structure of RL), acceptance-rate monitoring and fallback/kill switch built into the code, and controlled benchmarks across different reasoning workloads. It would also be interesting to target our current hardware (RTX 5070) but also try the finalized product on even weaker/more consumer friendly GPUs. 
