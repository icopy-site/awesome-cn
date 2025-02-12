<div class="github-widget" data-repo="alexk111/awesome-bitcoin-payment-processors"></div>
<div align="center">
<img width="500" src="https://raw.githubusercontent.com/alexk111/awesome-bitcoin-payment-processors/master/media/logo.svg?sanitize=true" alt="Awesome Bitcoin Payment Processors"/>
</div>

## Awesome Bitcoin Payment Processors [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A curated list of awesome Bitcoin payment processors enabling merchants, businesses and nonprofits to accept Bitcoin payments.



## Self-Hosted Bitcoin Payment Processors

Self-Hosted payment processors run on your server and provide you with a full control over the entire payment process and funds. There's no third-party involvement - that significantly increases the censorship-resistance, privacy, and security for you and your customers. 

| Processor | Fees | Lightning | Directly to Your Wallet | Conversion to Fiat | Requirements |
| --------- |:----:|:---------:|:-----------------------:|:------------------:| ------------ |
| [BTCPay Server](https://btcpayserver.org/) | No fees | Yes | Yes | Via [Strike plugin](https://github.com/Marfusios/strike-btcpayserver-plugin) or [Exchange Integration](https://redbtc.org/flows/integrations/kraken-exchange/) | 2 GB RAM, 80 GB Storage, Docker |
| [One Time Address](https://github.com/alexk111/One-Time-Address) | No fees | No | Yes | No | NodeJS |
| [CryptoWoo](https://www.cryptowoo.com/) | $34 - $99 per year | No | Yes | No | PHP 5.6+, Wordpress 4.3+, WooCommerce 3.0+ |
| [BitcartCC](https://bitcartcc.com) | No fees | Yes | Yes | No | 1 GB RAM, 10 GB Storage, Docker |
| [LnMe](https://github.com/bumi/lnme) | No fees | Yes | Yes | No | LND node |
| [SatSale](https://github.com/SatSale/SatSale) | No fees | Yes | Yes | Weakhands: [swap to USDT on Liquid](https://github.com/SatSale/SatSale/blob/471c8c03bbc269df1f322f6484b6e7a7364e5b34/config.toml#L101), no-KYC | Python. Bitcoin node, Lightning node & WooCommerce optional. |
| [Keagate](https://github.com/dilan-dio4/Keagate) | No fees | No | Yes | No | 1 GB RAM, Unix |
| [LNURL Daemon](https://github.com/yanascz/lnurld) | No fees | Yes | Yes | No | LND node |

## Hosted Bitcoin Payment Processors

Hosted payment processors run on someone else's server. This simplifies the initial setup process, but reduces the amount of control you have over the payment process.

### Non-Custodial

These processors use your wallets for receiving payments.

| Processor | Fees | Lightning | Directly to Your Wallet | Conversion to Fiat | Requirements |
| --------- |:----:|:---------:|:-----------------------:|:------------------:| ------------ |
| [Blockonomics](https://www.blockonomics.co/merchants) | 1% | No | Yes | Via [Payment Forwarding](https://www.blockonomics.co/views/payment_forwarding.html) | No |
| [Payscrypt](https://payscrypt.com/) | No fees | No | Yes | No | No |
| [Bitrequest](https://bitrequest.io/) | No fees | Yes | Yes | No | No |
| [Zaprite](https://zaprite.com/) | $25 per month | Yes | Yes | No | No |
| [Paymento](https://paymento.io/) | 0.5% | No | Yes | No | No |

### Custodial

The following processors use their own wallets, not yours, for receiving payments.

⚠ They not only collect data about payments, they have full control over the funds. There are many risks associated with custodians, which might end up with lost/locked funds.

⚠ Most of them have KYB/KYC/AML requirements, which poses a serious threat to your and your customers' privacy.

⚠ They have country-based restrictions for merchants and merchants' customers.

| Processor | Fees | Lightning | Directly to Your Wallet | Conversion to Fiat | Requirements |
| --------- |:----:|:---------:|:-----------------------:|:------------------:| ------------ |
| [Confirmo](https://confirmo.net/) | 1.3% (0.8% invoicing + 0.5% payouts) | Yes | No | Yes | Information about business / website. May require certain documents. |
| [CoinGate](https://coingate.com/accept) | 1% (merchant) + some [variable service fee](https://support.coingate.com/en/109/why-does-coingate-charge-service-fee) (customer) | Yes | No | Yes | Requires [a lot of information and business documents](https://blog.coingate.com/2019/05/verify-merchant-account-faq), officially translated in english. |
| [CoinPayments](https://www.coinpayments.net/) | 0.5% | Yes | No | No | On withdrawal may require a number of forms of identification and will require settlement of any outstanding amounts. |
| [OpenNode](https://www.opennode.co/) | 1% | Yes | No | Yes | Requires [KYC/KYB documents](https://help.opennode.com/en/articles/3654899-kyc-and-kyb-requirements) |
| [Strike](https://strike.me/business/) | 1% | Only | No | No | Requires [basic business info, documents, identity verifications of owners and operators](https://strike.me/faq/how-do-i-sign-up-for-a-strike-business-account/). |
| [Coinremitter](https://coinremitter.com/) | 0.23% + 0.0001 | No | No | No | No |
| [Utrust](https://utrust.com/) | 1% | No | No | Yes | Require certain documents. |
| [NOWPayments](https://nowpayments.io/) | ≤0.5% | No | No | No | KYC/AML procedure applied to certain clients, wallet addresses and select assets. |
| [ElenPAY](https://elenpay.tech) | ≤1% | Yes | Yes | No (Soon) | Low KYC |
| [Speed](https://tryspeed.com/) | 1% | Yes | No | No | No |
| [Sheepy](https://www.sheepy.com/) | 1% + $0.25 | No | No | Yes | Requires [KYB documents](https://www.sheepy.com/faq/what-documents-are-required-to-verify-my-merchant-account) |
| [ALFAcoins](https://www.alfacoins.com/) | 0.99% | No | No | No | Requires KYB documents |
| [Apirone](https://apirone.com/) | 1% | No | No | No | No |

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

[[Donate](https://mynode.alexkaul.com/gh-donate)] Thank you for your support! 🙌
