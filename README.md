<svg viewBox="0 0 1200 200" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <defs>
        <style type="text/css">
            html, body{
                height: 100%;
                font-weight: 800;
            }

            svg {
                font-family: Helvetica, sans-serif;
            }

            svg {
                display: block;
                font: 10.5em 'Helvetica';
                width: 960px;
                height: 300px;
                margin: 0 auto;
            }

            .text-copy {
                fill: none;
                stroke: white;
                stroke-dasharray: 6% 29%;
                stroke-width: 5px;
                stroke-dashoffset: 0%;
                animation: stroke-offset 5.5s infinite linear;
            }

            .text-copy:nth-child(1){
                stroke: #264653;
                animation-delay: -1;
            }

            .text-copy:nth-child(2){
                stroke: #2a9d8f;
                animation-delay: -2s;
            }

            .text-copy:nth-child(3){
                stroke: #e9c46a;
                animation-delay: -3s;
            }

            .text-copy:nth-child(4){
                stroke: #f4a261;
                animation-delay: -4s;
            }

            .text-copy:nth-child(5){
                stroke: #e76f51;
                animation-delay: -5s;
            }

            @keyframes stroke-offset{
                100% {stroke-dashoffset: -35%;}
            }
        </style>
    </defs>

    <symbol id="s-text">
        <text text-anchor="middle" x="50%" y="80%">HACKERMAN</text>
    </symbol>

    <g class = "g-ants">
        <use xlink:href="#s-text" class="text-copy"></use>
        <use xlink:href="#s-text" class="text-copy"></use>
        <use xlink:href="#s-text" class="text-copy"></use>
        <use xlink:href="#s-text" class="text-copy"></use>
        <use xlink:href="#s-text" class="text-copy"></use>
    </g>
</svg>
