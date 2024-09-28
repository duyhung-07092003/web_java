<%-- 
    Document   : trangchu
    Created on : Sep 28, 2024, 2:34:16 PM
    Author     : hamva
--%>

<%@page contentType="text/html" pageEncoding="UTF-8"%>
<!DOCTYPE html>
<html>
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
        <title>Trang Chủ</title>
        <link rel="icon" href="./img/anhchup.jpg"/>
        <style>
            body,html{
                background: lightblue;
                
            }
        </style>
    </head>
    <body>
        <h1 style="text-align: center; color:blue;">Tổng Hiệu Tích Thương</h1>
        <%! int a = 12,b =4;%>
        <h1 style="color: red; text-align: center; ">
        <%
            out.println("Tổng :"+ a +"+"+b +"=" +(a+b));
        %>
        </h1>
        <h1 style="color: yellow;text-align: center;">
        <%
            out.println("Hiệu: "+ a +"-"+b +"=" +(a-b));
        %>
        </h1>
         <h1 style="color: green;text-align: center;">
        <%
            out.println("Thương:" + a +"/"+b +"=" +(a/b));
        %>
        </h1>
        <h1 style="color: aqua;text-align: center;">
        <%
            out.println("Tích:" + a +"*"+b +"=" +(a*b));
        %>
        </h1>
    </body>
</html>
