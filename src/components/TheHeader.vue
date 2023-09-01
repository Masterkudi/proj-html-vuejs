<script>
export default {
    name: 'MyComponent'
}
</script>

<template>
    <div class="header-cover">
        <img src="../assets/img/hero-07-2x.jpg" alt="header-bg">

        <div class="menu d-flex">
            <img class="logo" src="../assets/img/author-logo-round.png" alt="">
            <ul class="navbar d-flex">
                <li class="nav-item">
                    <a class="nav-link" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">About Me</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Testimonials</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">My Blog</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Meetup</a>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" href="#" role="button"
                        aria-expanded="false">Shop</a>
                    <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">Single Product</a></li>
                        <li><a class="dropdown-item" href="#">Variable Product</a></li>
                    </ul>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#"><i class="fa-solid fa-cart-shopping"></i></a>
                </li>
            </ul>
        </div>
        <div>
            <div class="title-container d-flex">
                <div class="title-row">
                    <div class="col-6 ps-8 my-component">
                        <h1>Damon Vaughn</h1>
                        <h2>Best-Selling Author And The Most Influential Public Intellectual in The Western World Right Now.
                        </h2>

                        <h4>– The New York Times</h4>
                    </div>
                </div>
            </div>
        </div>
        <div>
            <!--
                <div class="banner d-flex">
                <div class="banner-row">
                    <div class="col-3 bg-white">
                        <img src="../assets/img/book-widget.png" alt="">
                        Latest Book Release
                        D. VAUGHN AUTOBIOGRAPHY

                        Donec fringilla nunc eu turpis dignissim, at euismod sapien tincidunt. Maecenas eleifend congue
                        cursus.
                    </div>
                </div>
            </div>
            -->
        </div>
    </div>
</template>

<style scoped>
.header-cover img {
    position: absolute;
    width: 100%;
}

.menu {
    display: flex;
    justify-content: space-between;
}

.menu .logo {
    width: 10rem;
    position: absolute;
    padding: 1rem;
}

.menu .navbar {
    position: absolute;
    color: #fff;
    padding: 0 2rem;
    margin: 0;
}

.menu .nav-item {
    list-style: none;
    padding: 1rem;
    margin: 0 1rem;
}

.menu li {
    border-top: 4px solid transparent;
}

.menu li:hover {
    transition: 1s;
    color: #F4B429;
}

.title-container {
    position: absolute;
}

.col-6 {
    position: relative;
    color: #fff;
}

.col-6.my-component {
    padding-left: 10rem;
    padding-top: 5rem;
}

.my-component h1 {
    font-family: 'Kristi', cursive;
    color: #F4B429;
    font-size: 4rem;
}

.my-component h2 {
    font-family: 'Playfair Display', serif;
    font-size: 2.5rem;
}

.my-component h4 {
    color: #A6A6A6;
}

.banner-row {
    display: flex;
    align-self: center;
    position: absolute;
}

.col-3 {
    padding: 2rem;
    display: flex;
    flex-direction: row;
    position: relative;
    align-content: flex-end;
}
.col-3 img {
    width: 10rem;
}

</style>