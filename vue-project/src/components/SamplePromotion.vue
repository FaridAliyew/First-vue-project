<template>
    <section class="sample-promotion">
        <div class="overlay"></div>
        <div class="content">
            <h6>Free Sample</h6>
            <h1>Powerful Generator and Free Figma Sources</h1>
            <p>Startup Framework contains components and complex blocks which can easily be integrated into almost any design. All of the components are made in the same style, and can easily be integrated into projects, allowing you to create hundreds of solutions.</p>
        </div>
    </section>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@100..1000&display=swap');

.sample-promotion {
    height: 70vh;
    background-image: url('../images/img2.png');
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center; 
    align-items: center; 
    text-align: center;
    color: white;
    padding: 20px;
    position: relative; 
}

.overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgb(67, 32, 132);
    z-index: -1; 
}

.content {
    position: relative;
    z-index: 2; 
    color: white;
}

.sample-promotion h6, .sample-promotion h1, .sample-promotion p{
    font-family: "DM Sans", sans-serif;
}

.sample-promotion h6 {
    font-size: 14px;
    margin: 0;
    text-transform: uppercase;
}

.sample-promotion h1 {
    font-size: 58px;
    margin: 10px 0;
    width: 815px;
    margin-bottom: 30px;
}

.sample-promotion p {
    font-size: 18px;
    max-width: 700px;
    margin: 0 auto;
}
</style>
