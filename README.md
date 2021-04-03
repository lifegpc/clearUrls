# ClearUrls Custom Rules
This repo can provide a custom rules for [ClearUrls](https://gitlab.com/KevinRoebert/ClearUrls).  
Rules Url: [`https://cs.kanahanazawa.com/clearUrl`](https://cs.kanahanazawa.com/clearUrl)  
Hash Url: [`https://cs.kanahanazawa.com/clearUrl?hash`](https://cs.kanahanazawa.com/clearUrl?hash)

## Available GET parameters
- `t`: Specify the [type](#rules-types) of rules. If this is empty, use all types. Can use `,` to separate two types.

# Rules Types
## log
This type of rules block logging requests in web page. Logging requests always contains lots of data, which be used to track. Blocking these requests will not have any side effects.
## track
This type of rules remove unnecessary get parameter which used to track user.
