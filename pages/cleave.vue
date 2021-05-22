<template>
 <div>
 
 <input type="text" class="scroll-target" id="scroll-target">
 </div>

</template>

<script>

    import Cleave from 'cleave.js'


    export default {
        mounted(){
    setTimeout(function () {
      console.log(document.querySelector('#scroll-target'));



const cleave = new Cleave('.scroll-target', {
    date: true,
    delimiter: '-',
    datePattern: ['Y', 'm', 'd']
});






    }.bind(this), 2000);
        }
    }


    /*
    
    var cleave = new Cleave('.input-element', {
    date: true,
    delimiter: '-',
    datePattern: ['Y', 'm', 'd']
});
    
    
    */
</script>

