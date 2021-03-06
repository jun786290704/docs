# PCM 代币经济学



所有按照黑洞地址制作的PCM都会在每周的烧制中烧掉，永远不会进入流通。

因此，我们没有将其包括在上述排放率中。

奖励/阻止（占排放量的百分比）

奖励/阻止（总PCM）

其中一个被转移并烧毁

每日PCM总排放量

### &#x20;<a href="#other-deflationary-mechanics" id="other-deflationary-mechanics"></a>

除上述情况外，PCM还通过以下方式燃烧：

* 通过PCMSwap V2进行的每笔交易的1.05%
* 在IFO中筹集100%的PCM
* PCM 100%用于个人资料创建和NFT制作
* 在农场拍卖期间，100%的PCM出价
* 自动PCM池中每个产量收获的2%
* NFT市场上所有NFT销售的2%用于购买PCM燃烧

### &#x20;<a href="#why-is-the-cake-burn-manual" id="why-is-the-cake-burn-manual"></a>

PCMSwap作为MVP（最低可行产品）推出，并与MasterChef签订合同，每个区块可发射40个PCM。出于这个原因，早期的团队没有添加额外的功能，比如定制PCM造币逻辑的能力。由于迁移到新的主厨需要花费大量时间和精力，团队选择通过创建两个池，通过手动燃烧过程来减少PCM排放：

* 旧式彩票池（PID-137）-从彩票中烧掉的PCM
* 燃烧池（PID-138）-每个区块燃烧的PCM

这些池的工作方式与农场类似，厨师可以在每次PCM减排投票后调整分配给它的每个区块40 PCM的百分比。

烧伤当天，主页上显示的供应量可能会突然增加数百万PCM。

别担心——这种蛋糕实际上从未进入流通：

这种明显的跳跃仅仅是因为分配给刻录的所有PCM在一周内的存储方式。

发送到PID-137和PID-138两个池的PCM在完成每周代币燃烧之前被收集，这使得现场显示的总供应量增加了约6M。这是因为待处理的PCM直到在燃烧日收获后才计入总供应量。一旦完成代币烧录交易，烧录日期中会显示\~6M。

### &#x20;<a href="#how-to-confirm-cake-supply-for-yourself" id="how-to-confirm-cake-supply-for-yourself"></a>

要确认PCMSwap主页上显示的循环PCM电源是正确的，

1. 然后，从BscScan显示的“总供应量”中减去燃烧量。
2. 这给了你
