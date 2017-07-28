# DeepLearning


## Tensorflow Tricks

* Allocate gpus 
<br/>
⋅⋅⋅CUDA_VISIBLE_DEVICES=0 python script_one.py
<br/>
⋅⋅⋅CUDA_VISIBLE_DEVICES=0 python script_one.py
<br/>
⋅⋅⋅In both cases, tensorflow only sees tf.device('/gpu:0')
<br/>


