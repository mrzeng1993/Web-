# 记录前端学习掌握的要点,包括HTML，CSS，JavaScript
***
## HTML
***
## CSS
### css样式自动换行（强制换行）
自动换行问题,正常字符的换行是比较合理的,而连续的数字和英文字符常常将容器撑大,挺让人头疼,下面介绍的是CSS如何实现换行的方法对于div,p等块级元素,正常文字的换行(亚洲文字和非亚洲文字)元素拥有默认的 white-space:normal ,当定义的宽度之后自动换行
'''
html:
  <div id="wrap">正常文字的换行(亚洲文字和非亚洲文字)元素拥有默认的white-space:normal,当定义</div>
  css:
  #wrap{white-space:normal; width:200px; }
'''
