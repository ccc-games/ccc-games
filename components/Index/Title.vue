<template>
    <div id="title-wrapper">
        <h1 id="ccc">Chilling Con Carne</h1>
        <hr width="30">
        <h1 id="games">Games</h1>           
    </div>
</template>

<style scoped>

#title-wrapper {
    position: absolute;
    top: 30%;
    left: 50%;
    transform: translate(-50%);

    display: flex;
    flex-direction: column;
    gap: 20px;
}

#ccc {
    width: fit-content;
    margin: auto;
    color:white;
    text-decoration: underline;
}

#games {
    text-transform: uppercase;
    font-size: 36px;
    background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
	background-size: 400% 400%;
	animation: gradient 15s ease infinite;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

@keyframes gradient {
	0% {
		background-position: 0% 50%;
	}
	50% {
		background-position: 100% 50%;
	}
	100% {
		background-position: 0% 50%;
	}
}

</style>