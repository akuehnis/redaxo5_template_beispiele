# redaxo5_tempalte_beispiele

## Artikel aufrufen und ausgeben

<?php
$article_id = 3;
$clang_id   = 2;
$art = new rex_article_content($article_id, $clang_id);
echo $art->getArticle();
?>
