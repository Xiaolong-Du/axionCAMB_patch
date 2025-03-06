# axionCAMB_patch
A patch for the [axionCAMB](https://github.com/dgrin1/axionCAMB) code.

The patch contains two main changes:

1. Include the velocity tranfer function of axion in the output.
2. Take the absolute value of the tranfer function before outputting to avoid negative values.

To apply the changes, you first need to download the original [axionCAMB](https://github.com/dgrin1/axionCAMB) code. Copy the patch to the directory of axionCAMB. For axionCAMB v1.0, run
```
git apply axionCAMB_v1.0.patch
```
For axionCAMB v2.0, run
```
git apply axionCAMB_v2.0.patch
```
If you use this patch in your work, we kindly ask you to cite the original axionCAMB code: [http://arxiv.org/abs/1410.2896](http://arxiv.org/abs/1410.2896) and the following paper: [https://arxiv.org/abs/2410.03635](https://arxiv.org/abs/2410.03635).
