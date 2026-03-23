/* Body Layout - Centers the card on the screen */
body {
    font-family: var(--ff-kumbh);
    background-color: var(--blue-600);
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 1.5rem;
}

.card {
    background-color: white;
    width: 100%;
    max-width: 350px;
    border-radius: 15px;
    overflow: hidden; /* Clips the background pattern to the border radius */
    box-shadow: 0 50px 100px -20px rgba(8, 70, 94, 0.5);
    text-align: center;
}

/* Header & Images */
.card__header {
    position: relative;
    height: 140px;
}

.card-bg {
    width: 100%;
    display: block;
}

.victor-img {
    border: 5px solid white;
    border-radius: 50%;
    position: absolute;
    left: 50%;
    bottom: 0;
    transform: translate(-50%, 50%); /* Moves image halfway down to overlap */
}

/* Card Body Content */
.card__body {
    padding: 4.5rem 1.5rem 1.5rem; /* Large top padding to make room for overlapping img */
    border-bottom: 1px solid var(--gray-100);
}

.name {
    font-size: var(--fs-stats);
    color: var(--navy-950);
    margin-bottom: 0.5rem;
}

.age {
    color: var(--gray-500);
    font-weight: 400;
    margin-left: 0.5rem;
}

.location {
    color: var(--gray-500);
    font-size: 0.875rem;
    letter-spacing: 1px;
}

/* Statistics Footer */
.card__stats {
    padding: 1.5rem;
}

.stats-list {
    list-style: none;
    display: flex;
    justify-content: space-around;
}

.stats-list li {
    display: flex;
    flex-direction: column;
}

.stats-val {
    display: block;
    color: var(--navy-950);
    font-size: 1.125rem;
}

.stats-label {
    display: block;
    color: var(--gray-500);
    font-size: 0.625rem;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    margin-top: 0.25rem;
}