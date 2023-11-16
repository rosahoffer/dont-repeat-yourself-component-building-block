<section>
    <nav>
        <a href="/" class="nav-button">
            <img src="/images/home-icon.svg" alt="home button">
            <p>Home</p>
        </a>
        <a href="/" class="nav-button">
            <img src="/images/all-players-icon.svg" alt="all players button">
            <p>All Players</p>
        </a>
        <a href="/" class="nav-button">
            <img src="/images/all-teams-icon.svg" alt="all teams button">
            <p>All Teams</p>
        </a>
        <a href="/" class="nav-button">
            <img src="/images/all-tournaments-icon.svg" alt="all tournaments button">
            <p>All <br> Tournaments</p>
        </a>
        <a href="/" class="nav-button">
            <img src="/images/current-tournament-icon.svg" alt="all players button">
            <p>Current <br> Tournament</p>
        </a>
    </nav>
</section>

<style>

    section{
        margin-left: auto;
        height: 100vh;
        max-width: 8rem;
        padding: 1rem;
    }
    
    nav{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        height: 100%;
        width: 100%;
        border-radius: 10px;
        gap: 4rem;
        box-shadow: var(--box-shadow);
    }

    .nav-button{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
        text-decoration: none;
        font-family: var(--secondary-font-family);
        font-size: 0.8rem;
        font-weight: 500;
        color: var(--selected-background-color)
    }

    .nav-button:last-child{
        color: var(--button-background-color)
    }

    .nav-button img{
        max-width: 2rem;
    }

    .nav-button:hover{
        opacity: 0.5;
    }

    .nav-button:focus{
        background-color: var(--hover-background-color);
        border-radius: 5px;
        min-width: 5rem;
    }

</style>