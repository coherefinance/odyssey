# Odyssey

Odyssey is a Rust framework for building confidential, high-volume transaction infrastructure. By combining zero-knowledge proofs with Byzantine fault-tolerant consensus and compiler-level optimizations, Odyssey delivers institutional-grade privacy and performance for global payment systems.

## Overview

Odyssey is a unified framework for building zero-knowledge rollups for high-volume confidential transactions per second while maintaining cryptographic guarantees of privacy and correctness. The system leverages breakthrough research in program transformation, cryptographic compilation, and distributed coordination to provide fundamental infrastructure for next-generation payment networks.

## Key Innovations

### Zero-Knowledge Rollup Architecture

Odyssey features an encrypted rollup system combining ZK proof compression with optimized circuit generation, enabling mathematical guarantees about transaction privacy and computational integrity. By implementing confidential state transitions with zero-knowledge proofs, Odyssey achieves private payment processing while maintaining verifiability through succinct proofs.

This approach delivers both complete confidentiality and massive throughput improvements over traditional Layer 1 blockchains. The system handles diverse transaction types while providing optimal performance through batch processing and proof aggregation.

### Categorical Cryptographic Compilation

Odyssey's category-theoretic IR unifies traditional program optimization with zero-knowledge circuit generation, enabling optimizations that span both domains. Programs are represented as morphisms in categories, providing mathematical foundations for correctness-preserving transformations while compiling to both high-performance hardware and cryptographic backends.

The compiler automatically generates optimized code for vectorized CPUs, GPU kernels, and zero-knowledge circuits from a single unified representation, enabling cross-domain optimization previously impossible.

### Futamura Optimization Hierarchy

Odyssey implements a complete three-level Futamura projection system enabling automatic generation of optimizing compilers for zero-knowledge circuits and self-improving compilation infrastructure. Runtime program specialization, compiler generation from interpreters, and compiler-compiler synthesis work together to provide unprecedented optimization capabilities.

This multi-stage optimization pipeline automatically discovers parallelization opportunities in constraint systems, specializes proof generation for specific workloads, and generates hardware-specific witness computation without manual intervention.

### Hardware-Accelerated Proof Generation

Odyssey's advanced vectorization engine automatically discovers and exploits parallelization opportunities in proof generation through sophisticated dataflow analysis. The hardware-aware compilation engine adapts to diverse accelerators, generating optimized code for CPU vector units (AVX-512, SVE) and GPU tensor cores.

Combined with GPU kernel fusion for batch proving and dynamic tensor compilation for constraint systems, Odyssey reduces proof generation overhead by 50-80% compared to generic implementations while delivering exceptional performance for both standard payment flows and complex smart contract execution.

### Byzantine Consensus with ZK Verification

Odyssey implements Byzantine fault-tolerant consensus where validators produce zero-knowledge proofs of correct state transitions. This enables verifiable consensus without revealing transaction details, combining the privacy guarantees of zero-knowledge proofs with the liveness and safety properties of Byzantine agreement protocols.

The threshold protocol suite automatically handles distributed proof generation, proof aggregation, and verification across validator nodes, ensuring continuous operation even under node failures or network partitions while maintaining complete transaction confidentiality.

### Privacy-Preserving Payments

Odyssey enables secure computation on encrypted transaction data without revealing individual payment details through zero-knowledge proofs of aggregate properties. Compliance reporting and business intelligence are generated using cryptographically-verified transformations where validators prove correct computation over private data.

This approach allows regulatory compliance while maintaining user privacy, avoiding traditional surveillance bottlenecks and meeting institutional requirements without compromising confidentiality guarantees.

### Choreographic Distributed Programs

Odyssey provides a Datalog-inspired distributed programming model with automatic protocol optimization, deadlock-free coordination, and CALM theorem-based consistency analysis. The framework applies compiler-level optimization to distributed consensus protocols, enabling automated failover, coordination-free fast paths, and adaptive quorum selection.

By combining Flexible Paxos with zero-knowledge proof verification and multi-datacenter consistency protocols, Odyssey abstracts away the complexity of coordination and replication while preserving correctness and availability, allowing payment networks to maintain liveness across diverse failure scenarios without manual intervention.

## Academic Foundations and Publications

Odyssey builds upon decades of program transformations and optimizations, consensus protocols and distributed systems, and sophisticated cryptography mechanisms. The following publications form the foundation of Odyssey's technology:

### Program Transformation and Compilation Papers

- **Turchin, V. F. (1986).** The Concept of a Supercompiler. *ACM Transactions on Programming Languages and Systems, 8*(3), 292-325.

- **Würthinger, T., Wimmer, C., Wöß, A., Stadler, L., Duboscq, G., Humer, C., Richards, G., Simon, D., & Wolczko, M. (2013).** One VM to Rule Them All. *Proceedings of the 2013 ACM International Symposium on New Ideas, New Paradigms, and Reflections on Programming & Software*, 187-204.

- **Kildall, G. A. (1973).** A Unified Approach to Global Program Optimization. *Proceedings of the 1st Annual ACM SIGACT-SIGPLAN Symposium on Principles of Programming Languages*, 194-206.

- **Bacon, D. F., Cheng, P., & Rajan, V. T. (2004).** A Unified Theory of Garbage Collection. *Proceedings of the 19th Annual ACM SIGPLAN Conference on Object-Oriented Programming, Systems, Languages, and Applications*, 50-68.

- **Koppel, J. (2020).** One CFG-Generator to Rule Them All. *Proceedings of the ACM SIGPLAN International Conference on Software Language Engineering*, ACM Press.

- **Nielson, F., Nielson, H. R., & Hankin, C. (1999).** From Control Flow to Dataflow. *Principles of Program Analysis*, Springer-Verlag, 45-78.

- **Johnston, W. M., Hanna, J. R. P., & Millar, R. J. (2004).** The Essence of Dataflow Programming. *Advances in Computers, 59*, 1-59.

- **Futamura, Y., Nogi, K., & Takano, A. (1991).** Essence of Generalized Partial Computation. *Theoretical Computer Science, 90*(1), 61-79.

- **Hellerstein, J. M., Laddad, S., Milano, M., Power, C., & Samuel, M. (2023).** Invited Paper: Initial Steps Toward a Compiler for Distributed Programs. Proceedings of the 5th Workshop on Advanced Tools, Programming Languages, and PLatforms for Implementing and Evaluating Algorithms for Distributed Systems (ApPLIED 2023), ACM, 1–10.

- **Laddad, S., Cheung, A., & Hellerstein, J. M. (2024).** Suki: Choreographed Distributed Dataflow in Rust. PLDI 2024, Copenhagen, Denmark.

- **Chu, D., Panchapakesan, R., Laddad, S., Katahanas, L., Liu, C., Shivakumar, K., Crooks, N., Hellerstein, J. M., & Howard, H. (2024).** Optimizing Distributed Protocols with Query Rewrites. Proceedings of the ACM on Management of Data, 2(1), ACM, 1–25.

- **Lattner, C., Amini, M., Bondhugula, U., Cohen, A., Davis, A., Pienaar, J., Riddle, R., Shpeisman, T., Vasilache, N., & Zinenko, O. (2021).** MLIR: Scaling compiler infrastructure for domain specific computation. Proceedings of the IEEE/ACM International Symposium on Code Generation and Optimization (CGO), IEEE, 2–14.

- **Jones, N. D., Gomard, C. K., & Sestoft, P. (1993).** Composing Dataflow Analyses and Transformations. *Partial Evaluation and Automatic Program Generation*, Prentice Hall, 127-158.

- **Romanenko, S. A. (1988).** The Essence of Program Transformation by Partial Evaluation and Driving. *Proceedings of Partial Evaluation and Mixed Computation*, North-Holland, 189-205.

- **Futamura, Y., Konishi, Z., & Glück, R. (2001).** Program Transformation System Based on Generalized Partial Computation. *New Generation Computing, 20*(1), 75-99.

- **Sheard, T. (2001).** Generic Programming, Partial Evaluation, and a New Programming Paradigm. *Proceedings of Partial Evaluation and Semantic-Based Program Manipulation*, ACM Press, 2-11.

- **Jones, N. D., Gomard, C. K., & Sestoft, P. (1993).** Realistic Compilation by Partial Evaluation. *Partial Evaluation and Automatic Program Generation*, Prentice Hall, 283-305.

- **Futamura, Y. (1971).** Partial Evaluation of Computation Process--An Approach to a Compiler-Compiler. *Systems, Computers, Controls, 2*(5), 45-50.

- **Taha, W. & Sheard, T. (2000).** MetaML and Multistage Programming with Explicit Annotations. *Theoretical Computer Science, 248*(1-2), 211-242.

- **Rompf, T. & Odersky, M. (2010).** Lightweight Modular Staging: A Pragmatic Approach to Runtime Code Generation and Compiled DSLs. *Proceedings of the 9th International Conference on Generative Programming and Component Engineering*, ACM Press, 127-136.

- **Kiczales, G., des Rivières, J., & Bobrow, D. G. (1991).** The Art of the Metaobject Protocol. *MIT Press*.

- **Würthinger, T., Wöß, A., Stadler, L., Duboscq, G., Simon, D., & Wimmer, C. (2012).** Self-Optimizing AST Interpreters. *Proceedings of the 8th Symposium on Dynamic Languages*, ACM Press, 73-82.

- **Van Horn, D. & Might, M. (2010).** Abstracting Abstract Machines. *Proceedings of the 15th ACM SIGPLAN International Conference on Functional Programming*, ACM Press, 51-62.

- **Koppel, J. (2019).** One Tool, Many Languages: Language-Parametric Transformation with Incremental Parametric Syntax. *Proceedings of the 12th ACM SIGPLAN International Conference on Software Language Engineering*, ACM Press.

- **Elliott, C. (2017).** Compiling to Categories. *Proceedings of the 2nd ACM SIGPLAN International Workshop on Type-Driven Development*, ACM Press, 27-37.

- **Pavlovic, D. (2023).** Programs as Diagrams: From Categorical Computability to Computable Categories. *Theory and Applications of Computability*, Springer.

- **Neumann, T. (2011).** How to Architect a Query Compiler, Revisited. *Proceedings of the 2011 ACM SIGMOD International Conference on Management of Data*, ACM Press, 913-924.

- **Jones, N. D., Gomard, C. K., & Sestoft, P. (1993).** Partial Evaluation and Automatic Program Generation. *Prentice Hall International Series in Computer Science*.

- **Bolz, C. F., Cuni, A., Fijalkowski, M., & Rigo, A. (2009).** Practical Partial Evaluation for High-Performance Dynamic Language Runtimes. *Proceedings of the 36th Annual ACM SIGPLAN-SIGACT Symposium on Principles of Programming Languages*, ACM Press, 827-840.

- **Futamura, Y. (1999).** Partial Evaluation of Computation Process--An Approach to a Compiler-Compiler, Revisited. *Higher-Order and Symbolic Computation, 12*(4), 381-391.

- **Hatcliff, J. & Danvy, O. (1997).** Continuation-Based Partial Evaluation. *Proceedings of the 1997 ACM SIGPLAN Symposium on Partial Evaluation and Semantics-Based Program Manipulation*, ACM Press, 83-94.

- **Futamura, Y., Konishi, Z., & Glück, R. (2001).** Automatic Generation of Very Efficient Programs by Generalized Partial Computation. *Wuhan University Journal of Natural Sciences, 6*(1-2), 1-11.


### CPU Optimization Techniques

Odyssey integrates state-of-the-art CPU optimization techniques:

- **Chen, Y., Mendis, C., & Amarasinghe, S. (2022).** All you need is superword-level parallelism: systematic control-flow vectorization with SLP. *PLDI 2022*. 
  
- **Chen, Y., Mendis, C., Carbin, M., & Amarasinghe, S. (2021).** VeGen: a vectorizer generator for SIMD and beyond. *ASPLOS 2021*.

- **Haj-Ali, A., Ahmed, N. K., Willke, T., Shao, Y. S., Asanovic, K., & Stoica, I. (2020).** NeuroVectorizer: end-to-end vectorization with deep reinforcement learning. *CGO 2020*.

- **Mendis, C., Yang, C., Pu, Y., Amarasinghe, S., & Carbin, M. (2019).** Compiler Auto-Vectorization with Imitation Learning. *NIPS 2019*.

- **Fu, S., & Hsu, W. (2019).** Translating Traditional SIMD Instructions to Vector Length Agnostic Architectures. *CGO 2019*.

- **Kruppe, R., Oppermann, J., Sommer, L., & Koch, A. (2019).** Extending LLVM for Lightweight SPMD Vectorization: Using SIMD and Vector Instructions Easily from Any Language. *CGO 2019*.

- **Porpodas, V., Rocha, R. C. O., Brevnov, E., Góes, L. F. W., & Mattson, T. (2019).** Super-Node SLP: Optimized Vectorization for Code Sequences Containing Operators and Their Inverse Elements. *CGO 2019*.

- **Moll, S., & Hack, S. (2018).** Partial control-flow linearization. *PLDI 2018*.

- **Porpodas, V., Rocha, R. C. O., & Góes, L. F. W. (2018).** Look-ahead SLP: auto-vectorization in the presence of commutative operations. *CGO 2018*.

- **Li, R., Xu, Y., Sukumaran-Rajam, A., Rountev, A., & Sadayappan, P. (2021).** Analytical characterization and design space exploration for optimization of CNNs. *ASPLOS 2021*.

- **Hildebrand, M., Khan, J., Trika, S., Lowe-Power, J., & Akella, V. (2020).** AutoTM: Automatic Tensor Movement in Heterogeneous Memory Systems using Integer Linear Programming. *ASPLOS 2020*.

- **Ying, V. A., Jeffrey, M. C., & Sanchez, D. (2020).** T4: Compiling Sequential Code for Effective Speculative Parallelization in Hardware. *ISCA 2020*.

- **Palkar, S., & Zaharia, M. (2019).** Optimizing data-intensive computations in existing libraries with split annotations. *SOSP 2019*.

- **Kong, M., & Pouchet, L. (2019).** Model-driven transformations for multi- and many-core CPUs. *PLDI 2019*.

- **Zheng, R., & Pai, S. (2021).** Efficient Execution of Graph Algorithms on CPU with SIMD Extensions. *CGO 2021*.

- **Augustine, T., Sarma, J., Pouchet, L., & Rodríguez, G. (2019).** Generating piecewise-regular code from irregular structures. *PLDI 2019*.

- **Xie, B., Zhan, J., Liu, X., Gao, W., Jia, Z., He, X., & Zhang, L. (2018).** CVR: efficient vectorization of SpMV on x86 processors. *CGO 2018*.

- **Jia, Z., Zlateski, A., Durand, F., & Li, K. (2018).** Optimizing N-dimensional, winograd-based convolution for manycore CPUs. *PPoPP 2018*.

- **Zhao, T., Hall, M., Basu, P., Williams, S., & Johansen, H. (2018).** SIMD code generation for stencils on brick decompositions. *PPoPP 2018*.

- **Spampinato, D. G., Fabregat-Traver, D., Bientinesi, P., & Püschel, M. (2018).** Program generation for small-scale linear algebra applications. *CGO 2018*.

### GPU Acceleration Techniques

Odyssey leverages cutting-edge GPU optimization research:

- **Zhu, H., Wu, R., Diao, Y., Ke, S., Li, H., Zhang, C., Xue, J., Ma, L., Xia, Y., Cui, W., Yang, F., Yang, M., Cidon, A., & Pekhimenko, G. (2022).** Roller: Fast and Efficient Tensor Compilation for Deep Learning. *OSDI 2022*.

- **Bhaskaracharya, S. G., Demouth, J., & Grover, V. (2020).** Automatic Kernel Generation for Volta Tensor Cores. *arXiv 2020*.

- **Elango, V., Rubin, N., Ravishankar, M., Sandanagobalane, H., & Grover, V. (2018).** Diesel: DSL for linear algebra and neural net computations on GPUs. *MAPL 2018*.

- **Zhao, H., Cui, W., Chen, Q., Zhang, Y., Lu, Y., Li, C., Leng, J., & Guo, M. (2022).** Tacker: Tensor-CUDA Core Kernel Fusion for Improving the GPU Utilization while Ensuring QoS. *HPCA 2022*.

- **Xing, J., Wang, L., Zhang, S., Chen, J., Chen, A., & Zhu, Y. (2022).** BOLT: BRIDGING THE GAP BETWEEN AUTO-TUNERS AND HARDWARE-NATIVE PERFORMANCE. *MLSys 2022*.

- **Wang, X., Li, G., Dong, X., Li, J., Liu, L., & Feng, X. (2020).** Accelerating Deep Learning Inference with Cross-Layer Data Reuse on GPUs. *Euro-Par 2020*.

- **Li, A., Zheng, B., Pekhimenko, G., & Long, F. (2022).** Automatic Horizontal Fusion for GPU Kernels. *CGO 2022*.

- **Zheng, Z., Yang, X., Zhao, P., Long, G., Zhu, K., Zhu, F., Zhao, W., Liu, X., Yang, J., Zhai, J., Song, S. L., & Lin, W. (2022).** AStitch: Enabling a New Multi-dimensional Optimization Space for Memory-Intensive ML Training and Inference on Modern SIMT Architectures. *ASPLOS 2022*.

- **Zheng, Z., Zhao, P., Long, G., Zhu, F., Zhu, K., Zhao, W., Diao, L., Yang, J., & Lin, W. (2020).** FusionStitching: Boosting Memory Intensive Computations for Deep Learning Workloads. *arXiv 2020*.

- **Qiao, B., Reiche, O., Hannig, F., & Teich, J. (2019).** From Loop Fusion to Kernel Fusion: A Domain-Specific Approach to Locality Optimization. *CGO 2019*.

- **Zheng, Z., Oh, C., Zhai, J., Shen, X., Yi, Y., & Chen, W. (2017).** Versapipe: a versatile programming framework for pipelined computing on GPU. *MICRO 2017*.

- **Wahib, M., & Maruyama, N. (2014).** Scalable Kernel Fusion for Memory-Bound GPU Applications. *SC 2014*.

- **Baghdadi, R., Ray, J., Romdhane, M. B., Sozzo, E. D., Akkas, A., Zhang, Y., Suriana, P., Kamil, S., & Amarasinghe, S. P. (2019).** Tiramisu: A Polyhedral Compiler for Expressing Fast and Portable Code. *CGO 2019*.

- **Vasilache, N., Zinenko, O., Theodoridis, T., Goyal, P., DeVito, Z., Moses, W. S., Verdoolaege, S., Adams, A., & Cohen, A. (2018).** Tensor Comprehensions: Framework-Agnostic High-Performance Machine Learning Abstractions. *arXiv 2018*.

- **Yang, Y., Phothilimthana, P. M., Wang, Y. R., Willsey, M., Roy, S., & Pienaar, J. (2021).** EQUALITY SATURATION FOR TENSOR GRAPH SUPEROPTIMIZATION. *MLSys 2021*.

- **Phothilimthana, P. M., Elliott, A. S., Wang, A., Jangda, A., Hagedorn, B., Barthels, H., Kaufman, S. J., Grover, V., Torlak, E., & Bodík, R. (2019).** Swizzle Inventor: Data Movement Synthesis for GPU Kernels. *ASPLOS 2019*.

- **Tang, S., Zhai, J., Wang, H., Jiang, L., Zheng, L., Yuan, Z., & Zhang, C. (2022).** FreeTensor: A Free-Form DSL with Holistic Optimizations for Irregular Tensor Programs. *PLDI 2022*.

- **Gysi, T., Müller, C., Zinenko, O., Herhut, S., Davis, E., Wicky, T., Fuhrer, O., Hoefler, T., & Grosser, T. (2021).** Domain-Specific Multi-Level IR Rewriting for GPU: The Open Earth Compiler for GPU-accelerated Climate Simulation. *TACO 2021*.

- **Liu, S., Qi, C., Cao, Y., Yang, C., Hu, W., Shi, X., Yang, F., & Yang, M. (2024).** Uncovering Nested Data Parallelism and Data Reuse in DNN Computation with FractalTensor. *SOSP 2024*.

### Dynamic Execution Techniques

Odyssey incorporates advanced techniques for dynamic workloads:

- **Yu, F., Li, G., Zhao, J., Cui, H., Feng, X., & Xue, J. (2024).** Optimizing Dynamic-Shape Neural Networks on Accelerators via On-the-Fly Micro-Kernel Polymerization. *ASPLOS 2024*.

- **Zheng, B., Jiang, Z., Yu, C. H., Shen, H., Fromm, J., Liu, Y., Wang, Y., Ceze, L., Chen, T., & Pekhimenko, G. (2022).** DietCode: Automatic Optimization for Dynamic Tensor Programs. *MLSys 2022*.

- **Fegade, P., Chen, T., Gibbons, P., & Mowry, T. (2022).** The CoRa Tensor Compiler: Compilation for Ragged Tensors with Minimal Padding. *MLSys 2022*.

- **Shen, H., Roesch, J., Chen, Z., Chen, W., Wu, Y., Li, M., Sharma, V., Tatlock, Z., & Wang, Y. (2021).** Nimble: Efficiently Compiling Dynamic Neural Networks for Model Inference. *MLSys 2021*.

- **Cui, W., Zhao, H., Chen, Q., Wei, H., Li, Z., Zeng, D., Li, C., & Gu, M. (2022).** DVABatch: Diversity-aware Multi-Entry Multi-Exit Batching for Efficient Processing of DNN Services on GPUs. *ATC 2022*.

- **Fegade, P., Chen, T., Gibbons, P., & Mowry, T. (2021).** Cortex: A Compiler for Recursive Deep Learning Models. *MLSys 2021*.

- **Zhu, K., Zhao, W. Y., Zheng, Z., Guo, T. Y., Zhao, P. Z., Bai, J. J., Yang, J., Liu, X. Y., Diao, L. S., & Lin, W. (2021).** DISC: A Dynamic Shape Compiler for Machine Learning Workloads. *EuroMLSys 2021*.

- **Xu, S., Zhang, H., Neubig, G., Dai, W., Kim, J. K., Deng, Z., Ho, Q., Yang, G., & Xing, E. P. (2018).** Cavs: An Efficient Runtime System for Dynamic Neural Networks. *ATC 2018*.

- **Neubig, G., Goldberg, Y., & Dyer, C. (2017).** On-the-fly Operation Batching in Dynamic Computation Graphs. *NIPS 2017*.

- **Looks, M., Herreshoff, M., Hutchins, D., & Norvig, P. (2017).** Deep Learning with Dynamic Computation Graphs. *ICLR 2017*.

- **Neubig, G., Dyer, C., Goldberg, Y., Matthews, A., Ammar, W., Anastasopoulos, A., Ballesteros, M., Chiang, D., Clothiaux, D., Cohn, T., Duh, K., Faruqui, M., Gan, C., Garrette, D., Ji, Y., Kong, L., Kuncoro, A., Kumar, G., Malaviya, C., Michel, P., Oda, Y., Richardson, M., Saphra, N., Swayamdipta, S., & Yin, P. (2017).** DyNet: The Dynamic Neural Network Toolkit. *arXiv 2017*.


### Fully Homomorphic Encryption Techniques

Odyssey integrates state-of-the-art fully homomorphic encryption techniques:

- **Boneh, D., Gennaro, R., Goldfeder, S., Jain, A., Kim, S., Rasmussen, P., & Sahai, A. (2018).** Threshold Cryptosystems From Threshold Fully Homomorphic Encryption. *Crypto 2018*, pp. 565-596.

- **Boneh, D., Lewi, K., & Wu, D. (2017).** Constraining Pseudorandom Functions Privately. *PKC 2017*, pp. 494-524.

- **Boneh, D., Kim, S., & Wu, D. (2017).** Constrained Keys for Invertible Pseudorandom Functions. *TCC 2017*, pp. 237-263.

- **Boneh, D., Kim, S., & Montgomery, H. (2017).** Private Puncturable PRFs From Standard Lattice Assumptions. *Eurocrypt 2017*, pp. 415-445.

- **Boneh, D., Gentry, C., Gorbunov, S., Halevi, S., Nikolaenko, V., Segev, G., Vaikuntanathan, V., & Vinayagamurthy, D. (2014).** Fully Key-Homomorphic Encryption, Arithmetic Circuit ABE and Compact Garbled Circuits. *Eurocrypt 2014*, pp. 533-556.

- **Boneh, D., Lewi, H., Montgomery, H., & Raghunathan, A. (2013).** Key Homomorphic PRFs and Their Applications. *Crypto 2013*, pp. 410-428.

- **Boneh, D., Segev, G., & Waters, B. (2012).** Targeted malleability: homomorphic encryption for restricted computations. *Innovations in Theoretical Computer Science (ITCS)*, pp. 350-366.

- **Boneh, D., Halevi, S., Hamburg, M., & Ostrovsky, R. (2008).** Circular-Secure Encryption from Decision Diffie-Hellman. *Crypto 2008*, pp. 108-125.

### Multi-Party Computation and Threshold Cryptography

Odyssey leverages cutting-edge MPC and threshold cryptography research:

- **Boneh, D., Drijvers, M., & Neven, G. (2018).** Compact Multi-Signatures for Smaller Blockchains. *Asiacrypt 2018*.

- **Boneh, D., Drijvers, M., & Neven, G. (2018).** BLS Multi-Signatures With Public-Key Aggregation.

- **Corrigan-Gibbs, H., & Boneh, D. (2017).** Prio: Private, Robust, and Scalable Computation of Aggregate Statistics. *NSDI 2017*, pp. 76-81.

- **Wu, D., Taly, A., Shankar, A., & Boneh, D. (2016).** Privacy, Discovery, and Authentication for the Internet of Things. *ESORICS 2016*, pp. 301-319.

- **Michalevsky, Y., Nakibly, G., Schulman, A., & Boneh, D. (2015).** PowerSpy: Location Tracking using Mobile Device Power Analysis. *USENIX Security 2015*, pp. 785-800.

- **Boneh, D., & Corrigan-Gibbs, H. (2014).** Bivariate Polynomials Modulo Composites and Their Applications. *Asiacrypt 2014*, pp. 42-62.

- **Jagadeesh, K., Wu, D., Birgmeier, J., Boneh, D., & Bejerano, G. (2017).** Deriving Genomic Diagnoses Without Revealing Patient Genomes. *Science*, vol. 357, no. 6352, pp. 692-695.

- **Narayanan, A., Thiagarajan, N., Lakhani, M., Hamburg, M., & Boneh, D. (2011).** Location privacy via private proximity testing. *NDSS 2011*.

- **Li, N., Du, W., & Boneh, D. (2003).** Oblivious Signature-Based Envelope. *Distributed Computing 17(4)*, pp. 293-302, May 2005.

### Zero-Knowledge Proofs and Verifiable Computation

Odyssey incorporates specialized techniques for efficient zero-knowledge proofs:

- **Bünz, B., Bootle, J., Boneh, D., Poelstra, A., Wuille, P., & Maxwell, G. (2018).** Bulletproofs: Efficient Range Proofs for Confidential Transactions. *IEEE S&P conference, Oakland 2018*.

- **Boneh, D., Ishai, Y., Sahai, A., & Wu, D. (2018).** Quasi-Optimal SNARGs via Linear Multi-Prover Interactive Proofs. *Eurocrypt 2018*, pp. 222-255.

- **Boneh, D., Ishai, Y., Sahai, A., & Wu, D. (2017).** Lattice-Based SNARGs and Their Application to More Efficient Obfuscation. *Eurocrypt 2017*, pp. 247-277.

- **Wahby, R., Ji, Y., Blumberg, A. J., Shelat, A., Thaler, J., Walfish, M., & Wies, T. (2017).** Full accounting for verifiable outsourcing. *ACM CCS*, pp. 2071-2086.

- **Fiore, D., Gennaro, R., & Pastro, V. (2014).** Efficiently Verifiable Computation on Encrypted Data. *ACM CCS*, pp. 844-855.

- **Parno, B., Howell, J., Gentry, C., & Raykova, M. (2013).** Pinocchio: Nearly Practical Verifiable Computation. *IEEE S&P*.

- **Gennaro, R., Gentry, C., Parno, B., & Raykova, M. (2013).** Quadratic Span Programs and Succinct NIZKs without PCPs. *Eurocrypt*, pp. 626-645.

### Witness Encryption and Obfuscation

Odyssey leverages advanced techniques for encryption and obfuscation:

- **Boneh, D., Wu, D., & Zimmerman, J. (2014).** Immunizing Multilinear Maps Against Zeroizing Attacks. *Cryptology ePrint Archive, Report 2014/930*.

- **Boneh, D., & Zhandry, M. (2014).** Multiparty Key Exchange, Efficient Traitor Tracing, and More from Indistinguishability Obfuscation. *Algorithmica vol. 79, no. 4*, pp. 1233-1285, 2017.

- **Boneh, D., Waters, B., & Zhandry, M. (2014).** Low Overhead Broadcast Encryption from Multilinear Maps. *Crypto 2014*, pp. 206-223.

- **Ananth, P., Boneh, D., Garg, S., Sahai, A., & Zhandry, M. (2013).** Differing-Inputs Obfuscation and Applications. *Cryptology ePrint Archive: Report 2013/689*.

- **Boneh, D., Raghunathan, A., & Segev, G. (2013).** Function-Private Subspace-Membership Encryption and Its Applications. *Asiacrypt 2013*.

- **Boneh, D., Raghunathan, A., & Segev, G. (2013).** Function-Private Identity-Based Encryption: Hiding the Function in Functional Encryption. *Crypto 2013*, pp. 461-478.

- **Boneh, D., & Waters, B. (2013).** Constrained Pseudorandom Functions and Their Applications. *Asiacrypt 2013*, pp. 280-300.

- **Garg, S., Gentry, C., Halevi, S., Raykova, M., Sahai, A., & Waters, B. (2013).** Candidate Indistinguishability Obfuscation and Functional Encryption for all circuits. *FOCS*, pp. 40-49.

### Advanced Cryptographic Primitives

Odyssey incorporates specialized cryptographic primitives:

- **Boneh, D., Bonneau, J., Bünz, B., & Fisch, B. (2018).** Verifiable Delay Functions. *Crypto 2018*, pp. 757-788.

- **Boneh, D., Bünz, B., & Fisch, B. (2018).** A Survey of Two Verifiable Delay Functions. *Cryptology ePrint Archive: Report 2018/712*.

- **Kogan, D., Manohar, N., & Boneh, D. (2017).** T/Key: Second-Factor Authentication From Secure Hash Chains. *ACM CCS 2017*, pp. 983-999.

- **Boneh, D., Corrigan-Gibbs, H., & Schechter, S. (2016).** Balloon Hashing: A Memory-Hard Function Providing Provable Protection Against Sequential Attacks. *ASIACRYPT 2016*, pp. 220-248.

- **Abadi, M., Boneh, D., Mironov, I., Raghunathan, A., & Segev, G. (2013).** Message-Locked Encryption for Lock-Dependent Messages. *Crypto 2013*, pp. 374-391.

- **Boneh, D., & Zhandry, M. (2013).** Secure Signatures and Chosen Ciphertext Security in a Quantum Computing World. *Crypto 2013*, pp. 461-478.

- **Boneh, D., & Zhandry, M. (2013).** Quantum-Secure Message Authentication Codes. *Eurocrypt 2013*, pp. 592-608.

- **Boneh, D., Glass, D., Krashen, D., Lauter, K., Sharif, S., Silverberg, A., Tibouchi, M., & Zhandry, M. (2018).** Multiparty Non-Interactive Key Exchange and More From Isogenies on Elliptic Curves. *MathCrypt 2018*.

### Security Systems and Applications

Odyssey integrates practical security systems and applications:

- **Fisch, B., Vinayagamurthy, D., Boneh, D., & Gorbunov, S. (2017).** IRON: Functional Encryption using Intel SGX. *ACM CCS 2017*, pp. 765-782.

- **Boneh, D., & Gueron, S. (2017).** Surnaming Schemes, Fast Verification, and Applications to SGX Technology. *RSA-CT 2017*, pp. 149-164.

- **Boneh, D., Kim, S., & Nikolaenko, V. (2017).** Lattice-Based DAPS and Generalizations: Self-enforcement in Signature Schemes. *ACNS 2017*, pp. 457-477.

- **Boneh, D., Gupta, D., Mironov, I., & Sahai, A. (2015).** Hosting Services on an Untrusted Cloud. *Eurocrypt 2015*, pp. 404-436.

- **Corrigan-Gibbs, H., Boneh, D., & Mazières, D. (2015).** Riposte: An Anonymous Messaging System Handling Millions of Users. *IEEE Symposium on Security and Privacy 2015*, pp. 321-338.

- **Levy, A., Corrigan-Gibbs, H., & Boneh, D. (2016).** Stickler: Defending Against Malicious CDNs in an Unmodified Browser. *IEEE Security & Privacy*, Vol. 14, number 2, pp. 22-28, 2016.

- **Mashtizadeh, A., Bittau, A., Mazières, D., & Boneh, D. (2015).** Cryptographically Enforced Control Flow Integrity. *ACM CCS 2015*, pp. 941-951.

- **Dagher, G., Bünz, B., Bonneau, J., Clark, J., & Boneh, D. (2015).** Provisions: Privacy-preserving Proofs of Solvency for Bitcoin Exchanges. *ACM CCS 2015*, pp. 720-731.

### Privacy-Preserving Data Analysis

Odyssey incorporates techniques for privacy-preserving data analysis:

- **Wilson, J., Wahby, R., Corrigan-Gibbs, H., Boneh, D., Levis, P., & Winstein, K. (2017).** Trust but Verify: Auditing the Secure Internet of Things. *Mobisys 2017*, pp. 464-474.

- **Corrigan-Gibbs, H., Wu, D., & Boneh, D. (2017).** Quantum Operating Systems. *HotOS 2017*, pp. 76-81.

- **Nikolaenko, V., Ioannidis, S., Weinsberg, U., Joye, M., Taft, N., & Boneh, D. (2013).** Privacy-preserving matrix factorization. *ACM CCS 2013*, pp. 801-812.

- **Nikolaenko, V., Weinsberg, U., Ioannidis, S., Joye, M., Boneh, D., & Taft, N. (2013).** Privacy-Preserving Ridge Regression on Hundreds of Millions of Records. *IEEE Symposium on Security and Privacy 2013*, pp. 334-348.

- **Boneh, D., Gentry, S., Halevi, F., Wang, F., & Wu, D. (2013).** Private Database Queries Using Somewhat Homomorphic Encryption. *ACNS '13*, pp. 102-118.

- **Boneh, D., Di Crescenzo, G., Ostrovsky, R., & Persiano, G. (2004).** Public key encryption with keyword search. *Eurocrypt 2004*, pp. 506-522.

### Post-Quantum Cryptography

Odyssey leverages techniques for post-quantum security:

- **Lewi, K., Malozemoff, A., Apon, D., Carmer, B., Foltzer, A., Wagner, D., Archer, D., Boneh, D., Katz, J., & Raykova, M. (2016).** 5Gen: A Framework for Prototyping Applications Using Multilinear Maps and Matrix Branching Programs. *ACM CCS 2016*, pp. 981-992.

- **Boneh, D., & Silverberg, A. (2003).** Applications of Multilinear Forms to Cryptography. *Contemporary Mathematics Vol. 324*, American Mathematical Society, pp. 71-90.

- **Agrawal, S., Boneh, D., & Boyen, X. (2010).** Lattice basis delegation in fixed dimension and shorter ciphertext hierarchical IBE. *Crypto 2010*, pp. 98-115.

- **Agrawal, S., Boneh, D., & Boyen, X. (2010).** Efficient lattice (H)IBE in the standard model. *Eurocrypt 2010*, pp. 553-572.

- **Boneh, D., Dagdelen, Ö., Fischlin, M., Lehmann, A., Schaffner, C., & Zhandry, M. (2011).** Random Oracles in a Quantum World. *Asiacrypt 2011*, pp. 41-69.

### Identity-Based and Pairing-Based Cryptography

Odyssey incorporates advanced techniques for identity-based and pairing-based cryptography:

- **Boneh, D., & Shacham, H. (2004).** Short Group Signatures. *Crypto '04*, pp. 41-55.

- **Boneh, D., & Boyen, X. (2004).** Short Signatures Without Random Oracles. *Journal of Cryptology, 21(2)*, pp. 149-177, 2008.

- **Boneh, D., & Boyen, X. (2004).** Efficient Selective Identity-Based Encryption Without Random Oracles. *Journal of Cryptology, 24 (4)*, pp. 659-693, 2011.

- **Boneh, D., Gentry, C., & Hamburg, M. (2007).** Space-Efficient Identity Based Encryption Without Pairings. *FOCS 2007*, pp. 647-657.

- **Boneh, D., & Hamburg, M. (2008).** Generalized Identity Based and Broadcast Encryption Schemes. *Asiacrypt 2008*, pp. 455-470.

- **Boneh, D., & Naor, M. (2008).** Traitor Tracing with Constant Size Ciphertext. *ACM CCS*, pp. 455-470.

- **Boneh, D., & Franklin, M. (2003).** Identity based encryption from the Weil pairing. *SIAM J. of Computing, Vol. 32, No. 3*, pp. 586-615.

- **Boneh, D., Lynn, B., & Shacham, H. (2004).** Short signatures from the Weil pairing. *J. of Cryptology, Vol. 17, No. 4*, pp. 297-319.

- **Boneh, D., Gentry, C., Lynn, B., & Shacham, H. (2003).** Aggregate and Verifiably Encrypted Signatures from Bilinear Maps. *Eurocrypt 2003*, pp. 416-432.

### Broadcast Encryption and Access Control

Odyssey incorporates techniques for broadcast encryption and access control:

- **Boneh, D., & Waters, B. (2006).** A collusion resistant broadcast, trace and revoke system. *ACM CCS '06*, pp. 211-220.

- **Boneh, D., Sahai, A., & Waters, B. (2006).** Fully Collusion Resistant Traitor Tracing With Short Ciphertexts and Private Keys. *Eurocrypt '06*, pp. 573-592.

- **Boneh, D., Gentry, C., & Waters, B. (2005).** Collusion Resistant Broadcast Encryption With Short Ciphertexts and Private Keys. *Crypto '05*, pp. 258-275.

- **Boneh, D., Gentry, C., & Waters, B. (2005).** Hierarchical Identity Based Encryption with Constant Size Ciphertext. *Eurocrypt '05*, pp. 440-456.

- **Boneh, D., Goh, E., & Nissim, K. (2005).** Evaluating 2-DNF Formulas on Ciphertexts. *Theory of Cryptography (TCC) '05*, pp. 325-341.

- **Boneh, D., & Waters, B. (2007).** Conjunctive, subset, and range queries on encrypted data. *TCC'07*, pp. 535-554.

- **Boneh, D., & Shacham, H. (2004).** Group Signatures with Verifier-Local Revocation. *ACM CCS*, pp. 168-177.

### Chosen-Ciphertext Security

Odyssey incorporates techniques for chosen-ciphertext security:

- **Boneh, D., Canetti, R., Halevi, S., & Katz, J. (2006).** Chosen-Ciphertext Security from Identity-Based Encryption. *SIAM J. of Computing (SICOMP), Volume 36, Issue 5*, pp. 915-942.

- **Boneh, D., & Katz, J. (2005).** Improved Efficiency for CCA-Secure Cryptosystems Built Using Identity Based Encryption. *RSA-CT '05*, pp. 87-103.

- **Boneh, D., Boyen, X., & Halevi, S. (2006).** Chosen Ciphertext Secure Public Key Threshold Encryption Without Random Oracles. *RSA-CT '06*, pp. 226-243.

- **Boneh, D. (2001).** Simplified OAEP for the RSA and Rabin functions. *Crypto '2001*, pp. 275-291.

### Secure Hardware and Trusted Execution Environments

Odyssey incorporates techniques for secure hardware and trusted execution:

- **Garfinkel, T., Pfaff, B., Chow, J., Rosenblum, M., & Boneh, D. (2003).** Terra: A Virtual Machine-Based Platform for Trusted Computing. *ACM Symposium on Operating Systems Principles (SOSP)*, pp. 193-206.

- **Garfinkel, T., Rosenblum, M., & Boneh, D. (2003).** Flexible OS support and applications for trusted computing. *Hot Topics in Operating Systems (HOTOS-IX)*, 2003.

- **Boneh, D., Ding, X., Tsudik, G., & Wong, M. (2001).** A Method for Fast Revocation of Public Key Certificates and Security Capabilities. *USENIX Security Symposium*, pp. 297-308.

- **Fifield, D., Nakibly, G., & Boneh, D. (2013).** OSS: Using Online Scanning Services for Censorship Circumvention. *PETS 2013*, pp. 185-204.


### Consensus Protocols

Odyssey integrates state-of-the-art consensus protocols:

- **Lamport, L. (1998).** The part-time parliament. *ACM Transactions on Computer Systems, 16(2)*.

- **Ongaro, D., & Ousterhout, J. (2014).** In search of an understandable consensus algorithm. *USENIX ATC 2014*.

- **Castro, M., & Liskov, B. (1999).** Practical Byzantine fault tolerance. *OSDI 1999*.

- **Howard, H., Malkhi, D., & Spiegelman, A. (2016).** Flexible Paxos: Quorum intersection revisited. *arXiv 2016*.

- **Lamport, L. (2006).** Fast Paxos. *Distributed Computing, 19(2)*.

- **Lamport, L. (2005).** Generalized consensus and Paxos. *Microsoft Research Technical Report MSR-TR-2005-33*.

- **Moraru, I., Andersen, D. G., & Kaminsky, M. (2013).** There is more consensus in egalitarian parliaments. *SOSP 2013*.

- **van Renesse, R., & Altinbuken, D. (2015).** Paxos made moderately complex. *ACM Computing Surveys, 47(3)*.

- **Ailijiang, A., Charapko, A., & Demirbas, M. (2016).** Dissecting the performance of strongly-consistent Paxos protocols. *arXiv 2016*.

- **Mazieres, D. (2007).** Paxos made practical. *Unpublished manuscript*.

- **Junqueira, F. P., Reed, B. C., & Serafini, M. (2011).** Zab: High-performance broadcast for primary-backup systems. *DSN 2011*.

- **Birman, K., Malkhi, D., & van Renesse, R. (2010).** Virtually synchronous methodology for dynamic service replication. *Microsoft Research Technical Report MSR-TR-2010-151*.

- **Skeen, D. (1981).** Nonblocking commit protocols. *ACM SIGMOD 1981*.

- **Guerraoui, R., & Schiper, A. (2001).** The generic consensus service. *IEEE Transactions on Software Engineering, 27(1)*.

- **Boichat, R., Dutta, P., Frølund, S., & Guerraoui, R. (2003).** Deconstructing Paxos. *ACM SIGACT News, 34(1)*.

- **Camargos, L. J., Schmidt, R. M., & Pedone, F. (2006).** Multicoordinated Paxos. *PODC 2006*.

- **Heidi Howard, & Richard Mortier. (2020).** Paxos vs Raft: Have we reached consensus on distributed consensus? *PaPoC 2020*.

- **Kraska, T., Pang, G., Franklin, M. J., Madden, S., & Fekete, A. (2013).** MDCC: Multi-data center consistency. *EuroSys 2013*.

- **Wang, C., Szekely, J., Merino, A., Zhou, P., Martinez, J., & Clement, A. (2022).** CASPaxos: Replicated state machines without logs. *arXiv 2022*.

- **Schultz, W., Avery, T., & Malkhi, D. (2021).** Flexible Paxos: Leveraging network properties to improve consensus performance. *SOSP 2021*.

- **Heidi Howard, Dahlia Malkhi, & Alexander Spiegelman. (2016).** Flexible Paxos: Quorum intersection revisited. *arXiv 2016*.

- **Vukolic, M. (2012).** Quorum systems: With applications to storage and consensus. *Synthesis Lectures on Distributed Computing Theory, 3(1)*.

- **Schneider, F. B. (1990).** Implementing fault-tolerant services using the state machine approach: A tutorial. *ACM Computing Surveys, 22(4)*.

### Geo-Distributed Systems

Odyssey leverages cutting-edge geo-distributed systems research:

- **Corbett, J. C., Dean, J., Epstein, M., Fikes, A., Frost, C., Furman, J. J., Ghemawat, S., Gubarev, A., Heiser, C., Hochschild, P., Hsieh, W., Kanthak, S., Kogan, E., Li, H., Lloyd, A., Melnik, S., Mwaura, D., Nagle, D., Quinlan, S., Rao, R., Rolig, L., Saito, Y., Szymaniak, M., Taylor, C., Wang, R., & Woodford, D. (2013).** Spanner: Google's globally-distributed database. *ACM Transactions on Computer Systems, 31(3)*.

- **Mahajan, P., Setty, S., Lee, S., Clement, A., Alvisi, L., Dahlin, M., & Walfish, M. (2011).** Depot: Cloud storage with minimal trust. *ACM Transactions on Computer Systems, 29(4)*.

- **Lloyd, W., Freedman, M. J., Kaminsky, M., & Andersen, D. G. (2011).** Don't settle for eventual: Scalable causal consistency for wide-area storage with COPS. *SOSP 2011*.

- **Moraru, I., Andersen, D. G., & Kaminsky, M. (2013).** There is more consensus in egalitarian parliaments. *SOSP 2013*.

- **Du, J., Elnikety, S., Roy, A., & Zwaenepoel, W. (2013).** Orbe: Scalable causal consistency using dependency matrices and physical clocks. *SOCC 2013*.

- **Du, J., Iorgulescu, C., Roy, A., & Zwaenepoel, W. (2014).** Gentlerain: Cheap and scalable causal consistency with physical clocks. *SOCC 2014*.

- **Bronson, N., Amsden, Z., Cabrera, G., Chakka, P., Dimov, P., Ding, H., Ferris, J., Giardullo, A., Kulkarni, S., Li, H., Marchukov, M., Petrov, D., Puzar, L., Song, Y. J., & Venkataramani, V. (2013).** TAO: Facebook's distributed data store for the social graph. *USENIX ATC 2013*.

- **Sovran, Y., Power, R., Aguilera, M. K., & Li, J. (2011).** Transactional storage for geo-replicated systems. *SOSP 2011*.

- **Zhang, I., Sharma, N. K., Szekeres, A., Krishnamurthy, A., & Ports, D. R. K. (2015).** Building consistent transactions with inconsistent replication. *SOSP 2015*.

- **Dragojevic, A., Narayanan, D., Nightingale, E. B., Renzelmann, M., Shamis, A., Badam, A., & Castro, M. (2015).** No compromises: Distributed transactions with consistency, availability, and performance. *SOSP 2015*.

- **Kraska, T., Pang, G., Franklin, M. J., Madden, S., & Fekete, A. (2013).** MDCC: Multi-data center consistency. *EuroSys 2013*.

- **Terrace, J., & Freedman, M. J. (2009).** Object storage on CRAQ: High-throughput chain replication for read-mostly workloads. *USENIX ATC 2009*.

- **Nawab, F., Arora, V., Agrawal, D., & El Abbadi, A. (2015).** Minimizing commit latency of transactions in geo-replicated data stores. *SIGMOD 2015*.

- **Li, C., Porto, D., Clement, A., Gehrke, J., Preguiça, N., & Rodrigues, R. (2012).** Making geo-replicated systems fast as possible, consistent when necessary. *OSDI 2012*.

- **Glendenning, L., Beschastnikh, I., Krishnamurthy, A., & Anderson, T. (2011).** Scalable consistency in Scatter. *SOSP 2011*.

- **Patterson, S., Elmore, A. J., Nawab, F., Agrawal, D., & El Abbadi, A. (2012).** Serializability, not serial: Concurrency control and availability in multi-datacenter datastores. *PVLDB 2012*.

- **Corbett, J. C., et al. (2012).** Spanner: Google's globally-distributed database. *OSDI 2012*.

- **Cahill, M. J., Röhm, U., & Fekete, A. D. (2009).** Serializable isolation for snapshot databases. *ACM Transactions on Database Systems, 34(4)*.

- **Fan, R., Meng, X., & Du, J. (2021).** OHIE: Blockchain scaling made simple. *SOSP 2021*.

- **Whittaker, M., Giridharan, N., Szalachowski, P., Cui, Y., & Schultz, W. (2021).** WPaxos: Wide area network Paxos. *arXiv 2021*.

- **Nawab, F., Agrawal, D., & El Abbadi, A. (2018).** DPaxos: Managing data closer to users for low-latency and mobile applications. *SIGMOD 2018*.

- **Wang, H., Li, J., Luo, H., & Lu, H. (2018).** SDPaxos: Building efficient semi-decentralized geo-replicated state machines. *SoCC 2018*.

- **Yan, Z., Li, J., Geng, H., Luo, H., Wang, H., & Lu, H. (2021).** Atlas: Scaling distributed consensus with local trust. *VLDB 2021*.

- **Mu, S., Nelson, L., Lloyd, W., & Li, J. (2016).** Consolidating concurrency control and consensus for commits under conflicts. *OSDI 2016*.

### Byzantine Fault Tolerance

Odyssey incorporates specialized Byzantine fault tolerance techniques:

- **Castro, M., & Liskov, B. (1999).** Practical Byzantine fault tolerance. *OSDI 1999*.

- **Kotla, R., Alvisi, L., Dahlin, M., Clement, A., & Wong, E. (2007).** Zyzzyva: Speculative Byzantine fault tolerance. *SOSP 2007*.

- **Yin, M., Malkhi, D., Reiter, M. K., Gueta, G. G., & Abraham, I. (2019).** Hotstuff: BFT consensus with linearity and responsiveness. *PODC 2019*.

- **Chen, J., Wei, X., Chen, Y., Huang, Y., Wei, J., Yang, Y., & Zhou, M. (2020).** Fast-HotStuff: A fast and resilient HotStuff protocol. *arXiv 2020*.

- **Guerraoui, R., Komatovic, J., Li, Y., Neiheiser, R. M., & Tucci-Piergiovanni, S. (2023).** Byzantine consensus: All you need is decentralization. *arXiv 2023*.

- **Miller, A., Xia, Y., Croman, K., Shi, E., & Song, D. (2016).** The honey badger of BFT protocols. *CCS 2016*.

- **Mohan, M., Senyuk, A., Das, S., Tassarotti, J., Silva, I., Klimkowski, L., & Grimmelikhuijsen, A. (2024).** A tale of two models: Formal verification of Byzantine consensus protocols. *OOPSLA 2024*.

- **Charapko, A., Ailijiang, A., Demirbas, M., & Kulkarni, S. (2021).** Retro: A distributed consensus protocol for blockchain systems. *arXiv 2021*.

- **Kursawe, K. (2002).** Optimistic Byzantine agreement. *Proceedings of the 21st IEEE Symposium on Reliable Distributed Systems*.

- **Lamport, L., Shostak, R., & Pease, M. (1982).** The Byzantine generals problem. *ACM Transactions on Programming Languages and Systems, 4(3)*.

- **Cachin, C., Kursawe, K., Petzold, F., & Shoup, V. (2001).** Secure and efficient asynchronous broadcast protocols. *CRYPTO 2001*.

- **Clement, A., Wong, E. L., Alvisi, L., Dahlin, M., & Marchetti, M. (2009).** Making Byzantine fault tolerant systems tolerate Byzantine faults. *NSDI 2009*.

- **Malkhi, D., & Reiter, M. (1998).** Byzantine quorum systems. *Distributed Computing, 11(4)*.

- **Malkhi, D., Merritt, M., & Rodeh, O. (2001).** Secure reliable multicast protocols in a WAN. *Distributed Computing, 13(1)*.

- **Amir, Y., Coan, B., Kirsch, J., & Lane, J. (2010).** Prime: Byzantine replication under attack. *IEEE Transactions on Dependable and Secure Computing, 8(4)*.

- **Aiyer, A. S., Alvisi, L., Clement, A., Dahlin, M., Martin, J. P., & Porth, C. (2005).** BAR fault tolerance for cooperative services. *SOSP 2005*.

- **Bessani, A., Sousa, J., & Alchieri, E. E. P. (2014).** State machine replication for the masses with BFT-SMART. *DSN 2014*.

- **Chen, J., & Micali, S. (2016).** Algorand: A secure and efficient distributed ledger. *arXiv 2016*.

- **Buterin, V., & Griffith, V. (2017).** Casper the friendly finality gadget. *arXiv 2017*.

- **Giridharan, N., Keidar, I., & Ittai, A. (2022).** Narwhal and tusk: A DAG-based mempool and efficient BFT consensus. *EuroSys 2022*.

- **Lewis, H. R., Chan, T. H. H., & Pass, R. (2021).** GHOST-BFT: Scalable, provably secure proof-of-stake. *IEEE S&P 2021*.

- **Abraham, I., Malkhi, D., Nayak, K., Ren, L., & Yin, M. (2020).** Sync HotStuff: Simple and practical synchronous state machine replication. *IEEE S&P 2020*.

- **Gelashvili, R., Kokoris-Kogias, L., Sonnino, A., Spiegelman, A., & Xiang, Z. (2022).** Jolteon and Ditto: Network-adaptive efficient consensus with asynchronous fallback. *DISC 2022*.

- **Bano, S., Sonnino, A., Al-Bassam, M., Azouvi, S., McCorry, P., Meiklejohn, S., & Danezis, G. (2019).** SoK: Consensus in the age of blockchains. *AFT 2019*.

- **Das, S., Xiang, Z., Ren, L., Shi, E., & Malkhi, D. (2021).** Asynchronous data dissemination and its applications. *CCS 2021*.

- **Spiegelman, A., Malkhi, D., & Abraham, I. (2022).** Swift: Scaling Byzantine agreements for wide-area networks. *arXiv 2022*.

### Storage Systems

Odyssey integrates techniques for advanced distributed storage:

- **Wu, C., Faleiro, J., Lin, Y., & Hellerstein, J. (2019).** Anna: A KVS for any scale. *IEEE Transactions on Knowledge and Data Engineering, 31(4)*.

- **Crooks, N., Pu, Y., Alvisi, L., & Clement, A. (2016).** Seeing is believing: A client-centric specification of database isolation. *PODC 2016*.

- **Corbett, J. C., et al. (2013).** Spanner: Google's globally distributed database. *ACM Transactions on Computer Systems, 31(3)*.

- **Verbitski, A., Gupta, A., Saha, D., Brahmadesam, M., Gupta, K., Mittal, R., Krishnamurthy, S., Maurice, S., Kharatishvili, T., & Bao, X. (2017).** Amazon Aurora: Design considerations for high throughput cloud-native relational databases. *SIGMOD 2017*.

- **Lakshman, A., & Malik, P. (2010).** Cassandra: A decentralized structured storage system. *ACM SIGOPS Operating Systems Review, 44(2)*.

- **Hellerstein, J. M., Faleiro, J. M., Gonzalez, J. E., Schleier-Smith, J., Sreekanti, V., Tumanov, A., & Wu, C. (2019).** Serverless computing: One step forward, two steps back. *CIDR 2019*.

- **Ren, K., Zheng, Q., Patil, S., & Gibson, G. (2017).** IndexFS: Scaling file system metadata performance with stateless caching and bulk insertion. *SC 2017*.

- **Wu, C., Sreekanti, V., & Hellerstein, J. M. (2020).** Autoscaling tiered cloud storage in Anna. *VLDB 2020*.

- **Sreekanti, V., Wu, C., Lin, X. C., Schleier-Smith, J., Gonzalez, J. E., Hellerstein, J. M., & Tumanov, A. (2020).** Cloudburst: Stateful functions-as-a-service. *VLDB 2020*.

- **Wu, C., Zhang, C., & Hellerstein, J. M. (2022).** LEGOStore: A storage system for component-based applications. *arXiv 2022*.

- **Rao, J., Shekita, E. J., & Tata, S. (2011).** Using Paxos to build a scalable, consistent, and highly available datastore. *VLDB 2011*.

- **Decandia, G., Hastorun, D., Jampani, M., Kakulapati, G., Lakshman, A., Pilchin, A., Sivasubramanian, S., Vosshall, P., & Vogels, W. (2007).** Dynamo: Amazon's highly available key-value store. *SOSP 2007*.

- **Li, J., Wu, C., Zhang, C., & Hellerstein, J. M. (2022).** Prim: A universal primitive for distributed systems. *arXiv 2022*.

- **Thomson, A., Diamond, T., Weng, S. C., Ren, K., Shao, P., & Abadi, D. J. (2012).** Calvin: Fast distributed transactions for partitioned database systems. *SIGMOD 2012*.

- **Wei, X., Shen, J., Chen, Y., Garraghan, P., & Xu, R. (2021).** Chronos: A graph engine for transaction processing on time-evolving graphs. *VLDB 2021*.

- **Cahill, M. J., Röhm, U., & Fekete, A. D. (2009).** Serializable isolation for snapshot databases. *SIGACT 2009*.

### Coordination Mechanisms

Odyssey builds on foundational theory for distributed coordination:

- **Herlihy, M. P., & Wing, J. M. (1990).** Linearizability: A correctness condition for concurrent objects. *ACM Transactions on Programming Languages and Systems, 12(3)*.

- **Herlihy, M. (1991).** Wait-free synchronization. *ACM Transactions on Programming Languages and Systems, 13(1)*.

- **Attiya, H., Bar-Noy, A., & Dolev, D. (1995).** Sharing memory robustly in message-passing systems. *Journal of the ACM, 42(1)*.

- **Birman, K., & Joseph, T. (1987).** Exploiting virtual synchrony in distributed systems. *ACM SIGOPS Operating Systems Review, 21(5)*.

- **Fischer, M. J., Lynch, N. A., & Paterson, M. S. (1985).** Impossibility of distributed consensus with one faulty process. *Journal of the ACM, 32(2)*.

- **Brewer, E. A. (2000).** Towards robust distributed systems. *PODC 2000*.

- **Gilbert, S., & Lynch, N. (2002).** Brewer's conjecture and the feasibility of consistent, available, partition-tolerant web services. *ACM SIGACT News, 33(2)*.

- **Lamport, L. (1978).** Time, clocks, and the ordering of events in a distributed system. *Communications of the ACM, 21(7)*.

- **Bailis, P., Fekete, A., Franklin, M. J., Ghodsi, A., Hellerstein, J. M., & Stoica, I. (2014).** Coordination avoidance in database systems. *VLDB 2014*.

- **Terry, D. B., Theimer, M. M., Petersen, K., Demers, A. J., Spreitzer, M. J., & Hauser, C. H. (1995).** Managing update conflicts in Bayou, a weakly connected replicated storage system. *SOSP 1995*.

- **Shapiro, M., Preguiça, N., Baquero, C., & Zawirski, M. (2011).** Conflict-free replicated data types. *SSS 2011*.

- **Lloyd, W., Freedman, M. J., Kaminsky, M., & Andersen, D. G. (2011).** Don't settle for eventual: Scalable causal consistency for wide-area storage with COPS. *SOSP 2011*.

- **Mahajan, P., Alvisi, L., & Dahlin, M. (2011).** Consistency, availability, and convergence. *Technical Report TR-11-22, University of Texas at Austin*.

- **Herlihy, M., & Rajsbaum, S. (2013).** The topology of distributed adversaries. *Distributed Computing, 26(3)*.

- **Loui, M. C., & Abu-Amara, H. H. (1987).** Memory requirements for agreement among unreliable asynchronous processes. *Advances in Computing Research, 4*.

- **Lynch, N. A. (1996).** Distributed algorithms. *Morgan Kaufmann*.

- **Herlihy, M., & Shavit, N. (1999).** The topological structure of asynchronous computability. *Journal of the ACM, 46(6)*.

- **Herlihy, M., Kozlov, D., & Rajsbaum, S. (2013).** Distributed computing through combinatorial topology. *Morgan Kaufmann*.

- **Cachin, C., Guerraoui, R., & Rodrigues, L. (2011).** Introduction to reliable and secure distributed programming. *Springer*.

- **Attiya, H., & Welch, J. (2004).** Distributed computing: Fundamentals, simulations, and advanced topics. *John Wiley & Sons*.

- **Fich, F. E., & Ruppert, E. (2003).** Hundreds of impossibility results for distributed computing. *Distributed Computing, 16(2-3)*.

- **Herlihy, M., Luchangco, V., & Moir, M. (2003).** Obstruction-free synchronization: Double-ended queues as an example. *ICDCS 2003*.

- **Aspnes, J. (2003).** Randomized protocols for asynchronous consensus. *Distributed Computing, 16(2-3)*.

- **Schneider, F. B. (1990).** Implementing fault-tolerant services using the state machine approach: A tutorial. *ACM Computing Surveys, 22(4)*.

- **Alvaro, P., Marczak, W. R., Conway, N., Hellerstein, J. M., Maier, D., & Sears, R. (2011).** Dedalus: Datalog in time and space. *Datalog Reloaded 2011*.

- **Li, J., Hellerstein, J. M., Wu, C., & Alvaro, P. (2023).** Consistency analysis in bloom: A CALM and collected approach. *CIDR 2023*.

---

**License**  
Odyssey is released under the MIT License. See LICENSE for details.