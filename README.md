# PDF Flipbook

https://pdfflipbook.vercel.app - Demo

## FAQ

# Documentation


# File Structure

This flipbook plugin is jQuery based. Basically you can copy the files in folder to your working directory. You don't need to include the lib folder..

```
lib/ 
    ├── css/
    │   ├── dflip.css
    │   └── themify-icons.css
    │
    ├── fonts/
    │   ├── themify.eot
    │   ├── themify.svg
    │   ├── themify.ttf
    │   └── themify.woff
    │
    ├── images/
    │   └── loading.gif
    |
    ├── sound/
    │   └── turn2.mp3
    │
    └── js/
        ├── dflip.js
        ├── dflip.min.js
        └── libs/
            ├── jquery.min.js
            ├── pdf.min.js
            ├── pdf.worker.min.js
            ├── three.min.js
            └── mockup.min.js

}
```

## File Template
And ensure the following files are included in the html.

CSS:
```
            
                <!-- Flipbook StyleSheet -->
                <link href="http://www.yoursite.com/dflip/css/dflip.css" rel="stylesheet" type="text/css">

                <!-- Icons Stylesheet -->
                <link href="http://www.yoursite.com/dflip/css/themify-icons.css" rel="stylesheet" type="text/css">
            
        
```
JavaScript:

Note: Include them just before </body> tag. Don't use them in head.

```
            
<!-- jQuery 1.9.1 or above -->
<script src="http://www.yoursite.com/dflip/js/libs/jquery.min.js" type="text/javascript"></script>

<!-- Flipbook main Js file -->
<script src="http://www.yoursite.com/dflip/js/dflip.min.js" type="text/javascript"></script>
            
        
```
Basic HTML Template
```

    <html>
    <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Basic HTML Template</title>

    <!-- Flipbook StyleSheet -->
    <link href="http://www.yoursite.com/dflip/css/dflip.css" rel="stylesheet" type="text/css">

    <!-- Icons Stylesheet -->
    <link href="http://www.yoursite.com/dflip/css/themify-icons.css" rel="stylesheet" type="text/css">

    </head>
    <body>
    <div class="_df_thumb" id="df_manual_thumb" source="location of pdf.pdf" thumb="location of thumbnail.jpg"> PDF Example</div >
    <!-- Refer to other examples on how to create different types of flipbook -->

    <!-- jQuery 1.9.1 or above -->
    <script src="http://www.yoursite.com/dflip/js/libs/jquery.min.js" type="text/javascript"></script>

    <!-- Flipbook main Js file -->
    <script src="http://www.yoursite.com/dflip/js/dflip.min.js" type="text/javascript"></script>

    </body>
    </html>
```
Create Flipbook through Button lightbox.
```
<div class="_df_button"
    source="http://www.yoursite.com/books/dflip manual.pdf"
    id="df_manual_button">
    Button
</div>
```
## Acknowledgements

 - [Dflip]()


## Authors

- [@HiIamChaitanya](https://www.github.com/HiIamChaitanya)



# flipbook pages are not visible/defect in PDF
check pdf if using link make sure that cross-origin resource sharing is enabled 

-----
