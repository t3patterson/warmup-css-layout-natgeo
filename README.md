#CSS Layout - Warmup

### Mockup
![mockup](./mockups/nat-geo-layout-mockup.png)

### Setup


#####(1) Get the files

```sh
cd ~/TIY/warmups
curl https://raw.githubusercontent.com/t3warmups/warmup-css-layout-natgeo/master/warmup-files.zip > warmup-files.zip
unzip warmup-files.zip
cd warmup-css-layout-natgeo
```

#####(2) Get the fontawesome icon set
Note: you will have to add the fontawesome icons to the `index.html` file.

Link to Icons: http://fontawesome.io/icons/

1. Link to it in the `<head>` of your HTML.
  - *Note:* make sure you link to fontawesome *on the line before your `style.css` link*
  ```
  <head>
     …
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="./css/style.css">
  </head>
  ```

2. Reference the icons in your HTML's `<body>` 
  ```
  <i class="fa fa-facebook" aria-hidden="true"></i>
  ```



