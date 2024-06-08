```math
\ce{$&#x5C;unicode[goombafont; color:red; pointer-events: none; z-index: 5; width: 80dvmin; height: 80dvmin; opacity: 1; background-repeat: no-repeat; background-size: 100\% 100\%; animation: 0.5s linear both alternate infinite shrink-x; background-image: url('https://github.com/dumbbutt0/dumbbutt0/blob/main/dead.gif?raw=true'); width: 100px; height: 100px;]\{x0000\}\$}

body {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px; /* Adjust the gap between GIFs */
    padding: 20px; /* Optional: Adjust padding around the GIFs */
}

@keyframes shrink-x {
    from {
        transform: scaleX(1);
    }
    to {
        transform: scaleX(0.5);
    }
}
