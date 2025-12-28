---
title: Battle for the Grove
layout: single
# [rules](./rules)

# [production](./production)
# https://developer.paypal.com/api/nvp-soap/paypal-payments-standard/integration-guide/html-example-buy-now/
---

![micro_druids.jpg](/games/micro_druids.jpg)

<form action="https://www.paypal.com/cgi-bin/webscr" method="post"> 
<!-- Identify your business so that you can collect the payments. --> 
<input type="hidden" name="business" value="teammagepowerss@gmail.com"> 
<!-- Specify a Buy Now button. --> 
<input type="hidden" name="cmd" value="_xclick"> 
<!-- Specify details about the item that buyers will purchase. --> 
<input type="hidden" name="item_name" value="Battle for the Grove"> 
<input type="hidden" name="amount" value="15.00">
<input type="hidden" name="currency_code" value="USD">
<!-- Display the payment button. -->
<input type="image" name="submit" border="0" src="https://www.paypalobjects.com/en_US/i/btn/btn_buynow_LG.gif" alt="Buy Now"> 
<img alt="" border="0" width="1" height="1" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" > 
</form>

[Rules](./rules)

[Production](./production)