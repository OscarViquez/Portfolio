# Portfolio2.github.io
revamped version of the original
https://oscarviquez.github.io/Portfolio2.github.io/

.service {
    /* stops from getting to big and expand when the screen expands */
    max-width: 500px;
    margin: 0 auto;
}


.section__subtitle--intro {
        align-self: start;
        grid-column: -1 / 1;
        /* to get that lack of overlapping issue we do this */
        grid-row: 2;
        text-align: right;
        position: relative;
        left: -1.5em;
        width: calc(100% + 1.5em);

    }