## What is autoISF 3.0?
AutoISF adds more power to the algorithm used in AndroidAPS by adjusting the insulin sensitivity based on different scenarios (e.g. high BG,
accelerating/decelerating BG, BG plateau). autoISF has many different settings to fine-tune these adjustments.
However, it is important to start with well-tested basal rate and settings for insulin sensitivity and carb ratios.

## Where do I get autoIFS
* The majority of the AutoISF design and development effort was done by [ga-zelle](https://github.com/ga-zelle) with support from
  [swissalpine](https://github.com/swissalpine), [claudi](https://github.com/lutzlukesch),
  [BerNie](https://github.com/bherpichb), [mountrcg](https://github.com/mountrcg), [T-o-b-i-a-s](https://github.com/T-o-b-i-a-s) and [myself](https://github.com/blaqone).

* You can get AndoidAPS with autoIFS 3.0 at https://github.com/T-o-b-i-a-s/AndroidAPS/tree/3.2.0.2-ai3.0
* [Here in the wiki](https://github.com/blaqone/autoISF/wiki) you can find the Documentation

  ## What's new in AutoISF Version 3.0 when compared to 2.2.8.1
* Activity Monitor takes step counter from phone into consideration
* iob-Threshold allows to better limit/control the total amount of insulin on board
* New automation triggers and actions to allow for Automation rules specific for autoISF
  
# autoISF version 2.2.8.1
The autoISF add-on to AAPS V3.1.0.3 using oref1 can adapt ISF if glucose or its trends show certain behaviour. See the Quick Guide for details of those scenarios. The effects can be tuned individually to further improve your results if you already have a TIR of about 90%.
