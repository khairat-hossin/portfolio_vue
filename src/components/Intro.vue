<template>
    <div class="row mt-5 pt-5">
        <div class="col-sm-6 align-self-center">
            <p class="title-color">Hello, This is</p>
            <h1 class="mb-3 text-white">Khairat Hossin</h1>
            <h2>Fullstack Developer</h2>
            <p class="mt-3 text-white">
                A self-motivated and enthusiastic web developer with a deep
                interest in JavaScript. To work in the Software industry with
                modern web technologies of different local &amp; multinational
                Software/ IT agencies of Bangladesh and grow rapidly with
                increasing responsibilities.
            </p>
            <div class="my-5">
                <a href="/home#contact"
                    ><button type="button" class="me-4 btn btn-outline-success">
                        Get In Touch
                    </button>
                </a>
            </div>
        </div>

        <div class="col-sm-6 align-items-center text-center">
            <img
                src="../assets/images/profile.jpg"
                alt=""
                class="img-thumbnail rounded-circle"
                 style="width:60%; height: auto"
            />
        </div>
    </div>
</template>

<script>
export default {
    name: "Intro",
};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap');


.typing::before {
    content: '';
    position: absolute;
    top: 0;
    right: 0;
    width: 2px;
    height: 100%;
    background: #4FC3F7;
    animation: cursorBlink 0.8s steps(3) infinite;
}

@keyframes cursorBlink {

    0%,
    75% {
        opacity: 1;
    }

    76%,
    100% {
        opacity: 0;
    }
}

.typing {
    position: relative;
    -webkit-box-reflect: below 1px linear-gradient(transparent, #3333);
}

.typing h2 {
    position: relative;
    color: #4FC3F7;
    letter-spacing: 5px;
    font-size: 4rem;
    overflow: hidden;
    margin-bottom: 0;
    animation: type 5s steps(11) infinite;
}

@keyframes type {

    0%,
    100% {
        width: 0px;
    }

    30%,
    60% {
        width: 394.09px;
    }
}

@media(max-width: 330px) {
    .typing h2 {
        font-size: 3rem;
        animation: type 5s steps(10) infinite;
    }

    @keyframes type {

        0%,
        100% {
            width: 0px;
        }

        30%,
        60% {
            width: 305px;
        }
    }
}
</style>