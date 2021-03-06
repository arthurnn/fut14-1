.. :changelog:

Changelog
---------


0.0.14 (2014-07-06)
++++++++++++++++++

* core: relist returns number of delted/sold if clean parameter was set
* add new exception FeatureDisabled
* core: add emulate
* core: add stats
* core: add clubInfo


0.0.13 (2014-04-19)
++++++++++++++++++

* core: add sendToWatchlist


0.0.12 (2014-02-23)
++++++++++++++++++

* exceptions: add Unauthorized & MultipleSession
* fix quicksell


0.0.11 (2014-02-15)
++++++++++++++++++

* fix logger
* setup.py is now executable


0.0.10 (2014-02-15)
++++++++++++++++++

* core: add clean ability to relist (remove sold cards)
* core: keepalive returns credit amount


0.0.9 (2014-01-26)
++++++++++++++++++

* fix relist


0.0.8 (2014-01-26)
++++++++++++++++++

* add new exception Conflict
* init docs
* core: add relist
* core: add sendToClub


0.0.7 (2014-01-13)
++++++++++++++++++

* add few exceptions


0.0.6 (2013-12-30)
++++++++++++++++++

* core: add DEBUG feature
* add multiplatform support (xbox/ps3/and/ios)


0.0.5 (2013-12-23)
++++++++++++++++++

* core: add assetId param to searchAuction method
* core: add pileSize
* core: add leagueId to item data parser


0.0.4 (2013-11-10)
++++++++++++++++++

* convert lowercase function/method names to mixedCase (send_to_tradepile -> sendToTradepile)
* drop python-2.5 (requests)
* core: python 3 support


0.0.3 (2013-10-25)
++++++++++++++++++

* core: move requests session init & headers from login to init
* core: update credits on every request (only if it is avaible included in response)


0.0.2 (2013-10-17)
++++++++++++++++++

* core: add watchlist
* core: add card_info function
* core: add alias for base_id & card_info


0.0.1 (2013-10-15)
++++++++++++++++++

* init
