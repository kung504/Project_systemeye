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
  

 
  <button href="#">สมัครสมาชิก</button>
  <button href="#">ปรึกษาแพทย์ VDO CALL</button>
  
</div>

<div class="footer">
  <p>EYES TELEMEDICINE</p>
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
  background-color: rgb(255, 255, 255);
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
  background-color: #ddd;
  color: black;
}

/* Style the content */
.content {
  background-color: rgb(255, 251, 251);
  padding: 10px;
  height: 447px; /* Should be removed. Only for demonstration */
}

/* Style the footer */
.footer {
  background-color: #F0F8FF;
  padding: 30px;
}

</style>
