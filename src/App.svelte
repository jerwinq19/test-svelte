<script>

</script>


<main>
     <div class="card">
          <div class="img"></div>
          <h1>Card 1</h1>
          <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quos asperiores, aliquid, ab explicabo doloribus deserunt voluptates in eaque et, quas praesentium accusamus ea voluptas error nesciunt quod voluptatibus vitae maiores.</p>
     </div>

     <div class="card">
          <div class="img"></div>
          <h1>Card 1</h1>
          <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quos asperiores, aliquid, ab explicabo doloribus deserunt voluptates in eaque et, quas praesentium accusamus ea voluptas error nesciunt quod voluptatibus vitae maiores.</p>
     </div>

     <div class="card">
          <div class="img"></div>
          <h1>Card 1</h1>
          <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quos asperiores, aliquid, ab explicabo doloribus deserunt voluptates in eaque et, quas praesentium accusamus ea voluptas error nesciunt quod voluptatibus vitae maiores.</p>
     </div>

     <div class="card">
          <div class="img"></div>
          <h1>Card 1</h1>
          <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quos asperiores, aliquid, ab explicabo doloribus deserunt voluptates in eaque et, quas praesentium accusamus ea voluptas error nesciunt quod voluptatibus vitae maiores.</p>
     </div>
     
     <div class="card">
          <div class="img"></div>
          <h1>Card 1</h1>
          <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quos asperiores, aliquid, ab explicabo doloribus deserunt voluptates in eaque et, quas praesentium accusamus ea voluptas error nesciunt quod voluptatibus vitae maiores.</p>
     </div>

     <div class="card">
          <div class="img"></div>
          <h1>Card 1</h1>
          <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quos asperiores, aliquid, ab explicabo doloribus deserunt voluptates in eaque et, quas praesentium accusamus ea voluptas error nesciunt quod voluptatibus vitae maiores.</p>
     </div>

     
</main>

<style>
     main {
          display: grid;
          grid-template-columns: repeat(3,3fr);
          grid-template-rows: auto;
          gap: 25px;
          background-color: #0A5EB0;
          padding: 2rem;
     }

     .img {
          width: 100%;
          height: 250px;
          background-color: #2A3335;
          box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px, rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px, rgba(0, 0, 0, 0.17) 0px 12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
     }
     .card {
          background-color: #0A97B0;
          color: white;
          padding: 2rem;
          width: 100%;
          max-width: 300px;
          height: auto;
          color: #FFCFEF;
          transition: all 1s ease;
     }

     .card:hover {
          transform: translateY(-10px);
          box-shadow: 0px 0px 10px #2A3335;
     }

     @media (max-width: 600px){
          main {
               grid-template-columns: 1 1;
               grid-template-rows: auto;
          }

     }

</style>