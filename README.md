# Debug_Record
A record for code debugging.


### 1. Extract audio (.wav) from video (.mp4) with ffmpeg.
```
ffmpeg -y -i " + file_path + " -ac 1 -ar 16000 "  + new_path
-y overwrite
-ac 1 get one channel
-ar 16000 set the sample_rate as 16kHz
```

refer：[1](https://blog.csdn.net/qq_24629659/article/details/123816563), [2](https://ffmpeg.org/ffmpeg-devices.html)


### 2. read audio with three different tools

refer: [1](https://www.cnblogs.com/znhung/p/16945554.html), [2](https://docs.scipy.org/doc/scipy/reference/generated/scipy.io.wavfile.read.html), [3](https://juejin.cn/s/python%20%E8%AF%BB%E5%8F%96%E9%9F%B3%E9%A2%91)


### 3. Change 2-d list to 1-d

```
list1 = [[1, 1], [2, 2]]
ans = [item for list in list1 for item in list]
```


refer: [1](https://www.bmabk.com/index.php/post/87444.html)


### 4. Pytorch-Lightening 

使用模板[参考1](https://zhuanlan.zhihu.com/p/556040754), [参考2](https://zhuanlan.zhihu.com/p/459701671)

torchmetrics[文档](https://torchmetrics.readthedocs.io/en/stable/classification/accuracy.html)

[torchmetrics in Pytorch-Lightening](https://torchmetrics.readthedocs.io/en/stable/pages/lightning.html)


### Pandas 数据读取

参考： [1](https://blog.csdn.net/sinat_26811377/article/details/103124749)


### WeightedRandomSampler 处理不平衡集

[Sampler](https://pytorch.org/docs/stable/data.html), [WeightedRandomSampler理解](https://blog.csdn.net/tyfwin/article/details/108435756), [方法](http://spytensor.com/index.php/archives/45/)


