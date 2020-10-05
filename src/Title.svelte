<script>
    export let classList = 'main';
    export let link = '/'
</script>
<style>
    .main {
    font-size: 100px;
    margin-bottom: 0%;
    padding-bottom: 0%;
    font-weight: normal;
    }
    p.engSubs {
    font-family: NotoSans, EBSHunminjeongeumSBA;
    font-style: normal;
    display: flexbox;
    line-height: normal;
    }
</style>
<a href={link}>
    <h1 class={classList}>한글로 쓰인 별 사이 쪽글</h1>
    <!-- <span class="engSubs">A Interstellar Message Written in Hangeul</span></h1> -->
    <p class="engSubs w3-xxxlarge">A Interstellar Message Written in Hangeul</p>
</a>