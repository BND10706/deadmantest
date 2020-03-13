<template>
  <div>
    <div class="product">
      <div class="imgbox">
        <img src="../../public/img/brand/product.jpg">
      </div>
      <div class="specifies">
        <h2>
          Beef Jerky <br />
        </h2>
        <div class="price">$15</div>
        <br>
        <span>This is amazing Beef Jerky with a smokey flavor</span>
        <button class="btn-product btn-primary">Buy Now</button>
      </div>
    </div>
  </div>
</template>
<script>
export default {
    name: "productcard"
};
</script>
<style>

@import url('https://fonts.googleapis.com/css?family=Open+Sans&display=swap');

 .product {
     position: relative;
     top: 50%;
     left: 50%;
     transform: translate(-50%, -50%);
     width: 300px;
     height: 400px;
     box-shadow: 0 20px 40px rgba(0, 0, 0, .2);
     border-radius: 5px;
     background: #0e0e0f;
     overflow: hidden;
     margin: 15px;
 }

 .product .imgbox {
     height: 100%;
 }

 .product .imgbox img {
     display: block;
     width: 100%;
 }

 .specifies {
     position: absolute;
     width: 100%;
     bottom: -160px;
     background: #fff;
     padding: 10px;
     box-sizing: border-box;
     transition: .5s
 }

 .product:hover .specifies {
     bottom: 0
 }

 .specifies h2 {
     margin: 0;
     padding: 0;
     font-size: 20px;
     width: 100%
 }

 .specifies h2 span {
     font-size: 15px;
     color: #ccc;
     font-weight: normal
 }

 .specifies .price {
     position: absolute;
     top: 12px;
     right: 25px;
     font-weight: bold;
     color: #000;
     font-size: 30px
 }

 label {
     display: block;
     margin-top: 5px;
     font-weight: bold;
     font-size: 15px
 }

 ul {
     display: flex;
     margin: 0;
     padding: 0
 }

 ul li {
     list-style: none;
     margin: 5px 5px 0;
     font-size: 15px;
     font-style: normal;
     color: #ccc
 }

 ul li:first-child {
     margin-left: 0
 }

 .btn-product {
     background-color:grey;
     display: block;
     padding: 5px;
     color: #fff;
     margin: 10px 0 0;
     width: 100%;
     font-size: 13px;
     border-radius: 2px;
     border-color: grey;
 }
 .btn-product:hover{
     background-color: red;
     border-color:red;
 }
 </style>
