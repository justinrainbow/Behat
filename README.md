Behat
=====

* The main website with documentation is at [http://everzet.com/Behat](http://everzet.com/Behat)
* Official Google Group is at [http://groups.google.com/group/behat](http://groups.google.com/group/behat)
* The wiki pages is at [http://github.com/everzet/Behat/wiki](http://github.com/everzet/Behat/wiki)
* The API documentation is at [http://everzet.com/Behat/api/](http://everzet.com/Behat/api/)


Note on Patches/Pull Requests
-----------------------------
 
* Fork the project `develop` branch (all new development happens here, master for releases & hotfixes only).
* Make your feature addition or bug fix.
* Add features for it (look at test/Behat/features for examples).
  This is important so I don't break it in a future version unintentionally.
* Commit, do not mess with `BehatApplication` version, or `CHANGES.md` one.
  (if you want to have your own version, that is fine but
   bump version in a commit by itself I can ignore when I pull)
* Send me a pull request.

Running tests
-------------

	behat

If you get errors about missing dependencies - just run

	git submodule update --init

Copyright
---------

Copyright (c) 2010 Konstantin Kudryashov (ever.zet). See LICENSE for details.

Contributors
------------

* Konstantin Kudryashov [everzet](http://github.com/everzet) [lead developer]
* Daniel Anderson Tiecher [datiecher](http://github.com/datiecher) [contributor - pt-BR translation]

