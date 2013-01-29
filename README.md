yii-cli-color
=============

Adding colors to console output



# YII CLI Color Class
A very simple, intuitive way to add color to your console

## class.jira.php

Quick example: (This will output red text in a white background)

<?php
echo Yii::app()->cliColor->getColoredString("Removing File: {$file}", 'red', 'white');
?>



