# Javascriptit
# Javascriptit
# Javascriptit
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Positioning Items</title>
    <meta charset="UTF-8">
    <style>

        /*////////////////////
        // Positioning items
        //////////////////////

        Reset *
        Display: inline vs block
        https://www.w3schools.com/cssref/pr_class_display.asp

        Box-sizing
        https://www.w3schools.com/css/css3_box-sizing.asp

        Using percentages and max-width
        https://www.w3schools.com/cssref/css_units.asp

        Float and clear
        https://www.w3schools.com/cssref/pr_class_float.asp

        Flexbox - https://www.w3schools.com/css/css3_flexbox.asp

        Absolute/Relative positioning
        https://www.w3schools.com/cssref/pr_class_position.asp

        Centering
        https://www.w3schools.com/css/css_align.asp

        overflow:hidden jos menee yli se korjaa tuon värin
        margin

        */

        * {
            /*margin: 0;
            padding: 0;*/

        }

        body {

        }

        .box {
            display: block;
            height: 100px;
            width: 100px;
            border: 10px solid #b3d4fc;
            color: #b3d4fc;
            box-sizing: border-box;

        }

        #red { background-color: red;}
        #green { background-color: green;}
        #blue { background-color: blue;}
        #yellow { background-color: yellow; color: black;}
        #orange { background-color: orange;}


        .clear { clear: both;}

        /* img */
        img {
            width: 50%;

            
        }

        /* container */
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            background-color: #b3d4fc;
            text-shadow: none;
            overflow: hidden;
            margin: auto;
        }

        /* relative and absolute positioning with blue */
        #blue {
        }

        h1{

        }

    </style>


</head>
<body>
<div class="container">


<div class="box" id="red">Box 1</div>
<div class="box" id="green">Box 2</div>
<div class="box" id="blue">Box 3</div>
<div class="box" id="yellow">Box 4</div>
<div class="box" id="orange">Box 5</div>
</div>


<!-- Float continues, clearing -->

<h1>Heading 1</h1><h1>Heading 2</h1>

<!-- Responsive images and centering -->
<img src="maisema+(9).jpeg">


</body>
</html>
