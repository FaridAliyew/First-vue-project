<template>
    <div id="main-container">
        <div class="overlay"></div>
        <div>
            <img src="../images/Mockup.png" width="90%" alt="">
        </div>

        <div class="content">
            <div class="text-box">
                <h1>We Create Something New</h1>
                <p>We have created a new product that will help designers, developers, and companies create websites for
                    their startups quickly and easily.</p>
            </div>
            <div class="features">
                <div class="feature-box">
                    <i class="fa-regular fa-copy"></i>
                    <p class="feature-title">30 NEW FEATURE PAGES</p>
                    <p style="font-size: 16px;">Startup Framework contains components and complex blocks which can easily.</p>
                </div>
                <div class="feature-box">
                    <i class="fa-regular fa-gem"></i>
                    <p class="feature-title">USEFUL SYMBOL COMPONENTS</p>
                    <p style="font-size: 16px;">Samples will show you the feeling on how to play around using the components.</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=DM+Sans:wght@100..1000&display=swap');

#main-container {
    position: relative;
    background-image: url('../images/Rectangle.png');
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    height: 600px;
    overflow: hidden;
}

.overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgb(50, 14, 134);
    z-index: -1;
}

.content {
    position: relative;
    margin-left: 120px;
    color: white;
}

.text-box {
    width: 600px;
    margin-bottom: 60px;
}

h1,
p {
    font-family: "DM Sans", sans-serif;
}

h1 {
    font-size: 42px;
    color: white;
}

p {
    font-size: 22px;
    color: white;
}

.features {
    display: flex;
}

.feature-box {
    width: 271px;
    margin-right: 40px;
}

.feature-box i {
    font-size: 37.5px;
}

.feature-title {
    font-size: 14px;
    font-weight: bold;
}
</style>