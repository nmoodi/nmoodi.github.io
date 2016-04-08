---
layout: post
title:  "معرفی Jquery"

date:   2016-04-06 21:45:15 +0430
categories: jekyll update
---

jQuery یکی از کتابخانه ها یا framework های پرطرفدار JavaScript است .

jQuery به معنای واقعی، برنامه نویسی JavaScript را آسان کرده است .
یادگیری jQuery ، آسان است و از آموزش آن لذت خواهید برد .
در هر فصل برای آموزش بهتر مطالب از مثال های فراوانی استفاده شده است.
نمونه:

 {% raw %}
    <!DOCTYPE html>
	<html>
	<head>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script> 
	<script> 
	$(document).ready(function () {
	$("p").click(function () { 
	$(this).hide();
	});
	});
	</script> 
	</head>
	<body>
	<p>If you click on me, I will disappear.</p>
	<p>Click me away!</p>
	<p>Click me too!</p>
	</body> 
	</html>
    {% endraw %}

 
 <b>پیش نیازهای یادگیری jQUERY:</b>
 
 پیش از پرداختن به یادگیری این مبحث، بایستی یک سری اطلاعات پایه ای، در خصوص موارد زیر داشته
باشید:

آموزش HTML

آموزش CSS

آموزش JavaScrip
 
 