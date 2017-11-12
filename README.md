# Httplib
php的网页请求类，非本人所写，只是为了composer依赖。才放出仓库里的

# Composer.josn

#### "require": {"fps2tao/httplib": "dev-master"}

#### "autoload": {"psr-4": {"Http\\Httplib\\":"vendor/fps2tao/httplib/src/"}}

# Example
	$url = "http://www.xx.com";

	$http = new \Http\Httplib($url);

	$http->send();

	$webHtml = $http->response();

	echo $webHtml;
	

	...