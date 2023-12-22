Welcome to ISSPA-lqz's documentation!
===================================

**ISSPA-lqz (Intelligent Self-driving System empowering Physical Agent)** is an experimental platform for 
self-driving physical agents, which was originally designed to facilitate researchers by creating a 
baseline library that is easy to use, algorithmically verifiable, and modularly extensible. And it was 
built under the leadership of the `TIS Lab <https://tis.ios.ac.cn/>`_, of which the team members 
are listed in :doc:`Team`.

It has the following features:

- Some open source baseline frameworks for autonomous driving.

- A cloud platform that supports the remote use of physical vehicles.

Contents
--------

..
  #. If you don't want to build a physical car and just want to play around in the simulator, head straight to :ref:`Simulation <doc_going_forward_simulation>`.

If you are looking for the old page, you can find it `here <https://f1tenth.github.io/build-old.html>`_. Please note that we no longer provide support for the old build page. If you have questions, please post to the `F1TENTH Discourse <https://f1tenth.discourse.group/>`_.

.. centered:: Talk with other F1TENTH teams on Slack!

.. image:: img/add-to-slack.png
   :target: https://join.slack.com/t/f1tenth-teams/shared_invite/enQtMzc3ODU2ODM1NzE3LTBjMmVkMzZjZTJiNWUzZDFhZTJiODgzMjg0MTA1MDAxZTUxMzkwMDRhNTM2NzdjNDc5MTk5YTc5YmNhNTdhMTU
   :align: center



.. note:: F1TENTH is an open source project developed by a community of
          researchers and students. The documentation team can always use your
          feedback and help to improve the tutorials and class reference. If
          you don't understand something, or cannot find what you
          are looking for in the docs, help us make the documentation better
          by letting us know!

          Submit an issue `GitHub repository <https://github.com/f1tenth/f1tenth_doc>`_.

The table of contents in the sidebar should let you easily access the
documentation for your topic of interest. You can also use the search function
in the top left corner.


.. toctree::
   :maxdepth: 1
   :caption: Build and Drive
   :name: sec-getting-started
   :hidden:

   getting_started/intro
   getting_started/build_car/index
   getting_started/software_setup/index
   getting_started/firmware/index
   getting_started/driving/index


.. toctree::
   :maxdepth: 1
   :caption: Simulate
   :name: sec-forward
   :hidden:

   going_forward/simulator/index
..
   going_forward/drive_rosbag
   going_forward/simulation/index
   going_forward/algorithms/index

.. toctree::
   :maxdepth: 1
   :caption: Autoware @ F1TENTH
   :name: sec-autoware
   :hidden:

   autoware/intro


.. toctree::
   :maxdepth: 1
   :caption: Support
   :name: sec-support-contact
   :hidden:

   getting_started/faq
   support/contact
   support/acknowledgment


.. Indices and tables
.. ------------------
..
.. * :ref:`genindex`
.. * :ref:`modindex`
.. * :ref:`search`
