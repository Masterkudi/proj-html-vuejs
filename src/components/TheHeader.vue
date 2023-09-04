<script>
export default {
    name: 'MyComponent',
    components: {

    }
}
</script>

<template>
    <header>
        <div class="header-cover">

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
                        <ul class="dropdown-menu bg-black text-white">
                            <li><a class="dropdown-item" href="#">Single Product</a></li>
                            <li><a class="dropdown-item" href="#">Variable Product</a></li>
                        </ul>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#"><i class="fa-solid fa-cart-shopping"></i></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contact Me</a>
                    </li>
                </ul>
            </div>
            <div>
                <div class="title-container d-flex">
                    <div class="title-row">
                        <div class="col-6 ps-8 my-component">
                            <h1>Damon Vaughn</h1>
                            <h2>Best-Selling Author And The Most Influential Public Intellectual in The Western World Right
                                Now.
                            </h2>

                            <h4>– The New York Times</h4>
                        </div>
                    </div>
                </div>
            </div>
            <div class="banner">
                <div class="banner-row d-flex">
                    <div class="col-4">
                        <div class="p-5 bg-white d-flex flex-direction-row align-items-flex-end">
                            <img src="../assets/img/book-widget.png" alt="">
                            <div>
                                <h2>Latest Book Release</h2>
                                <h4>D. VAUGHN AUTOBIOGRAPHY</h4>
                                <p>
                                    Donec fringilla nunc eu turpis dignissim, at euismod sapien tincidunt. Maecenas
                                    eleifend
                                    congue cursus.
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<style scoped lang="scss">
.header-cover {
    display: flex;
    flex-direction: column;
    background-image: url(../assets/img/hero-07-2x.jpg);
    background-color: rgba(0, 0, 0, );
    background-position-y: center;
    background-position-x: center;
    width: 100vw;
    min-height: 100vh;
}

.menu {
    display: flex;
    justify-content: space-between;
    max-height: 10rem;
    margin-bottom: 10rem;
}

.menu .logo {
    width: 10rem;
    display: flex;
    position: relative;
    padding: 1rem;
}

.menu .navbar {
    position: relative;
    color: #fff;
    padding: 0 2rem;
    margin: 0;
}

.menu .nav-item {
    list-style: none;
    padding: 2rem 1rem;
    margin: 2rem 0rem;
}


.menu li:hover {
    transition: 1s;
    color: #F4B429;
    margin-top: 2px solid #F4B429;
}

.title-row {
    padding: 10rem;
}

.title-container {
    position: absolute;
}

.col-6 {
    position: relative;
    color: #fff;
}


.my-component h1 {
    font-family: 'Kristi', cursive;
    color: #F4B429;
    font-size: 4rem;
}

.my-component h2 {
    font-family: 'Playfair Display', serif;
    font-size: 2.5rem;
    font-weight: 600;
    line-height: 4rem;
}

.my-component h4 {
    color: #A6A6A6;
}

.banner-row {
    position: absolute;
    flex-direction: row-reverse;
    align-items: flex-end;
    width: 100%;
}

.col-3 {
    padding: 5rem;
    display: flex;
    position: relative;
    align-content: flex-end;
}
</style>