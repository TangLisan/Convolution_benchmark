# tf_cnn_benchmarks: High performance benchmarks

## Getting Started

To run ResNet50 with synthetic data without distortions with a single GPU, run

```
python tf_cnn_benchmarks.py --num_gpus=1 --num_batches=3 --batch_size=3 
--model=resnet152 --tfprof_file=logs --variable_update=parameter_server
```

