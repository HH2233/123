# myapp
个人信息系统demo

### 安装依赖
    npm i
### 运行
    node app.js
### php

<?php
header("Access-Control-Allow-Origin : http://10.30.29.76:63341");
header("Access-Control-Allow-Credentials : true");
header('Access-Control-Allow-Headers : Content-Type');

//echo '{"userName":"123"}';
$data=array("userName"=>"123hw");
echo json_encode($data);
?>
