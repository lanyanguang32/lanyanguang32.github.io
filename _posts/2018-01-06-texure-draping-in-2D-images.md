# 面料替换2D图像

面料花型设计和模特贴图在传统CAD/CAM中已经是必备工具。但是大多数属于单机版软件，缺乏即用性，通常是给设计师用的。
如今在线面料替换2D图像和客户端展现的需求比较多，本文讨论在线2D面料试穿的技术实现尝试。

> 清单
- 普通的层叠替换效果
- 面料褶皱替换效果
- 面料扭曲替换效果
- 3D面料提花效果

## 普通的层叠替换效果

普通的层叠替换效果是类似PS软件中的正片叠底效果，需要做一个带有透明图层的模特底图，透明图层需带有一定明暗阴影，通过阴影来体现立体感。再将面料花型图案进行图层合并。在特定模特底图和特定花型图案时才有一定效果。

## 面料褶皱替换效果

面料褶皱替换效果是类似PS软件中的位移滤镜效果，需求根据模特底图制作一个位移图层。再将面料花型图案进行图层合并。在特定模特底图和特定花型图案时需要调整明暗度和饱和度。

## 面料扭曲替换效果

面料扭曲替换效果是类似PS软件中的自由扭曲工具，通常模特的形体会有弯曲部分，例如手臂等。在色织布类似的面料中，如果不做扭曲贴图的话，看上去缺乏真实感。

## 3D面料提花效果

3D面料提花效果是将2D图像的一面做成3D模型，通过mesh曲线建立3D模型遮罩，将面料花型图案进行图层合并。这需要特定的2D模特底图才行，但是达到的效果很真实。

## 参考文献

- [Change Clothes With A Pattern Fill In Photoshop](https://www.sitepoint.com/change-clothes-with-a-pattern-fill-in-photoshop/)
- [How to Change Fabric to Clothing in Photoshop](https://www.youtube.com/watch?v=wMVG--BEkf0)
- [Use The Displace Filter & Displacement Maps To Make A Realistic Flag](http://www.photoshopsupport.com/elements/tutorials/displace-filter/displacement-map.html)
- [Illustrator Tutorial: How to Manipulate Patterns with Envelope Distort](http://fashionclassroom.com/blog/illustrator-tutorial-how-to-manipulate-patterns-with-envelope-distort)
- [SERVER SIDE TEXTURE MAPPING FOR FASHION](https://www.researchgate.net/publication/311966378_SERVER_SIDE_TEXTURE_MAPPING_FOR_FASHION_-_THE_CASE_OF_ARAHDRAPE)
- [Texture Design and Draping in 2D Images](http://maverick.inria.fr/Publications/2009/WOBT09/TextureDraping_EGSR_2009.pdf)

## 案例
- 普通的层叠替换效果 ![普通的层叠替换效果](/images/11.png)

- 面料褶皱替换效果 ![面料褶皱替换效果](/images/22.png)

- 面料扭曲替换效果 ![面料扭曲替换效果](/images/33.jpeg)

- 3D面料提花效果 ![3D面料提花效果](/images/44.png)

