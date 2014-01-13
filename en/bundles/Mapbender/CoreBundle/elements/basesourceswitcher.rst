.. _basesourceswitcher:

BaseSourceSwitcher
***********************

BaseSourceSwitcher is a button group to change the map's background sources. The BaseSourceSwitcher allows you to switch over between the predefined source sets.


Configuration
=============

The configuration occurs in 2 steps: 

* Create a BaseSourceSwitcher Element with Title, Tooltip and Target
* Add Sourceset/s

.. image:: ../../../../../figures/basesourceswitcher_configuration.png
     :scale: 80


YAML-Definition:

.. code-block:: yaml

    title: 'BaseSourceSwitcher'                         # title
    tooltip: 'BaseSourceSwitcher'                       # text to use as tooltip
    target: map                                         # Id of Map element
    sourcesets:                                         # List of sourcesets
        - { title: sourcesetname, sources: [sourceId]}	# sourceset: title, sources list of sources
        

Class, Widget & Style
============================

* Class: Mapbender\\CoreBundle\\Element\\BaseSourceSwitcher
* Widget: mapbender.element.basesourceswitcher.js


HTTP Callbacks
==============

None.

JavaScript API
==============

None.

JavaScript Signals
==================

None.