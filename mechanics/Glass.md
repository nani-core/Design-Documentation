# GLASS / 玻璃

## Properties / 性质

- 玻璃，基本参照现实中的玻璃，着重注意有如下三条性质需要实现，其他的可以忽略：

  1. 通透性。玩家可以透过玻璃，看到其后面的场景，同时必须能看出玻璃的存在（换言之玻璃不能绝对透明，用勾边、反光等效果强调其存在）。

  2. 阻隔性。实体不能通过玻璃，无论是玩家还是物体。

  3. 菲涅尔反射。当玩家视线与玻璃面夹角小时，在体现通透性的同时，还要将玩家一侧的场景反射出来，虚像叠加于实像上，如此组成的回形也可以交互。用于设计谜题，详见谜题设计文档「[Reflection / 反射]」。

[Reflection / 反射]: https://github.com/nani-core/Puzzle-Design-Documentation/blob/master/Market.md#reflection--%E5%8F%8D%E5%B0%84
