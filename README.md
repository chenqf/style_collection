

## 水波纹效果

<style>
    .water-waves {
        margin: 0 auto;
        border-radius: 50%;
        overflow: hidden;
        border: 1px solid silver;
        position: relative;
        width: 100px;
        height: 100px;
    }

    .water-waves__item {
        -webkit-animation: water-waves linear infinite;
        animation: water-waves linear infinite;
        position: absolute;
        width: 200%;
        height: 200%;
    }

    .water-waves__item--1 {
        top: 50%;
        background: #33cfff;
        opacity: .7;
        border-radius: 40%;
        left: -25%;
        -webkit-animation-duration: 5s;
        animation-duration: 5s;
    }

    .water-waves__item--2 {
        top: 45%;
        background: #0eaffe;
        opacity: .5;
        border-radius: 35%;
        left: -35%;
        -webkit-animation-duration: 7s;
        animation-duration: 7s;
    }

    .water-waves__item--3 {
        top: 50%;
        border-radius: 33%;
        opacity: .3;
        left: -35%;
        background: #0f7ae4;
        -webkit-animation-duration: 11s;
        animation-duration: 11s;
    }

    @-webkit-keyframes water-waves {
        0% {
            -webkit-transform: rotate(0deg);
            transform: rotate(0deg);
        }
        100% {
            -webkit-transform: rotate(360deg);
            transform: rotate(360deg);
        }
    }

    @keyframes water-waves {
        0% {
            -webkit-transform: rotate(0deg);
            transform: rotate(0deg);
        }
        100% {
            -webkit-transform: rotate(360deg);
            transform: rotate(360deg);
        }
    }
</style>

<div class="water-waves">
    <div class="water-waves__item water-waves__item--1"></div>
    <div class="water-waves__item water-waves__item--2"></div>
    <div class="water-waves__item water-waves__item--3"></div>
</div>