It is possible to host external fonts on ao3 by exporting them to SVG files, and linking in those svgs.









<style>

kbd {
    background: none !important;
    border: none !important;
    box-shadow: none !important;
}
.skinless {
    display: none;
}

.skin_show.hidden {
    display: inline !important;
    
}

.skin_show.hidden img {
    visibility: visible !important;
}

.svg_font {
    display: inline-flex;
    flex-direction: row;
    filter: invert(100%) drop-shadow(1px 1px 0px rgb(0, 0, 0));
    align-items: flex-start;
    user-select: text;
    -webkit-user-drag: none;
    user-drag: none;
    /* width: 2em; */
}

.svg_font img {
    /* display: inline-block; */
    color: rgb(255, 255, 255);
    /* padding: 0.1em; */
    /* display: block; */
    height: 1em;
    /* font-size: 0; */
}


.SelectContainer {
    padding: 1em;
    max-width: 320px;
    max-height: 259px;
    margin: auto;
}


.SelectContainer > div {
    display: block;
}


.SelectContainer>.DEV_CHAPTER_SELECT {
    border: solid white 2px;
    box-shadow: 0 0 0.1em 0.1em black;
    background-color: rgb(0, 0, 0);
    width: fit-content;
    padding: 0.2em;
    color: white;
}

.SelectContainer>.DEV_CHAPTER_SELECT .TIME_ELAPSED {
    margin-left: 2em;
}


.DEV_CHAPTER_SELECT .regular-align {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
}

.DEV_CHAPTER_SELECT .heart-align {
    display: flex;
    align-items: center;
}

.DEV_CHAPTER_SELECT .HEART {
    display: block;
    background-image: url("/Undertale_SOUL.png");
    /* position: absolute; */
    background-size: contain;
    content: '';
    margin-right: 0.5em;
    width: 0.7em;
    height: 0.7em;
}

.DEV_CHAPTER_SELECT kbd {
    font-family: '8BitOperator JVE', monospace;
    font-size: 1.2em;
    text-shadow: 1px 1px 0px #000000;
    margin: 0;
}

.DEV_CHAPTER_SELECT .TOP .svg_font{
    transform: translateY(0.2em);
}


.DEV_CHAPTER_SELECT .NAME {
    padding-right: 1em;
}

</style>
<div class="SelectContainer">
    <p class="DEV_CHAPTER_SELECT" align="center">
        <span class="heart-align">
            <span class="hidden HEART"></span>
                <span class="regular-align">
                    <span class="TOP">
                        <kbd><span class="NAME"><span class="svg_font"><span class="skin_show hidden"><img alt="N" src="/img/8bitoperator-JVE/N_8bitoperator-JVE.svg"><img alt="O" src="/img/8bitoperator-JVE/O_8bitoperator-JVE.svg"><img alt="E" src="/img/8bitoperator-JVE/E_8bitoperator-JVE.svg"><img alt="L" src="/img/8bitoperator-JVE/L_8bitoperator-JVE.svg"><img alt="L" src="/img/8bitoperator-JVE/L_8bitoperator-JVE.svg"><img alt="E" src="/img/8bitoperator-JVE/E_8bitoperator-JVE.svg"></span><span class="skinless">NOELLE</span></span></span></kbd> 
                        <span
                        class="skinless">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span><kbd><span
                        class="TIME_ELAPSED"><span class="svg_font"><span class="skin_show hidden"><img alt="1" src="/img/8bitoperator-JVE/one_8bitoperator-JVE.svg"><img alt="7" src="/img/8bitoperator-JVE/seven_8bitoperator-JVE.svg"><img alt=":" src="/img/8bitoperator-JVE/colon_8bitoperator-JVE.svg"><img alt="2" src="/img/8bitoperator-JVE/two_8bitoperator-JVE.svg"><img alt="6" src="/img/8bitoperator-JVE/six_8bitoperator-JVE.svg"><img alt=":" src="/img/8bitoperator-JVE/colon_8bitoperator-JVE.svg"><img alt="4" src="/img/8bitoperator-JVE/four_8bitoperator-JVE.svg"><img alt="1" src="/img/8bitoperator-JVE/one_8bitoperator-JVE.svg"></span><span class="skinless">17:26:41</span></span></span></kbd>
                    </span>
                        <br><kbd><span class="LOCATION"><span class="svg_font"><span class="skin_show hidden"><img alt="C" src="/img/8bitoperator-JVE/C_8bitoperator-JVE.svg"><img alt="l" src="/img/8bitoperator-JVE/l_8bitoperator-JVE.svg"><img alt="i" src="/img/8bitoperator-JVE/i_8bitoperator-JVE.svg"><img alt="f" src="/img/8bitoperator-JVE/f_8bitoperator-JVE.svg"><img alt="f" src="/img/8bitoperator-JVE/f_8bitoperator-JVE.svg"><img alt="s" src="/img/8bitoperator-JVE/s_8bitoperator-JVE.svg"><img alt="—" src="/img/8bitoperator-JVE/emdash_8bitoperator-JVE.svg"><img alt="S" src="/img/8bitoperator-JVE/S_8bitoperator-JVE.svg"><img alt="h" src="/img/8bitoperator-JVE/h_8bitoperator-JVE.svg"><img alt="o" src="/img/8bitoperator-JVE/o_8bitoperator-JVE.svg"><img alt="p" src="/img/8bitoperator-JVE/p_8bitoperator-JVE.svg"></span><span class="skinless">Cliffs—Shop</span></span></span></kbd>
            </span>
        </span>
    </p>
</div>