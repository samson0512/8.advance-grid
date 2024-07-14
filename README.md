# 8.advance-grid
## program:
```
<!DOCTYPE html>
<html>
  <head>
    <title>grid area</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    
        <div class="content">
      <div class="item1">1</div>
      <div class="item2">2</div>
      <div class="item3">3</div>
      <div class="item4">
        <div class="nestest">
          <div class="item">1</div>
          <div class="item">2</div>
          <div class="item">3</div>
          <div class="item">4</div>
        </div>
      </div>
      <div class="item5">4</div>
      <div class="item6">5</div>
      </div>
      
  </body>
</html>
body{
  padding:0;
  margin:0;
  font-family:Arial;
  
  
}
.content{
  display:grid;
 
  grid-template-columns:1fr 1fr 1fr;
  grid-template-rows: auto 1fr;
  grid-gap:5px;
  background-color:#23f343;
  
}
.item1,.item2,.item3,.item4,.item5,.item6{
    border:2px solid;
  
}
.item4{
  grid-row:1/ span 3;
}

.nestest{
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:5px;

  }
.item{
  background:white;
  border:1px solid;
}
```
## output:
![WhatsApp Image 2024-07-14 at 22 33 35_8fab850d](https://github.com/user-attachments/assets/5124fdce-c42b-4e94-9081-dc777a28f548)
