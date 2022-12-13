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
// $blue_page: #0282f9;

/* footer */
footer li {
    list-style-type: none;
}


/* section 1 */
footer .section1 {
    width: 100%;
    padding: 50px 0;
    background-color: $blue_page;
}

.section1 ul {
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}

/* section 2 */
footer .section2 {
    /* padding-left: 100px; */
    padding-top: 50px;
    padding-bottom: 50px;
    gap: 50px;
    display: flex;
}

/* section 3 */
footer .section3 {
    /* padding-left: 100px; */
    padding-top: 50px;
    padding-bottom: 50px;
    align-items: center;
    justify-content: space-between;
    display: flex;
}

.section3 div {
    gap: 30px;
    display: flex;
}
</style>