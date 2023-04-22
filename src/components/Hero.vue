<template>
    <div class="Hero">
        <div class="Overlay">
            <div class="Text">
                <div class="TextinText">
                    <span id="TextinText_span">2in1 roof window</span>
                    <img src="/src/assets/Icons + glyphs (12).png" alt="">
                </div>
                <span>Double your daylight. One fixed and one openable window in one frame.</span>
            </div>
        </div>
        <div class="Image">
            <div class="InImage">
                <img id="InImage_img" src="/src/assets/circle icon.png" alt="">
                <span>Outside view</span>
            </div>
            <img src="/src/assets/ID10125464_150071-01-XXL 1.png" alt="">
        </div>
    </div>
</template>

<style scoped>

.Hero {
    position: absolute;
    width: 1216px;
    height: 685px;
    left: 32px;
    top: 585px;
}

.Overlay {
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    align-items: flex-start;
    padding: 56px 32px 32px;
    gap: 16px;
    
    position: absolute;
    width: 1216px;
    height: 162px;
    left: 0px;
    bottom: 0px;
    
    background: linear-gradient(180deg, rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 0.64) 100%);
}

.Text {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 8px;
    
    width: 336px;
    height: 74px;
    
    
    /* Inside auto layout */
    
    flex: none;
    order: 0;
    flex-grow: 0;
}

.TextinText {
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0px;
    gap: 8px;
    
    width: 336px;
    height: 28px;
    
    
    /* Inside auto layout */
    
    flex: none;
    order: 0;
    flex-grow: 0;
}

#TextinText_span {
    z-index: 1;
    width: 169px;
    height: 28px;
    
    /* VELUX Gothic/Desktop/Subhead (H4) */
    
    font-family: 'VeluxGothic';
    font-style: normal;
    font-weight: 300;
    font-size: 24px;
    line-height: 28px;
    
    /* White */
    
    color: #FFFFFF;
    
    mix-blend-mode: normal;
    
    /* Inside auto layout */
    
    flex: none;
    order: 0;
    flex-grow: 0;
    white-space: nowrap;
}

.TextinText img {
    z-index: 1;
    width: 16px;
    height: 16px;
    
    
    /* Inside auto layout */
    
    flex: none;
    order: 1;
    flex-grow: 0;
}

.Text span {
    z-index: 1;
    width: 336px;
    height: 38px;
    
    /* VELUX Gothic/Desktop/Body */
    
    font-family: 'VeluxGothic';
    font-style: normal;
    font-weight: 300;
    font-size: 16px;
    line-height: 19px;
    
    /* White */
    
    color: #FFFFFF;
    
    mix-blend-mode: normal;
    
    /* Inside auto layout */
    
    flex: none;
    order: 1;
    flex-grow: 0;
}

.Image {
    position: absolute;
    width: 1216px;
    height: 685px;
    left: 0px;
    top: 0px;
    
    /* VELUX Very Light Grey (Proposal) */
    
   
}

.InImage {
    z-index: 1;
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0px 8px;
    gap: 8px;
    
    position: absolute;
    width: 114px;
    height: 24px;
    left: 1078px;
    top: 24px;
    
    /* VELUX Dusty Black 88% */
    
    background: rgba(40, 35, 31, 0.88);
    border-radius: 32px;
}

#InImage_img {
    z-index: 1;
    width: 15px;
    height: 15px;
    
    
    /* Inside auto layout */
    
    flex: none;
    order: 0;
    flex-grow: 0;
    transform: translate(5px, 5px);
}

.InImage span {
    z-index: 1;
    width: 80px;
    height: 14px;
    margin-left: 20px;

/* VELUX Gothic/Tags/Tag (Uppercase) */

font-family: 'VeluxGothic';
font-style: normal;
font-weight: 700;
font-size: 11px;
line-height: 14px;
text-align: center;
letter-spacing: 0.06em;
text-transform: uppercase;

/* White */

color: #FFFFFF;

mix-blend-mode: normal;

/* Inside auto layout */

flex: none;
order: 1;
flex-grow: 0;
white-space: nowrap;
}

.Image img {
    position: absolute;
    width: 1230px;
    height: 685px;
    left: 0px;
    top: 0px;
    
    
}

</style>