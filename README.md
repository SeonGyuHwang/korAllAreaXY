https://github.com/SeonGyuHwang/korAllAreaXY


&lt;script src="경로/korAllAreaXY.mix.js"&gt;&lt;/script&gt;<br/>
&lt;script type="text/javascript"&gt;<br/>
　getArea.setSido("서울특별시"); <br/>
　var mapObj = getArea.getObj(); <br/><br/>
　 
　// mapObj.lng : lng 값 <br/>
　// mapObj.lat : lat 값 <br/>
　// mapObj.zoom : zoom 값 <br/><br/>

　// 만일 입력된 시/도가 없으면 null 을 리턴합니다. <br/>
　// 시/군/구 가 필요할경우 아래처럼 하시면 됩니다. <br/><br/>

　var gugun = mapObj['강남구']<br/>
&lt;/script&gt;　
