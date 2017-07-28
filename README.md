# DeepLearning


## Tensorflow Tricks

* Allocate gpus 
⋅⋅⋅CUDA_VISIBLE_DEVICES=0 python script_one.py
⋅⋅⋅CUDA_VISIBLE_DEVICES=0 python script_one.py
⋅⋅⋅In both cases, tensorflow only sees tf.device('/gpu:0')
