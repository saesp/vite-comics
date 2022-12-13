<script setup>
import { ref } from 'vue'
</script>


<template>
    <footer>
        <section class="section1">
            <ul>
                <li>
                    <a href="#">DIGITAL COMICS</a>
                </li>
                <li>
                    <a href="#">DIGITAL COMICS</a>
                </li>
                <li>
                    <a href="#">DIGITAL COMICS</a>
                </li>
                <li>
                    <a href="#">DIGITAL COMICS</a>
                </li>
                <li>
                    <a href="#">DIGITAL COMICS</a>
                </li>
            </ul>
        </section>
        <section class="section2 container">
            <div class="list-sect2">
                <div>
                    <h4>DC COMICS</h4>
                    <ul>
                        <li>
                            <a href="#">Comics</a>
                        </li>
                        <li>
                            <a href="#">Comics</a>
                        </li>
                        <li>
                            <a href="#">Comics</a>
                        </li>
                        <li>
                            <a href="#">Comics</a>
                        </li>
                        <li>
                            <a href="#">Comics</a>
                        </li>
                        <li>
                            <a href="#">Comics</a>
                        </li>
                        <li>
                            <a href="#">Comics</a>
                        </li>
                        <li>
                            <a href="#">Comics</a>
                        </li>
                    </ul>

                    <h4>SHOP</h4>
                    <ul>
                        <li>
                            <a href="#">Comics</a>
                        </li>
                        <li>
                            <a href="#">Comics</a>
                        </li>
                    </ul>
                </div>

                <div>
                    <h4>DC</h4>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                </div>

                <div>
                    <h4>SITES</h4>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                    <li>
                        <a href="#">Comics</a>
                    </li>
                </div>
            </div>
            <img src="../../public/img/dc-logo-bg.png" alt="">
        </section>
        <section class="section3 container">
            <button>SIGN-UP NOW!</button>
            <div>
                <h4>FOLLOW US</h4>
                <span>F</span>
                <span>T</span>
                <span>YT</span>
            </div>
        </section>
    </footer>
</template>

<style lang="scss" scoped>
@use '../style.scss' as *;


/* footer */
footer {
    background-image: url(../../public/img/footer-bg.jpg);
}

footer li {
    list-style-type: none;

    a {
        color: white;
    }
}


/* section 1 */
.section1 {
    width: 100%;
    padding: 50px 0;
    background-color: $blue_page;
    z-index: 100;

    ul {
        display: flex;
        align-items: center;
        justify-content: space-evenly;
    }
}


/* section 2 */
.section2 {
    padding-top: 50px;
    padding-bottom: 50px;
    display: flex;
    justify-content: space-between;

    .list-sect2 {
        gap: 50px;
        display: flex;
    }

    img {
        width: 400px;
    }
}

/* section 3 */
.section3 {
    background-color: gray;
    padding-top: 40px;
    padding-bottom: 40px;
    align-items: center;
    justify-content: space-between;
    display: flex;

    button {
        border: 1px solid $blue_page;
        padding: 10px
    }

    div {
        gap: 30px;
        display: flex;
    }

    h4 {
        color: $blue_page;
    }
}
</style>