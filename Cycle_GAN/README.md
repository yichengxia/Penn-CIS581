In the notebook folder, there are 4 notebooks and a folder with our trained models for testing.

The baseline_CycleGAN is trained on 7000 real photos and 400 Van Gogh's paintings.

The CycleGAN-vgg-encoder modifies the architecture by replacing the encoder with pretrained VGG-19 layers.

The load and test notebook defines the generator architecture and tests using our trained models. Note that for different trained model, you need to initialize different architectures and use different inverse normalization functions.

The CycleGAN_video-v2-correct-rgb is used for taking frames from source video and generating stylized videos using trained models.

