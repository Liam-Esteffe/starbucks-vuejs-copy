<template>
<NavBar/>

    <div class="flex-display">
        <div id="long">
            <img class="img-long" src="https://www.starbucks.fr/sites/starbucks-fr/files/styles/c02_horizontal_card_1335x534/public/2022-09/3083_AUT22_FR_Website_Hero_1335x534_PSL_v01.jpg.webp?itok=lSzDcMYO">
            <div class="flex-props">
            <h2>Avec le changement de saison viennent de nouvelles saveurs vives et audacieuses ! 🎃</h2>
        <p>
                Découvrez nos nouvelles boissons savoureuses et fraîchement préparées et profitez<br>pleinement du retour du PSL.<br/> A retrouver en édition limitée et en exclusivité chez Starbucks.
            </p>
            <button class="green-button">Trouvez votre salon le plus proche</button>
            <div class="flex-section">
                <img class="img-section" src="https://www.starbucks.fr/sites/starbucks-fr/files/styles/c10_2_col_text_560x467/public/2021-06/030612_Starbucks_MOP_FR_v01_0.jpg.webp?itok=vijKF4Og">
                <div class="flex-col">
                    <h3>Nouveau: Click & Collect</h3>
                    <p id="parap">Avec l'application Starbucks® France, vous pouvez commander sur le pouce.Commandez à l'avance et cumulez les étoiles.</p>
                    <button class="green-button-section">Télécharger l'appli</button>
                </div>
            </div>
        </div>
        </div>
        <!-- fix image -->
        <div id="short">
            <img class="img-short" src="https://www.starbucks.fr/sites/starbucks-fr/files/styles/c01_vertical_card_724x1009/public/2022-03/3031_FR_MOP_Homepage_banner_v01.jpg.webp?itok=bx-uttqo">
        </div>
    </div>

</template>

<script lang="ts">
 import NavBar from '../components/NavBar.vue';

export default {
    components : {
        NavBar,
    }
}
</script>

<style lang="scss">
.hero {
    margin: 0;
    padding: 0;
}

.flex-display {
display: flex;
flex-direction: row-reverse;
}

#long {
    width: 62%;
    height: 350px;
    overflow: scroll;
    height: 100%;
}

.img-long {
    width: 100%;
    height: 100%;
}

.img-short {
    width: 100%;
    height: 100%;
}

h2 {
font-family: 'Helvetica';
font-weight: 400;
font-size: 28px;
text-align: start;
}

p {
font-family: 'Helvetica';
font-weight: 400;
font-size: 15px;
width: 50%;
color: gray;
text-align: start;

}

.img-section {
    width: 60%;
    height: 60%;
}

.green-button {

padding: 8px;
border: 1px solid green;
color: green;
border-radius: 60px;
background-color: white;
font-weight: bold;
font-size: 13px;
width: 300px;
cursor: pointer;
}

#parap {
    width: 80%;
}

.flex-props {
    display: flex;
    width: 80%;
    flex-direction: column;
    justify-content: start;
    align-items: start;
    padding-left: 20px;
}

.green-button:hover {
    background-color: rgb(208, 237, 208);
    opacity: 0.7;
    color: green;
}

.green-button-section:hover {
    background-color: rgb(208, 237, 208);
    opacity: 0.7;
    color: green;
}

h3 {
    font-family: 'Helvetica';
    font-weight: 600;
    font-size: 20px;
    text-align: start;
}

.flex-section {
    display: flex;
    flex-direction: row;
    justify-content: start;
    align-items: center;
    margin-top: 20px;
}

.flex-col {
    display: flex;
    flex-direction: column;
    justify-content: start;
    align-items: start;
    padding-left: 20px;
    padding-bottom: 100px;
}

#short {
    margin: 0;
    padding: 0;
    width: 38%;
    height: 700px;
    position: fixed;
    top:10;
    left: 0;
    repeat: repeat-x;
    
}

span {
    float: left;
    padding-left: 80px;
}

.green-button-section {
    padding: 8px;
    border: 1px solid green;
    color: green;
    border-radius: 60px;
    background-color: white;
    font-weight: bold;
    font-size: 13px;
    width: 200px;
    cursor: pointer;
}

</style>