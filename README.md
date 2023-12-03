﻿# Table-and-list-by-using-div-tag
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Table and list</title>
    <style>
        .container{
            display: table;
            width: 90%;
            border-collapse: collapse;
        }
        .heading{
            font-weight: bold;
            display: table-row;
            background-color: grey;
            text-align: center;line-height: 25px;
            font-size: 14px;
            font-family: Georgia, 'Times New Roman', Times, serif;
            color: #fff;
        }
        .table-row{
            display: table-row;
            text-align: center;
        }
        .col {
            display: table-cell;
        }
        .col{
            display: table-cell;
            border: 1px solid;#ccc
        }

            </style>
</head>
<body>
   <div class="container">
    <div class="heading">
        <div class="col">Name on credit</div>
        <div class="col">Credit card number</div>
        <div class="col"> Expiration</div>
        <div class="col">Cvv</div>
    </div>
    <div class="table-row">
        <div class="col">Abhishek singh</div>
        <div class="col">1122335513</div>
        <div class="col">5/2025</div>
        <div>1234</div>
    </div>
    <div class="table-row">
        <div class="col">Rohan</div>
        <div class="col"> 52642425</div>
        <div class="col">6/2026</div>
        <div class="col">9285</div>
    </div>
   </div>  
   <button>Click here to continue</button>
</body>
</html>
