<template>
  <div class="container">
    <div class="title">
      <h2>gerenciamento de times</h2>
    </div>
    <div class="form-input">
      <input type="text">
      <button>salvar</button>
    </div>

  </div>
</template>

<style>
.title{
  margin: 2rem auto;
  display: flex;
  justify-content: center;
}

.form-input{
  margin-top: 10px;
  display: flex;
  justify-content: center;

}

.form-input input{
  width: 60%;
  height: 40px;
  border: 1px solid #ccc;
  border-radius: 10px;
  padding: 0 10px;
}

.form-input button{
  margin-left: 1%;
  width: 20%;
  height: 40px;
  border: 1px solid rgb(80, 98, 137);
  border-radius: 10px;
  background-color: rgb(80, 98, 137);
  color: white;
  font-weight: bold;
  cursor: pointer;
}
</style>
