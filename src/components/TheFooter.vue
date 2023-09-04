<script>
export default {

}
</script>

<template>
    <footer>
        <div class="footer-cover">
            <div class="footer-text d-flex">
                <div class="logo">
                    <img src="../assets/img/author-logo-round.png" alt="">
                </div>
                <div class="about">
                    <h5>ABOUT ME</h5>
                    <p>
                        Vivamus suscipit tortor eget felis <br> porttitor volutpat. Nulla quis lorem <br> ut libero
                        malesuada <br>
                        feugiat. Vivamus suscipit tortor <br> eget felis porttitor volutpat.
                    </p>
                </div>
                <div class="links">
                    <h5>USEFUL LINKS</h5>
                    <ul>
                        <li><i class="fa-solid fa-chevron-right"></i> Latest Books</li>
                        <li><i class="fa-solid fa-chevron-right"></i> Upcoming Events</li>
                        <li><i class="fa-solid fa-chevron-right"></i> Recent Articles</li>
                        <li><i class="fa-solid fa-chevron-right"></i> Business Enquiries</li>
                        <li><i class="fa-solid fa-chevron-right"></i> Visit My Foundation</li>
                    </ul>
                </div>
                <div class="info">
                    <h5>CONTACT INFO</h5>
                    <p>63 E. Studebaker Street Bolingbrook, IL 60440</p>
                    <p>Phone: (800)000-0000</p>
                    <p>Mobile: (800)000-0000</p>
                    <p>Email: info@your-company.com</p>
                    <div class="social-icons">
                        <a href="https://www.facebook.com/"><i class="fa-brands fa-facebook-f"></i></a>
                        <a href="https://twitter.com/"><i class="fa-brands fa-x-twitter"></i></a>
                        <a href="https://instagram.com/"><i class="fa-brands fa-instagram"></i></a>
                        <a href="https://youtube.com/"><i class="fa-brands fa-youtube"></i></a>
                        <a href="https://linkedin.com/"><i class="fa-brands fa-linkedin-in"></i></a>
                    </div>
                </div>
            </div>
            <div>
                <h6 class="copyright text-center p-5 m-0">© Copyright 2012 - 2023 | Avada Theme by <a href="https://avada.com/about-us/">ThemeFusion</a> | All
                    Rights Reserved | Powered by <a href="https://wordpress.org/">WordPress</a></h6>
            </div>
        </div>
    </footer>
</template>

<style scoped>
.footer-cover {
    background-image: url(../assets/img/footer-3.jpg);
    color: #fff;
    justify-content: space-evenly;
    position: relative;
}

.footer-text .logo,
.about,
.links,
.info {
    padding: 4rem;
}

.footer-text h5 {
    margin-bottom: 2rem;
}

.footer-text .links ul {
    list-style: none;
    padding-left: 0;
}

.links li:hover {
    color: #F4B429;
}

.footer-text img {
    align-self: center;
    width: 10rem;
}

.social-icons a {
    color: #fff;
    padding: .5rem;
}
.social-icons a:hover {
    color: #0B84FC;
}
.copyright a {
    text-decoration: none;
    color: #fff;
}
.copyright a:hover {
    color: #F4B429;
}
</style>