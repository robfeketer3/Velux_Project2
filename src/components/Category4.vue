<template>
    <div class="Category">
        <div class="Overlay">
            <div class="Text">
                <div class="TextinText">
                    <span id="TextinText_span">Roof balcony, and terrace</span>
                    <img src="/src/assets/iconnum3.png" alt=".">
                </div>
                <span id="TextinText_span2">Transform your home and welcome in the outdoors.</span>
            </div>
        </div>
        <div class="Image">
            <div class="InImage">
                <img id="InImage_img" src="/src/assets/Button_ On top (Change view) - Dark.png" alt=".">
            </div>
        <img src="/src/assets/ID10052863_122291-01-XXL.png" alt=".">
        </div>
    </div>
</template>

<style scoped>

#TextinText_span {
    position: absolute;
    left: 700px;
    top: 1910px;
    color: white;
    z-index: 1;

    font-family: 'VeluxGothic';
    font-style: normal;
    font-weight: 300;
    font-size: 24px;
    line-height: 28px;
}

.TextinText img {
    z-index: 1;
    position: absolute;
    left: 950px;
    top: 1915px;
}

#TextinText_span2 {
    z-index: 1;
    position: absolute;
    left: 700px;
    top: 1950px;
    color: white;

    font-family: 'VeluxGothic';
    font-style: normal;
    font-weight: 300;
    font-size: 16px;
    line-height: 19px;

}

#InImage_img {
    z-index: 1;
    position: absolute;
    width: 115px;
    height: 25px;
    left: 1140px;
    top: 1690px;
}

.Image img {
    position: absolute;
    width: 600px;
    max-height: 100%;
    left: 670px;
    top: 1670px;
}

@media (max-width: 376px) {

    .Image img {
        margin-top: -80px;
        margin-left: -20px;
        max-width: 350px;
        height: 280px;
        top: 1845px;
        left: 32.5px;
    }

}

</style>