<script>
    import {
        Howl,
        Howler
    } from 'howler';
    import {
        onMount
    } from 'svelte';

    export let src;
    let soundSrc = [];
    let buttons;
    let topButton;
    let pauseButton;
    let playButton;

    soundSrc.push(src);
    export let sound = new Howl({
        src: soundSrc,
        autoplay: false,
        loop: true,
        html5:true,
        onplayerror: function () {
            sound.once('unlock', function () {
                sound.play();
            });
        }
    })
    sound.play();
    let soundState = {
        playing: true
    };

    onMount(() => {
        topButton = buttons.querySelector('#top');
        pauseButton = buttons.querySelector('#pause');
        playButton = buttons.querySelector('#play');

    })

    window.addEventListener("scroll", scrollFunc);

    function handleSound() {
        soundState.playing = !soundState.playing;
        if (soundState.playing === true) {
            sound.play();
        } else {
            sound.pause();
        }
    }

    function scrollFunc() {
        var y = window.scrollY;
        if (y >= 300) {
            topButton.className = "w3-display-bottomright w3-black w3-xlarge to-top w3-button w3-animate-opacity"
            playButton.className = "w3-black w3-xlarge playing w3-button w3-opacity-max"
            pauseButton.className = "w3-black w3-xlarge pause w3-button w3-animate-fading w3-opacity-max"
        } else {
            topButton.className = "w3-display-bottomright w3-black w3-xlarge to-top w3-button w3-hide"
            playButton.className = "w3-black w3-xlarge playing w3-button"
            pauseButton.className = "w3-black w3-xlarge pause w3-button w3-animate-fading w3-opacity-off"
        }
    }

    function handleScroll() {
        let scrollOptions = {
            top : 0,
            behavior : 'smooth'
        }
        window.scrollTo(scrollOptions);
    }
</script>


<div bind:this={buttons} class="w3-container w3-display-bottomleft">
    {#if soundState.playing}
    <button on:click={handleSound} id="play" class="w3-black w3-xlarge playing w3-button">></button>
    {:else}
    <button on:click={handleSound} id="pause" class="w3-black w3-xlarge pause w3-button w3-animate-fading">=</button>
    {/if}
    <button on:click={handleScroll} id="top" class="w3-display-bottomright w3-black w3-xlarge to-top w3-button w3-hide">↑</button>
</div>

<style>
    button {
        font-size:3em;
        color: aliceblue;
        
    }
    button#top{
        margin-right: 2rem;
    }
    
        div {
            position: -webkit-sticky;
            /* Safari */
            position: sticky;
            bottom: 0;
        }
</style>