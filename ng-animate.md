
## ngAnimate做了什么  

ngAnimate 模型可以添加移除class。  
ngAnimate 模型并不能使HTML元素产生动画，但是ngAnimate会检测事件，
类似隐藏显示HTML元素，如果事件发生ngAnimate就会使用预定义的class来
设置HTML元素的动画。  

AngularJS添加/移除class的指令;  
- ng-show 
- ng-hide    
- ng-class  
- ng-view  
- ng-include  
- ng-repeat  
- ng-if  
- ng-switch  
ng-show和ng-hide指令用于添加或移除 ng-hide class的值。
当HTML元素位置改变时，ng-repeat指令同样可以添加ng-move类。
此外，在动画完成后，HTML元素的类集合被移除。例如：ng-hide指令会添加一下类：
ng-animate  
ng-hide-animate  
ng-hide-add (如果元素将被隐藏)
ng-hide-remove(如果元素将显示)
ng-hide-add-active(如果元素将隐藏)
ng-hide-remove-active(如果元素将显示)

