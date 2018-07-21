
--------------------------------
2018 07 19 afternoon

DrawLines-DrawCircleUseRadious(val: Vector3)
其中
cir.ApplyMatrix(app.m_Editor.UCSMatrix); 
不理解对该方法的解释
“使用统一的方法设置对象的矩阵
需要对缩放矩阵进行重载，避免对象矩阵不是单位矩阵”

promise回调


---------------------------------
2018 07 20 afternoon
 
addEventListener

https://skyyen999.gitbooks.io/-study-design-pattern-in-java/content/singleton.html

单例模式：一开始我们就直接new出这个类别的实体物件，并且将constructor宣告为private，这样其他程式就无法再new出新物件，如此一来就能保证这个类别只会存在一个实体物件， 这种写法因为一开始就已经建立物件，因此也称为贪婪单例模式(Greed Singleton)。

并且，因为构造器已经private，需要另外提供方法让其他程式调用到这个单例。

观察者模式？

射线 raycaster 选择 获取从相机沿着鼠标的方向射去遇上的第一个物体 一般就是我们想操作的对象

 Three.js 中，是通過 OrbitControls.js API 來支持鼠標交互的，該 API 位於 Three.js 源代碼樹的 examples/js/controls 目錄。是可选的库，OrbitControls 的工作原理是在 3D 場景內與鼠標輸入一致地移動攝像機的位置

-----------------------------------
2018 07 21 morning

打包png 用的require是什么意思

promise 
异步

https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Statements/async_function

当调用一个 async 函数时，会返回一个 Promise 对象。当这个 async 函数返回一个值时，Promise 的 resolve 方法会负责传递这个值；当 async 函数抛出异常时，Promise 的 reject 方法也会传递这个异常值。

async 函数中可能会有 await 表达式，这会使 async 函数暂停执行，等待表达式中的 Promise 解析完成后继续执行 async 函数并返回解决结果。

    注意， await 关键字仅仅在 async function中有效。如果在 async function函数体外使用 await ，你只会得到一个语法错误（SyntaxError）。

