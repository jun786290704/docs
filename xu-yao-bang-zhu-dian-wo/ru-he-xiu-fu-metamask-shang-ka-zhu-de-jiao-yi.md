# 如何修复 MetaMask 上卡住的交易

如果您在 MetaMask 上的交易卡在了「等待中」，并且无法通过「取消」按钮清除，请根据该教程清除您的钱包交易记录。

这个方法将使用一个优先级更高的交易去覆盖卡住的交易。

### &#x20;<a href="#1-enable-customized-transaction-nonce" id="1-enable-customized-transaction-nonce"></a>

### **1. 启用「**自定义交易 nonce**」** <a href="#1-enable-customized-transaction-nonce" id="1-enable-customized-transaction-nonce"></a>



1. 打开您的 MetaMask 插件。\
   ![](https://lh6.googleusercontent.com/fYsgD0BKjYVjrbCpbEQgMyWG\_sW-4c2Ev7wu9bVzsOWtqIzCmYqiv6Xj8G\_FY2TK5uYul3XaOY2WflfcW1W56R2KCuyW-Y5RjHH9DZDgUmATLlnOnMPn371nniPZqaaD7KAgYgMc)
2. 点击右上角彩色头像，并在菜单中点击**设置**。\
   ![](https://lh3.googleusercontent.com/DpSeFrHsmPNXU73C3NB9iRANEe81rJ2XUhbxs6k7PqJSVy6IkAijeX\_TeIbUupalmD3mlE2G0C90XHJJy\_JPk-\_mswNRf4liUwR4AUhx2AWygp4yIP9kjHo1QQk\_60wEtjGkfwSk)
3. 在菜单中，选择**高级**\
   ****.![](https://lh4.googleusercontent.com/F-o1qfi84wh6YNUP16b8lbyS6f8i04SYEUR2VrncMbBaoeaAjOw4Af\_oOwRUfWnhZn6NFb4O1uopoc1KNego8XelHmDDWeRRAb0oMJGE\_ZI\_xJJeqfH-bJrai0pakyxC-235E4nq)
4. 滚动至 **高级燃料控制**，点击启用它。\
   ![](https://lh5.googleusercontent.com/ePraz\_2Z8k1V62DMROjv0jbIjEcf8ATvaH-Lxe5wtoNo6oVTyRPelC1m7UVaizcNpW5bHByrbC9xv1KDZfjNnXvQ8J0ukHUHK7vK4rX5gpQVHmfyJr81wCGdeArvksNhshon1Btn)
5. 不要离开，继续往下滚动，直至 **自定义交易 nonce** ，点击启用它。

### **2. 找到卡住的交易** <a href="#2-find-your-stuck-transaction" id="2-find-your-stuck-transaction"></a>

1.  1\.

    我们现在要找到卡住的交易，并记录它的 "nonce"。它是该交易的标识号吗，我们之后将会用到。 ​
2.  2\.

    回到最初的页面，在「资产」选项卡处，找到「活动」并点击。之后，在下方找到卡住的交易。 ​
3. 点击卡住的交易，查看更多信息。
4. 找到 **Nonce** 一栏，并记录数值。

### **3. 覆盖卡住的交易** <a href="#3-overwrite-the-stuck-transaction" id="3-overwrite-the-stuck-transaction"></a>

现在我们要发起一个新的交易去覆盖之前卡住的交易。我们将自定义 Nonce 值，让它与卡住的交易一致。（即您刚刚记录的数值）

![​](https://gblobscdn.gitbook.com/assets%2F-MHREX7DHcljbY5IkjgJ%2F-M\_Qf9PqrqKwKENMLChq%2F-M\_QfJwbI-p6skTud7\_o%2Fimage.png?alt=media\&token=13db2345-9ad7-46a4-9937-7f26d7187749)

1.  1\.

    新建一个新的交易去覆盖之前的交易，它可以是任何交易（您也可以自己转账给自己）。这次，将 **燃料价格** (Gas Price) 增加至 20。这将大幅度增加该笔交易上链的几率和速度。

&#x20;![](https://gblobscdn.gitbook.com/assets%2F-MHREX7DHcljbY5IkjgJ%2F-M\_Qf9PqrqKwKENMLChq%2F-M\_Qft-wFWL0NENZfvV\_%2Fimage.png?alt=media\&token=14028feb-3c51-405c-bc3e-3d8e87d1d37d)​

1.  2\.

    在确认页面，请确认燃料价格 (Gas Price) 被设置为 20。
2.  3\.

    找到 **自定义 NONCE** 一栏，并将它的值改为之前记录的数值。
3.
4.  5\.

    新的交易将被纳入区块并覆盖之前的交易，请回到「活动」页面检查。 ​
5.  6\.

    新的交易将显示在最上方，如果仍显示橙色的「等待中」，请稍等片刻，或使用更高的 Gas Price 重试。

每笔交易的 nonce 值都应为独一无二。所以，您新的交易将覆盖旧的、卡住的交易。
