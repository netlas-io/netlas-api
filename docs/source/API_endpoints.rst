API Endpoints
==================================
.. attention::
    API documentation is under development

.. note::
    All requests to endpoints below should include X-API-Key header with your api key which can be found in profile page

Responses
-----------
Search
+++++++++++++++++++
Get documents by given query

**Example:** ``api/responses/?q=<QUERY>&indices=<INDEX_ID>``

+----------+------------------------------+-----------------------------------------------------------------+
| Method   |  Request                     |  Description                                                    |
+==========+==============================+=================================================================+
| ``GET``  | * ``q``                      |* ``str`` Search query                                           |
|          | * ``indices (optional)``     |* ``int`` Comma separated list of indices ids (default - latest) |
|          | * ``start (optional)``       |* ``int`` offset (default 0)                                     |
+----------+------------------------------+-----------------------------------------------------------------+


Count
+++++++++++++++++++
Count documents by given query

**Example:** ``api/responses_count/?q=<QUERY>&indices=<INDEX_ID>``

+----------+------------------------------+-----------------------------------------------------------------+
| Method   |  Request                     |  Description                                                    |
+==========+==============================+=================================================================+
| ``GET``  | * ``q``                      |* ``str`` Search query                                           |
|          | * ``indices (optional)``     |* ``int`` Comma separated list of indices ids (default - latest) |
+----------+------------------------------+-----------------------------------------------------------------+


Get download link
+++++++++++++++++++
Get link for downloading documents by given query

**Example:** ``api/responses/download/?q=<QUERY>&indices=<INDEX_ID>``

+-----------+------------------------------+----------------------------------------------------------------------------------------------------------------+
| Method    |  Request                     |  Description                                                                                                   |
+===========+==============================+================================================================================================================+
| ``POST``  | * ``q``                      |* ``str`` Search query                                                                                          |
|           | * ``fields``                 |* ``list`` Comma-separated list of fields to include/exclude                                                    |
|           | * ``size``                   |* ``int`` Number of documents to download                                                                       |
|           | * ``source_type``            |* ``str`` Include or exclude fields (choices: include, exclude)                                                 |
|           | * ``indices (optional)``     |* ``list`` Comma-separated IDs of selected data indices (can be retrieved by indices method) (default - latest) |
|           | * ``type (optional)``        |* ``str`` File format (choices: json, csv) (default "json")                                                     |
|           | * ``raw (optional)``         |* ``bool`` (default False)                                                                                      |
+-----------+------------------------------+----------------------------------------------------------------------------------------------------------------+


Download
+++++++++++
Download documents using file stream

**Example:** ``api/filestream/d54e6ad8cccf419bd6416180349e9132/869455736a241b3c69cfa3ab741c78c6/``


Domains
-----------
Search
+++++++++++++++++++
Get documents by given query

**Example:** ``api/domains/?q=<QUERY>``

+----------+------------------------------+-----------------------------------------------------------------+
| Method   |  Request                     |  Description                                                    |
+==========+==============================+=================================================================+
| ``GET``  | * ``q``                      |* ``str`` Search query                                           |
+----------+------------------------------+-----------------------------------------------------------------+


Count
+++++++++++++++++++
Count documents by given query

**Example:** ``api/domains_count/?q=<QUERY>``

+----------+------------------------------+-----------------------------------------------------------------+
| Method   |  Request                     |  Description                                                    |
+==========+==============================+=================================================================+
| ``GET``  | * ``q``                      |* ``str`` Search query                                           |
+----------+------------------------------+-----------------------------------------------------------------+


Get download link
+++++++++++++++++++
Get link for downloading documents by given query

**Example:** ``api/domains/download/?q=<QUERY>``

+-----------+------------------------------+----------------------------------------------------------------------------------------------------------------+
| Method    |  Request                     |  Description                                                                                                   |
+===========+==============================+================================================================================================================+
| ``POST``  | * ``q``                      |* ``str`` Search query                                                                                          |
|           | * ``fields``                 |* ``list`` Comma-separated list of fields to include/exclude                                                    |
|           | * ``size``                   |* ``int`` Number of documents to download                                                                       |
|           | * ``source_type``            |* ``str`` Include or exclude fields (choices: include, exclude)                                                 |
|           | * ``indices (optional)``     |* ``list`` Comma-separated IDs of selected data indices (can be retrieved by indices method) (default - latest) |
|           | * ``type (optional)``        |* ``str`` File format (choices: json, csv) (default "json")                                                     |
|           | * ``raw (optional)``         |* ``bool`` (default False)                                                                                      |
+-----------+------------------------------+----------------------------------------------------------------------------------------------------------------+


Download
+++++++++++
Download documents using file stream

**Example:** ``api/filestream/d54e6ad8cccf419bd6416180349e9132/869455736a241b3c69cfa3ab741c78c6/``





Certificates
----------------
Search
+++++++++++++++++++
Get documents by given query

**Example:** ``api/certs/?q=<QUERY>``

+----------+------------------------------+-----------------------------------------------------------------+
| Method   |  Request                     |  Description                                                    |
+==========+==============================+=================================================================+
| ``GET``  | * ``q``                      |* ``str`` Search query                                           |
+----------+------------------------------+-----------------------------------------------------------------+


Count
+++++++++++++++++++
Count documents by given query

**Example:** ``api/certs_count/?q=<QUERY>``

+----------+------------------------------+-----------------------------------------------------------------+
| Method   |  Request                     |  Description                                                    |
+==========+==============================+=================================================================+
| ``GET``  | * ``q``                      |* ``str`` Search query                                           |
+----------+------------------------------+-----------------------------------------------------------------+


Get download link
+++++++++++++++++++
Get link for downloading documents by given query

**Example:** ``api/certs/download/?q=<QUERY>``

+-----------+------------------------------+----------------------------------------------------------------------------------------------------------------+
| Method    |  Request                     |  Description                                                                                                   |
+===========+==============================+================================================================================================================+
| ``POST``  | * ``q``                      |* ``str`` Search query                                                                                          |
|           | * ``fields``                 |* ``list`` Comma-separated list of fields to include/exclude                                                    |
|           | * ``size``                   |* ``int`` Number of documents to download                                                                       |
|           | * ``source_type``            |* ``str`` Include or exclude fields (choices: include, exclude)                                                 |
|           | * ``indices (optional)``     |* ``list`` Comma-separated IDs of selected data indices (can be retrieved by indices method) (default - latest) |
|           | * ``type (optional)``        |* ``str`` File format (choices: json, csv) (default "json")                                                     |
|           | * ``raw (optional)``         |* ``bool`` (default False)                                                                                      |
+-----------+------------------------------+----------------------------------------------------------------------------------------------------------------+


Download
+++++++++++
Download documents using file stream

**Example:** ``api/filestream/d54e6ad8cccf419bd6416180349e9132/869455736a241b3c69cfa3ab741c78c6/``






IP Search
-----------
Search
+++++++++++++++++++
Get documents by given query

**Example:** ``api/ip/?q=<QUERY>``

+----------+------------------------------+-----------------------------------------------------------------+
| Method   |  Request                     |  Description                                                    |
+==========+==============================+=================================================================+
| ``GET``  | * ``q``                      |* ``str`` Search query                                           |
+----------+------------------------------+-----------------------------------------------------------------+





Domain Search
----------------
Search
+++++++++++++++++++
Get documents by given query

**Example:** ``api/domain/?q=<QUERY>``

+----------+------------------------------+-----------------------------------------------------------------+
| Method   |  Request                     |  Description                                                    |
+==========+==============================+=================================================================+
| ``GET``  | * ``q``                      |* ``str`` Search query                                           |
| ``GET``  | * ``related_ip``             |* ``int`` Related ip for domain                                  |
+----------+------------------------------+-----------------------------------------------------------------+





API Key
-----------
Reset API Key
+++++++++++++++++++
Reset current api key and get new one

**Example:** ``api/api_keys/reset_api_key/``




Indices
-----------
List
+++++++++++++++++++
Get list of available indices

**Example:** ``api/indices/``





User
-----------
Profile
+++++++++++++++++++
Get data about current user

**Example:** ``api/users/profile/``






