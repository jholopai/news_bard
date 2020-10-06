# news_bard


                         ,
                    A   (,
                   / \ (,
                 __===_,
                 /| oo|\\
                ´´ === ´´
                  /i i\

This is a silly little script I made for our init-project which handled some basics in network administration. For our last exercise we could create any script of our choice. I was really new to scripting and wanted to try some new commands like curl or select, so a news-bearing bard was what I came up with.

The script does the following:
* Checks if user has curl installed
* If not, asks if they would like it installed (if not, the script ends)
* Installs curl
* Continues to the actual script
* Asks user for a topic word they would like to hear news about
* Looks up that word on the news site Yle's English RSS-feed with curl
* If a title with that word is found, returns the title
* But! Before returning it will take the title through a Shakespearean English translator API (https://funtranslations.com/api/shakespeare)
* That's it

While the script does not serve the most useful purpose, it was definitely a lot of fun to make! There's many points that could be improved upon, like being given the option of hearing the entire article after the title, for example.