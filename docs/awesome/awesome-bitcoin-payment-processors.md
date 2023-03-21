<div class="github-widget" data-repo="alexk111/awesome-bitcoin-payment-processors"></div>
<div align="center">
<img width="500" src="https://raw.githubusercontent.com/alexk111/awesome-bitcoin-payment-processors/master/media/logo.svg?sanitize=true" alt="Awesome Bitcoin Payment Processors"/>
</div>

## Awesome Bitcoin Payment Processors [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

精选的比特币支付处理器列表，使商家、企业和非营利组织能够接受比特币支付.

为什么他们很棒？

1. 他们要么不受金融审查制度的影响，要么根本不实行.
2. 他们通过本地比特币地址接受比特币，不需要钱包来使用 [controversial payment protocol](https://blog.samouraiwallet.com/post/169222582782/bitpay-qr-codes-are-no-longer-valid-important).
3. 他们没有 [block payments by IPs/locations](https://twitter.com/alex_kaul/status/1090211252331208705).



## Self-Hosted Bitcoin Payment Processors

自托管支付处理器在您的服务器上运行，让您可以完全控制整个支付流程和资金. 没有第三方参与 - 这显着增加了您和您的客户的抗审查性、隐私和安全性. 

 | 处理器 | 费用 | 闪电 | 直接到您的钱包 | 转换为菲亚特 | 要求 |
| --------- |:----:|:---------:|:-----------------------:|:------------------:| ------------ |
| [BTCPay Server](https://btcpayserver.org/)  | 不收费 | 是 | 是 | 通过 [Payment Forwarding](https://www.blockonomics.co/views/payment_forwarding.html) 和 [Exchange Integration](https://redbtc.org/flows/integrations/kraken-exchange/)  |  2 GB RAM，80 GB 存储空间，Docker |
| [One Time Address](https://github.com/alexk111/One-Time-Address)  | 不收费 | 否 | 是 | 否 | 节点 |
| [CryptoWoo](https://www.cryptowoo.com/)  | 每年 $34 - $99 | 否 | 是 | 否 |  PHP 5.6+、Wordpress 4.3+、WooCommerce 3.0+ |
| [BitcartCC](https://bitcartcc.com)  | 不收费 | 是 | 是 | 否 |  1 GB RAM，10 GB 存储空间，Docker |
| [LnMe](https://github.com/bumi/lnme)  | 不收费 | 是 | 是 | 否 |  LND 节点 |
| [SatSale](https://github.com/nickfarrow/SatSale)  | 不收费 | 是 | 是 | 弱点： [swap to USDT on Liquid](https://github.com/nickfarrow/SatSale/blob/master/config.toml#L82) , 无 KYC | 比特币节点和 Python.  Lightning 节点和 Woocommerce 可选 |
| [CypherpunkPay](https://cypherpunkpay.org/)  | 不收费 | 否 | 是 | 否 |  Linux（1GB 内存）|

## Hosted Bitcoin Payment Processors

托管支付处理器在其他人的服务器上运行. 这简化了初始设置过程，但减少了您对付款过程的控制量.

### Non-Custodial

 | 处理器 | 费用 | 闪电 | 直接到您的钱包 | 转换为菲亚特 | 要求 |
| --------- |:----:|:---------:|:-----------------------:|:------------------:| ------------ |
| [Blockonomics](https://www.blockonomics.co/merchants)  |  1% | 否 | 是 | 通过 [Payment Forwarding](https://www.blockonomics.co/views/payment_forwarding.html)  | 否 |
| [Bittery.io](https://bittery.io/)  | 不收费 | 是 | 是 | 通过 [Payment Forwarding](https://www.blockonomics.co/views/payment_forwarding.html) 和 [Exchange Integration](https://redbtc.org/flows/integrations/kraken-exchange/)  | 否 |
| [Payscrypt](https://payscrypt.com/)  | 不收费 | 否 | 是 | 否 | 否 |
| [Bitrequest](https://bitrequest.io/)  | 不收费 | 否 | 是 | 否 | 否 |

### Custodial

 ⚠ 以下处理者使用自己的钱包接收付款. 他们不仅收集有关付款的数据，而且还可以完全控制资金.

 | 处理器 | 费用 | 闪电 | 直接到您的钱包 | 转换为菲亚特 | 要求 |
| --------- |:----:|:---------:|:-----------------------:|:------------------:| ------------ |
| [Confirmo](https://confirmo.net/)  |  0.8% | 是 | 否 | 是 | 有关业务/网站的信息. 可能需要某些文件.  |
| [CoinGate](https://coingate.com/accept-bitcoin)  |  1%（商家）+一些 [variable service fee](https://support.coingate.com/en/109/why-does-coingate-charge-service-fee)  （客户） | 是 | 否 | 是 | 要求 [a lot of information and business documents](https://blog.coingate.com/2019/05/verify-merchant-account-faq) ，正式翻译成英文.  |
| [CoinPayments](https://www.coinpayments.net/)  |  0.5% | 是 | 否 | 否 | 提款时可能需要多种形式的身份证明，并且需要清算任何未付款项.  |
| [GloBee](https://globee.com/)  |  1% ($10 min. invoice) | 是 | 否 | 通过 [Luno](https://www.luno.com) 和 [Uphold](https://uphold.com/)  | 有关业务/网站的信息. 可能需要某些文件.  |
| [OpenNode](https://www.opennode.co/)  |  1% | 是 | 否 | 是 | 要求 [KYC/KYB documents](https://help.opennode.com/en/articles/3654899-kyc-and-kyb-requirements) |
| [Strike](https://strike.acinq.co/)  |  1% | 仅| 否 | 否 | 对于公司，公司名称和实际地址.  |
| [Coinremitter](https://coinremitter.com/)  |  0.23% + 0.0001 | 否 | 否 | 否 | 否 |
| [Utrust](https://utrust.com/)  |  1% | 否 | 否 | 是 | 需要某些文件.  |
| [NOWPayments](https://nowpayments.io/)  |  ≤0.5% | 否 | 否 | 否 | 适用于某些客户、钱包地址和特定资产的 KYC/AML 程序.  |
| [COINQVEST](https://www.coinqvest.com/) | 0.5-1%, [Free to try](https://www.coinqvest.com/en/pricing)  | 否 | 否 | 是（美元、欧元、ARS、BRL、NGN）| 需要 KYC 验证.  |

## Backers 💝

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

[[Donate](https://mynode.alexkaul.com/gh-donate)] 感谢您的支持！
