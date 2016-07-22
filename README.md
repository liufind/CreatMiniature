#生成多种类型的缩略图

####类名：CreatMiniature

###基本参数：

* $srcFile

* $echoType

###方法用到的参数：

* $toFile,生成的文件

* $toW,生成的宽 

* $toH,生成的高

* $bk1,背景颜色参数 以255为最高

* $bk2,背景颜色参数 

* $bk3,背景颜色参数

### 例子:
`include('thumb.php');

 $cm=new CreatMiniature();

 $cm->SetVar('1.jpg','file');

 $cm->Distortion('dis_bei.jpg',150,200);

 $cm->Prorate('pro_bei.jpg',150,200);//附带切割

 $cm->Cut('cut_bei.jpg',150,200);
 
 $cm->BackFill('fill_bei.jpg',150,200);`

