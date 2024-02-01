# Cifar_10_classifier
End to end deployment of machine learning model

Model Architecture
<!-- # so resnet 18 follows basically this architecture
# x=  x + Res_block(x)
# each resblock has 2 convolution layer

# so we will start from 32x32x3
# one prep layer- one conv block 3x3x64 => output size 32x32x32
# each layer containing 2 resblock (conv-relu-batchnorm-conv-relu-batchnorm), first conv of first resblock will be pooling layer with stride of 2 to reduce output size
# we will have total of 4 layers, thus making it 4 * 4  = 16 conv layer
# then we will use pooling (average) and final one fc layer so total of 18 layers
# lets build -->