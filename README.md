# adtask18-waterfall-news
注意点：
1、当li绝对定位时，ul高度塌陷
imgWaterfall.height(Math.min.apply(null,nodeArr));//解决ul元素高度塌陷的问题
2、 var $nodes=$(html);
      imgWaterfall.append($nodes);
      return $nodes;
使用 return($html)会出现问题
