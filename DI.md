## value  
> value是一个简单的javascript对象,用于控制器传递值（ 配置阶段 ）  
## factory  
> factory是一个函数用于返回值。在service和controller需要时创建。  
  通常我们使用factory函数来计算或返回值。
## service  
> 
## provider  
> angularJS中通过provider创建一个service、factory等（配置阶段）。
Provider中提供了一个factory方法get()，它用于返回value/service/factory.
## constant  
> constant(常量)用来在配置阶段传递数字，注意这个常量在配置阶段是不可用的。
