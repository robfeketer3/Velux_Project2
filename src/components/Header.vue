<template>
    <div class="Header">
        <div class="Text">
            <h1>Sloped roof windows</h1>
            <span id="text">Add daylight, fresh air and a feeling of more space into your home with VELUX roof windows.<br><br>
                Explore our products below.</span>
        </div>
    </div>
</template>

<style scoped>

.Header {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 72px 40px;
    
    position: absolute;
    width: 1280px;
    height: 364px;
    left: 0px;
    top: 151px;
    
    /* White */
    
    
}

.Text {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 0px;
    gap: 32px;
    
    width: 800px;
    height: 220px;
    
    
    /* Inside auto layout */
    
    flex: none;
    order: 0;
    flex-grow: 0;
}

.Text h1 {
    width: 592px;
    height: 76px;
    
    /* VELUX Gothic/Desktop/Title 1 (H1) */
    
    font-family: 'VeluxGothic';
    font-style: normal;
    font-weight: 300;
    font-size: 64px;
    line-height: 76px;
    /* identical to box height */
    
    
    /* VELUX Dusty Black */
    
    color: #28231F;
    
    mix-blend-mode: normal;
    
    /* Inside auto layout */
    
    flex: none;
    order: 0;
    flex-grow: 0;
}

#text {
    z-index: 1;
    width: 800px;
    height: 112px;
    
    /* VELUX Gothic/Desktop/Subhead (H4) */
    
    font-family: 'VeluxGothic';
    font-style: normal;
    font-weight: 300;
    font-size: 24px;
    line-height: 28px;
    
    /* VELUX Dusty Black */
    
    color: black;
    
    mix-blend-mode: normal;
    
    /* Inside auto layout */
    
    flex: none;
    order: 1;
    flex-grow: 0;
}

@media (max-width: 375px) {
    
}

</style>