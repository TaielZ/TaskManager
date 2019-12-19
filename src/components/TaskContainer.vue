<template>
    <div> 
        Titulo:{{title}}  
    </div>
</template>
<script>
export default {
    name : "TaskContainer" ,
    props:{
        title: String  
    }
}
</script>