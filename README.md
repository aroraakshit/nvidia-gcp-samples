# NVIDIA GPU Accelerated Application Samples in Google Cloud Platform

**Table Of Contents**
- [Description](#description)
- [Prerequisites](#prerequisites)
- [Samples](#samples)
- [Additional Resources](#additional-resources)
- [Known issues](#known-issues)
- [License](#license)

## Description

This repository contains sample applications

## Prerequisites

 - [Install Google Cloud SDK on your laptop/client workstation](https://cloud.google.com/sdk/docs/install), so that `gcloud` SDK cli interface could be ran on the client
 - In addition, user could leverage [Google Cloud shell](https://cloud.google.com/shell/docs/launching-cloud-shell) and further improve the user experience with [Boost Mode](https://cloud.google.com/shell/docs/how-cloud-shell-works#boost_mode)

## Samples

 - [Triton Autoscaling Example with Triton in Google Kubernetes Engine](kubernetes-engine-samples/triton_gke)
 - [BERT fine tuning, TensorRT optimization, Serve TensorRT Engine through Triton in AI Platform Prediction ](ai-platform-samples/bert_on_caip)
 - [XGBoost with LocalCUDACluster Dask Single Node Sample](ai-platform-samples/xgboost_single_node/gcsfs_localcuda)

## Additional Resources

See the following resources to learn more about NVIDIA NGC and GPU resources in Google Cloud Platform

**Documentation**

- [GPU in Google Cloud Platform](https://cloud.google.com/gpu)
- [Optimize GPU Performance in Google Cloud Platform](https://cloud.google.com/compute/docs/gpus/optimize-gpus)
- [Getting started with NGC on Google Cloud Platform](https://docs.nvidia.com/ngc/ngc-gcp-setup-guide/index.html#abstract)

# Known Issues

NA

# License

See [LICENSE](LICENSE).