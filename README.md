amoveo_exchange
=====

This is an exchange written for trades between bitcoin and amoveo.

[installation](docs/installation.md)

[turn it on](docs/boot_up.md)

The exchange only touches VEO. You send bitcoin to the person you are trading with, and the exchange watches the trade happen on the bitcoin blockchain.


[what needs to get done](docs/todo.md)


====== Warnings

* If you ever deleted the database for any reason, it is important to change your public key in the veo full node. Otherwise you could accept payments from your history that are no longer valid. Allowing people to trade in your market without paying you.
