<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.2/dist/js/bootstrap.bundle.min.js"></script>
    <title>Document</title>
</head>
<body>

    <div class="offcanvas offcanvas-start" id="demo">
        <div class="offcanvas-header">
            <h1 class="offcanvas-title">
                ini Header
            </h1>
            <button type="button" class="btn-close" data-bs-dismiss="offcanvas"></button>
        </div>
        <div class="offcanvas-body">
            <p>Some Text</p>
            <p>Some Text</p>
            <p>Some Text</p>
            <button type="button" class="btn btn-danger float-end" data-bs-dismiss="offcanvas">Close</button>
        </div>
    </div>
    <button type="button" class="btn btn-danger mt-3 ms-3 p-2" data-bs-toggle="offcanvas" data-bs-target="#demo">
        Ajimas
    </button>

</body>
</html>
