# elasticsearch-ILM-policy
Elasticsearch ILM Policy file

**config directory contains the below sample policy files.**
1. age_rollover_policy.json
2. doc_rollover_policy.json
3. sample_rollover_policy.json
4. size_rollover_policy.json


**age_rollover_policy.json**

    This policy is for rolling over the indices when age of the index reaches configurable age.
    As per the configuration, if the index reaches 1 day the index would be rolled over.



**doc_rollover_policy.json**

    This policy is for rolling over the indices when document count of the index reaches configurable document count.
    As per the configuration, if the index reaches 1000 documents the index would be rolled over.




**size_rollover_policy.json**

    This policy is for rolling over the indices when size of the index reaches configurable size.
    As per the configuration, if the index reaches 500mb the index would be rolled over.




**sample_rollover_policy.json**

    This policy is for rolling over the indices when age of the index or document count or size reaches configurable.
    As per the configuration, if the index reaches 1 day or 10000 count or 500mb the index would be rolled over.

