<main style="height: calc(100vh - calc(60px + 1vh)) ; width: 95vw;">
    <div
        class="left"
        data-aos="fade-right"
        data-aos-duration="800"
        data-aos-offset="500"
        data-aos-easing="ease-in-sine"
    >
        <div class="content">
            <h2>Molecule</h2>
            <p>Text editor without pain</p>
            <span
                >Molecule is an native and lightweight text editor in Dart. Dive
                right in!</span
            >
            <br />
            <br />
            <button>Read more!</button>
        </div>
    </div>
    <div
        class="right"
        data-aos="fade-left"
        data-aos-offset="500"
        data-aos-easing="ease-in-sine"
        data-aos-duration="800"
    >
        <div class="preview">
            <div class="editor">
                <h2 style="font-family: 'Roboto', sans-serif; color: white;">
                    COMING SOON
                </h2>
            </div>
        </div>
    </div>
    <!-- <img src="./assets/icons/down.svg" alt="godown" id="downToFeatures"> -->
</main>

<style>
    main {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        width: 90vw;
        padding-left: 5vw;
        padding-right: 5vw;
    }
    main .right {
        width: 40vw;
        display: flex;
    }

    main .right .preview {
        margin-top: 5vw;
        background-repeat: no-repeat;
        background-position: center center;
        height: 600px;
        width: 40vw;
        background-image: url("/blob.svg");
        display: flex;
        justify-content: left;
        align-self: flex-end;
        margin-left: 5vw;
        margin-right: 5vw;
    }

    main .right .preview .editor {
        background-color: #2b3339;
        height: 350px;
        width: 500px;
        margin-top: 10vh;
        /* margin-left: -6vw; */
        position: relative;
        top: -5vh;
        left: -8vw;
        margin-right: 5vw;
        border-radius: 15px;
        box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }

    main .left {
        margin-top: -5vw;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    main .left .content {
        height: 200px;
        width: 40vw;
    }

    main .left .content h2 {
        font-family: "Roboto", sans-serif;
        color: #445055;
        font-size: 3vw;
        margin: 0;
        margin-bottom: 1vw;
    }

    main .left .content p {
        margin: 0;
        font-family: "Roboto", sans-serif;
        color: #999f93;
        /* color: #445055; */
        font-size: 2vw;
    }

    main .left .content span {
        margin: 0;
        font-size: 1.5vw;
        color: #999f93;
        font-family: "Roboto", sans-serif;
    }

    main .left .content button {
        box-shadow: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px,
            rgba(0, 0, 0, 0.06) 0px 2px 4px -1px;
        background: linear-gradient(
            135deg,
            rgba(231, 76, 60, 0.9) 0%,
            rgba(243, 156, 18, 0.9) 100%
        );
        color: white;
        height: 45px;
        width: 8vw;
        border: none;
        cursor: pointer;
        border-radius: 7px;
        font-family: "Roboto", sans-serif;
        font-weight: 600;
        font-size: 2vh;
    }
</style>
