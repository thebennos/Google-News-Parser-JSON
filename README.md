Google-News-Parser-JSON
=======================

Google News Parser JSON

###Basic usage

```  
<?php
include('news.php');
$news = new GoogleNews();
echo $news->getNews();
?>  
```  
###More than basic usage :P

```  
<?php
include('news.php');
$news = new GoogleNews();
$news->setSearchQuery('Bangladesh');
$news->setNumberOfNews('10');
echo $news->getNews();
?>  
```
