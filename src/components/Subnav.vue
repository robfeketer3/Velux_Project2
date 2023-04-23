<template>
    <div class="Subnav">
        <div class="Sections">
            <div class="Section">
                <span>Products</span>
                <div class="Select">
                    <span>Sloped roof windows</span>
                    <img src="/src/assets/Icons + glyphs (11).png" alt=".">
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>

.Subnav {
display: flex;
flex-direction: column;
justify-content: center;
align-items: flex-start;
padding: 15px 40px 15px 16px;
gap: 8px;

position: absolute;
width: 1280px;
height: 56px;
left: 0px;
top: 95px;

/* White */

background: #FFFFFF;
}

.Sections {
display: flex;
flex-direction: row;
align-items: flex-start;
padding: 0px;

width: 279px;
height: 21px;


/* Inside auto layout */

flex: none;
order: 0;
flex-grow: 0;
}

.Section {
display: flex;
flex-direction: row;
align-items: flex-start;
padding: 0px 24px;
gap: 8px;

width: 279px;
height: 21px;


/* Inside auto layout */

flex: none;
order: 0;
flex-grow: 0;
}

.Section span {
width: 58px;
height: 19px;

/* VELUX Gothic/Desktop/Body */

font-family: 'VeluxGothic';
font-style: normal;
font-weight: 300;
font-size: 16px;
line-height: 19px;
/* identical to box height */


/* VELUX Dusty Black */

color: #28231F;

mix-blend-mode: normal;

/* Inside auto layout */

flex: none;
order: 0;
flex-grow: 0;
}

.Select {
display: flex;
flex-direction: row;
align-items: center;
padding: 0px;
gap: 8px;

width: 165px;
height: 21px;


/* Inside auto layout */

flex: none;
order: 1;
flex-grow: 0;
}

.Select span {
width: 147px;
height: 21px;

/* VELUX Gothic/Desktop/Body (Strong) */

font-family: 'VeluxGothic';
font-style: normal;
font-weight: 700;
font-size: 16px;
line-height: 21px;
/* identical to box height */

letter-spacing: 0.01em;

/* VELUX Dusty Black */

color: #28231F;

mix-blend-mode: normal;

/* Inside auto layout */

flex: none;
order: 0;
flex-grow: 0;
}

.Select img {
width: 10px;
height: 10px;


/* Inside auto layout */

flex: none;
order: 1;
flex-grow: 0;
}

@media (max-width: 376px) {
    .Subnav {
    z-index: 1;
    position: fixed;
    }
}

</style>