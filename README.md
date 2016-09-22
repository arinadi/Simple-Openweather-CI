# Simple-Openweather-CI
See the current weather with PHP
CodeIgniter 3 + Openweathermap

# Install
Paste all folder to your CI application/ folder.

# Usage
***Call Modal***
```PHP
<?php
$this->load->model('M_weather'); ?>
```
***Send variabel city to model***
```PHP
<?php
$city="Yogyakarta";

$data="$this->M_weather->get($city)"; //array ?>
```
***Use to View***
```PHP
The weather of <?=$data['name']?> at <?=date("d M Y")?> is <?=$data2['weather'][0]['main']?>
```
