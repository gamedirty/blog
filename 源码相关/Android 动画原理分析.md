

Android animation动画原理分析
在分析原理之前，我们先尝试找出现实中动画的实现思路。抛开代码细节去分析能让我们站在更宏观的一个角度全面看待问题。

先看百度关于动画的定义：
> 动画是通过把人物的表情、动作、变化等分解后画成许多动作瞬间的画幅，再用摄影机连续拍摄成一系列画面，给视觉造成连续变化的图画。

有两个关键点：变化的瞬间画幅和连续

体现在手机上就是把一个动画分解成若干帧，再连续呈现在屏幕上。