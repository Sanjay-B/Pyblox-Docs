class ``pyblox.api.friends.Friends``
=======================================
.. py:function:: friendList(id)

   Gets Friend List

   :param str id: The user's ID
   :return: Friend list
   :rtype: List

.. py:function:: checkFriendship(id1, id2)

   Checks whether the 2 users has friendship.

   .. note::

      The 2 user ids should be interchangeable

   :param str id1: User ID
   :param str id2: User ID
   :return: whether they are friends
   :rtype: boolean

.. py:function:: checkBestFriendship(id1, id2)

   Similar to above function , but only for "Best friendship"

    .. note::

      The 2 user ids should be interchangeable

   :param str id1: User ID
   :param str id2: User ID
   :return: whether they are friends
   :rtype: boolean

.. py:function:: bestFriendList(id)

   Gets Best Friend List

   :param str id: The user's ID
   :return: Friend list
   :rtype: List