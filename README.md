# icon-background-color-change-hover
Creating good user experiences means clearly defining items that are links or otherwise clickable; if using icons, one way to do that is to change the background color and the icon color on hover.

## Tutorial
For detailed instruction's, view Solodev's [How to Change Icon Colors and Background Colors on Hover](https://www.solodev.com/blog/web-design/how-to-change-icon-colors-and-background-colors-on-hover.stml) article.

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/zv24ufcr/).

## HTML

The tutorial contains the following basic HTML markup.

```
  <div class="col-md-8 col-md-push-8 container">
        <div class="ct-icon-boxes">
            <div class="ct-icon-box top-left" onclick="location.href='#'">
                <div class="inner">
                    <div class="ct-icon-box__icon">
                        <i class="fa fa-newspaper-o fa-4x" aria-hidden="true"></i>
                    </div>
                    <h3 class="ct-icon-box__header mt-3 font-weight-bold">
                        News
                    </h3>
                </div>
            </div>
            <div class="ct-icon-box top-right" onclick="location.href='#'">
                <div class="inner">
                    <div class="ct-icon-box__icon">
                        <i class="fa fa-calendar fa-4x" aria-hidden="true"></i>
                    </div>
                    <h3 class="ct-icon-box__header mt-3 font-weight-bold">
                        Events
                    </h3>
                </div>
            </div>
            <div class="ct-icon-box bottom-all" onclick="location.href='#'">
                <div class="inner">
                    <div class="ct-icon-box__icon">
                        <i class="fa fa-picture-o fa-4x" aria-hidden="true"></i>
                    </div>
                    <h3 class="ct-icon-box__header mt-3 font-weight-bold">
                        Gallery
                    </h3>
                </div>
            </div>
        </div>
    </div>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js"></script>
<script src="https://use.fontawesome.com/948cc87750.js"></script>
```
