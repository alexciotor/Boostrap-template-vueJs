<template>
<section  >
  <h1>Colors</h1>
  <div class="container">
 <h4 class="text-danger bg-light" >This is a color class</h4>
 <h4 class="text-primary bg-dark orange" >This is a color class</h4>
 <h4 class="text-info bg-secondary " >This is a color class</h4>
 <h4 class="text-success bg-warning " >This is a color class</h4>
 <h4 class="text-warning bg-success" >This is a color class</h4>
 <h4 class="text-secondary bg-info " >This is a color class</h4>
 <h4 class="text-dark bg-primary" >This is a color class</h4>
 <h4 class="text-light bg-danger " >This is a color class</h4>
 <h4 class="text-muted" >This is a color class</h4>
 </div>

 <h1>Typography</h1>
 <br><br><br> 
 <div class="container">
<h3>default font-size 16px</h3>
<h3>default line-height 1.5</h3>
<p>all elements have margin-top: 0 and margin bottom 1rem(16px)</p>
<br><br><br> 
<h1>hello i am 40 px</h1>
<h2>hello i am 32 px</h2>
<h3>hello i am 28 px </h3>
<h4>hello i am 24 px </h4>
<h5>hello i am 20 px </h5>
<h6>hello i am 16 px </h6>
<br><br><br>
<!-- adding a class of heading gives the element that size -->
<h1 class="h5">hello i am 40 px</h1>
<p class="h1" >hello i am 40 px</p>
<!-- Display classs -->
<h1 class="display-1">Display 1</h1>
<h1 class="display-2">Display 2</h1>
<h1 class="display-3">Display 3</h1>
<h1 class="display-4">Display 4</h1>
<p class="display-4" >Display class works with any element</p>
 <br><br><br>
<h4>normal text <small>small text</small></h4>
<p>small text <small>smaller text</small></p>
<p>I can highlight with <mark>marked text</mark></p>
<p>i can highlight with  <code>code element</code></p>
<p>i can highlight with  <kbd>kbd element</kbd></p>

 <br><br><br>
<h2>Font weights</h2>
 <p class="font-weight-bold"  >Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptates, sunt?</p>
 <p class="font-weight-light">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Earum, repudiandae.</p>
 <p class="font-italic">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Molestias, iste?</p>
 <p class="lead" >Lorem ipsum dolor sit amet consectetur adipisicing elit. Quis, necessitatibus!</p>
 <p class="text-center">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Est, eaque!</p>
  <p class="text-right">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Est, eaque!</p>
   <p class="text-left">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Est, eaque!</p>
   <p class="text-uppercase">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quia, veritatis.</p>
   <p class="text-capitalize">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum, blanditiis.</p>
   <p class="text-lowercase">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ad, distinctio.</p>
 </div>
 <h1>Containers</h1>
 
<div class="container bg-danger text-light">i am sa simple container
</div>
<div class="container-fluid bg-primary text-ligfht">i am a simple container fluid</div><br><br><br>
 <section id="skills" class="bg-warning" >
<div class="container bg-danger text-light">i am sa simple container
</div>
 </section>
  <section id="about" class="bg-warning" >
<div class="container-fluid bg-primary text-light">i am sa simple container
</div>
 </section>
<br><br><br><br>
<h1>Media queries</h1>
<!-- 12 -->
<div class="container bg-secondary text-white">
  <div class="row">
    <div class="col bg-danger">i am single column</div>
  </div>
</div>
<div class="container-fluid bg-secondary text-white">
  <div class="row">
    <div class="col bg-primary">i am single column</div>
      <div class="col bg-dark">i am second column</div>
  </div>
</div>
<div class="container  bg-secondary text-white">
  <div class="row">
    <div class="col bg-warning">i am single column</div>
      <div class="col bg-dark">i am second column</div>
         <div class="col bg-info">i am second column</div>
  </div>
</div>

<br><br><br>
<h1>Screen sizes</h1>
<div class="container   text-white">
  <div class="row">
    <div class="col-7 bg-warning">i am single column</div>
      <div class="col-3 bg-dark">i am second column</div>
         <div class="col-2 bg-info">i am second column</div>
  </div>
  <br><br><br><br>
</div>
<div class="container   text-white">
  <div class="row">
    <div class="col-sm-6 col-md-3 bg-warning">i   am single column</div>
      <div class="col-sm-6 col-md-3  bg-dark">i am second column</div>
         <div class="col-sm-6 col-md-3  bg-info">i am second column</div>
            <div class="col-sm-6 col-md-3  bg-danger">i am second column</div>
  </div>
  
</div>
<br><br><br><br><br><br>

<h1>margin and paddings</h1>
<!-- m p 0-5 -->
  <div class="container">
  <div class=" p-5 bg-danger m-5">i am div</div>
  <div class=" p-4 bg-info m-4">i am div</div>
  <div class=" p-3 bg-warning m-3">i am div</div>
  <div class=" p-2 bg-success m-2">i am div</div>
  <div class=" p-1 bg-secondary m-1">i am div</div>
   <div class="p-0 bg-primary ">i am div</div>
  
</div>
 
<!-- m p 0-5 -->
  <div class="container">
  <div class="  mt-5 bg-danger ">i am div</div>
  <div class="  bg-info ">i am div</div>
  <div class=" mb-5 bg-warning ">i am div</div>
  <div class=" ml-5  bg-success ">i am div</div>
  <!-- my - margin top-bottom -->
  <div class=" my-5 bg-secondary ">i am div</div>
  <!-- mx- margin left right -->
   <div class=" mx-5 bg-primary ">i am div</div>
  
</div>
  <div class="container">
  <div class="  pt-5 bg-danger ">i am div</div>
  <div class="  bg-info ">i am div</div>
  <div class=" pb-5 bg-warning ">i am div</div>
  <div class=" pl-5  bg-success ">i am div</div>
  <!-- my - margin top-bottom -->
  <div class=" py-5 bg-secondary ">i am div</div>
  <!-- mx- margin left right -->
   <div class=" px-5 bg-primary ">i am div</div>
  
</div>
<!-- w = with from 25 to 100 -->
<!-- mx-auto to center div  -->
  <div class="container mt-5">
    <!-- you can add screen size to id ( media query Md ) -->
  <div class=" w-25 bg-danger  mx-md-auto  ">i am div</div>
  <div class=" w-50 bg-info  mx-auto  ">i am div</div>
  <div class=" w-75 bg-warning  mx-auto  ">i am div</div>
  <div class=" w-100  bg-success ">i am div</div>
   
  <div class="   bg-secondary ">i am div</div>
  <!-- mx- margin left right -->
   <div class="   bg-primary ">i am div</div>
  
</div>
<span class="border  border-5 d-block text-primary">hello</span>
<h1 class="">flexBox </h1>
 </section> 
</template>

<script>
export default {
  
  head(){
    return{
      title:'Boostrap '
    }
  }
}
</script>

<style>
body{
  text-transform: capitalize;
}
/* add different styles to an element by adding a class  */
 .orange{
    font-size: 3rem;
 }
 
</style>
