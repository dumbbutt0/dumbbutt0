\ce{$&#x5C;unicode[goombafont; color:red; pointer-events: none; z-index: 5; position: fixed; left: 50dvi; top: 50dvb; width: 80dvmin; background-position: 0 0; height: 80dvmin; translate: -50\% -50\%; opacity: 1; background-repeat: no-repeat; background-size: 100\% 100\%; height: 100px; width: 1000px; animation: 0.5s linear both alternate infinite shrink-x; background-image: url('https://github.com/dumbbutt0/dumbbutt0/blob/main/dead.gif?raw=true');]\{x0000\}\$}

body {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px; /* Adjust the gap between GIFs */
    padding: 20px; /* Optional: Adjust padding around the GIFs */
}

.gif-item {
    pointer-events: none;
    z-index: 5;
    position: fixed;
    left: 50dvi;
    top: 50dvb;
    width: 80dvmin;
    height: 80dvmin;
    translate: -50\% -50\%;
    opacity: 1;
    background-repeat: no-repeat;
    background-size: 100\% 100\%;
    animation: 0.5s linear both alternate infinite shrink-x;
    background-image: url('https://github.com/dumbbutt0/dumbbutt0/blob/main/dead.gif?raw=true');
    width: 1000px; /* Adjust the width of each GIF */
    height: 100px; /* Adjust the height of each GIF */
}

/* Animation for shrinking the GIF horizontally */
@keyframes shrink-x {
    from {
        transform: scaleX(1);
    }
    to {
        transform: scaleX(0.5);
    }
}
