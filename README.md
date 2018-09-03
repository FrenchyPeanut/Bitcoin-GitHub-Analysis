# Bitcoin-GitHub-Analysis
## Analysis of the Bitcoin Open source project though GitHub Archive data

In ten years of existence, Bitcoin proved to be the most successful cryptographic
currency in the history. Originally created by Satoshi Nakamoto,
first as a WhitePaper in 2008, followed quickly by the source-code of the
original software in 2009. The Bitcoin software is completely open-source
and is the first fully decentralized peer-to-peer version of electronic cash
system that is not controlled by any central authority or control point that
could be compromised. \
By using GitHub archive of data, we quantify aspects
of developer participation, community growth and internal issues
for this OSS project. We then use the price of the Bitcoin token to correlate
and reveal some important patterns that may indicate new behaviors in
the OSS community. We conclude that a new economy got created in the
OSS community by the issuing of crypto-currency that get real-world value
from its core and volunteer work.

## Retrieving the GitHub Archive data

The main focus of this study is to understand and explain the development of the Bitcoin
open-source software and identify a relevant relationship between its development and
the price of the Bitcoin currency. The Bitcoin software was originally stored on Source-
Forge but switched to GitHub afterward to allow the community to contribute more
easily to the project. To retrieve the historical data of Bitcoin in GitHub, we used two
sources; GhTorrent and GitHub Archive. 
The official GitHub API has some constraints,
most notably themaximumnumber of API requests per hour, which is currently fixed at
5000 formost purposes. As we need to experiment with large datasets, we only use this
data source for specific experiments when the data is not available on both GhTorrent
and GitHub Archive.
