
$if(toc)$
$if(toc-title)$
# $toc-title$
$endif$

$toc$

$endif$

$for(header-includes)$
$header-includes$

$endfor$
$for(include-before)$
$include-before$

$endfor$
$if(toc)$
$toc$

$endif$
$body$
$for(include-after)$

$include-after$
$endfor$
