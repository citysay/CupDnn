# CupCnn
CupCnn是个用java写的卷积神经网络

## 为什么选择java?<br>
CupCnn是我在学习卷积神经网络的时候自己尝试写的，写出来后，希望能给那些还在学习卷积神经网络的同学一个参考，
能让它们少走点弯路吧。java是近年来最流行的编程语言，它有广泛的用户基础，因此，用java来编写卷积升经网络，可以帮助
到更多的人，尤其是那些看到c++晦涩的语法就退却的人。当然了，卷积神经网络正真要部署到具体的设备上，可能c++还是首选，
所以，可以通过CupCnn快速学习卷积神经网络，但是也不要忘记学习c++.

## 设计的思路<br>
我希望它是以足够简单的神经网络，这样有利于初学者学习。所以我没有实现那些并发加速的东西，这保证的代码的简介性。
设计的时候，我将卷积神经网络分为四个模块：
		 Network
layer		blob		loss		active
这点可以从包名中看出来。layer,loss,active都有一个基类，整个神经网络的编程都是面向基类的。
	
## 目前的表现<br>
目前，在mnist数据集上，仅全连接层的神经网络和卷积神经网络的准确率都能超过95%。最好的成绩还没能超过96%,可能是
实现上有一些细微的bug,也可能是训练的还不到位。不管怎么样，我会进一步调试和完善CupCnn.

	
	
			


