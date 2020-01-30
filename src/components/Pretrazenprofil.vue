<template>
    <div class="pretrazenprofil">
        <div class="card text-center" style="margin: auto; width: 30%;">
            <h2><strong> {{podatak.ime}}  {{podatak.prezime}}</strong> </h2>
                <div class="podaci">
                    <p><strong>Spol: </strong> {{podatak.spol}} </p>
                    <p><strong> Imam: </strong> {{podatak.brojgodina}} god.</p>
                    <p><strong> Grad: </strong> {{podatak.grad}}</p>
                    <p><strong> Moj kontakt: </strong> {{podatak.kontakt}}</p>
                    <p><strong> Ostalo: </strong> {{podatak.ostalo}}</p>
                </div>    
        </div>
    </div>
    
</template>


<script>
import store from '@/store.js'
export default {
    props: ["podatak"]
}
</script>

<style scoped>
h2{
    border-bottom: 3.5px solid 	rgb(175, 196, 204);
    background-color:rgb(175, 196, 204);
    padding: 2%;

}
.pretrazenprofil {
    margin-bottom: 30px;
}

.podaci{
   font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}

</style>
