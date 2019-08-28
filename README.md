# Sensifai Video Tagging NPU SDK
This repository contains an Android SDK for [Sensifai](https://sensifai.com) video recognition and tagging using Huawei Kirin980 technology.
This SDK brings ability to any application which needs to understand and recognize the concepts within a video and do all the process on the device. 

This SDK can be used on the Huawei devices which utilize Kirin980 chip with Neural Processing Unit (NPU), such as P30 and Mate20 series. For the next versions, we are going to release SDKs for Qualcomm chips as well.

This SDK is meant to show the ability and the power of the technology of video tagging as a good demo and covering a limited number of tags (almost 800). If you are interested to have a specialized SDK with different set of concepts for recognition please contact us (support@sensifai.com).

You can also check our live video tagging android [app](https://play.google.com/store/apps/details?id=com.sensifai.hiaidemo&hl=en) working on same devices which tags all of the concepts from the camera video footage.

# Video Tagging Engine Training
Our video tagging engine is trained with advanced deep neural network architectures using sensifai private video/image dataset. For people who do not have access to similar dataset, there are some opportunities to use some open access dataset such as [Open Images Dataset](https://storage.googleapis.com/openimages/web/index.html).

# Deep ConvNet Model and Code
[Here](https://github.com/sensifai/Sensifai-NPU-SDK/tree/master/NPU-Pytorch-model), you can find the [Pytorch](https://pytorch.org/) model and code for the ConvNet which is used in the SDK. For converting the models to a working model on Huawei Kirin NPUs, you should follow the [Huawei NPU DDK Insturctions](https://developer.huawei.com/consumer/en/devservice/doc/2020105).

# How To Use
Check the [SDK guide](https://github.com/sensifai/Sensifai_NPU_SDK/blob/master/Sensifai%20HiAI%20Video%20Tagging%20Library%20User%20Manual.pdf).
