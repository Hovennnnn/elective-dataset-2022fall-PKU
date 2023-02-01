# elective-dataset-2022fall-PKU
某校2022年秋季选课系统四位验证码数据集(1781张）

选课系统验证码有四位验证码和五位验证码两种，两种类型的验证码均由Google开源的验证码工具[Kaptcha](https://code.google.com/archive/p/kaptcha/)自动生成。

仓库里的数据集是四位的验证码图片，来源于选课系统。验证码的字体未知。

尝试过使用k折交叉验证的方式训练，能得到90%左右准确率的模型，如果需要扩大数据集，可以采用类似[zhongxinghong/PKUElectiveCaptcha2021Spring](https://github.com/zhongxinghong/PKUElectiveCaptcha2021Spring)的方式进行自举


数据集采用 [知识共享署名-非商业性使用 4.0 国际许可协议](https://creativecommons.org/licenses/by-nc/4.0/) 进行许可。

