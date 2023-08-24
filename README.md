# vql-javascript-library
Library for customers to integrate the Vql feature on their website.


# How to use
```
...
<div class="sharering-query" queryId="641275f07cd216005d5481cc" mode="dynamic" qrcodeOwner="shareledger1fja6aazgvw6zfrh59xjc6w0jdpfhdkharz72lr" app="Identifi Me" oninit="onInit" onscan="onScan">
  <div class="qrcode-content">
      <div id="qrcode"></div>
  </div>
</div>
...
<script src="https://raw.githack.com/ShareRing/vql-javascript-library/master/sharering.query.lib.prod.min.js" crossorigin="anonymous"></script>
<script>
  function onScan(data){
    //do something with the result
  }
  function onInit(data){
    console.log('onInit', data);
  }
</script>
```

QueryID = ID of the query from the VQL dashboard

QRCode owner = ShareLedger account linked to the VQL creator

