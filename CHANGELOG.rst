^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cmu_pocketsphinx
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.0.3 (2017-12-19)
------------------
* Preparing for release part
* Merge branch 'kinetic-devel' of https://github.com/Pankaj-Baranwal/cmu-pocketsphinx into kinetic-devel
* Merge branch 'lunar-devel' of https://github.com/Pankaj-Baranwal/cmu-pocketsphinx into lunar-devel
* Updating contributor emailID
* Updated README.md
* Syncing repo with Pankaj-Baranwal/pocketsphinx
* Adding Mike as the original author
* Contributors: Michael Ferguson, Pankaj Baranwal

0.4.0 (2014-06-03)
------------------
* update changelog
* add ~source parameter, for setting things like 'alsasrc'
* add depend on python-gst
* Contributors: Michael Ferguson

0.3.0 (2013-11-27)
------------------
* "0.3.0"
* update changelog
* convert print statements to rosinfo/rosdebugs
* Merge pull request `#7 <https://github.com/Pankaj-Baranwal/cmu_pocketsphinx/issues/7>`_ from jdddog/hydro-devel
  Change language model at runtime + specify audio source
* * Now changing the language model at runtime updates what language model is being used by the recognizer because the lm/dic parameters are reloaded when the ~start service is called.
  * Specify a microphone name to connect to. This is useful when you want to have multiple audio sources each processed by independent recognizers.
* Contributors: Michael Ferguson, jdddog

0.2.2 (2013-09-29)
------------------
* add changelog
* Contributors: Michael Ferguson

0.2.1 (2013-09-21)
------------------
* fix `#5 <https://github.com/Pankaj-Baranwal/cmu_pocketsphinx/issues/5>`_
* Contributors: Mike Ferguson

0.2.0 (2013-07-12)
------------------
* fix `#2 <https://github.com/Pankaj-Baranwal/cmu_pocketsphinx/issues/2>`_, clean up some formatting
* Merge pull request `#1 <https://github.com/Pankaj-Baranwal/cmu_pocketsphinx/issues/1>`_ from wrousseau/groovy-devel
  Added support to grammar fsg files
* Added support to grammar fsg files
* fix catkinization
* starting to muck around with catkin
* Contributors: Michael Ferguson, Woody Rousseau
