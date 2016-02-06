# LocalBitcoins API

LocalBitcoins documentation: https://localbitcoins.com/api-docs/


**Do you like this project? Support it by donating**
- ![Paypal](https://raw.githubusercontent.com/reek/anti-adblock-killer/gh-pages/images/paypal.png) Paypal: [Donate](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=YNVNPLE45DNG6)
- ![btc](https://camo.githubusercontent.com/4bc31b03fc4026aa2f14e09c25c09b81e06d5e71/687474703a2f2f7777772e6d6f6e747265616c626974636f696e2e636f6d2f696d672f66617669636f6e2e69636f) Bitcoin: 1DCEpC9wYXeUGXS58qSsqKzyy7HLTTXNYe 

## Examples

```python
import LocalBitcoin

lc = LocalBitcoin.LocalBitcoin(hmac_auth_key, hmac_auth_secret, False)
lc.getMyself()
```

To generate `hmac_auth_key` (key) and `hmac_auth_secret` (secret), go to: https://localbitcoins.com/accounts/api/

If you want debug enabled, change `False` to `True`

## MIT License
