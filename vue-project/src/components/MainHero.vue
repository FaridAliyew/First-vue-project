<template>
    <section id="main-hero">
        <div>
            <h3>Startup 3</h3>
            <h1>Forget About Code</h1>
            <p>Startup Framework gives you complete freedom over your creative process - you don't have to think about any technical aspects. There are no limits and absolutely no coding.</p>
            <button>Create an Account</button>
        </div>
    </section>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@100..1000&display=swap');

#main-hero {
    height: 100vh;
    display: flex;
    justify-content: center; 
    align-items: center; 
    z-index: 1;
}

#main-hero > div {
    text-align: center; 
}

h3, h1, p {
    font-family: "DM Sans", sans-serif;
    margin: 15px 0;
    color: white;
}

h3{
    font-weight: bold;
    font-size: 24px;
}

h1{
    font-weight: bold;
    font-size: 72px;
}

p{
    font-size: 22px;
    width: 736px;
}

button {
    margin-top: 20px;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
    background-color: #482BE7;
    border-radius: 25px;
    border: none;
    color: white;
    padding: 15px;
    width: 200px;
}
</style>
