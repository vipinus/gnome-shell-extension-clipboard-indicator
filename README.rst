============================
📋 Clipboard Indicator (vipinus fork)
============================

   ⚠️ **This is an unofficial fork** of `Tudmotu's Clipboard Indicator
   <https://github.com/Tudmotu/gnome-shell-extension-clipboard-indicator>`_,
   maintained by `vipinus <https://github.com/vipinus>`_.

   The fork adds **GNOME 50 support**, **complete translations for all 24
   bundled languages**, modernized GJS APIs, and search-path performance
   improvements. The original extension is © Yotam Bar-On and is licensed
   under MIT — see ``LICENSE.rst``. Please use the upstream extension for
   the official version.

A reliable, feature-rich clipboard manager for GNOME, originally with over
**1M** downloads on the upstream listing.

|Screenshot|

.. |Screenshot| image:: ./screenshot.png
  :width: 400
  :alt: A screenshot of the clipboard manager, showing clipboard history including images

This extension is also packaged by the community for many popular Linux distros
— search your package manager.

🧰 Features:
----------------

- Highly customizable
- Supports both text and images
- Allows pinning items to top
- Includes a "private" mode
- Has configurable shortcuts
- Keyboard control

In-Menu Keyboard Controls
^^^^^^^^^^^^^^^^^^^^^^^^^^

- Use arrows to navigate
- :code:`v` to paste directly from menu
- :code:`p` to pin item
- :code:`<Delete>` to delete an item

📦 Install from source
----------------

Installation via git is performed by cloning the repo into your local gnome-shell extensions directory (usually :code:`~/.local/share/gnome-shell/extensions/`)::

    $ git clone https://github.com/vipinus/gnome-shell-extension-clipboard-indicator.git <extensions-dir>/clipboard-indicator@vipinus.github.com

After cloning the repo, the extension is practically installed yet disabled. In order to enable it, run the following command::

    $ gnome-extensions enable clipboard-indicator@vipinus.github.com


✅ GNOME Version Support
--------------------------
Depending on your GNOME version, you will need to install the following
Clipboard Indicator versions:

* GNOME 46 and above:

  * Use latest version

* GNOME 45:

  * v57

* GNOME 42-44

  * v47

* GNOME 40-41

  * v39

* GNOME <40

  * v37

⌨️ Contributing
----------------
Contributions to this project are welcome.

Please follow these guidelines when contributing:

- If you want to contribute code, your best bet is to look for an issue with the label "Up for grabs"
- DO NOT open unsolicited PRs unless they are for updating translations
- Look at the list of previous PRs before you open a PR, if your PR conflicts with another, it will be rejected
- If you have a feature idea, open an issue and discuss it there before implementing. DO NOT open a PR as a platform for discussion

Release Cycle
^^^^^^^^^^^^^
This project loosely follows the release cycle of GNOME. That means it will
usually receive 2 updates a year, close to the release of a new major GNOME
version. If there are features you'd like to implement or suggest, it is advised
to start the discussion a month or two before a GNOME release.
