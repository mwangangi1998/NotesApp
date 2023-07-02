<template>
  <main>
    <div class="overlay">
<div class="modal">
  <textarea name="" id="note" cols="30" rows="10"></textarea>
  <button>Add note</button>
</div>
    </div>
    <div class="container">
      <header>
        <h1>Notes</h1>
        <button>+</button>
      </header>
      <div class="cards-container">
        <div class="card">
          <p class="main-text">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum, unde!
          </p>
          <p class="date">
            12/12/2023
          </p>
        </div>
        <div class="card">
          <p class="main-text">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum, unde!
          </p>
          <p class="date">
            12/12/2023
          </p>
        </div>
      </div>
    </div>
  </main>
</template>
<script>

</script>
<style scoped>
main {
  width: 100%;
  height: 100%;
}

.container {
  max-width: 980px;
  padding: 10px;
  margin: 0 auto;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

h1 {
  margin-bottom: 25px;
  font-weight: 400;
  margin: 25px;
  font-size: 60px;
}

header button {
  border: none;
  padding: 10px;
  width: 50px;
  height: 50px;
  cursor: pointer;
  background-color: rgb(15, 211, 225);
  border-radius: 100%;
  color: white;
}

.card {
  width: 225px;
  height: 225px;
  background-color: rgb(248, 219, 2);
  padding: 10px;
  border-radius: 15px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  margin-right: 20px;
  margin-bottom: 20px;
  border-right: 8px;
}

.main-text {
  color: black;
  font-size: 15px;
}

.date {
  font-size: 12.3px;
  color: black;
  font-weight: 800;
}

.cards-container {
  display: flex;
  flex-wrap: wrap;
}
.overlay{
  position: absolute;
  width: 100%;
  height: 100%;
  background: rgba(54, 17, 17, 0.349);
  z-index: 10;
  display: flex;
  align-items: center;
justify-content: center;
  }
  .modal{
    width: 750px;
    padding: 30px;
    display: flex;
    position: relative;
    background-color: white;
    padding: 30px;
    flex-direction: column;
  }
  .modal button{
    padding: 10px 20px;
    font-size: 20px;
    width: 100%;
    border: none;
   margin-top: 15px;
   border-radius: 8px;
   color: white;
    background-color: blueviolet;
    cursor: pointer;
  }
</style>