<div class="github-widget" data-repo="alexk111/awesome-bitcoin-payment-processors"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<div align="center">
<img width="500" src="https://raw.githubusercontent.com/alexk111/awesome-bitcoin-payment-processors/master/media/logo.svg?sanitize=true" alt="Awesome Bitcoin Payment Processors"/>
</div>

## Awesome Bitcoin Payment Processors [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

精选的很棒的比特币支付处理器列表，使商家，企业和非营利组织可以接受比特币支付.

他们为什么很棒？

1.他们要么不受金融审查的影响，要么就不实行金融审查.
2.他们通过本地比特币地址接受比特币，不需要钱包使用 [controversial payment protocol](https://blog.samouraiwallet.com/post/169222582782/bitpay-qr-codes-are-no-longer-valid-important).
3.他们不 [block payments by IPs/locations](https://twitter.com/alex_kaul/status/1090211252331208705).



## Self-Hosted Bitcoin Payment Processors

自托管支付处理器在您的服务器上运行，可为您提供对整个支付流程和资金的完全控制. 没有第三方的参与-极大地提高了您和您的客户的审查审查抵抗力，隐私和安全性. 

 | 处理器| 费用| 闪电| 直接到您的钱包| 转换为菲亚特| 要求|
| --------- |:----:|:---------:|:-----------------------:|:------------------:| ------------ |
| [BTCPay Server](https://btcpayserver.org/)  | 没有费用| 是的是的通过 [Payment Forwarding](https://www.blockonomics.co/views/payment_forwarding.html) 和 [Exchange Integration](https://redbtc.org/flows/integrations/kraken-exchange/)  |  2 GB RAM，80 GB存储，Docker |
| [One Time Address](https://github.com/alexk111/One-Time-Address)  | 没有费用| 没有是的没有 NodeJS |
| [CryptoWoo](https://www.cryptowoo.com/)  | 每年$ 34-$ 99 | 没有是的没有 PHP 5.6 +，Wordpress 4.3 +，WooCommerce 3.0+ |
| [BitcartCC](https://bitcartcc.com)  | 没有费用| 是的是的没有 1 GB RAM，10 GB存储，Docker |
| [LnMe](https://github.com/bumi/lnme)  | 没有费用| 是的是的没有 LND节点|
| [SatSale](https://github.com/nickfarrow/SatSale)  | 没有费用| 是的是的没有一个比特币节点和Python. 闪电节点和Woocommerce可选|

## Hosted Bitcoin Payment Processors

托管付款处理器在其他人的服务器上运行. 这简化了初始设置过程，但减少了您对付款过程的控制量.

### Non-Custodial

 | 处理器| 费用| 闪电| 直接到您的钱包| 转换为菲亚特| 要求|
| --------- |:----:|:---------:|:-----------------------:|:------------------:| ------------ |
| [Blockonomics](https://www.blockonomics.co/merchants)  |  1％| 没有是的通过 [Payment Forwarding](https://www.blockonomics.co/views/payment_forwarding.html)  | 没有
| [Bittery.io](https://bittery.io/)  | 没有费用| 是的是的通过 [Payment Forwarding](https://www.blockonomics.co/views/payment_forwarding.html) 和 [Exchange Integration](https://redbtc.org/flows/integrations/kraken-exchange/)  | 没有
| [Payscrypt](https://payscrypt.com/)  | 没有费用| 没有是的没有没有

### Custodial

 ⚠以下处理者使用他们自己的钱包来接收付款. 他们不仅收集有关付款的数据，而且对资金有完全控制权.

 | 处理器| 费用| 闪电| 直接到您的钱包| 转换为菲亚特| 要求|
| --------- |:----:|:---------:|:-----------------------:|:------------------:| ------------ |
| [Confirmo](https://confirmo.net/)  |  0.8％| 没有没有是的有关企业/网站的信息. 可能需要某些文件.  |
| [CoinGate](https://coingate.com/accept-bitcoin)  |  1％（商家）+一些 [variable service fee](https://support.coingate.com/en/109/why-does-coingate-charge-service-fee)  （客户）| 是的没有是的需要 [a lot of information and business documents](https://blog.coingate.com/2019/05/verify-merchant-account-faq) ，正式翻译成英文.  |
| [CoinPayments](https://www.coinpayments.net/)  |  0.5％| 是的没有没有提款可能需要多种形式的身份证明，并且需要结清任何未偿还的款项.  |
| [GloBee](https://globee.com/)  |  1％（最低发票$ 10）| 是的没有通过 [Luno](https://www.luno.com) 和 [Uphold](https://uphold.com/)  | 有关企业/网站的信息. 可能需要某些文件.  |
| [OpenNode](https://www.opennode.co/)  |  1％| 是的没有是的需要 [KYC/KYB documents](https://help.opennode.com/en/articles/3654899-kyc-and-kyb-requirements) |
| [Strike](https://strike.acinq.co/)  |  1％| 仅| 没有没有对于公司，是公司名称和实际地址.  |
| [Coinremitter](https://coinremitter.com/)  |  0.23％+ 0.0001 | 不不不不
| [Utrust](https://utrust.com/)  |  1％| 没有没有是的需要某些文件.  |
| [NOWPayments](https://nowpayments.io/)  |  ≤0.5％| 没有没有没有 KYC / AML程序适用于某些客户，钱包地址和选定资产.  |

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

[[Donate](https://mynode.alexkaul.com/gh-donate)] 谢谢您的支持！ 
