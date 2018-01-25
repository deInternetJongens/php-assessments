# PHP Assessments

## 1. File Owners
Implement a groupByOwners function that:

Accepts an associative array containing the file owner name for each file name.
Returns an associative array containing an array of file names for each owner name, in any order.
For example, for associative array ["Input.txt" => "Randy", "Code.py" => "Stan", "Output.txt" => "Randy"] the groupByOwners function should return ["Randy" => ["Input.txt", "Output.txt"], "Stan" => ["Code.py"]].


```
<?php
class FileOwners
{
    public function groupByOwners($files)
    {
        return NULL;
    }
}

$files = array
(
    "Input.txt" => "Randy",
    "Code.py" => "Stan",
    "Output.txt" => "Randy"
);
$fileOwners = new FileOwners();
var_dump($fileOwners->groupByOwners($files));
```