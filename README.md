# Adblock Filter list for Malicious Frontends

Recently, various DeFi frontends have taken to using various malicious companies to surveil and block Ethereum addresses perceived as "suspicious" from using their services. This has led to [predictable](https://twitter.com/justinsuntron/status/1558397647165091840) and [hilarious](https://twitter.com/DrSoldmanGachs/status/1558377643917312000) results.

This repository contains a list of filters for AdBlock which ought to prevent these frontends from blocking their users.

To import these rules, simply go to your AdBlock settings, navigate to "Filter Lists", and add the following URL:

`https://raw.githubusercontent.com/ape-dev-cs/unblock-dapps/master/filter`

This has been built & tested around uBlock Origin, but should be compatible with all browser extension ad-blockers.

### Supported Frontends:
- [AAVE](https://aave.com)
- [Uniswap](https://uniswap.org)
- [Oasis](https://oasis.app)
- [Balancer](https://balancer.fi)


### Additional frontends

If you encounter any other frontends which maliciously block users, please feel free to open an issue, and I'll see what I can do to support it.

Note that some frontends may require a higher level of complexity to unblock, such as a GreaseMonkey/TamperMonkey script.