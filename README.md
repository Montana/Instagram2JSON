# InstagramQL
Something I created in Python to crawl Instagram photos and spit info about them out into JSON and also make them graphable in GraphQL. You can run this locally, and/or Docker.

## Usage

```chmod u+x crawler.py```


When logged into Revfluence

| QueryID | Endpoint |
|---------|----------|
|17875800862117404|posts for tags|
|17874545323001329|user following|
|17851374694183129|user followers|
|17888483320059182|user posts|
|17864450716183058|likes on posts|
|17852405266163336|comments on posts|
|17842794232208280|posts on feed|
|17847560125201451|feed profile suggestions|
|17863787143139595|post suggestions|

Some of this can be done by JS via the "node_fetch" argument, but for the sake of argument Python will do just fine. 
