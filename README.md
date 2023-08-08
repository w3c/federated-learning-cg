# [W3C Federated Learning CG](https://www.w3.org/community/federated-learning/)
The purpose of the group is to establish and explore the necessary standards related with the Web for federated learning via the analysis of current implementations related with federated learning such as TensorFlow Federated.

The rough roadmap for FL CG is as follows:
(Timeline is TBD)
* Step 1: Gathering and analysing implementation frameworks for federated learning
* Step 2: Looking for the candidate items for W3C standards
* Step 3: Writing down the CG report regarding federated learning
* Step 4: Developing the draft of W3C spec related with federated learning

## Federated Learning API
 * Current version: [Editor's draft of Federated Learning API](https://w3c.github.io/federated-learning-cg/reports/index.html)
 * Version 0.1 (06.30):
 * Version 0.3 (09.15):
 * Version 0.5 (10.15):
 * Version 0.6 (11.30):
     
## Current implementations for federated learning
* [TensorFlow Federated(TFF)](https://github.com/tensorflow/federated): 
  * TFF is an open-source framework for machine learning and other computations on decentralized data
  * TFF has been developed to facilitate open research and experimentation with Federated Learning (FL), an approach to machine learning where a shared global model is trained across many participating clients that keep their training data locally
* [FATE (Federated AI Technology Enabler)](https://fate.fedai.org/)
  * FATE is an open-source project that aims to support a secure and federated AI ecosystem
* [Substra](https://www.substra.ai/)
  * Substra is a federated learning software framework developed by a multi-partner research project around Owkin, a French startup founded in 2016. Substra is focused on the medical field with the purpose of data ownership and privacy
* [PySyft](https://github.com/OpenMined/PySyft) + [PyGrid](https://github.com/OpenMined/PyGrid)
  * PySyft is an open-source Python 3 based library that enables federated learning for research purposes and uses FL, differential privacy, and encrypted computations
  * PyGrid implements federated learning on web, mobile, edge devices, and different types of terminals. PyGrid is the API to manage and deploy PySyft at scale
* [OpenFL](https://github.com/intel/openfl)
  * Intel® Open Federated Learning is a Python 3 open-source project developed by Intel to implement FL on sensitive data. OpenFL has deployment scripts in bash and leverages certificates for securing communication, but requires the user of the framework to handle most of this by himself
  * [Federated Learning in Healthcare Use Cases | Intel Software](https://www.youtube.com/watch?v=z5jJsvvfKbM)
* [IBM Federated Learning](https://ibmfl.mybluemix.net/)
  * IBM Federated Learning provides a basic fabric for FL on which advanced features can be added. It is not dependent on any specific machine learning framework and supports different learning topologies, e.g., a shared aggregator, and protocols
  * It is meant to provide a solid basis for federated learning that enables a large variety of federated learning models, topologies, learning models, in enterprise and hybrid-Cloud settings
* [NVIDIA CLARA](https://developer.nvidia.com/clara)
  * NVIDIA CLARA is an application framework designed for healthcare use cases. It includes full-stack GPU-accelerated libraries, SDKs, and reference applications for developers, data scientists, and researchers to create real-time, secure, and scalable federated learning solutions


## Other related activities
* [Web Machine Learning Working Group](https://www.w3.org/groups/wg/webmachinelearning)
  * The mission of WebML WG is to develop APIs for enabling efficient machine learning inference in the browser
  * [Web Neural Network API](https://www.w3.org/TR/webnn/): This specification describes a dedicated low-level API for neural network inference hardware acceleration
* [Web Machine Learning Community Group](https://www.w3.org/community/webmachinelearning/)
  * The mission of WebML CG is to make Machine Learning a first-class web citizen by incubating and developing a dedicated low-level Web API for machine learning inference in the browser
  * [Model Loader API](https://webmachinelearning.github.io/model-loader/): This specification defines an API to load a custom pre-trained machine learning model
* [ONNX.js](https://github.com/microsoft/onnxjs):
  * ONNX.js is a Javascript library for running ONNX models on browsers and on Node.js
  * ONNX.js has adopted WebAssembly and WebGL technologies for providing an optimized ONNX model inference runtime for both CPUs and GPUs
* [WebAssembly System Interface(WASI)](https://github.com/WebAssembly/wasi-nn)
  * Why Wasm for ML?: Trained machine learning models are typically deployed on a variety of devices with different architectures and operating systems. WebAssembly provides an ideal portable form of deployment for those models
  * Why WASI?: Although a whole machine learning framework could be potentially compiled into Wasm, special hardware acceleration is often needed in order to be performant. For example, SIMD instructions such as AVX512 on a CPU can speed up performance by several hundred times. Other hardware acclerator examples are GPU, TPU, FPGA. All of those acceleration mechanisms are not available within Wasm. In addition, the field of machine learning is still evolving rapidly, with new operations and network topologies emerging continuously. It would be a challenge to define an evolving set of operations to support in the API 


 ## How to join the group
 * Please see [Join the Community](https://www.w3.org/community/federated-learning/join)
