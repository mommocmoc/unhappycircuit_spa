        <script>
            import {onMount} from 'svelte';
            import Howler from './Howler.svelte';
            import Typed from 'typed.js';
            let titles;
            let typingArea;
            let options = {
                strings: ["한글로 쓰인 별 사이 쪽글"],
                typeSpeed: 500,
                showCursor:false,
            }
            onMount(() => {
                typingArea = titles.querySelectorAll('.typing');
                typingArea.forEach(element => {
                    var typed = new Typed(element, options);
                });
                //  var typed = new Typed(typingArea[0], options);
                //  var typedMedium = new Typed(typingArea[1], options);
            })
            

            function handle() {
                // sound.play()
            }
        </script>
        <style>
            .xLarge {
                font-size: 140px;
            }
        </style>

        <div bind:this={titles} class="child w3-container w3-black">
            <a href="/list">
                <div class="large-container w3-hide-small w3-hide-medium">
                        <h1 class="xLarge typing"> </h1>
                </div>
                <div class="medium-container vertical w3-hide-small w3-hide-large">
                    <h1 class="medium typing"> </h1>
                </div>

                <div class="mobile-container vertical w3-hide-medium w3-hide-large">
                    <h1 id='type' class="w3-xxlarge typing"> </h1>
                </div>
            </a>
        </div>