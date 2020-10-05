<script>
    import Title from '../Title.svelte'
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
        margin-bottom: 20.5px;
    }

    h2 {
        font-size: 50px;
    }
</style>
<div class="child w3-container w3-black w3-center">
    <!-- 일반 모니터 -->
    <div class="large-container w3-hide-small w3-hide-medium">
        <Title classList="main" />
        <!-- <a href="/">
            <h1 class="main">한글로 쓰인 별 사이 쪽글</h1>
            <p class="engSubs w3-xxxlarge">A Interstellar Message Written in Hangeul</p>
        </a> -->

        <h2>쪽글에 관하여</h2>
        <p class="engSubs w3-xlarge">About the message [<a href="/about_kor">한국어</a>/<a href="/about_eng">English</a>]
        </p>
        <a href="/contents_of_message">
            <h2>쪽글내리</h2>
            <p class="engSubs w3-xlarge">Contents of the message</p>
        </a>
        <a href="/full_text_of_message">
            <h2>모든쪽글</h2>
            <p class="engSubs w3-xlarge">Full text of the message</p>
        </a>
        <a href="/unicode_digits_of_message">
            <h2>이씩셈쪽글</h2>
            <p class="engSubs w3-xlarge">Full unicode digits of the message</p>
        </a>
        <a href="/appendix">
            <h2>덧붙임글</h2>
            <p class="engSubs w3-xlarge">Appendix</p>
        </a>
    </div>
    <!-- 타블릿 -->
    <div class="medium-container w3-hide-small w3-hide-large">
        <a href="/">
            <h1 class="medium">한글로 쓰인 별 사이 쪽글</h1>
            <p class="engSubs"> A Interstellar Message Written in Hangeul</p>
        </a>
        <h1 class="w3-xxxlarge">쪽글에 관하여</h1>
        <p class="engSubs w3-xlarge">About the message [<a href="/about_kor">한국어</a>/<a href="/about_eng">English</a>]
        </p>
        <a href="/contents_of_message">
            <h1 class="w3-xxxlarge">쪽글내리</h1>
            <p class="engSubs w3-xlarge">Contents of the message</p>
        </a>
        <a href="/full_text_of_message">
            <h1 class="w3-xxxlarge">모든쪽글</h1>
            <p class="engSubs w3-xlarge">Full text of the message</p>
        </a>
        <a href="/unicode_digits_of_message">
            <h1 class="w3-xxxlarge">이씩셈쪽글</h1>
            <p class="engSubs w3-xlarge">Full unicode digits of the message</p>
        </a>
        <a href="/appendix">
            <h1 class="w3-xxxlarge">덧붙임글</h1>
            <p class="engSubs w3-xlarge">Appendix</p>
        </a>
    </div>
    <!-- 모바일 -->
    <div class="mobile-container w3-hide-medium w3-hide-large">
        <a href="/">
            <h1 class="semi-medium">한글로 쓰인 별 사이 쪽글</h1>
            <p class="engSubs w3-medium"> A Interstellar Message Written
                in
                Hangeul</p>
        </a>
        <h1 class="semi-medium">쪽글에 관하여</h1>
        <p class="engSubs w3-medium">About the message [<a href="/about_kor">한국어</a>/<a
                href="/about_eng">English</a>]</p>
        <a href="/contents_of_message">
            <h1 class="semi-medium">쪽글내리</h1>
            <p class="engSubs w3-medium">Contents of the message</p>
        </a>
        <a href="/full_text_of_message">
            <h1 class="semi-medium">모든쪽글</h1>
            <p class="engSubs w3-medium">Full text of the message</p>
        </a>
        <a href="/unicode_digits_of_message">
            <h1 class="semi-medium">이씩셈쪽글</h1>
            <p class="engSubs w3-medium">Full unicode digits of the message</p>
        </a>
        <a href="/appendix">
            <h1 class="semi-medium">덧붙임글</h1>
            <p class="engSubs w3-medium">Appendix</p>
        </a>
    </div>
</div>