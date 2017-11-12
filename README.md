# Httplib
php的网页请求类，非本人所写，只是为了composer依赖。才放出仓库里的

#example
	$url = "http://www.xx.com";
	$http = new \Httplib($url);
	$http->send();
	$webHtml = $http->response();
	echo $webHtml;

	...