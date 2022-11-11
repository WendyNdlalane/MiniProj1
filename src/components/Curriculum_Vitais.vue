<template>
 <section class="layout">
  <div class="header"> <h1 class="center">Curriculum Vitae</h1> </div>
  <div class="leftSide">
  <table border="1">
    <tr>
      <td style="width:200px">
        <img src="C:/Users/wendy Ndlalane/Documents/miniproject1/src/assets/wendy.jpeg" alt="Wendy" style="width:128px;height:128px;">
       </td>
    </tr>
  </table>
   <h2> <p>Foto</p></h2>
  </div>
  
  <div class="body">
   <section class="layout">
    <div style="overflow-x: auto;">
  <table>
    
    <tr>
      
      <td></td>
     
    </tr>
  <tr>
      
      <td>
        <h3><p> <b>Quem eu sou ?</b></p></h3>
      <p>Wendy Amelia Ndlalane </p> 
     <p> Sou licenciada em Engenharia Informática e Telecomunicações.</p>
     <p> Sou Moçambicana e vivo em Moçambique.</p>
      </td>
    
    </tr>
    <tr>
      <td>
       </td>
   
    </tr>
    
      <tr>
     
      <td>
        <h3><p><b>O que Faco?</b></p></h3>
     <p> Trabalho numas das operadoras de telecomunicação do meu pais (Vodacom        Moçambique) a quase 3 anos.</p>
     <p> Sou voluntaria de programa Django Girls , como Organizadora e Trainer. </p>
     <p>Sou Voluntaria do programa da vodacom Code Like a Girl.</p>
      
      
      </td>
   
    </tr>
    
      <tr>
     
      <td>
     
      
      </td>
   
    </tr>
    
      <tr>
     
      <td>
       <h3><p><b>Hobbies</b></p></h3>
      <p>Cinema </p>
      <p>Praia</p>
      <p>Viajar </p>
       <p>Estudar </p>
      
      
      
      </td>
   
    </tr>
  </table>
</div>
  



 
</section>


  </div>
  <div class="footer">
    <p class="cente"> Procure por mim atraves das redes socias </p>
  <a href="https://www.linkedin.com/" target="_blank"><img src="C:/Users/wendy Ndlalane/Documents/miniproject1/src/assets/in.png" height="25"></a> 
  <a href="https://www.facebook.com/" target="_blank"><img src="C:/Users/wendy Ndlalane/Documents/miniproject1/src/assets/fb.png" height="25"></a> 
  <a href="https://www.twitter.com/" target="_blank"><img src="C:/Users/wendy Ndlalane/Documents/miniproject1/src/assets/t.png" height="25" ></a>
  <a href="https://www.instagram.com/" target="_blank"><img src="C:/Users/wendy Ndlalane/Documents/miniproject1/src/assets/instagram-6.png" height="25" ></a>
  <a href="https://www.Github.com/" target="_blank"><img src="C:/Users/wendy Ndlalane/Documents/miniproject1/src/assets/unnamed.png" height="25" ></a>

</div>
  
 
</section>

 </template>

<script>

export default{
  name: 'App',
    data () {
    return {
      title: 'footer_images'
    
    }
  }

}

    

</script>

<style scoped>
.layout {
  width: 1366px;
  height: 768px;

  display: grid;
  grid:
    "header header header" auto
    "leftSide body ." 1fr
    "footer footer footer" auto
    / auto 1fr auto;
  gap: 8px;
}

.header { grid-area: header;
  background-color: #666;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;


}
.leftSide { grid-area: leftSide; 
   box-shadow:auto ;
background-color: rgb(230, 238, 238);
; 

}
.body { grid-area: body; 
  
  background-color:#f1f1f1;
  
}

table {
  border-collapse: collapse;
  width: 100%;
}

th, td {
  text-align: left;
  padding: 8px;
}

tr:nth-child(even) {background-color: #f2f2f2;}

.footer { grid-area: footer;
   box-shadow:100%;
background-color: beige; 

background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;}


</style>