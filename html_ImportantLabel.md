#  a 标签的用法

     <a href="https://baidu.com">补充HTTPS网址</a>
   
    <a href="//google.com">补充斜杠网址</a>
    
    <a href="javascript:alert(我是a标签的js伪协议弹窗);">js伪协议</a>
    
    <a href="mailto:me_menglu@163.com">发送邮件（伪协议）</a>
   
    <a href="tel:18538714660">拨打电话伪协议</a>
    
    <a href="#xxx">内部锚点定位</a>
    <p>1</p>
    <p>2</p>
    <p>2</p>
    <p>2</p>
    <p>2</p>
    <p>2</p>
    <p>2</p>
    <p>2</p>
    <p>2</p>
    <p>2</p>
    <p>2</p>
    <p>2</p>
    <p>2</p>
    <p>2</p>
    <p>2</p>
    <p>2</p>
    <p>2</p>
    <p id="xxx">3(我是内部标签定位点)</p>

    <a href="https://baiducom"target="_blank">新标签页打开</a>
   <iframe src="" frameborder="0">
<a href="sekuai.html" >sekuan  </a>
<a href= "2.html"  target="_top">top色块</a>
</iframe>
```

#  img 标签的用法
    <img src="img/1615535168288.jpg" alt="" width="30px" height="20px">


# table 标签的用法


    <table >
    <thead><!--表头-->
    <tr><!--一行-->
    <th></th>
    <th>周一</th>
    <th>周二</th>
    <th>周三</th>
    <th>周四</th>
    <th>周五</th>
    </tr><!--一行-->
    </thead><!--表头-->

    <tbody><!--表内容-->
    <tr>
    <th>9:00-10:00</th>
    <th>英语</th>
    <th>英语</th>
    <th>数学</th>
    <th>语文</th>
    <th>科学</th>
    </tr>

    <tr>
    <th>10:00-11:00</th>
    <th>英语</th>
    <th>英语</th>
    <th>数学</th>
    <th>语文</th>
    <th>科学</th>
    </tr>

    <tr>
    <th>11:00-12:00</th>
    <th>英语</th>
    <th>英语</th>
    <th>数学</th>
    <th>语文</th>
    <th>科学</th>
    </tr>

    </tbody><!--表内容-->

    <tfoot><!--表尾-->
    <tr>
    <th>总计</th>
    <th>6</th>
    <th>8</th>
    <th>0</th>
    <th>1</th>
    <th>1</th>
    </tr>
    </tfoot><!--表尾-->
    
    </table>

    <style>
        table tr th{ border: 1px solid red ;}
        table{border-spacing: 0px;border-collapse: collapse }  
     </style>

    <!--表格-->


# 表单的用法
    <!--表单-->

    <form action="http://www.baidu.com"      method="POST">

    <!--单行文本-->
    <input type="text" name="用户名" placeholder="    请输入用户名">
    <!--单行文本-->
    
    <!--密码框-->
    <input type="password" name="密码"     placeholder="请输入密码">
    <!--密码框-->

    <!--单选/-->
        <label></label><input type="radio" name="sex"         value="1">男</label>
        <label></label><input type="radio" name="sex"         value="1">女</label>
        <!--单选-->
        
        <!--多选/-->
        <label></label><input type="checkbox"         name="sex" value="1">米饭</label>
        <label></label><input type="checkbox"         name="sex" value="1">青菜</label>
        <label></label><input type="checkbox"         name="sex" value="1">土豆</label>
        <label></label><input type="checkbox"         name="sex" value="1">洋葱</label>
        <!--多选-->

    <!--上传文件form表单上需增加 enctype="multipart/    form-data"-->
    <input type="file" >
    <!--上传文件-->
    
    <!--定义提交按钮-->
    <input type="submit" value="提交" >
    <!--定义提交按钮-->

    <!--定义重置按钮-->
    <input type="reset" value="重置" >
    <!--定义重置按钮-->

    <!--定义普通按钮-->
    <input type="reset" value="确定" >
    <!--定义普通按钮-->
    
    <!--多行文本-->
    <textarea name="text" rows="30" cols="40" placeholder="请输入文本"></textarea>
    <!--多行文本-->


    <!--下拉列表-->
    <select name="city" id="">
    <option value="hz" selected>河南</option><!--selected表示默认选项-->
    <option value="hz">上海</option>
    <optgroup><!--分组-->
    <option value="hz">河北</option>
    <option value="hz">海口</option>
    </optgroup>
    </select>
    <!--下拉列表-->

    <!--label 鼠标移到姓名上出输入框-->
    <label for="www">姓名</label>
    <input id="www" type="text">
    <!--label 鼠标移到姓名上出输入框-->

    <fieldset>
    <legend>登录吧</legend>
    <input type="text">
    </fieldset>

    </form>
    <!--表单-->


手敲代码，得认真细致.认真再认真