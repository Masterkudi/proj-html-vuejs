<script>
export default {

}
</script>

<template>
    <div class="header-cover">
        <img src="../assets/img/hero-07-2x.jpg" alt="header-bg">

        <div class="menu d-flex">
            <img class="logo" src="../assets/img/author-logo-round.png" alt="">
            <ul class="navbar text-center">
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
                    <a class="nav-link disa" aria-disabled="true">My Blog</a>
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

            </ul>
        </div>
        <div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.header-cover img {
    position: absolute;
    max-width: 100%;
}

.menu {
    display: flex;
    justify-content: space-between;
}

.menu .logo {
    width: 10rem;
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
    padding: 1rem;
}

.menu .nav-link {
    padding-top: 1rem;
    border-top: 4px solid;
    
}
.menu .nav-item:hover {
    transition: 1s;
    color: #F4B429;
}


</style>