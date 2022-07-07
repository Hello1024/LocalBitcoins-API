# LocalBitcoins API

LocalBitcoins documentation: https://localbitcoins.com/api-docs/

This project is unmaintained.   Donations welcome and I might be tempted to start maintaining it again.

## Examples

```python
import LocalBitcoin

lc = LocalBitcoin.LocalBitcoin(hmac_auth_key, hmac_auth_secret, False)
lc.getMyself()
```

To generate `hmac_auth_key` (key) and `hmac_auth_secret` (secret), go to: https://localbitcoins.com/accounts/api/

If you want debug enabled, change `False` to `True`

## MIT License
