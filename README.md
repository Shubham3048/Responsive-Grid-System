# Responsive-Grid-System

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
        <title>Grid System In Bootstrap</title>
        <style>
            .abhi{
                height: 1000px;
                border: 1px dashed blue;
            }
            .a_common{
                height: 200px;
            }
            .a_row_red{
                background: red;
            }
            .a_row_green{
                background: green;
            }
            .a1{
                border:1px dashed black;
            }
        </style>
    </head>
    <body>
        <div class="container-fluid abhi">
            <div class="row a_row_red a_common">
                <div class="col a1">Ant</div>
                <div class="col a1">Bee</div>
            </div>
            <div class="row a_row_green a_common">
                <div class="col-6 col-sm-1  bg-warning a1">Shubham</div>
                <div class="col-6 col-sm-1 bg-danger a1">Aadi</div>
            </div>
        </div>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
    </body>
</html>
