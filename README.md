JSwitchable
===========

a greate jquery plugin wrapper for yii community,you can easily do image switching

usage:
-----------
download it and extract to extension dir (or any other directory ), then  in your view or layout files:
<?php
$this->widget('ext.widgets.jswitchable.JSwitchable', array(
));
?>


## Basic Markup Structure

    <div id="container">
      <div>First Panel</div>
      <div>Second Panel</div>
      <div>Third Panel</div>
    </div>


## Initialize Switchable

    <script>
    $(function(){
      $('#container').switchable();
    });
    </script>
