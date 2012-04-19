Functions for loading and storing network data
==============================================

.. toctree::
	:hidden:
	
	bel.rst
	edgelist.rst
	gml.rst
	memlist.rst
	dot.rst
	scn.rst

Zen supports the following standard network data formats:

	* :doc:`Edgelist <edgelist>`
	* :doc:`Binary edgelist <bel>`
	* :doc:`Graph modeling language <gml>`
	* The :doc:`DOT format <dot>`
	
Also supported are a handful of more specialized formats that are particular to Zen alone:

	* :doc:`Memory-mapped edgelist <memlist>`: this storage format preserves the 
	  internal structure of a Zen graph (connectivity only).  The result is a format that can be read very quickly.  
	  This format is excellent for storing and loading very large networks.
	
	* The :doc:`Simple, Concise Network (SCN) format <scn>`: this storage format is an 
	  extension to the :doc:`edgelist <edgelist>` format in which an arbitrary number of attributes can also be specified 
	  for each node and edge.

Overview
--------

.. automodule:: zen.io
	