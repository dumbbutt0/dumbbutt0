\documentclass{article}
\usepackage{verbatim}

\begin{document}

\begin{verbatim}
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
    width: 80dvmin;
    height: 80dvmin;
    opacity: 1;
    background-repeat: no-repeat;
    background-size: 100% 100%;
    animation: 0.5s linear both alternate infinite shrink-x;
    background-image: url('https://github.com/dumbbutt0/dumbbutt0/blob/main/dead.gif?raw=true');
    width: 100px; /* Adjust the width of each GIF */
    height: 100px; /* Adjust the height of each GIF */
}

/* Animation for shrinking the GIF horizontally */
@keyframes shrink-x {
    from {
        transform: scaleX(1);
 
