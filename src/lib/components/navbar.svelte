<nav
    id="navbar"
    data-aos="fade-down"
    data-aos-duration="800"
    data-aos-offset="500"
    data-aos-easing="ease-in-sine"
>
    <div class="head">
        <h1>Molecule</h1>
    </div>
    <button on:click={() => {window.location.href = "https://github.com/m-editor/molecule"}}>Get Molecule</button>
</nav>

<style>
    #navbar {
        /* margin-top: 1vh; */
        height: 60px;
        width: 90vw;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        padding-left: 5vw;
        padding-right: 5vw;
        padding-top: 1vh;
        background: white;
    }

    /* #navbar .head img {
    width: 50px;
    height: 50px;
    margin-right: 30px;
} */

    #navbar .head {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
    }

    #navbar .head h1 {
        color: #ee7c3f;
        font-family: "Roboto", sans-serif;
        font-weight: 700;
        font-size: 30px;
    }

    #navbar button {
        box-shadow: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px,
            rgba(0, 0, 0, 0.06) 0px 2px 4px -1px;
        background: linear-gradient(
            135deg,
            rgba(231, 76, 60, 0.9) 0%,
            rgba(243, 156, 18, 0.9) 100%
        );
        color: white;
        height: 35px;
        width: 150px;
        border: none;
        cursor: pointer;
        border-radius: 7px;
        transition: all ease-in-out 500ms;
        font-family: "Roboto", sans-serif;
        font-size: 2vh;
        font-weight: 700;
    }

    #navbar button:active {
        box-shadow: none;
    }

    #navbar button:hover {
        transform: translateY(-3px);
    }
</style>
