# loading-modal
封装好的弹出加载层loading。。。可直接调用
如果你想要的是一个等待加载的家伙，这无疑是第一选择，不浪费资源，重用性高
你只需要在请求ajax之前 $.mask_element('#id'); //打开加载层,seccess之后 $.mask_close('#test_mask');//关闭加载层
