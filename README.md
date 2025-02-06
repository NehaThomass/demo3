<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Student Marks Card</title>

    <style>

        table {

            width: 50%;

            border-collapse: collapse;

            margin: 20px;

        }

        th, td {

            border: 1px solid #ddd;

            padding: 8px;

            text-align: left;

        }

        th {

            background-color: #f2f2f2;

        }

    </style>

</head>

<body>



<?php

$servername = "localhost";

$username = "root";

$password = "";

$dbname = "student";

// Create connection

$conn = new mysqli($servername, $username, $password, $dbname);



// Check connection

if ($conn->connect_error) {

    die("Connection failed: " . $conn->connect_error);

}

