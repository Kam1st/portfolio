<template>
  <br>

  <aos-vue animation="fade" data-aos-duration="600">
    <h2 style="color: #5F5E43;">Champlain College Saint-Lambert</h2>
    <h3 style="color: #5F5E43;">(2020-2023)</h3>
    <p style="color: #5F5E43;">At Champlain College, I am on my way to complete a 3-year Computer Science technical DEC. <br>
      This program taught me a lot about the world of computers and software programming (and is the reason I can code this
      wonderful website all by myself:)).
    </p>
  <div>
    <img src="@/assets/edu/champ.jpg" width="800" height="400"/>
  </div>
  </aos-vue>

  <br>
  <br>
  <aos-vue animation="fade-down">
    <div>
      <h2 style="color: #5F5E43">Universal Marketing Inventory System</h2>
      <br>
      <p style="color: #5F5E43" >  Universal Marketing Co. Ltd (UMCL) is a wholesale supplier for plumbing equipment to  retail  businesses  and  professionals.
        <br>Currently,  the  company  uses  an  external Business Management service to store and retrieve data for all transactions,
        called MYOB (Mind Your Own Business). Transactions include: <br>

        <br>Placing orders
        <br>Restocking inventory
        <br>Producing invoices
        Tracking client activity.
      </p>
      <p style="color: #5F5E43;">They wish to have their own service to store their data and carry out these transactions. <br> This project was built
        using Java and Sprint Boot as well as Vue.js</p>
    </div>

    <div>
      <img src="@/assets/projects/um.png" width="800" height="500"/>
      <p style="color: #5F5E43;"> Check out the complete project at
        <a href="https://github.com/Kam1st/um_inventory_frontend" style="color: #5F5E43;">https://github.com/Kam1st/um_inventory_frontend </a> and <br>
        <a href="https://github.com/Kam1st/um_inventory" style="color: #5F5E43;">https://github.com/Kam1st/um_inventory </a>
      </p>
      <br>
    </div>
  </aos-vue>

  <br>

  <aos-vue animation="fade-right" :delay="50">
    <h2 style="color: #5F5E43;">Adventure Coin</h2>

    <p style="color: #5F5E43;">Adventure Coin is a 2D platformer made with the Unity plateform and coded in C#. <br> This project was made for my
      Game Development class with Unity and the goal was to use everything learnt in class in a final game. <br> Things
      like parallax, assets, scripts and much more helped create the finished product.
    </p>
    <div>
      <img src="@/assets/projects/game_level1.png" width="800" height="500"/>
    </div>
  </aos-vue>

  <aos-vue animation="fade-left" :delay="50">
    <div>
      <img src="@/assets/projects/game_ending.png" width="800" height="500"/>
      <p style="color: #5F5E43;">Check out the complete project at <a href="https://github.com/Kam1st/adventure_coin" style="color: #5F5E43;">https://github.com/Kam1st/adventure_coin </a></p>

    </div>
  </aos-vue>

</template>

<script>
export default {
  name: "educationPage",
}
</script>

<style scoped>

</style>