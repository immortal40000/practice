# practice
```
<?php

function vertMirror($array) {
$result = '';
  
  foreach($array as $val){
    $result .= strrev($val) . "\n";
}
  echo $result;
}

  function horMirror($array) {
    $arrReverse = array_reverse($array);
    print_r(implode("\n",$arrReverse));
}

$array = array("abcd", "efgh", "ijkl", "mnop");
vertMirror($array);
echo "\n";
horMirror($array);
```
