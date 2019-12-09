# 9/12/2019
Done:
  - Solved the "Scopus401Error: Invalid API Key".

After run the block "Perform Search" in Jupyter for the first time, I was asked to fill in the API Key, then I got the "Scopus401Error: Invalid API Key". 
To refilled in the API key, it is necessary to remove the cache stored in the directory .scopus. Use this:
```sh
$ cd ~/.scopus
$ rm -rf .scopus
```
