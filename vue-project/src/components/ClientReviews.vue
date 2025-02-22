<template>
    <div class="main-container">
        <h2 class="reviews-title">Our Happy Clients</h2>
        <section class="reviews">
            <div class="review">
                <img src="../images/Mask.png" alt="Reviewer 1">
                <div class="review-content">
                    <p>"Get a fully retina ready site when you build with Startup Framework. Websites look sharper and
                        more gorgeous on devices with retina display support"</p>
                    <p class="reviewer-name">-Rayhan Curran</p>
                </div>
            </div>
            <div class="review">
                <img src="../images/Userpic.png" alt="Reviewer 2">
                <div class="review-content">
                    <p>"As a business targeting high net worth individuals, we were looking for a slick, cool and
                        minimalistic design for our website"</p>
                    <p class="reviewer-name">-Kayley Frame</p>
                </div>
            </div>
            <div class="review">
                <img src="../images/Maskk.png" alt="Reviewer 3">
                <div class="review-content">
                    <p>"The most important part of the Startup Framework is the samples"</p>
                    <p class="reviewer-name">-Gene Whitfield</p>
                </div>
            </div>
            <div class="review">
                <img src="../images/Userpicc.png" alt="Reviewer 4">
                <div class="review-content">
                    <p>"I've built my website with Startup just in one day, and it was ready-to-go."</p>
                    <p class="reviewer-name">-Allan Kim</p>
                </div>
            </div>
        </section>
    </div>
</template>

<style scoped>
.main-container {
    background-color: rgb(38 19 96);
    height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 20px;
}

.reviews-title {
    font-size: 2em;
    margin-bottom: 20px;
    text-align: center;
    color: white;
}

.reviews {
    display: grid;
    grid-template-columns: 1fr;
    gap: 20px;
    width: 100%;
    max-width: 900px;
}

@media (min-width: 768px) {
    .reviews {
        grid-template-columns: repeat(2, 1fr);
    }
}

.review {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
    background-color: white;

}

.review img {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    margin-right: 20px;
}

.review-content {
    flex-grow: 1;
    text-align: center;
}

.reviewer-name {
    font-style: italic;
}

@media (max-width: 768px) {
    .review {
        flex-direction: column;
        text-align: center;
    }

    .review img {
        margin-right: 0;
        margin-bottom: 10px;
    }
}
</style>
