# reddit-web-scraper
A web scraper to view traffic for a keyword on reddit

Using traffic command:
  node cli.js traffic bitcoin
  
Output:
  {
    "bitcoin": {
      "monthly": {
        "2016/02": {
          "uniques": 311240,
          "pageViews": 2047459
        },
        "2016/01": {
          "uniques": 525246,
          "pageViews": 4105705
        }
        // ..
        "2015/03": {
          "uniques": 664930,
          "pageViews": 5782364
        }
      },
      "daily": {
        "2016/02/21": {
          "uniques": 14839,
          "pageViews": 61852,
          "subscriptions": 68
        },
        // ..
        "2015/12/28": {
          "uniques": 25651,
          "pageViews": 126991,
          "subscriptions": 167
        },
        "2015/12/27": {
          "uniques": 26370,
          "pageViews": 132347,
          "subscriptions": 125
        }
      }
    }
  }
  
More commands:
  traffic <subReddit> [moreSubReddits...]
