# common-processes

A sample KQL (Kusto Query Language) query that you can use to retrieve information about the most common processes that have been running on your machines in the last 7 days

This query retrieves the top 10 most common process names that were running on your machines in the last 7 days, along with the process command line, the process GUID, and the account that started the process.

You can use this query in the Microsoft Sentinel Advanced hunting by pasting the query in the KQL editor.

Please note that you need an Azure tenant, and a Microsoft Sentinel subscription to access the Advanced hunting feature and to be able to run the queries.
