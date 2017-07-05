### 路由设置对象
AngularJS 路由可以通过不同的模板来实现。
$routeProvider.when函数的第一个参数是URL或者URL正则规则，第二个参数为路由配置对象。
路由配置对象语法规则如下：
***
<pre>

$routeProvider.when(url, {
    template: string,
    templateUrl: string,
    controller: string, function 或 array,
    controllerAs: string,
    redirectTo:string, function,
    resolve: object<key, function>
});
</pre>

### 参数说明：
** 1. template:** 
如果我们只需要在ng-view中插入简单的HTML内容，则使用该参数：*    

 ** 2. templateUrl: **
如果我们只需要在ng-view中插入HTML模板文件，则使用该参数  
<pre>
  $routeProvider.when('/computers', {
    templateUrl:'views/computers.html', 
  });
</pre>  
** 3. controller: **
   function、string或数组类型，在当前模板上执行的controller函数，生成新的scope.  
** 4. controllerAs: ** 
   string类型，为controller指定别名。  
 ** 5. redirectTo:**  
   重定向的地址。  
** 6. resolve: **  
   指定当前controller所依赖的其他模块  
