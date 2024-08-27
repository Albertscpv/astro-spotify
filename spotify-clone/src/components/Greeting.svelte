<script lang="ts">
    const currenTime = new Date();
    const currentHour = currenTime.getHours();

    let greeting = "";

    if(currentHour < 12){
        greeting = "Good Morning!"
    }else if(currentHour< 18){
        greeting = "Good Afternoon!"
    }else{
        greeting = "Good Evening!"
    }

</script>



<h1 class="text-3xl font-light ">
    {greeting}
</h1>