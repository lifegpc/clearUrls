# ClearUrls Custom Rules
[![Custom Rules Number (Include Offical Rules)](https://cs.kanahanazawa.com/clearUrl?bagel&fuckinggithubcache)](https://cs.kanahanazawa.com/clearUrl)
[![Custom Rules Number](https://cs.kanahanazawa.com/clearUrl?bagel&noda&fuckinggithubcache)](https://cs.kanahanazawa.com/clearUrl?noda)  
This repo can provide a custom rules for [ClearUrls](https://gitlab.com/KevinRoebert/ClearUrls).  
Rules Url: [`https://cs.kanahanazawa.com/clearUrl`](https://cs.kanahanazawa.com/clearUrl)  
Hash Url: [`https://cs.kanahanazawa.com/clearUrl?hash`](https://cs.kanahanazawa.com/clearUrl?hash)

## Available GET parameters
- `t`: Specify the [type](#rules-types) of rules. If this is empty, use all types. Can use `,` to separate two types.
- `hash`: Return hash value rather than rules.
- `noda`: Don't include origin rules.

# Rules Types
## log
[![Custom Rules Number (Types: log, Include Offical Rules)](https://cs.kanahanazawa.com/clearUrl?bagel&t=log&fuckinggithubcache)](https://cs.kanahanazawa.com/clearUrl?t=log)
[![Custom Rules Number (Types: log)](https://cs.kanahanazawa.com/clearUrl?bagel&t=log&noda&fuckinggithubcache)](https://cs.kanahanazawa.com/clearUrl?t=log&noda)  
This type of rules block logging requests in web page. Logging requests always contains lots of data, which be used to track. Blocking these requests will not have any side effects.
## track
[![Custom Rules Number (Types: track, Include Offical Rules)](https://cs.kanahanazawa.com/clearUrl?bagel&t=track&fuckinggithubcache)](https://cs.kanahanazawa.com/clearUrl?t=track)
[![Custom Rules Number (Types: track)](https://cs.kanahanazawa.com/clearUrl?bagel&t=track&noda&fuckinggithubcache)](https://cs.kanahanazawa.com/clearUrl?t=track&noda)  
This type of rules remove unnecessary get parameter which used to track user.
## redirect
[![Custom Rules Number (Types: redirect, Include Offical Rules)](https://cs.kanahanazawa.com/clearUrl?bagel&t=redirect&fuckinggithubcache)](https://cs.kanahanazawa.com/clearUrl?t=redirect)
[![Custom Rules Number (Types: redirect)](https://cs.kanahanazawa.com/clearUrl?bagel&t=redirect&noda&fuckinggithubcache)](https://cs.kanahanazawa.com/clearUrl?t=redirect&noda)  
This type of rules can skip unnecessary redirect page.
