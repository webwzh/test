1.将两个字符利用字符串对象的方法变成一个字符,显示在页面id为h1的元素中
答:     var p = document.getElementById('h1')
    var str = "字符1";
    p.innerHTML=str.concat('字符2')

2.一个富豪想存87万,给理财顾问写了87w,请自动生成存储870000的方法,显示在页面id为h2的元素中
答:var p = document.getElementById('h2')
 var num = '870000';
 p.innerHTML= num;

3.一个数字79387.348的工程款,保留两位小数存入,显示在页面id为h3的元素中
答: var p = document.getElementById('h3')
 var num = 79387.348;
 p.innerHTML= num.toFixed(2);

4.一张图片是一个相对路径img/head/icon/1.jpg,我只需要拿到它的文件夹目录后显示在页面id为h4的元素中
答:var p = document.getElementById('h4');
          var img = document.getElementById('img');
          p.innerHTML=img.src;

5.用户输入验证码,无论大小写输入都会正确的方法,显示在页面id为h1的元素中,显示在页面id为h5的元素中
答:
var inpt = document.getElementById('inpt');
       toupperCase = inpt.value;