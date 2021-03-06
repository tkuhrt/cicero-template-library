# Cicero Template Library

[![Build Status](https://travis-ci.org/accordproject/cicero-template-library.svg?branch=master)](https://travis-ci.org/accordproject/cicero-template-library)

Repository for Smart Legal Contract Templates that conform that to the [Accord Protocol Template Specification](https://docs.google.com/document/d/1UacA_r2KGcBA2D4voDgGE8jqid-Uh4Dt09AE-shBKR0), the protocol is managed by the open-source community of the [Accord Project](https://accordproject.org). 

These templates can be parsed and executed by the [Cicero](https://github.com/accordproject/cicero) engine.

## Library

### Educational Samples

| Template Name | Description | Type |
|---------------|-------------|------|
| [Hello World](helloworld/) | This is the Hello World of Accord Protocol Templates. Executing the clause will simply echo back the text that occurs after the string Hello prepended to text that is passed in the request. | Clause |

### Supply Chain

| Template Name | Description | Type |
|---------------|-------------|------|
| [Acceptance of Delivery](acceptance-of-delivery/) | This clause allows the receiver of goods to inspect them for a given time period after delivery. | Clause |
| [Fragile Goods](fragile-goods/) | This clause specifies penalties for shocks caused to a fragile package in transport | Clause |
| [Late Delivery and Penalty](latedeliveryandpenalty/) | A sample Late Delivery And Penalty clause. | Clause | 
| [Perishable Goods](perishable-goods/) | This clause specifies penalties if the transport conditions (temperature and humidity) for a package are breached. | Clause |

### Finance

| Template Name | Description | Type |
|---------------|-------------|------|
| [Simple Agreement for Future Tokens](saft/) | The SAFT contract is a futures contract where a person invests in a company in exchange for receiving utility tokens that may be used when a product launches. | Contract |
| [Volume Discount](volumediscount/) | A sample volume discount clause. | Clause |

### Services

| Template Name | Description | Type |
|---------------|-------------|------|
| [Service Level Agreement](servicelevelagreement/) | A service level agreement that gives invoice credit based on service availability. | Contract |

## Contributing

Can't find a something? Then why not make a new template yourself? 

[Follow the instuctions in the docs.](http://accordcicero.readthedocs.io/en/latest/tutorial_001.html#creating-a-new-template)

## License

All templates in this library are made available under the [Apache-2 License](LICENSE).

