# Docker Jenkins #

基于官方的Jenkins镜像，主要是修改了jenkins用户的UID（1000 => 9998）。

修改UID的原因主要是和AWS上的Ubuntu（ami-fce3c696）镜像中默认用户ubuntu的UID冲突了。

使用说明请参考[官方说明](https://github.com/jenkinsci/docker)。