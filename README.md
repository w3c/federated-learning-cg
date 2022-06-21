# [W3C Federated Learning CG](https://www.w3.org/community/federated-learning/)
The purpose of the group is to establish and explore the necessary standards related with the Web for federated learning via the analysis of current implementations related with federated learning such as TensorFlow Federated.

The rough roadmap for FL CG is as follows:
* Step 1: Gathering and analysing implementation frameworks for federated learning
* Step 2: Looking for the candidate items for W3C standards
* Step 3: Writing down the CG report regarding federated learning
* Step 4: Developing the draft of W3C spec related with federated learning

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
* [ONNX.js](https://github.com/microsoft/onnxjs):
  * ONNX.js is a Javascript library for running ONNX models on browsers and on Node.js
  * ONNX.js has adopted WebAssembly and WebGL technologies for providing an optimized ONNX model inference runtime for both CPUs and GPUs


 ## How to join the group
 * Please see [Join the Community](https://www.w3.org/community/federated-learning/join)
