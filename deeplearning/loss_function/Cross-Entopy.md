# Cross-Entopy

**数学公式(julia-language)**
```julia
 corss_entopy(x) = -sum(x .* log.(x))
```
**解释**
x为随机事件的概率分布的矩阵
比如抛硬币某一面的概率为50%，摇色子某一面的概率为1/6
可以这样调用cross_entopy([0.5, 1/6])

**返回结果含义**
返回结果在0～1之间
数值越大表示越不稳定，数值取经与0最好
