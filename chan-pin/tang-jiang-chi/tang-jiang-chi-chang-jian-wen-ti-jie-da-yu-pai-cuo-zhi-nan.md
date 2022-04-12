# 糖浆池常见问题解答与排错指南

## 排错指南

### 我质押的糖浆池消失了！

您可以在「已完成」页面内找到之前质押的糖浆池。

选择「仅限已质押」，更方便快捷地找到您质押的资产。

### **为什么我无法从糖浆池内解质押？**

如果您无法从手动 PCM 糖浆池解质押，请检查您的钱包内是否有足够的 SYRUP 代币。这个代币是您在手动 PCM 糖浆池中质押的凭证，请妥善保管，不要出售或转出。

### **为什么在追加质押/提取后，我的收益变成了 0 ？**

别担心，它们已经在您的钱包内。

每当您对农场或糖浆池，进行质押或解质押操作。待收获收益将被自动收获至您的钱包内。

## **常见问题**

### 糖浆池的年化利率 (APR) 是怎么计算的？**常见问题**

### 糖浆池的年化利率 (APR) 是怎么计算的？

### &#x20;<a href="#tang-jiang-chi-de-nian-hua-li-shuai-apr-shi-zen-mo-ji-suan-de" id="tang-jiang-chi-de-nian-hua-li-shuai-apr-shi-zen-mo-ji-suan-de"></a>

> 糖浆池年化利率 (APR) = 年化收益 (USD美金) / 糖浆池中质押资产 (USD美金) \* 100

让我们来举一个简单的例子：一个为期 60 天，拥有价值 300,000 美金奖励的糖浆池，然后用户们一共质押了价值 3,000,000 美金的 PCM 在里面。

年化利率无时无刻在改变，它受该糖浆池质押量、PCM 币价、奖励代币币价的共同影响。

|                         | 计算                                | 数量                       |
| ----------------------- | --------------------------------- | ------------------------ |
| 奖励总量 (USD美金)            |                                   | 300,000 USD              |
| 奖励周期                    |                                   | 60 天                     |
| 每日奖励数                   | 300,000 / 60 =                    | <p>每日 <br>5,000 USD </p> |
| **年化收益 (USD美金)**        | 5,000 \* 365 =                    | **1,825,000 USD**        |
| **在池中质押的 CAKE (USD美金)** |                                   | **3,000,000 USD**        |
| 年化利率 (APR)              | (1,825,000 / 3,000,000) \* 100 =  | **60.833% APR**          |



### **糖浆池中的「**结束倒计时**」指的是什么？**



「结束倒计时」显示距离奖励分发结束，还有多少个区块。一旦到达该区块，您需要从糖浆池中解开质押，因为该糖浆池将不再分发奖励。

### &#x20;<a href="#tang-jiang-chi-zhong-de-jiang-li-cong-na-li-lai" id="tang-jiang-chi-zhong-de-jiang-li-cong-na-li-lai"></a>

### **糖浆池中的奖励从哪里来？**

糖浆池总共分为三种：

1. 质押 CAKE，赚取 CAKE
2. 质押 CAKE，赚取其他代币&#x20;
3. 质押其他代币，赚取 CAKE

「质押 PCM，赚取 PCM」糖浆池中的奖励来自 PCM[生产](https://docs.pancakeswap.finance/tokenomics/cake/cake-tokenomics)。每当有一个新的区块，一定数量的 PCM 会被生产并按比例分发，作为奖励。

「质押 PCM，赚取其他代币」的奖励来自于其他项目团队的赞助。

「质押其他代币，赚取 PCM」，我们将使用 PCMSwap 储备金库，从市场中回购 PCM 作为奖励。这些糖浆池由 PCMSwap 自己出资，与其他项目无关。

### 什么是 SYRUP 代币？

每当您质押至**手动**「质押 PCM，赚取 PCM」糖浆池，PCMSwap’s SYRUP 代币会被分发至您的钱包内。

您可以将它视作「借条」，它代表您质押了多少 PCM 入糖浆池中。

当您从手动 PCM 糖浆池中解质押时，它需被退回并被销毁。

{% hint style="warning" %}
请不要出售您的 SYRUP 代币！当您从手动 PCM 糖浆池中解除质押时，您需要退回**同等数量**的 SYRUP 代币。
{% endhint %}