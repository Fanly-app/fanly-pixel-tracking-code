# ![Alt](fanly-word-blue.png "Fanly") #
## Pixel Tracking Code ##



Fanly pixel code is made up of two main elements:

1. Pixel script tag

2. Fanly Client ID (provided by your Account Manager)

The Fanly pixel code tracks activity and should be installed on every page of your website.

1. Paste the Fanly pixel code between the `<head>` and `</head>` tags of your web page. You may already have other existing code between the head tags, so just place the pixel code underneath that, but above `</head>`.

2. Change **_Client-ID_** code to the one provided by your Account Manager.


~~~~
<!-- Fanly Pixel Code -->
<script>

!function(f,a,n,l,y){if(f.fanly)return;f.fanly = {};f.fanly.loaded=!0;f.fanly.version='1.0';
y=a.createElement('script');y.async=!0;y.src=n;l=a.getElementsByTagName('script')[0];
l.parentNode.insertBefore(y,l);}(window,document,'https://engage.serve.fans/cheers.js');

fanly.init("Client-ID"); 

</script>
<noscript>
    <img height="1" width="1" style="display:none" src="https://serve.fans/pv1/engage.gif?clientId=Client-ID"/>
</noscript>
<!-- End Fanly Pixel Code -->
~~~~


That should be it, thanks for helping us serve your Fans!



