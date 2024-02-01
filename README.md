
# web eSheep
Can you remember the nice sheep from the '90 years?<br />[![eSheep for 64bit systems](https://img.youtube.com/vi/xN90p16tKGE/0.jpg)](https://www.youtube.com/watch?v=xN90p16tKGE)

```javascript
<head>
...
<script src="https://YOURURL/vendor/web-esheep/dist/esheep.min.js"></script>
</head>
<body>
...
<script>
var sheep = new eSheep(); 
sheep.Start(); 
</script>
</body>
```


### And now?
Check out the demo, to see how integrate it in your webpage:
[https://adrianotiger.github.io/web-esheep/samples/](https://adrianotiger.github.io/web-esheep/samples/)

If you want create your animation, you can use the editor or find some other already-created animations on the webpage: [ehseep.petrucci.ch](http://esheep.petrucci.ch)

### Tampermonkey script
Do you have Firefox, Chrome, Opera or Edge? Add this sheep to Google and Bing search machines over this simple Tampermonkey script:
[esheep.user.js]

### Credits
**Tatsutoshi Nomura** is the creator of the esheep and designed it for Fuji Television. This is only a copy, using some images found in the web.

# Build GitHub project
eSheep uses `composer` to build it. 

### Set up build environment  
into vendor/composer.json
{
  "require": {
  "torayld/web-esheep": "dev-master",
  },
  "repositories": [
    {
      "type": "vcs",
      "url" : "https://github.com/Torayld/web-esheep.git"
    }
  ]
}

update project `composer update`
