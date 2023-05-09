<svelte:head>
    
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" >
<link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;500&family=Peralta&display=swap"
rel="stylesheet">
<meta name="viewport" content="width=device-width, initial-scale=1">
<script src="https://kit.fontawesome.com/d0c488930b.js" crossorigin="anonymous"></script>
</svelte:head>



<slot/>


<style>

:global(html,body) {
    width: 100%;
    height: 100%;
    background: #fffde7;
}

:global(*){
    margin:0;
    padding:0;
    font-family: "Open sans";
}



.parent {

    width : 100%;
    height: 100%;
    display : flex;
    flex-direction: row;
}

.sidebar {

    background-color: cyan;
    width: 200px;
    height : 100%;

}

.content {

    display: flex;
    flex-direction: column;
}

</style>