<script>

export default {
  data() {
    return {
        title: 'la mia nuova app con vite'
    };
  },
};

    </script>

    <template>
  
        <header>
            <h1>
                {{ title }}
            </h1>
        </header>
  
    </template>

<style scoped>
h1{
   background-color: green;
   font-size: larger;
   font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
}

header:hover{
    width: 200px;
    color: yellow;
}
</style>
