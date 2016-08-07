<?php
/*************************************************
 * Micro News
 *
 * Version: 1.0
 * Date: 2007-07-12
 *
 * Usage:
 *
 ****************************************************/

// This function reads all available news
function getNewsList(){
	
   $fileList = array();
   
	// Open the actual directory
	if ($handle = opendir("news")) {
		// Read all file from the actual directory
		while ($file = readdir($handle))  {
		    if (!is_dir($file)) {
		       $fileList[] = $file;
      	}
		}
	}	
	
	rsort($fileList);
	
	return $fileList;
}

?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "DTD/xhtml1-transitional.dtd">
<html>
<head>
   <title>Micro News</title>
   <link href="style/style.css" rel="stylesheet" type="text/css" />
</head>
<body>
  <div id="main">
    <div id="caption">Micro News</div>
    <table width="100%">
    <?php
    
      $list = getNewsList();
      foreach ($list as $value) {
      	$newsData = file("news/".$value);
      	$newsTitle  = $newsData[0];
         $submitDate = $newsData[1];	
         unset ($newsData['0']);
         unset ($newsData['1']);
      	
         $newsContent = "";
         foreach ($newsData as $value) {
    	       $newsContent .= $value;
         }
      	
      	echo "<tr><th align='left'>$newsTitle</th><th align='right'>$submitDate</th></tr>";
      	echo "<tr><td colspan='2'>".$newsContent."<br/><hr size='1'/></td></tr>";
      }
    ?>
    </table>
	 <div id="source">Micro News 1.0</div>
  </div>
</body>   
