Reduced product of abstract domains bachelor thesis
===================================================

Latest build: [reduced_product.pdf](http://jandupal.com/publications/reduced_product.pdf)

## Description

[Canal](https://github.com/karelklic/canal) is a static analysis tool designed to analyze behaviour of application programs written in C. It is based on the theoretical framework of abstract interpretation, with focus on the scalability to large programs and proper handling of real-world source code.

Reduced product of abstract domains is a mechanism enabling an incremental evolution of abstract interpreter by introducing simple abstract domains one by one, and supporting program-specific domains. The reduced product itself is an abstract domain, and its operations (transformers) use the transformers of underlying domains component-wise. Underlying domains can improve their precision by exchanging information.

The goal of this thesis is to design and develop a generic reduced product in the context of Canal. The reduced product must provide means to exchange information between the underlying domains while keeping the domains themselves independent from each other. The impact of reduced product of integer intervals, bit field and set abstract domains on the analysis of numeric programs should be measured.
