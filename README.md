# js-toast
无依赖toast效果

# How To Use

toast("你好");//默认2s
toast("你好",5000);
toast("你好",function(){
  console.log("执行完毕!");
});
toast("你好",5000,function(){
  console.log("执行完毕!");
});
