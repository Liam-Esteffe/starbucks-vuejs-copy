<template>

<nav>

    <ul>
    <li><img class="logo" src="https://logo-marque.com/wp-content/uploads/2020/09/Starbucks-Logo.png"></li>
    <li><a>NOS CAFES</a></li>
    <li><a>MENU</a></li>
    <li><a>NUTRITION</a></li>
    <li><a>REWARDS</a></li>
    <li><a>DELIVERS</a></li>
    <li><a>SERVICE CLIENT</a></li>
    <li><a>CARRIERE</a></li>
    <li class='spacer'><button class="button-one" style="color: white;">Rejoindre maintenant</button></li>
    <li class='spacer' ><button class="button-sec">Se connecter</button></li>
    <li class='spacer' style="margin-right: 10px; font-size: 15px; !important;"><a>Trouver un salon</a></li>
    </ul>

</nav>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: white;
}

li {
    float: left;
}

li a {

    display: block;
    padding: 11px;
    font-size: 14px;
    font-weight: 800;
    font-style : 'Roboto';
    color: black;
    cursor: pointer;

}

li a:hover {

    color: green;

}

li p {

display: block;
font-size: 13px;
font-weight: 800;
font-style : 'Roboto';
color: black;

}

.logo {
    height: 50px;
}

.spacer {
    float: right;
}

.button-sec {
font-size: 13px;
font-weight: 800;
font-style : 'Roboto';
margin-top: 8px;
padding: 8px;
cursor: pointer;
border : 1px solid black;
border-radius: 60px;
width: 140px;
background-color: white;
color: black;
margin-left: 10px;
}

.button-one {
font-size: 13px;
font-weight: 800;
font-style : 'Roboto';
margin-top: 8px;
padding: 8px;
cursor: pointer;
border : 1px solid white;
border-radius: 60px;
width: 160px;
background-color: black;
color: white;
margin-left: 10px;
}



</style>