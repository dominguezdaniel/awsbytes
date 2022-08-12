## The Amazon Chime SDK announces elastic channels

The Amazon Chime SDK enables developers to add intelligent real-time audio, video, and screen share to their web and mobile applications. Starting today, Amazon Chime SDK messaging supports large-scale chat experiences for up to one million users with elastic channels. Use cases include watch parties for sporting events, political events, or live entertainment with create elastic channels. Elastic channels help make it easy for you to create secure, scalable, moderated chat experiences for large audiences which you can use with your built in moderation features to help enforce brand, corporate, or community guidelines.

Previously, Amazon Chime SDK messaging supported up to 100k members in a channel, and there was no easy way for human moderators to split the effort of monitoring content. Elastic channels allow you to create a single elastic channel with a common configuration across an elastic number of subchannels. When you create an elastic channel as individuals join, they are automatically assigned to a single subchannel. As individuals leave, subchannels are removed and remaining participants are automatically distributed across remaining subchannels. For example, you can create an elastic channel configured to have a maximum of 100 subchannels with 10,000 members each. By splitting the audience across subchannels, conversations are not only easier for participants to follow, but moderators can also split the effort of moderation by each watching a sub-set of the subchannels. On top of that, the existing channel flows feature can be used to automate moderation across all messages sent in the elastic channel. Using channel flows, you can execute business logic on in-flight messages using AWS Lambda before they are delivered to members .

Amazon Chime SDK messaging is available in the following AWS Regions: US East (N. Virginia) and Europe (Frankfurt). Elastic channels are available in the US East (N. Virginia) region. Customers with large chat channels often qualify for volume discounts on pricing, contact your account manager for more details.

To learn more about the Amazon Chime SDK and conversation APIs, review the following resources:

[Amazon Chime SDK](https://aws.amazon.com/chime/chime-sdk/)

[Amazon Chime SDK Developer Guide](https://docs.aws.amazon.com/chime/latest/dg/using-the-messaging-sdk.html)

[Amazon Chime SDK for JavaScript](https://github.com/aws/amazon-chime-sdk-js/blob/master/README.md)

> Source: https://aws.amazon.com/about-aws/whats-new/2022/08/amazon-chime-sdk-elastic-channels/