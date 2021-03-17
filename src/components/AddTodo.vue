<template>
    <div class="addTodo">
        <h3>Add Todo</h3>
        <div class="add">
            <form>
                <input type="text" v-model="title" placeholder="Add Todo...">
                <input type="submit" value="Submit">
            </form>
        </div>
    </div>
</template>

<script>
export default {
    name: "AddTodo"
}
</script>

<style>
.addTodo{
    display: flex;
    flex-direction: column;
    align-items: center;

}

form{
    display: flex;
    flex-direction: column;
}
input{
    margin: 1%;
}

input[type="text"]{
    border: 1px solid #41b883;
}

input[type="submit"]{
    background: #41b883;
    color: #fff;
    border: 1px solid #41b883;
    cursor: pointer;
}
</style>