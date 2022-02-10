# 模型主要思路
## &emsp; 模拟画家对于素描的绘制过程，将传统的人脸到素描之间一对一映射，变成了先描绘出来五官轮廓，再逐渐增加更多的细节，最后绘制出形象的人像素描。难点：利用前一步图生成的信息，辅助后一步生成器合成
  <div align="center">
  <img src="https://github.com/George2413/sketch/blob/main/photo/2.png" width="600" height="400"/><br/>
  <p>Perfectly balanced</p>
 </div>

## 模型在两个不同数据集的实验结果为了让学习到的模型能够生成清晰的素描图, 我们选取了 25 张图片中最具有代表性的三个步骤图来构成我们的合成步骤的真实数据集.如下图所示。
<img src="https://github.com/George2413/sketch/blob/main/photo/1.png" width="400" height="220"/> &emsp;

<img src="https://github.com/George2413/sketch/blob/main/photo/3.png" width="400" height="220"/>  &emsp; <img src="https://github.com/George2413/sketch/blob/main/photo/4.png" width="400" height="220"/><br/>

<img src="https://github.com/George2413/sketch/blob/main/photo/5.png" height="220"/> &emsp; 
