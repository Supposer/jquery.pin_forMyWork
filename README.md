jquery.pin_forMyWork
====================

jquery.pin_forMyWork

完全基于..https://github.com/webpop/jquery.pin..作修改以适应自身项目..

https://github.com/webpop/jquery.pin..由于在浏览器中部刷新后..父容器到浏览器顶部的高度为0..导致pin超出containerSelector..

所以,修改pin超出containerSelector的处理方法,不采用top控制,改用bottom: "0px"控制

但缺点是需要修改外部CSS作配合,

pin的父容器不允许position: relative;,

但是,pin的最高级父容器需要position: relative;,
