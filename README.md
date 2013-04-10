paymo-timer
===========

Paymo Timer bookmarklet to open a pop-up  window with your timer, no need to go to Paymo website first!

Install it from the [project page](http://littlepea.github.io/paymo-timer).

Here's the  code:

	javascript:(function start_client(){newwnd=window.open("https://app.paymo.biz/timetracker/client.html","client","height=490,width=340,status=no,toolbar=no,menubar=no,location=no,scrollbars=no,resizable=yes");if(!newwnd){alert("Turn off popup blocker to access this feature")}return false})();
