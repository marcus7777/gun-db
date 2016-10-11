# \<gun-db\>

webcomponent for GunDB

## Yeah Webcomponents 

GunDB as a webcomponent `gun-db`. Use GunDb without writing any javascript.

####Bower
```
bower install gun-db --save
```

Then in your html
```
<head>
...
<link rel="import" href="bower_components/guntagger/chain-guntagger.html">
...
</head>
<body>
 <gun-db></gun-db>

 </body>
```

need peers ? ( one string,  comma seperated urls)
```
<gun-db peers="http:<myServerUrl1>/gun,http:<myServerUrl2>/gun"></gun-db>
```

need to chain stuff ?
just add the name of the module as an attribute 
```
 <gun-db guntagger></gun-db>
```
i have gun modules as components also...only 
'guntagger' at the moment https://github.com/Stefdv/guntagger)

## Why?
First of all...i like Polymer. And i have a gun-ui-library that i want to publish. They have some dependencies ( Gun.js for instance ) . i Just want to make sure that the setup is painless.