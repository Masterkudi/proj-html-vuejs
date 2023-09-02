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
            <div>
                <div class="banner d-flex">
                    <div class="banner-row">
                        <div class="col-3 d-flex">
                            <div class="bg-white flex-direction-row">
                                <img src="../assets/img/book-widget.png" alt="">
                            
                                <h2>Latest Book Release</h2>
                                <h4>D. VAUGHN AUTOBIOGRAPHY</h4>
                                <p>
                                    Donec fringilla nunc eu turpis dignissim, at euismod sapien tincidunt. Maecenas eleifend
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

<style scoped>
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

.menu li {
    margin-top: 4px solid #F4B429;
}

.menu li:hover {
    transition: 1s;
    color: #F4B429;
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
    display: flex;
    position: relative;
    flex-direction: row-reverse;
    width: 100%;
}

.col-3 {
    padding: 5rem;
    display: flex;
    position: relative;
    align-content: flex-end;
}
</style>