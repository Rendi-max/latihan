<template>
    <div>
        <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.1.2/dist/tailwind.min.css" rel="stylesheet"/>
        <div class="">
            <h1>
                This is your first page on Nuxt Js
            </h1>
            <p class="hv:text-red-60">
                Nuxt mempermudah kita dalam membuat halaman pada website
            </p>
            <p>
                Website ini dibuat oleh "{{name}}"
            </p>
            <div class="input-container">
                <input v-model="name" placeholder="Silakan Masukkan Nama Anda" type="text">
                <button @click="showAlert">Show Message</button>
            </div>
        </div>
    </div>

  </template>

  <script>
export default {
  name: 'Beranda',
  data: () => ({
    name: null
  }),
  methods: {
    showAlert(){
      alert(`Hallo ${this.name}`)
    }
  },
}
</script> 
<style>
html, body {
  padding: 0;
  margin: 0;
}
body {
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  background-color: #001e26;
}
h1{
  font-weight: bold;
  font-size: 50px;
  color: #00dc82;
}
p{
  font-size: 20px;
  color: white;
}
.input-container{
  display: flex;
  align-items: center;
  justify-content: center;
}
input{
  width: 300px;
  height: 35px;
  background-color: #001e26;
  border: 1px solid white;
  color: white;
  font-size: 13px;
}
button{
  margin-left: 10px;
  height: 40px;
  font-size: 13px;
  background-color: #001e26;
  border: 1px solid #00dc82;
  color: #00dc82;
}
</style>

