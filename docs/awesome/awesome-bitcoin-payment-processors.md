<div class="github-widget" data-repo="alexk111/awesome-bitcoin-payment-processors"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<div align="center">
<img width="500" src="https://raw.githubusercontent.com/alexk111/awesome-bitcoin-payment-processors/master/media/logo.svg?sanitize=true" alt="Awesome Bitcoin Payment Processors"/>
</div>

## Awesome Bitcoin Payment Processors [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

一系列很棒的比特币支付处理器以及使用它们的商人的故事. 他们为什么很棒？

1.他们要么受到财政审查保护，要么不实行审查制度.
2.他们处理本地比特币交易，不需要钱包使用 [controversial payment protocol](https://blog.samouraiwallet.com/post/169222582782/bitpay-qr-codes-are-no-longer-valid-important).
3.他们不 [block payments by IPs/locations](https://twitter.com/alex_kaul/status/1090211252331208705).



## Self-Hosted Payment Processors

自托管支付处理器在您的服务器上运行，可为您提供对整个支付流程和资金的完全控制. 没有第三方的参与-极大地提高了您和您的客户的防审查性，隐私性和安全性. 

 | 处理器| 费用| 闪电| 直接到您的钱包| 转换为菲亚特| 要求|
| --------- |:----:|:---------:|:-----------------------:|:------------------:| ------------ |
| [BTCPay Server](https://btcpayserver.org/)  | 没有费用| 是的是的通过 [Payment Forwarding](https://www.blockonomics.co/views/payment_forwarding.html) 和 [Exchange Integration](https://redbtc.org/flows/integrations/kraken-exchange/)  |  2 GB RAM，80 GB存储，Docker |
| [One Time Address](https://github.com/alexk111/One-Time-Address)  | 没有费用| 没有是的没有 NodeJS |
| [CryptoWoo](https://www.cryptowoo.com/)  | 每年$ 34-$ 99 | 没有是的没有 PHP 5.6 +，Wordpress 4.3 +，WooCommerce 3.0+ |
| [BitcartCC](https://bitcartcc.com)  | 没有费用| 是的是的没有 1 GB RAM，10 GB存储，Docker |
| [LnMe](https://github.com/bumi/lnme)  | 没有费用| 是的是的没有 LND节点|

## Hosted Payment Processors

托管付款处理器在其他人的服务器上运行. 这简化了初始设置过程，但减少了您对付款过程的控制量.

### Non-Custodial

 | 处理器| 费用| 闪电| 直接到您的钱包| 转换为菲亚特| 要求|
| --------- |:----:|:---------:|:-----------------------:|:------------------:| ------------ |
| [Blockonomics](https://www.blockonomics.co/merchants)  |  1％| 没有是的通过 [Payment Forwarding](https://www.blockonomics.co/views/payment_forwarding.html)  | 没有
| [Bittery.io](https://bittery.io/)  | 没有费用| 是的是的通过 [Payment Forwarding](https://www.blockonomics.co/views/payment_forwarding.html) 和 [Exchange Integration](https://redbtc.org/flows/integrations/kraken-exchange/)  | 没有
| [Payscrypt](https://payscrypt.com/)  | 没有费用| 没有是的没有没有

### Custodial

 ⚠以下处理者使用他们自己的钱包来接收付款. 他们不仅收集有关付款的数据，而且对资金拥有完全控制权.

 | 处理器| 费用| 闪电| 直接到您的钱包| 转换为菲亚特| 要求|
| --------- |:----:|:---------:|:-----------------------:|:------------------:| ------------ |
| [Confirmo](https://confirmo.net/)  |  0.8％| 没有没有是的有关企业/网站的信息. 可能需要某些文件.  |
| [CoinGate](https://coingate.com/accept-bitcoin)  |  1％| 是的没有是的需要某些文件.  |
| [CoinPayments](https://www.coinpayments.net/)  |  0.5％| 是的没有是的提款可能需要多种形式的身份证明，并且需要结清任何未偿金额.  |
| [GloBee](https://globee.com/)  |  1％或（$ 30-$ 300）/ mo | 是的没有通过 [Luno](https://www.luno.com) 和 [Uphold](https://uphold.com/)  | 有关企业/网站的信息. 可能需要某些文件.  |
| [OpenNode](https://www.opennode.co/)  |  1％| 是的没有是的可能需要验证身份. 也可能需要核实有关已收款项的详细信息或资金来源.  |
| [Strike](https://strike.acinq.co/)  |  1％| 仅| 没有没有对于公司，是公司名称和实际地址.  |
| [Coinremitter](https://coinremitter.com/)  |  0.23％| 没有没有没有没有
| [Utrust](https://utrust.com/)  |  1％| 没有没有是的需要某些文件.  |
| [NOWPayments](https://nowpayments.io/)  |  ≤0.5％| 没有没有没有 KYC / AML程序适用于某些客户，钱包地址和选定资产.  |

## Merchant Stories

-[BTCPay服务器] [Blockstream: We're now accepting on-chain #Bitcoin payments](https://www.facebook.com/1052484058287964)
-[BTCPay服务器] [CheapAir: Update on Our Search for a New Bitcoin Payment Processor](https://www.cheapair.com/blog/update-on-our-search-for-a-new-bitcoin-payment-processor/)
-[BTCPay服务器] [Cryptoversity: ORIGINS, A Dramatic Story](https://youtu.be/S0difABxO3g)
-[BTCPay服务器] [Gab Says Bitcoin is The Clear Solution as ‘Free Speech Money’](https://bitcoinist.com/free-speech-money-gab-bitcoin/)
-[确认（ex-BitcoinPay）] [Trezor: Ever wondered how do we process your TREZOR order?](https://blog.trezor.io/trezor-shipping-process-delivery-dispatch-explained-order-logistics-58e45e25ee8)
-[Blockonomics] [How a Small Business in the Arctic Circle is Selling to the World](https://hackernoon.com/how-a-small-business-in-the-arctic-circle-is-selling-to-the-world-8dbe8d7f9fc4)
-[CryptoWoo] [Keys4Coins: Seamless integration of cryptocurrency payments in WooCommerce](https://www.keys4coins.com/cryptowoo-testimonial/)

## Backers 💝

[[Become a backer](https://mynode.alexkaul.com/gh-donate)]

[![Backer](https://mynode.alexkaul.com/gh-backer/top/0/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/0/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/1/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/1/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/2/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/2/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/3/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/3/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/4/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/4/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/5/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/5/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/6/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/6/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/7/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/7/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/8/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/8/profile)
[![Backer](https://mynode.alexkaul.com/gh-backer/top/9/avatar/60)](https://mynode.alexkaul.com/gh-backer/top/9/profile)

## How to Contribute

请阅读 [CONTRIBUTING](https://github.com/alexk111/awesome-bitcoin-payment-processors/blob/master/CONTRIBUTING.md).

## How to Share

- [Share on Twitter](https://twitter.com/home?status=List%20of%20awesome%20bitcoin%20payment%20processors.%20https%3A%2F%2Fgithub.com%2Falexk111%2Fawesome-bitcoin-payment-processors%20%23bitcoin)
- [Share on Facebook](https://www.facebook.com/sharer/sharer.php?u=https%3A//github.com/alexk111/awesome-bitcoin-payment-processors)
- [Share on LinkedIn](https://www.linkedin.com/shareArticle?mini=true&url=https%3A//github.com/alexk111/awesome-bitcoin-payment-processors&title=List%20of%20awesome%20bitcoin%20payment%20processors&summary=&source=)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [Alex Kaul](https://github.com/alexk111) 放弃了此作品的所有版权以及相关或邻近的权利.
