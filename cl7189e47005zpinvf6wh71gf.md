## Amazon Chime SDK now supports signaling client in C++

Amazon Chime SDK now supports connecting an open source signaling client implementation in C++. The Amazon Chime SDK lets developers add intelligent real-time audio, video, and screen share to their web and mobile applications. WebRTC is a common library for video conferencing applications, and the Amazon Chime SDK provides WebRTC based media clients in JavaScript, iOS and Android. However, some customers choose to bring their own custom WebRTC library and still want to connect server side to the Amazon Chime SDK.

With the Amazon Chime SDK for C++ signaling client developers can compile on their preferred platforms and establish a signaling connection to the Amazon Chime SDK media service. Developers have the ability to use a custom WebRTC implementation to send and receive audio, video, screen share, and data messages to Amazon Chime SDK meetings.

To help developers get started, here is a command line interface demo application that uses the Amazon Chime SDK C++ signaling client and libWebRTC library to connect to Amazon Chime SDK meetings and transmit test audio video data.

To learn more about the Amazon Chime SDK and media replication, review the following resources:

[Amazon Chime SDK](https://aws.amazon.com/chime/chime-sdk/) website

[Amazon Chime SDK Developer Guide](https://docs.aws.amazon.com/chime-sdk/latest/dg/what-is-chime-sdk.html)

[Amazon Chime SDK for C++](https://github.com/aws/amazon-chime-sdk-cpp/tree/main/chime-sdk-signaling-cpp/demo/cli) GitHub repository

> Source: https://aws.amazon.com/es/about-aws/whats-new/2022/08/amazon-chime-sdk-supports-signaling-client-c-plus-plus/