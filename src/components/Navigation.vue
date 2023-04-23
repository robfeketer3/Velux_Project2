<template>
  <div id="navigation">
      <div id="main-nav">
          <p id="Stories">Stories</p>
          <p id="Spaces">Spaces</p>
          <p id="Products">Products</p>
      </div>
      <div id="logo">
          <img id="logo_1st" src="../assets/Logo.png" alt="Logo">
          <img id="logo_2nd" src="../assets/Logo (1).png" alt="Logo2">
          <img id="ArrowToRight" src="../assets/Icons + glyphs.png" alt="ArrowToRight">
      </div>
      <div id="right-side">
          <button>
              <img id="ArrowToRight" src="../assets/Icons + glyphs.png" alt="ArrowToRight">
              <p>Get Started</p>
          </button>
          <img src="../assets/Burger.png" alt="Burger_Menu">
      </div>
  </div>
  </template>

  <style scoped>
  /* Navigation */

#navigation {
  position: fixed;
  z-index: 10;
  width: 1280px;
  height: 95px;
  left: 0px;
  top: 0px;
  background: #FFFFFF;
}

/* Right-Side */

#right-side {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  align-items: center;
  padding: 0px;
  gap: 40px;
  position: absolute;
  width: 198px;
  height: 48px;
  right: 25px;
  top: calc(50% - 48px/2 - 0.5px);
}

#right-side button {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 13px 0px 14px;
  gap: 8px;
  width: 134px;
  height: 48px;
  flex: none;
  order: 0;
  flex-grow: 0;
  border: none;
  background-color: transparent;
  outline: none;
}

#right-side button img {
  width: 16px;
  height: 16px;
  flex: none;
  order: 1;
  flex-grow: 0;
}

#right-side button p {
  width: 110px;
  height: 21px;
  font-family: 'VeluxGothic', 'Times New Roman', Times, serif;
  font-style: normal;
  font-weight: 900;
  font-size: 16px;
  line-height: 21px;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  color: #28231F;
  flex: none;
  order: 5;
  flex-grow: 0;
  white-space: nowrap;
}

#right-side img {
  width: 24px;
  height: 24px;
  flex: none;
  order: 1;
  flex-grow: 0;
}


/* Main Nav */

#main-nav {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 0px;
  gap: 32px;
  position: absolute;
  width: 236px;
  height: 21px;
  left: 40px;
  top: calc(50% - 21px/2 - 0.5px);
}

#Stories {
  width: 53px;
  height: 21px;
  font-family: 'VeluxGothic';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 21px;
  color: #28231F;
  flex: none;
  order: 0;
  flex-grow: 0;
}

#Spaces {
  width: 53px;
  height: 21px;
  font-family: 'VeluxGothic';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 21px;
  color: #28231F;
  flex: none;
  order: 1;
  flex-grow: 0;
}

#Products {
  width: 53px;
  height: 21px;
  font-family: 'VeluxGothic';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 21px;
  color: #28231F;
  flex: none;
  order: 2;
  flex-grow: 0;
}

/* Logo */

#logo {
  position: absolute;
  width: 140px;
  height: 47.16px;
  left: calc(50% - 140px/2);
  top: 23px;
}

#logo_1st {
  z-index: 1;
  position: absolute;
  left: 8.67%;
  right: 4.67%;
  top: 24%;
  bottom: 22.01%;
}

#logo_2nd {
  position: absolute;
  left: 0%;
  right: 0%;
  top: 0%;
  bottom: 0%;
  background: #EE0000;
}

/* Mobile */

@media (max-width: 376px) {
  #Stories, #Spaces, #Products, #right-side img {
    visibility: hidden;
  }

  #logo, #logo_1st {
    width: 100px;
  }

  #logo_2nd {
    width: 115px;
  }

   #right-side, #right-side button {
    position: absolute;
    top: 25px;
    left: 100px;
  }

  #ArrowToRight {
    position: absolute;
    visibility: visible;
    top: 14px;
    left: 310px;
  }

  #logo {
    position: absolute;
    top: 50px;
    left: 20px;
  }

}

  </style>
