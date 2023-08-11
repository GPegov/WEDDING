<template>
<div class="app">
    <h2></h2>
    <h4></h4>
    <div class="guestNames">
        <form>
            <input class="input" type="text" placeholder="Имя">
            <input class="input" type="text" placeholder="Фамилия">
            <button class="btn" @click="addGuest">Добавить гостя</button>
        </form>
    </div>
</div>
</template>


<script>
export default {
    data() {
        return{
            guests
        }
    }
}

</script>


<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.app {
    padding: 20px;
}
.guestNames {
    width: 20%;
    min-width: 200px;
    
}
.input {
    width: 100%;
    border: 1px solid rgb(181, 39, 252);
    padding: 10px 15px;
    margin-top: 10px;
    border-radius: 12px;
}
.btn {
    width: 50%;
    border: 1px solid rgb(181, 39, 252);
    padding: 10px 15px;
    margin-top: 20px;
    align-self: flex-end;
    background: none;
    color: rgb(181, 39, 252);
    border-radius: 12px;


}
form {
    display: flex;
    flex-direction: column;
}
</style>

