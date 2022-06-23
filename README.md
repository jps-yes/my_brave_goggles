# My Brave Search Goggles
Customization file for the brave search engine (in goggles folder)

## MediaBiasFactCheck (mediabiasfactcheck.goggle)
Boosts/Downranks news sources according to mediabiasfactcheck.com categories (as of 23 June 2022).

| **Category** | **weights** |  
| :--- | ---: |
[right bias](https://mediabiasfactcheck.com/right/) | -2 |
[right-center bias](https://mediabiasfactcheck.com/right-center/) | 0  |
[LEAST biased](https://mediabiasfactcheck.com/center/) | +3  |
[left-center bias](https://mediabiasfactcheck.com/leftcenter/) | 0  |
[left bias](https://mediabiasfactcheck.com/left/) | -2  |
[conspiracy-pseudoscience](https://mediabiasfactcheck.com/conspiracy/) | -1 |
[pro-science](https://mediabiasfactcheck.com/pro-science/) | 1 | 
[satire](https://mediabiasfactcheck.com/satire/) | 0  |

The weights are lower for science/pseudoscience categories because the focus of this goggle is on news sources, not science.

## Personal (personal.goggle) 
Includes:
- MediaBiasFactCheck goggle
- HackerNews goggle
- Penalization for top 1000 websites, with some exceptions:
    -  vimeo, youtube, wikipedia, github, reddit, blogspot, wordpress.org (wordpress.com is downranked), github.io, quora, w3.org, who.int, wikimedia.org, .gov sites, .edu sites, science journals, goodreads, stackexchange, coursera, elsevier, substack
- Some favorite websites

NOTE: a boosting rule will always take precedence over a downrank.
