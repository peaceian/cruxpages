# Crux pages
This project is a multi-page about the introduction of Crux, by using Bootstrap.<br>
All Crux reference from WiKi, ref='https://zh.wikipedia.org/zh-tw/%E5%8D%97%E5%8D%81%E5%AD%97%E5%BA%A7' <br>
The sidebar is fixed at the left, and the screen or window is smaller than 992px, changing into static at the top.<br>

     .sidebar {
            background-image: url(Ctx_crux.gif);
            position: fixed;
            background-size: cover;
            background-position: center 0;
            height: 100vh;
        }
        @media (max-width:992px) {
            .sidebar {
                position: static;
                height: 30vh;
                background-image: none;
                background-color: black;
            }

            .sidebarbox {
                height: auto;
            }
        }
The images will enlarge while the mouse hovers on.
    
    .zoom:hover {
            scale: 2.0;
            transition: 1s;
        }
