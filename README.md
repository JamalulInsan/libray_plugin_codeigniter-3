# libray_plugin_codeigniter-3
you  can load resource another like js and css so easay , can load anther page css and js

how you started so easy follow :
#1. copy Plugin.php to folder application/library/
#2. setting you resource css and javascript on metho function same name
exmple:

$css['Boostrap 3.1.1']='your resoure path';
$js ['Boostrap 3.1.1']='your resource path
#3. load libray can load with autoload and you can load on controller 

if you want load css like this

#<?php $this->plugin->vendor('css',['Boostrap 3.1.1','dataTables 1.2'])->html() ?>
if you want load javacript like this

#<?php $this->plugin->vendor('js',['Boostrap 3.1.1','dataTables 1.2'])->html() ?>
return echo $thml;

if you want debug , can use like this:
$debug=$this->plugin->vendor('js',['Boostrap 3.1.1','dataTables 1.2'])->result()
// return array 

var_dump($debug)


:) 
