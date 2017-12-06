<!DOCTYPE html>
<html>
<head>
<link href="https://fonts.googleapis.com/css?family=Oswald|PT+Sans" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Catamaran|Fjalla+One" rel="stylesheet">
<title>8 Sustainable Restaurants in HK</title>
<link rel="stylesheet" type="text/css" href="HK.css">
</head>
       

    
<!--slide area-->
  <div class="mySlides fade">
    <div class="numbertext">1 / 3</div>
    <img src="slide1new.jpg" style="width:100%">
    <div class="text">阿麦厨房</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">2 / 3</div>
    <img src="slide2.jpg" style="width:100%">
    <div class="text">LIFE有机素食餐厅</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">3 / 3</div>
    <img src="slide4.jpg" style="width:100%">
    <div class="text">Simply Life</div>
  </div>

  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
</div>

<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}
function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>

    <div class="sign">
  <p>香港八大环保有机餐厅推荐</p>
</div>

<body>
    <p>如果你是一个乐活旅行者，香港还有不少注重环保、善用有机材料、能够在“可持续发展”与“色香味俱全”之间寻找平衡的有机餐厅，在自家菜园种的新鲜蔬菜，自种黄豆，自己腌制的豆腐。吃进的不但是美味和健康，更是厨师对食物与人的关怀。</p>

    <figure>
<img src="1a.jpg" alt="life">
    <figcaption>中环LIFE有机餐厅</figcaption>
  <img src="1b.jpg" alt="abc">
    <figcaption>中环LIFE有机餐厅的老板一直坚持倡导健康饮食，并定期举办相关环保的展览。</figcaption>
    <img src="1c.jpg" alt="salad">
    <figacaption>LIFE餐厅的招牌沙拉</figacaption>
    </figure>
    
<h2>LIFE有机素食餐厅</h2>
<p>作为香港有机饮食的先驱，LIFE有机素食餐厅的老板从离岛的嬉皮生活，一路迁到心脏地带的中环，为的是一直努力推动环境保护。餐厅楼高三层，一砖一瓦、一桌一椅都是从回收物料再造而来，难得的是装潢仍然保留着现代设计感。就素食餐厅来说，LIFE的选择可谓是城中最丰富的一家，除了从国外进口的有机食材，近年老板更积极与本地有机农场合作，让有机素食不再是外国人口味的代名词。</p>

    <figure>
<img src="2a.jpg" alt="阿麦厨房">
<figcaption>阿麦厨房</figcaption>
    </figure>
<h2>阿麦厨房</h2>
<p>阿麦厨房的概念来自阿麦书房，希望提供一个空间让人同时享受书香、音乐与咖啡香的理想。位于加路连山道这一个铜锣湾中比较清静的地方，以原木与鲜艳橙色墙壁打造的悠闲咖啡空间，是阿麦书店的延伸。餐厅提供精致健康的地中海菜式，素食的比例有7成，也特别预留了位置用于艺术展览及音乐会。</p>
    
 <figure>
<img src="3a.jpg" alt="robert">
    <figcaption>有机意大利面（organic pasta）</figcaption></figure>
<h2>Simply Life</h2>
<p>　这里提倡的是慢活、慢食，因此，每次出炉的面包都不会多过10个，以确保让每个面包入口时还是香脆新鲜。Simply Life还选择了单是浸泡就要用上三四小时的有机糙米饭，或是来一盘手工制作的意大利面，配上有机即磨咖啡。</p>
    
<figure>
 
<img src="4a.jpg" alt="rosemary">
     <figcaption>明茶房</figcaption>
    </figure>
<h2>明茶房</h2>
 <p>越来越注重养生养心的香港人，兴起了对传统中国茶的热潮。明茶房的宗旨是要将喝茶“生活化”，成为生活的一部分。店铺一层售卖各种茶叶与泡茶用品，二楼是环境清雅的茶吧，让人能够放慢生活的步伐，欣赏茶的清雅甘甜。</p>   
    
<figure>
<img src="5a.jpg" alt="4diner">
    <figcaption>100%有机的新鲜蔬菜沙拉</figcaption></figure>
<h2>Pearl有机花食</h2>
<p>Pearl是澳大利亚出名的餐饮品牌。澳大利亚人爱吃花，故一般的食用花都是采用有机耕种。出自Pearl的原创菜式“剑鱼生鲜汤”先用橄榄油浸泡从日本运来的深海剑鱼，再加上日本鱼子和意大利黑鱼子，淋过浓缩的血橙汁后，再洒上鲜艳的花朵──全部由澳大利亚空运到香港的新鲜食用花，伴着嫩滑的剑鱼，从嘴角渗来一股清香，像是一个欢迎春天的仪式。</p>

<figure>
<img src="6a.jpg" alt="南岛书虫">
   <figcaption>南岛书虫是南丫岛上一家开了十年的有机餐厅，这里的午后咖啡时光是离岛难得的享受。</figcaption></figure>
<h2>南岛书虫</h2>
<p>南岛书虫的老板从90年代已经开始在岛上提供有机咖啡和素食的南岛书虫，他对于天然无添加的食材坚持始终没变。由于本地有机农产业渐渐兴起，南岛书虫也加入了不少本地生产的食材，2008年初更尝试于后花园种植香草。</p>
   
     <figure>
<img src="7a.jpg" alt="峰寿司">
   <figcaption>100%有机沙拉</figcaption></figure>
<h2>峰寿司</h2>
<p>这家原本是日本知名寿司专门店，如今引进香港后的几年中，成为在香港最受欢迎的寿司店，店内的食材全部选用有机材料。八成以上寿司都由手工现场制作。</p>
    
     <figure>
<img src="8a.jpg" alt="Aqua餐厅">
   <figcaption>最适合欣赏美景的餐厅</figcaption></figure>
<h2>Aqua餐厅</h2>
<p>几乎整个尖沙咀最美的餐厅，以意大利菜及日本菜作主打。在这里，人们可以一边品尝美食，一边欣赏维港景色。主菜包括新意大利美食，如意大利马铃薯面配黄菌及巴马干酪，而坊间少有的软忌廉玉米糕配野菌也有供应。</p>
    
<p>For more information<a href="http://style.sina.com.cn/taste/restau/2008-05-23/104713602.shtml"> Please click here</a></p>
    <p>&copy; sina</p>
</body>

</html>
