# jquery.limarquee
github repository http://masscode.ru/index.php/k2/item/44-limarquee

#use age
 <div class="container">
   <ul>
     <li>信息内容一</li>
     <li>信息内容二</li>
   </ul>
 </div>

 方法：
 import Limarquee from 'limarquee'
const limarquee = new Limarquee('.container')
limarquee.render({
  direction: left	// 滚动方向，可选 left / right / up / down
  loop:	-1	      // 循环次数，-1 为无限循环
  scrolldelay:	0	// 每次重复之前的延迟
  scrollamount:	50	// 滚动速度，越大越快
  circular:	true	// 无缝滚动，如果为 false， 则和 marquee 效果一样
  drag: true	    // 鼠标可拖动
  runshort:	true	// 内容不足是否滚动
  hoverstop: true	// 鼠标悬停暂停
  xml: false	    // 加载 xml 文件
  inverthover: false	// 反向，即默认不滚动，鼠 标悬停滚动
})
