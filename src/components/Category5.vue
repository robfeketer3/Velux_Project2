<template>
    <div class="Category">
        <div class="Overlay">
            <div class="Text">
                <div class="TextinText">
                    <span id="TextinText_span">Special function windows</span>
                    <img src="/src/assets/iconnum3.png" alt=".">
                </div>
                <span id="TextinText_span2">Praesent commodo cursus magna, vel scelerisque<br> nisl consectetur et.</span>
            </div>
        </div>
        <div class="Image">
            <div class="InImage">
                <img id="InImage_img" src="/src/assets/Button_ On top (Change view) - Dark.png" alt=".">
            </div>
        <img src="/src/assets/ID10132836_XXL 1.png" alt=".">
        </div>
    </div>
</template>

<style scoped>

#TextinText_span {
    position: absolute;
    left: 65px;
    top: 2290px;
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
    left: 320px;
    top: 2295px;

    
}

#TextinText_span2 {
    z-index: 1;
    position: absolute;
    left: 65px;
    top: 2330px;
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
    left: 500px;
    top: 2060px;
}

.Image img {
    position: absolute;
    width: 600px;
    max-height: 100%;
    left: 32px;
    top: 2040px;
}

@media (max-width: 376px) {
    *{
        visibility: hidden;
    }
}

</style>