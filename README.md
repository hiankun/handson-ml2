(Forked repo for learning ML.)

# Setup

```
conda env create -f environment.yml
conda activate handson-ml2_env
python -m ipykernel install --user --name=python3
```

[2020-07-11]

* Change the content of `environment.yml` so that the `tensorflow-gpu`
  will be installed by conda instead of pip.
  TF2 installed by pip will not pass the test using `tf.test.is_gpu_available()`.
