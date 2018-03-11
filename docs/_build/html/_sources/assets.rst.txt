class ``pyblox.api.assets.Assets``
======================================

.. py:function:: getPackageAssets(assetid)

   Gets Package ID

   :param str assetid: The Asset ID
   :return: the package id
   :rtype: list

.. py:function:: hasAsset(userid, assetid)

   check whether a user has an asset.
   ``https://api.roblox.com/Ownership/HasAsset?userId={userId}&assetId={assetId}``

   :param str usesrid: The User ID
   :param str assetid: The Asset ID
   :rtype: boolean

.. py:function:: getAssetInfo(assetid)

   Returns an asset's detail
   ``https://api.roblox.com/Marketplace/ProductInfo?assetId={assetid}``
   
   .. note::

      This works as if it is an instance of a class.

   :param str assetid: The Asset ID
   :return: Asset Info
   :rtype: list (or potentially an instance of a class)

.. py:function:: getAssetVersions(assetid)

  Returns the version  of an asset.
  ``https://www.roblox.com/studio/plugins/info?assetId={assetid}``

  :param str assetid: The Asset ID
  :return: Version
  :rtype: list