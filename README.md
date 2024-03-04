# MIV² (MIV^2) - CosmosOS Text Editor Update Project

 - MIV functions are similar to VIM.

It is possible to pass argument:
 - miv(null) - open blank page
 - miv(String) - open page with String
 
Possible action inside editor:
 - i (Enter INSERT mode)
 - ESC button (Exit INSERT mode)
 - :wq (Save and Exit), returns String of text
 - :q! (Quit without saving), returns null
 - :q (Asks if you want to quit w/out saving), then returns null
