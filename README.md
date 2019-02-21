# thehindu-scraper
Scraping archived web links from thehindu.com website

## Output structure

```bash
year-mm-dd/          # directory
  - links.csv
  - links-out.csv    # sub-directory
```

sample `links.csv` content
```txt
link,title
https://www.thehindu.com/todays-paper/sc-to-handle-ayodhya-title-dispute-only-as-a-land-issue/article22697171.ece,SC to handle Ayodhya title dispute only as a ‘land issue’
https://www.thehindu.com/todays-paper/two-ksrtc-drivers-killed-as-buses-collide-head-on/article22698589.ece,Two KSRTC drivers killed as buses collide head-on
...
```

sample `links-out.csv` content
```txt
link,title,content
https://www.thehindu.com/todays-paper/sc-to-handle-ayodhya-title-dispute-only-as-a-land-issue/article22697171.ece,SC to handle Ayodhya title dispute only as a ‘land issue’,[HUGE CONTENT]
```
