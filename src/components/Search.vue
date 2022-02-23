<template>
  <div class="search">
    <div class="search-header">
      <div class="search-result">
        <span>검색 결과</span>
        <span>></span>
      </div>
      <div class="remove-container">
        <div class="company">yap yap yap</div>
          <button class="totop_arrow1" type="button"></button>
      </div>
    </div>
    <input type="text" placeholder="기업명을 검색하세요" />
  </div>
</template>

<script>
export default {};
</script>
  
<style>
.totop_arrow1{
  margin-top: 6px;
  width:16px;
  height:16px;
  position:relative;
  background:#D2D2D2;
	border-radius:50%;
  text-indent:-9999px;
  border: none;
  cursor: pointer;
}
.totop_arrow1:before,.totop_arrow1:after{
  content:'';
  width: 11px;
  height: 2px;
  position:absolute;
  top:48%;
  border-radius:5px;
  background: white;
}
.totop_arrow1:before{
  left:2px;
  transform: rotate(45deg)
}
.totop_arrow1:after{
  right:3px;
  transform: rotate(-45deg)
}

.search-result {
  margin-left: 6px;
}
.company {
  color: rgb(161, 159, 159);
  margin-right: 10px;
}
.remove-container {
  display: flex;
  flex-direction: row;
  margin-right: 16px;
}

.search {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.search-header {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  width: 360px;
  height: 62px;
  background-color: white;
  
}

.search .search-header span:nth-child(1) {
  color: #727272;
  font-size: 16px;
  font-weight: 700;

  flex: none;
  order: 0;
  flex-grow: 0;
  margin: 0px 8px;
}

.search .search-header span:nth-child(2) {
  color: #727272;
  font-size: 16px;
  font-weight: 700;

  flex: none;
  order: 1;
  flex-grow: 0;
  margin: 0px 8px;
}

.search .search-header span:nth-child(3) {
  position: static;
  width: 65px;
  height: 20px;
  left: 16px;
  top: 0px;

  font-family: Noto Sans;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 140%;
  text-align: right;
  color: #727272;

  flex: none;
  order: 0;
  flex-grow: 0;
  margin: 0px 0px;
}

.search .search-header span:nth-child(4) {
  width: 16px;
  height: 16px;
  left: 0%;
  right: 0%;
  top: 0%;
  bottom: 0%;

  background: #D2D2D2;
  border-radius: 45.7143px;
}

input {
  padding: 12px 16px;
  width: 328px;
  height: 48px;
  left: 16px;
  top: 134px;
  background: #F8F8F8;
  border: 1px solid #F2F2F2;
  box-sizing: border-box;
  border-radius: 4px;
}

</style>