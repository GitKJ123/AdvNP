## AdvNP
An example of **Rethinking the Vulnerability of DNN Watermarking: Are**
**Watermarks Robust against Naturalness-aware Perturbations?**   (to be presented at the **ACM MM 2022**).

## Requirement

Configure the environment

```
python=3.7
tensorflow=1.14.0
numpy=1.21.5
imageio=2.16
```

## How to use

1. Build the environment
2. Models are available at  https://drive.google.com/file/d/1RxKx6GvVCRjn-piMawZH6YR13sUdzb7Z/view?usp=sharing
3. Add naturalness aware perturbations to data in single folder: run **relight_single_folder.py**
4. Add naturalness aware perturbations to data in multiple folders : run **relight_multi_folder.py**
5. You can adjust the SH-light directions in folder **target lightings** to get better attack rate and balance between preserving funcionality  to fit your tasks, different lighting directions may lead to various attack results.

## Related work

We use some code from the original  [Shadow-Mask-Face-Relighting](https://github.com/andrewhou1/Shadow-Mask-Face-Relighting) which is a brilliant work.

