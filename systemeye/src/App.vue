<template>
  <div id="app" class = "templates">
    <body>

<div class="topnav">
<h1>{{ msg }}</h1>
 <h1> EYES TELEMEDICINE</h1>
    <h2>WEB APPLICATION </h2>
  <a href="#">ค้นหาแพทย์</a>
  <a href="#">นัดหมายแพทย์</a>
  <a href="#">เกร็ดความรู้เรื่องตา</a>
</div>


<div class="content">
  <h2>ระบบให้ความปรึกษาโรคสายตา
  </h2>
  <p>WEB APPLICATION FOR EYES TELEMEDICINE</p>
  

 
  <button class but href="#">สมัครสมาชิก</button>
  <button class but ref="#">ปรึกษาแพทย์ VDO CALL</button>
  
</div>

<div class="footer">
  <p>EYES TELEMEDICINE</p>  
  <p>WEB APPLICATION</p>
   <h1>Contact</h1>
</div>

  </body>
    
  <template-table/>
  </div>
 
</template>




<script>

import Template from '@/components/Template'

export default {
  name: 'App',
  components: {
    Template
   
  }
}

</script>

<style>
.templates {

 
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the top navigation bar */
.topnav {
  overflow: hidden;
  background-color: #f5faff;
}

/* Style the topnav links */
.topnav a {
  float: left;
  display: block;
  color: #080808;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change color on hover */
.topnav a:hover {
  background-color: rgb(124, 124, 124);
  color: black;
}

/* Style the content */
.content {
  
  background-color: rgb(255, 251, 251);
  padding: 10px;
  height: 447px; /* Should be removed. Only for demonstration */

}
.content button{
 
  background-color: #c2390fcc;
  border: none;
  color: white;
  padding: 7px 14px;
  text-align: center;
  font-size: 16px;
  margin: 4px 2px;
  opacity: 0.6;
  transition: 0.3s;
  display: inline-block;
  text-decoration: none;
  cursor: pointer;
  
}

/* Style the footer */
.footer {
  background-color: #F0F8FF;
  padding: 5px;
}
.footer p{
  text-align:left;
  font-size: 18px;
}
.footer h1{
    text-align:right;
  font-size: 11px;
}

</style>
