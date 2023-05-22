<svelte:head>
<title>Артемьев Ярослав</title>
</svelte:head>

<div class='container'>
    <div class='info'>
        <div class='animate-background'>
            <div class='container info-container'>
                <div class='info-text'>
                    <h1>
                        <p class='animate-text-1'>Персональный сайт</p>
                        <p class='text-2'>Артемьева Ярослава</p>
                    </h1>
                </div>
                <h2 class='subtitle'>
                    Приветствую Вас на своем сайте. <br>Спасибо, что посетили мою страницу.<br> Давайте знакомиться.
                </h2>
                <div style='color:black' class='scroll-button animate-scroll' tabindex='0'>
                    <a href='/about'>Узнать обо мне</a>
                    <div class='arrow'>→</div>
                </div>
            </div>
        </div>
    </div>
</div>

<div class='background-div'></div>
<style>
    .info {
        text-align: center;
        position: relative;
    }

    .info-container {
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: left;
        align-items: start;
    }

    .container {
        max-width: 1400px;
        margin: 190px 0 0 2.5rem;
    }

    .info h1 {
        font-size: 4rem;
        margin: 0;
    }

    .info h1 p {
        position: relative;
        font: inherit;
        margin: 0;
        text-align: left;
        line-height: 130%;
        width: fit-content;
        font-weight: 800;
        letter-spacing: -0.03em;
    }

    .info h2 {
        max-width: 65ch;
        font-weight: 200;
        margin-top: 0.50rem;
    }

    .background-div {
        background-color: #ecebe8;
        width: 100%;
        height: 56vh;
        margin: -205px auto;
    }


    .info .info-text {
        position: relative;
    }

    .scroll-button {
        display: flex;
        border: none;
        outline: none;
        cursor: pointer;
    }

    .scroll-button .arrow {
        margin-left: 0.50rem;
    }
</style>
