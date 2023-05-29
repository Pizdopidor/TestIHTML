<!DOCTYPE html>
<html lang="en">
<head>
  <title>Fundraising Demo</title>
  <!-- добавьте коды Google Analytics и FundraiseUp -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'GA_MEASUREMENT_ID');
  </script>
  <script>(function(w,d,s,n,a){if(!w[n]){var l='call,catch,on,once,set,then,track'.split(','),i,o=function(n){return 'function'==typeof n?o.l.push([arguments])&&o: function(){return o.l.push([n,arguments])&&o}},t=d.getElementsByTagName(s)[0], j=d.createElement(s);j.async=!0;j.src='https://cdn.fundraiseup.com/widget/'+a;t.parentNode.insertBefore(j,t);o.s=Date.now();o.v=4;o.h=w.location.href;o.l=[];for(i=0;i<7;i++)o[l[i]]=o(l[i]);w[n]=o}})(window,document,'script','FundraiseUp','AEMZUDUM');</script>
</head>
<body>
  <h1>Fundraising Demo</h1>
  
  <!-- добавьте кнопку для открытия чекаута -->
  <a href="#XJKDHSTQ" style="display: none"></a>

  <script>
    // отслеживайте событие открытия чекаута в Google Analytics
    function trackCheckoutEvent() {
      ga('send', {
        hitType: 'event',
        eventCategory: 'Checkout',
        eventAction: 'Initiated',
        eventLabel: 'Donation',
        eventValue: 700
      });
    }
    
    // вызвать функцию, когда пользователь кликает на кнопку
    document.querySelector('a[href="#XJKDHSTQ"]').addEventListener('click', trackCheckoutEvent);
  </script>
</body>
</html>
