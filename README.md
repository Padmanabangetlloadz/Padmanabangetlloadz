<?php
$servername = "localhost";
$username = "getl_loadz";
$password = "tz1LDAoP8y!lLmKl";

// Create connection
$conn = new mysqli($servername, $username, $password);

// Check connection
if ($conn->connect_error) {
  die("Connection failed: " . $conn->connect_error);
}
echo "Connected successfully";
?>
