## AWS Elemental MediaConnect adds support for SRT caller mode

[AWS Elemental MediaConnect](https://aws.amazon.com/mediaconnect/) now supports Secure Reliable Transport (SRT) caller mode for both sources and outputs in MediaConnect flows. SRT caller mode provides greater flexibility when configuring video transport workflows using MediaConnect.

SRT, an open source protocol backed by the 575+ member [SRT Alliance](https://www.srtalliance.org/), helps deliver video reliably across the internet. SRT has two primary connection modes: caller and listener. SRT listener mode is already supported by MediaConnect for both sources and outputs, and with the addition of SRT caller, you can now use SRT in any source to output connection combination (i.e. listener to caller, caller to listener, caller to caller, and listener to listener). SRT caller in MediaConnect also supports both passphrase and streamID variables for encryption and advanced workflows.

SRT caller is supported in all AWS Regions where MediaConnect is available. MediaConnect supports a growing number of reliable transport protocols including Zixi, RIST, and Fujitsu QoS. For more information, please visit the [MediaConnect overview page](https://aws.amazon.com/mediaconnect/) and read the [MediaConnect documentation](https://docs.aws.amazon.com/mediaconnect/latest/ug/what-is.html).

> Source: https://aws.amazon.com/about-aws/whats-new/2022/09/aws-elemental-mediaconnect-support-srt-caller-mode/