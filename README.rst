♣ unicards
==========

.. image:: https://api.travis-ci.org/lmacken/unicards.png?branch=master
   :target: http://travis-ci.org/lmacken/unicards
.. image:: https://coveralls.io/repos/lmacken/unicards/badge.png?branch=master
   :target: https://coveralls.io/r/lmacken/unicards
.. image:: https://pypip.in/v/unicards/badge.png
   :target: https://crate.io/packages/unicards
.. image:: https://pypip.in/d/unicards/badge.png
   :target: https://crate.io/packages/unicards

A Python module for converting strings into unicode playing cards

🂡 🂢 🂣 🂤 🂥 🂦 🂧 🂨 🂩 🂪 🂫 🂬 🂭 🂮 🂱 🂲 🂳 🂴 🂵 🂶 🂷 🂸 🂹 🂺 🂻 🂼 🂽 🂾 🃁 🃂 🃃 🃄 🃅 🃆 🃇 🃈 🃉 🃊 🃋 🃌 🃍 🃎 🃑 🃒 🃓 🃔 🃕 🃖 🃗 🃘 🃙 🃚 🃛 🃜 🃝 🃞

♠ Installation
--------------

::

   pip install unicards

♦ API
-----

::

   >>> from unicards import unicard
   >>> print(unicard('As'))
   🂡
   >>> print(unicard('Jd'))
   🃋
   >>> print(unicard('Tc'))
   🃚
   >>> print(unicard('2h'))
   🂲
   >>> unicard('8d', color=True)
   u'\x1b[31m\U0001f0c8\x1b[39m'


♥ License
---------

.. image:: https://www.gnu.org/graphics/gplv3-127x51.png
   :target: https://www.gnu.org/licenses/gpl.txt
