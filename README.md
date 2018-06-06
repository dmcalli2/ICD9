# ICD9

NOT FINALISED YET. PLEASE IGNORE THIS REPOSITORY UNTIL THIS TEXT IS REMOVED.

## Reason for this repository
There are a number of websites purporting to hold copies of ICD9 (for example http://www.wolfbane.com/icd/index.html). However, most, if not all of these are for one of the ICD9 modifications (eg ICD9-CM or ICD9-AM), and **not** the original version created by the WHO. Others (such as http://icd9.chrisendres.com/ make it clear that they are using another version of ICD9.

This is a problem for researchers (and others working with health data) from outside the US and Canada, who may mistake files and look-up tools for ICD9-CM (or ICD9-AM) for the original WHO ICD9 codelist.

Moreover, while wikipedia does appear to provide a list of codes and labels for the original ICD9 coding scheme (https://en.wikipedia.org/wiki/List_of_ICD-9_codes), this is not available as single text document, but rather as linked pages.  Moreover, the wikipedia "list of ICD9 codes" landing page does not clearly state that this list is the original ICD9, and not a modified version.

Therefore, this repository has been created to provide [a standalone text file](icd9.csv) showing codes and labels for ICD9, clearly labelled as the original unmodified version.

## Mapping from ICD9-CM to ICD9.

Some researchers may wish to map from ICD9CM to ICD9. This is not straightforward as the addition of extra codes with additional detail will likely change the usage of existing codes within a system. Moreover, while ICD9-CM modifications generally appear to involve the addition of an extra digit, it is not straightforward to simply remove this extra digit as  [this file](Differences_icd9_icd9cm.md) shows.

