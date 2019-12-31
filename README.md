# gee_monkey

Batch export Google Earth Engine (GEE) tasks with `Tampermonkey`.

+ Tired of click GEE tasks run button in browser? 
+ Tired of translate `JavaScript` into `python`, because of `JavaScript` inconvenient batch exporting? 
+ Tired of paste JavaScript into console?  

__Tampermonkey can solve those problems!__

## Functions

![](image/gee_monkey_ui.png)

- **rAll** : batch run all tasks
- **rInv** : batch run all tasks in inverse order
- **cALL** : cancel all tasks
- **cSub** : only cancel `submitted-to-backend` tasks, and leave `running-on-backend` tasks 
- **ntask**: How many tasks to export? If not specified, it is all tasks.

to be continue

**Tasks submitted to GEE have two kinds:**   

1. `task submitted-to-backend`: just submitted and waiting in the queue  
2. `task running-on-backend`: submitted and running now (in skyblue backgroud)

![](image/gee_monkey_v0.1.3.png)

## Updates

* 2019-09-17 (version 0.1.4)
  -   add `rInv` and `ntask`

* 2018-07-20   
  -   `running-on-backend` task's background is set to skyblue to distinguish `submitted-to-backend` task.

## Installation

You need `chrome` and [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) (`firefox` is also OK).  
You also can submit tasks by your phone with `firefox` and `Tampermonkey`.

+ 1 Install [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) extension in `chrome` or `firefox`.
+ 2 Dashboard → New script → paste the script in [gee_monkey](https://github.com/kongdd/GEE_Tools/blob/master/gee_monkey.js) → F5 refresh GEE website.

![](image/s2_gee_monkey.gif)

## Donation

* [Donate](https://www.paypal.me/kongddsysu/10usd) first then email to me ask for gee_monkey (kongdd.sysu at gmail.com)

PayPal有较高的手续费，微信支付宝捐赠请戳下面链接：
https://github.com/kongdd/gee_monkey/blob/master/image/pay_kongdd_70.png
