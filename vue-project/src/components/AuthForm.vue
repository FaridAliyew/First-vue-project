<template>
    <section>
        <div class="overlay"></div>
        <div class="container">
            <h1>We solve digital problems with an outstanding creative flare</h1>
            <p>We have created a new product that will help designers, developers and companies create websites for
                their startups quickly and easily.</p>
        </div>
        <form>
            <div class="form-header">
                <p class="sign active">SIGN UP</p>
                <p class="login">LOGIN</p>
            </div>
            <div class="form-body">
                <input type="text" placeholder="Your email">
                <input type="password" placeholder="Your password">
                <button class="signup-btn">Create an Account</button>
                <p class="divider">or</p>
                <button class="twitter-btn">Login via Twitter</button>
            </div>
        </form>
    </section>
</template>

<style scoped>
section {
    background-image: url('../images/img2.png');
    background-size: cover;
    background-position: center;
    height: 500px;
    width: 100%;
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 190px;
}

.overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgb(63, 25, 134);
    z-index: -1;
}

.container {
    width: 369px;
    color: white;
}

.container h1 {
    font-size: 36px;
    margin-bottom: 15px;
}

.container p {
    font-size: 16px;
    line-height: 1.5;
}

form {
    background: rgb(255, 255, 255);
    padding: 20px;
    width: 400px;
    border-radius: 15px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    text-align: center;
    color: white;
}

.form-header {
    display: flex;
    justify-content: space-between;
    padding: 10px;
    font-weight: bold;
    font-size: 16px;
    cursor: pointer;
}

.form-header .active {
    color: black;
    border-bottom: 2px solid black;
}

.form-header .login {
    color: black;
}

input {
    display: block;
    width: 90%;
    padding: 12px;
    margin: 10px auto;
    border: 1px solid rgba(255, 255, 255, 0.5);
    background: transparent;
    border-radius: 20px;
}

.signup-btn,
.twitter-btn {
    width: 90%;
    padding: 12px;
    border-radius: 20px;
    margin: 10px auto;
    font-size: 14px;
    cursor: pointer;
    border: none;
    transition: 0.3s;
}

.signup-btn {
    background: #1ABC9C;
    color: white;
}

.signup-btn:hover {
    background: #16A085;
}

.twitter-btn {
    background: #3498DB;
    color: white;
}

.twitter-btn:hover {
    background: #2980B9;
}

.divider {
    margin: 10px 0;
    font-size: 14px;
    color: rgb(0, 0, 0);
}
</style>