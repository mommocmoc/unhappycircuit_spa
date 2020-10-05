<script>
    import Title from '../Title.svelte'
</script>
<style>
    h1.main {
        font-size: 4em;
        text-align: center;
        font-family: 'EBSHunminjeongeumSBA';
        font-weight: normal;
    }

    p.engSubs {
        font-family: NotoSans, EBSHunminjeongeumSBA;
        font-style: normal;
        display: flexbox;
        font-size: 1.666em;
    }
    h2{
        font-size: 3.333em;
        line-height: normal;
    }
    div.contents{
        font-size : 1.666em;
        font-family: EBSHunminjeongeumSBA;
        line-height: normal;
    }
</style>

<div class="w3-container w3-black w3-center">
    <!-- 일반 모니터 -->

    <div class="large-container w3-hide-small w3-hide-medium">
        <Title classList="main" link="/list" />
    </div>
    <a href="/list">
        <div class="w3-center w3-hide-small w3-hide-large">
            <h1 class="medium">한글로 쓰인 별 사이 쪽글</h1>
            <p class="engSubs w3-xlarge"> A Interstellar Message Written in Hangeul</p>
        </div>
        <div class="w3-center w3-hide-medium w3-hide-large">
            <h1 class="semi-medium">한글로 쓰인 별 사이 쪽글</h1>
            <p class="engSubs w3-medium"> A Interstellar Message Written
                in
                Hangeul</p>
        </div>
    </a>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">이씩셈</h2>
        <p class="engSubs w3-xlarge">Binary</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">이씩셈</h1>
        <p class="engSubs w3-medium">Binary</p>
    </div>
    <div class="contents w3-center">
        <p>
            0000<br>0001<br>0010<br>0011<br>0100<br>0101<br>0110<br>0111<br>1000<br>1001
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">같음</h2>
        <p class="engSubs w3-xlarge">Equals</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">같음</h1>
        <p class="engSubs w3-medium">Equals</p>
    </div>
    <div class="contents w3-center">
        <p>
            0000=0000
            <br>0001=0001
            <br>0010=0010
            <br>0011=0011
            <br>00100=0100
            <br>0101=0101
            <br>0110=0110
            <br>0111=0111
            <br>1000=1000
            <br>1000=1000
            <br>1001=1001
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">십씩셈글</h2>
        <p class="engSubs w3-xlarge">Decimal numbers</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">십씩셈글</h1>
        <p class="engSubs w3-medium">Decimal numbers</p>
    </div>
    <div class="contents w3-center">
        <p>
            0000=0000
            <br>0001=0001
            <br>0010=0010
            <br>0011=0011
            <br>00100=0100
            <br>0101=0101
            <br>0110=0110
            <br>0111=0111
            <br>1000=1000
            <br>1000=1000
            <br>1001=1001
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">덧셈, 뺄셈, 곱셈</h2>
        <p class="engSubs w3-xlarge">Addition, subtraction, multiplication</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">덧셈, 뺄셈, 곱셈</h1>
        <p class="engSubs w3-medium">Addition, subtraction, multiplication</p>
    </div>
    <div class="contents w3-center">
        <p>
            1+1=2
            <br>2-1=1
            <br>1-2=-1
            <br>2*2=4
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">나눗셈</h2>
        <p class="engSubs w3-xlarge">Division</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">나눗셈</h1>
        <p class="engSubs w3-medium">Division</p>
    </div>
    <div class="contents w3-center">
        <p>
            4/2=2
            <br>1/2=0.5
            <br>1-2=-1
            <br>1/3=0.3333…
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">제곱셈</h2>
        <p class="engSubs w3-xlarge">Exponentiation</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">제곱셈</h1>
        <p class="engSubs w3-medium">Exponentiation</p>
    </div>
    <div class="contents w3-center">
        <p>
            3^2=9
            <br>9^(1/2)=3
            <br>2^-1=1/2
            <br>2^(1/2)=1.414235...
            <br>10^12=1000000000000
            <span class="w3-xlarge w3-hide-small">
                <br>10^-31=0.0000000000000000000000000000001
            </span>
            <span class="w3-center w3-xlarge w3-hide-medium w3-hide-large">
                <br>10^-31=0.00000000000000<br>00000000000000001
            </span>
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">한글</h2>
        <p class="engSubs w3-xlarge">Korean characters</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">한글</h1>
        <p class="engSubs w3-medium">Korean characters</p>
    </div>
    <div class="contents w3-center">
        <p>
            [ㄱ,ㄴ,ㄷ,ㄹ,ㅁ,ㅂ,ㅅ,ㅇ,ㅈ,ㅊ,ㅋ,ㅌ,ㅍ,ㅎ]=홑닿소리
            <br>[ㄲ,ㄸ,ㅃ,ㅆ,ㅉ]=겹닿소리
            <br>
            <br>[[ㅏ,ㅐ,ㅑ,ㅒ,ㅓ,ㅔ,ㅕ,ㅖ,ㅣ],[ㅗ,ㅛ,ㅜ,ㅠ,ㅡ]]=홑홀소리
            <br>2^(1/2)=[ㅘ,ㅙ,ㅚ,ㅝ,ㅞ,ㅟ,ㅢ]=겹홀소리
            <br>
            <br>[ㄱ,ㄴ,ㄷ,ㄹ,ㅁ,ㅂ,ㅅ,ㅇ,ㅈ,ㅊ,ㅋ,ㅌ,ㅍ,ㅎ]=홑끝소리
            <br>[ㄲ,ㅆ,ㄳ,ㄵ,ㄶ,ㄺ,ㄻ,ㄼ,ㄽ,ㄾ,ㄿ,ㅀ,ㅄ]=겹끝소리
            <br>
            <br>닿소리=[홑닿소리,겹닿소리]
            <br>홀소리=[홑홀소리,겹홀소리]
            <br>끝소리=[홑끝소리,겹끝소리]
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">모아쓰기</h2>
        <p class="engSubs w3-xlarge">Combination</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">모아쓰기</h1>
        <p class="engSubs w3-medium">Combination</p>
    </div>
    <div class="contents w3-center">
        <p>
            닿소리+홀소리+끝소리
            <br>ㅎ+ㅏ+ㄴ=한
            <br>ㄱ+ㅡ+ㄹ=글
            <br>한글=[닿소리,홀소리,끝소리]
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">셈글</h2>
        <p class="engSubs w3-xlarge">Korean words for numbers</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">셈글</h1>
        <p class="engSubs w3-medium">Korean words for numbers</p>
    </div>
    <div class="contents w3-center">
        <p>
            [1,2,3,4,5,6,7,8,9,10...]=덧셈글
            <br>[-1,-2,-3,-4,-5,-6,-7,-8,-9,-10...]=뺄셈글
            <br>0=빈셈글
            <br>[덧수,뺄수,0]=바른셈글
            <br>
            <br>[2,3,5,7,11,13,17,19,23,29,31...]=씨셈글
            <br>2^77232917-1=가장 큰 씨셈글
            <br>
            <br>1/2=0.5=모자란셈글
            <br>1/3=0.3333...=되풀이모자란셈글
            <br>3.14159...=막된모자란셈글
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">셈글월</h2>
        <p class="engSubs w3-xlarge">Korean sentences for operations</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">셈글월</h1>
        <p class="engSubs w3-medium">Korean sentences for operations</p>
    </div>
    <div class="contents w3-center">
        <p>
            1+1=2
            <br>1더하기1은2
            <br>1 더하기 1은 2이다.
            <br>1과 1을 더하면 2가 된다.
            <br>
            <br>2-1=1
            <br>2빼기1은1
            <br>2 빼기 1은 1이다.
            <br>2에서 1을 빼면 1이 된다.
            <br>
            <br>2*2=4
            <br>2곱하기2는4
            <br>2 곱하기 2는 4이다.
            <br>2와 2를 곱하면 4가 된다.
            <br>2를 2곱하면 4가 된다.
            <br>
            <br>4/2=2
            <br>4나누기2는2
            <br>4 나누기 2는 2이다.
            <br>4를 2로 나누면 2가 된다.
            <br>
            <br>3^2=9
            <br>3의2제곱은9
            <br>3의 2제곱은 9이다.
            <br>3을 2제곱하면 9가 된다.
            <br>
            <br>9^(1/2)=3
            <br>9의1/2제곱은3
            <br>9의 1/2제곱은 3이다.
            <br>9를 1/2제곱하면 3이 된다.
            <br>9의 2제곱뿌리는 3이다.
            <br>
            <br>2^-1=1/2
            <br>2의-1제곱은1/2
            <br>2의 -1제곱은 1/2이다.
            <br>2를 -1제곱하면 1/2이 된다.
            <br>1/2는 2의 거꾸로셈글이다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">꼴</h2>
        <p class="engSubs w3-xlarge">Geometric shape</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">꼴</h1>
        <p class="engSubs w3-medium">Geometric shape</p>
    </div>
    <div class="contents w3-center">
        <p>
            a^2+b^2=c^2
            <br>바른모세모꼴
            <br>
            <br>둘레지름견줌=3.14159...
            <br>지름=둘레/둘레지름견줌
            <br>가른지름=지름*1/2
            <br>넓이=둘레지름견줌*가른지름^2
            <br>넓이_동그라미꼴=둘레지름견줌*가른지름^2
            <br>동그라미꼴의 넓이는 둘레지름견줌과 가른지름^2의 곱이다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">참, 거짓</h2>
        <p class="engSubs w3-xlarge">True, false</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">참, 거짓</h1>
        <p class="engSubs w3-medium">True, false</p>
    </div>
    <div class="contents w3-center">
        <p>
            1=1 참
            <br>1&gt;2 거짓
            <br>
            <br>1=하나
            <br>2=둘
            <br>1/2=둘 중 하나
            <br>
            <br>a=참 b=거짓 a∧b=거짓
            <br>a는 참이고 b는 거짓이면 a∧b는 거짓이다.
            <br>a와 b 둘 중 하나가 거짓이면 a∧b는 거짓이다.
            <br>
            <br>a=참 b=거짓 a∨b=참
            <br>a는 참이고 b는 거짓이면 a∨b는 참이다.
            <br>a 또는 b 둘 중 하나가 참이면 a∨b는 참이다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">작은바탕이</h2>
        <p class="engSubs w3-xlarge">Proton, neutron, electron</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">작은바탕이</h1>
        <p class="engSubs w3-medium">Proton, neutron, electron</p>
    </div>
    <div class="contents w3-center">
        <p>
            덧작은바탕이
            <br>빈작은바탕이
            <br>뺄바탕알갱이=바탕이둘레구름
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">덧뺄바탕크기</h2>
        <p class="engSubs w3-xlarge">Quantity of electric charge</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">덧뺄바탕크기</h1>
        <p class="engSubs w3-medium">Quantity of electric charge</p>
    </div>
    <div class="contents w3-center">
        <p>
            덧뺄바탕크기_덧작은바탕이=-덧뺄바탕크기_뺄바탕알갱이
            <br>덧작은바탕이의 덧뺄바탕크기는 뺄바탕알갱이의 뺄셈글이다.
            <br>
            <br>빈작은바탕이의 덧뺄바탕크기는 0이다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">바탕크기</h2>
        <p class="engSubs w3-xlarge">Mass</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">바탕크기</h1>
        <p class="engSubs w3-medium">Mass</p>
    </div>
    <div class="contents w3-center">
        <p>
            바탕크기_덧작은바탕이=바탕크기_뺄바탕알갱이*1836
            <br>덧작은바탕이의 바탕크기는 뺄바탕알갱이의 1836곱이다.
            <br>
            <br>빈작은바탕이의 바탕크기는 덧작은바탕이의 1.00138곱이다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">Kg</h2>
        <p class="engSubs w3-xlarge">Unit of mass</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">Kg</h1>
        <p class="engSubs w3-medium">Unit of mass</p>
    </div>
    <div class="contents w3-center">
        <p>
            덧작은바탕이의 바탕크기는 1.67262319*10^-27kg이다.
            <br>빈작은바탕이의 바탕크기는 1.67492747*10^-27kg이다.
            <br>뺄바탕알갱이의 바탕크기는 9.10938356*10^-31kg이다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">바탕이</h2>
        <p class="engSubs w3-xlarge">Atom</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">바탕이</h1>
        <p class="engSubs w3-medium">Atom</p>
    </div>
    <div class="contents w3-center">
        <p>
            바탕이=덧작은바탕이+빈작은바탕이+뺄바탕알갱이
            <br>
            <br>수소 바탕이=덧작은바탕이*1+빈작은바탕이*0
            <br>수소 바탕이는 덧작은바탕이 1개 더하기 빈작은바탕이 0개이다.
            <br>수소 바탕이는 덧작은바탕이 1개와 빈작은바탕이 0개의 더하기이다.
            <br>수소는 덧작은바탕이 1개와 빈작은바탕이 0개의 맺음이다.
            <br>
            <br>탄소는 덧작은바탕이 6개와 빈작은바탕이 6개의 맺음이다.
            <br>질소는 덧작은바탕이 7개와 빈작은바탕이 7개의 맺음이다.
            <br>산소는 덧작은바탕이 8개와 빈작은바탕이 8개의 맺음이다.
            <br>인은 덧작은바탕이 15개와 빈작은바탕이 16개의 맺음이다.
            <br>나트륨은 덧작은바탕이 11개와 빈작은바탕이 12개의 맺음이다.
            <br>알루미늄은 덧작은바탕이 13개와 빈작은바탕이 14개의 맺음이다.
            <br>규소는 덧작은바탕이 14개와 빈작은바탕이 14개의 맺음이다.
            <br>염소는 덧작은바탕이 17개와 빈작은바탕이 18개의 맺음이다.
            <br>아르곤은 덧작은바탕이 18개와 빈작은바탕이 21개의 맺음이다.
            <br>철은 덧작은바탕이 26개와 빈작은바탕이 30개의 맺음이다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">바탕이모임</h2>
        <p class="engSubs w3-xlarge">Molecule</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">바탕이모임</h1>
        <p class="engSubs w3-medium">Molecule</p>
    </div>
    <div class="contents w3-center">
        <p>
            바탕이모임=바탕이+바탕이
            <br>
            <br>질소 바탕이모임은 질소 바탕이 2개의 맺음이다.
            <br>산소 바탕이모임은 산소 바탕이 2개의 맺음이다.
            <br>이산화탄소는 탄소 바탕이 1개와 산소 바탕이 2개의 맺음이다.
            <br>물은 수소 바탕이 2개와 산소 바탕이 1개의 맺음이다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">m</h2>
        <p class="engSubs w3-xlarge">Unit of length</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">m</h1>
        <p class="engSubs w3-medium">Unit of length</p>
    </div>
    <div class="contents w3-center">
        <p>
            덧작은바탕이의 가른지름은 0.84*10^-15m이다.
            <br>빈작은바탕이의 가른지름은 0.8*10^-15m이다.
            <br>뺄바탕알갱이의 가른지름은 2.82*10^-15m이다.
            <br>
            <br>1m=100cm
            <br>1000m=1km
            <br>10^-9m=1nm
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">되돌이떨림</h2>
        <p class="engSubs w3-xlarge">Wave</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">되돌이떨림</h1>
        <p class="engSubs w3-medium">Wave</p>
    </div>
    <div class="contents w3-center">
        <p>
            [0 1 2 1 0 -1 -2 -1 0]=1셈 되돌이떨림
            <br>[0 1 2 1 0 -1 -2 -1 0 1 2 1 0 -1 -2 -1 0]=2셈 되돌이떨림
            <br>
            <br>떨림높이=2~-2
            <br>떨림너비=너비_1셈=1m
            <br>
            <br>되돌이동안=동안_1셈=1초=1s
            <br>
            <br>떨림셈=1셈/1초=1Hz
            <br>되돌이떨림의 떨림셈은 1셈/1초이다.
            <br>1Hz는 1초에 1셈 떨림이다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">초</h2>
        <p class="engSubs w3-xlarge">Unit of time</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">초</h1>
        <p class="engSubs w3-medium">Unit of time</p>
    </div>
    <div class="contents w3-center">
        <p>
            빛빠르기=299792458m/1s=299792458m/s
            <br>빛빠르기는 299792458m/s이다.
            <br>빛은 1초에 299792458m의 빠르기로 움직인다.
            <br>빛의 299792458m 움직임동안은 1초이다.
            <br>
            <br>1000000000Hz=1GHz
            <br>1s=1000ms
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">더움크기</h2>
        <p class="engSubs w3-xlarge">Unit of Temperature</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">더움크기</h1>
        <p class="engSubs w3-medium">Unit of Temperature</p>
    </div>
    <div class="contents w3-center">
        <p>
            1kg/m/s^2=1Pa
            <br>101325Pa
            <br>
            <br>더움크기_물_101325Pa=273K~373K
            <br>101325Pa의 물의 더움크기는 273K~373K이다.
            <br>101325Pa에서 물의 더움크기는 273K에서 373K 사이이다.
            <br>
            <br>0K=-273°C
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">해모임</h2>
        <p class="engSubs w3-xlarge">Solar System</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">해모임</h1>
        <p class="engSubs w3-medium">Solar System</p>
    </div>
    <div class="contents w3-center">
        <p>
            해=우리별
            <br>작은해붙이
            <br>밝은해붙이
            <br>우리해붙이
            <br>붉은해붙이
            <br>큰해붙이
            <br>고리해붙이
            <br>흰해붙이
            <br>푸른해붙이
            <br>
            <br>해모임=[해,(작은,밝은,우리,붉은,큰,고리,흰,푸른)해붙이]
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">해, 우리해붙이</h2>
        <p class="engSubs w3-xlarge">Sun, Earth</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">해, 우리해붙이</h1>
        <p class="engSubs w3-medium">Sun, Earth</p>
    </div>
    <div class="contents w3-center">
        <p>
            해의 바탕크기는 1.988*10^30kg이다.
            <br>해의 가른지름은 6.957*10^8m이다.
            <br>해의 더움크기는 5772K이다.
            <br>
            <br>우리해붙이의 바탕크기는 5.972*10^24kg이다.
            <br>우리해붙이의 가른지름은 6.378*10^6m이다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">떨어짐너비</h2>
        <p class="engSubs w3-xlarge">Distances of Solar System</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">떨어짐너비</h1>
        <p class="engSubs w3-medium">Distances of Solar System</p>
    </div>
    <div class="contents w3-center">
        <p>
            떨어짐너비_해~우리해붙이=150000000km
            <br>해~우리해붙이의 떨어짐너비는 150000000km이다.
            <br>해와 우리해붙이 사이의 떨어짐너비는 150000000km이다.
            <br>해와 우리해붙이는 150000000km 떨어져 있다.
            <br>
            <br>해와 작은해붙이는 58000000km 떨어져 있다.
            <br>해와 밝은해붙이는 108000000km 떨어져 있다.
            <br>해와 붉은해붙이는 228000000km 떨어져 있다.
            <br>해와 큰해붙이는 778000000km 떨어져 있다.
            <br>해와 고리해붙이는 1427000000km 떨어져 있다.
            <br>해와 흰해붙이는 2880000000km 떨어져 있다.
            <br>해와 푸른해붙이는 4513000000km 떨어져 있다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">이끌림돌기</h2>
        <p class="engSubs w3-xlarge">Earth's orbit</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">이끌림돌기</h1>
        <p class="engSubs w3-medium">Earth's orbit</p>
    </div>
    <div class="contents w3-center">
        <p>
            되돌이동안_이끌림돌기_우리해붙이~해=31536000초=1해
            <br>우리해붙이의 해 이끌림돌기의 되돌이동안은 1해이다.
            <br>우리해붙이는 해의 바깥 둘레를 1해 동안 이끌림돌기한다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">스스로돌기</h2>
        <p class="engSubs w3-xlarge">Earth's rotation</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">스스로돌기</h1>
        <p class="engSubs w3-medium">Earth's rotation</p>
    </div>
    <div class="contents w3-center">
        <p>
            되돌이동안_스스로돌기_우리해붙이=86400초=1날
            <br>우리해붙이의 스스로돌기의 되돌이동안은 1날이다.
            <br>우리해붙이는 1날 동안 스스로돌기한다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">달</h2>
        <p class="engSubs w3-xlarge">Moon</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">달</h1>
        <p class="engSubs w3-medium">Moon</p>
    </div>
    <div class="contents w3-center">
        <p>
            달=우리해붙이벗
            <br>우리해붙이와 달은 3844*10^5m 떨어져 있다.
            <br>달의 바탕크기는 7.342*10^22kg이다.
            <br>달의 가른지름는 1.737*10^6m이다.
            <br>
            <br>2332800초=27날
            <br>달은 우리해붙이의 바깥 둘레를 27날 동안 이끌림돌기한다.
            <br>
            <br>30날=1달
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">나이</h2>
        <p class="engSubs w3-xlarge">Age</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">나이</h1>
        <p class="engSubs w3-medium">Age</p>
    </div>
    <div class="contents w3-center">
        <p>
            나이_해=4.603*10^9해
            <br>해의 나이는 46억해이다.
            <br>
            <br>우리해붙이의 나이는 45억해이다.
            <br>
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">빛해</h2>
        <p class="engSubs w3-xlarge">Light year</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">빛해</h1>
        <p class="engSubs w3-medium">Light year</p>
    </div>
    <div class="contents w3-center">
        <p>
            9.46*10^12km=1빛해
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">놀뜀별과 우리해붙이</h2>
        <p class="engSubs w3-xlarge">Location of Earth and pulsars</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">놀뜀별과 우리해붙이</h1>
        <p class="engSubs w3-medium">Location of Earth and pulsars</p>
    </div>
    <div class="contents w3-center">
        <p>
            되돌이동안_놀뜀_놀뜀별1=808ms
            <br>놀뜀별1의 놀뜀의 되돌이동안은 808ms이다.
            <br>우리해붙이와 놀뜀별1은 424빛해 떨어져 있다.
            <br>
            <br>놀뜀별2의 놀뜀의 되돌이동안은 5.75ms이다.
            <br>우리해붙이와 놀뜀별2는 509.8ly빛해 떨어져 있다.
            <br>
            <br>놀뜀별3의 놀뜀의 되돌이동안은 237ms이다.
            <br>우리해붙이와 놀뜀별3은 587ly빛해 떨어져 있다.
            <br>
            <br>놀뜀별4의 놀뜀의 되돌이동안은 8510ms이다.
            <br>우리해붙이와 놀뜀별4는 815ly빛해 떨어져 있다.
            <br>
            <br>놀뜀별5의 놀뜀의 되돌이동안은 385ms이다.
            <br>우리해붙이와 놀뜀별5는 940ly빛해 떨어져 있다.
            <br>
            <br>놀뜀별6의 놀뜀의 되돌이동안은 89.33ms이다.
            <br>우리해붙이와 놀뜀별6은 959ly빛해 떨어져 있다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">우리해붙이</h2>
        <p class="engSubs w3-xlarge">Earth</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">우리해붙이</h1>
        <p class="engSubs w3-medium">Earth</p>
    </div>
    <div class="contents w3-center">
        <p>
            누를힘_우리해붙이=101325Pa
            <br>우리해붙이의 누를힘은 101325Pa이다.
            <br>273K&lt;더움크기_물_우리해붙이&lt;373K
            <br>273K보다 크다 더움크기_물_우리해붙이 작다 373K보다
            <br>우리해붙이의 물의 더움크기는 273K보다 크고 373K보다 작다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">하늘, 바다, 땅</h2>
        <p class="engSubs w3-xlarge">Atmosphere, ocean, crust</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">하늘, 바다, 땅</h1>
        <p class="engSubs w3-medium">Atmosphere, ocean, crust</p>
    </div>
    <div class="contents w3-center">
        <p>
            하늘_우리해붙이=[질소,산소,아르곤,이산화탄소]
            <br>우리해붙이의 하늘은 [질소,산소,아르곤,이산화탄소]이다.
            <br>우리해붙이의 하늘은 질소, 산소, 아르곤, 이산화탄소로 이루어져 있다.
            <br>
            <br>우리해붙이의 바다는 물, 나트륨, 염소로 이루어져 있다.
            <br>우리해붙이의 땅은 산소, 규소, 알루미늄, 철로 이루어져 있다.
            <br>
            <br>높이_하늘=8848m
            <br>하늘의 높이는 8848m이다.
            <br>
            <br>바다의 깊이는 11034m이다.
            <br>
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">바탕이끌릴힘크기</h2>
        <p class="engSubs w3-xlarge">Gravity of Earth</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">바탕이끌릴힘크기</h1>
        <p class="engSubs w3-medium">Gravity of Earth</p>
    </div>
    <div class="contents w3-center">
        <p>
            g=9.80665m/s^2
            <br>1kg=9.8N
            <br>바탕이끌릴힘크기_1kg_우리해붙이=9.8N
            <br>우리해붙이에서 1kg의 바탕이끌릴힘크기는 9.8N이다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">바탕이끌릴힘크기</h2>
        <p class="engSubs w3-xlarge">Gravity of Earth</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">바탕이끌릴힘크기</h1>
        <p class="engSubs w3-medium">Gravity of Earth</p>
    </div>
    <div class="contents w3-center">
        <p>
            g=9.80665m/s^2
            <br>1kg=9.8N
            <br>바탕이끌릴힘크기_1kg_우리해붙이=9.8N
            <br>우리해붙이에서 1kg의 바탕이끌릴힘크기는 9.8N이다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">사람</h2>
        <p class="engSubs w3-xlarge">Human</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">사람</h1>
        <p class="engSubs w3-medium">Human</p>
    </div>
    <div class="contents w3-center">
        <p>
            사람_우리해붙이
            <br>우리해붙이의 사람
            <br>
            <br>사람의 바탕크기는 70kg이다.
            <br>사람의 바탕크기는 70kg이다.
            <br>사람의 키는 1.7m이다.
            <br>사람의 한뉘는 70해이다.
            <br>사람의 더움크기는 310K이다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">빛보기</h2>
        <p class="engSubs w3-xlarge">Visual spectrum</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">빛보기</h1>
        <p class="engSubs w3-medium">Visual spectrum</p>
    </div>
    <div class="contents w3-center">
        <p>
            빛보기_사람=380nm~740nm
            <br>사람의 빛보기는 380nm에서 740nm 사이이다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">소리듣기</h2>
        <p class="engSubs w3-xlarge">Hearing frequency</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">소리듣기</h1>
        <p class="engSubs w3-medium">Hearing frequency</p>
    </div>
    <div class="contents w3-center">
        <p>
            소리듣기_사람=20Hz~20000Hz
            <br>사람의 소리듣기는 20Hz에서 20000Hz 사이이다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">빛깔</h2>
        <p class="engSubs w3-xlarge">Colors</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">빛깔</h1>
        <p class="engSubs w3-medium">Colors</p>
    </div>
    <div class="contents w3-center">
        <p>
            빛너비_푸른빛깔=450nm~485nm
            <br>푸른빛깔의 빛너비는 450nm에서 485nm 사이이다.
            <br>
            <br>갈맷빛깔의 빛너비는 500nm에서 565nm 사이이다.
            <br>붉은빛깔의 빛너비는 625nm에서 740nm 사이이다.
            <br>
            <br>푸른빛깔+갈맷빛깔+붉은빛깔=흰빛깔
            <br>푸른빛깔+갈맷빛깔+붉은빛깔은 흰빛깔이다.
            <br>푸른빛깔, 갈맷빛깔, 붉은빛깔을 섞으면 흰빛깔이 된다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">어울린소리</h2>
        <p class="engSubs w3-xlarge">Chords</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">어울린소리</h1>
        <p class="engSubs w3-medium">Chords</p>
    </div>
    <div class="contents w3-center">
        <p>
            가=440.00Hz
            <br>나=493.88Hz
            <br>다=523.25Hz
            <br>라=587.33Hz
            <br>마=659.26Hz
            <br>바=698.46Hz
            <br>사=783.99Hz
            <br>가=880.00Hz
            <br>
            <br>[[다,마,사],[다,바,가],[라,사,나]]=밝게 어울린소리
            <br>[[라,바,가],[나,마,사],[가,다,마]]=어둡게 어울린소리
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">여사람, 남사람</h2>
        <p class="engSubs w3-xlarge">Female, male</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">여사람, 남사람</h1>
        <p class="engSubs w3-medium">Female, male</p>
    </div>
    <div class="contents w3-center">
        <p>
            사람=여사람∪남사람=7786000000
            <br>사람은 여사람∪남사람이다.
            <br>사람은 여사람과 남사람의 ∪이다.
            <br>사람은 여사람과 남사람으로 이루어진다.
            <br>우리해붙이의 사람은 78억명이다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">사람 낳음</h2>
        <p class="engSubs w3-xlarge">Sexsual reproduction</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">사람 낳음</h1>
        <p class="engSubs w3-medium">Sexsual reproduction</p>
    </div>
    <div class="contents w3-center">
        <p>
            여사람+남사람→[여,남,여]∨[여,남,남]
            <br>여사람 맺음 남사람은 [여,남,여] 또는 [여,남,남]이다.
            <br>여사람과 남사람의 맺음은 새로운 여사람 또는 남사람을 만든다.
            <br>여사람과 남사람은 맺음을 통해 새로운 여사람 또는 남사람을 낳는다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">삶바탕이</h2>
        <p class="engSubs w3-xlarge">Cell</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">삶바탕이</h1>
        <p class="engSubs w3-medium">Cell</p>
    </div>
    <div class="contents w3-center">
        <p>
            사람=40*10^12*삶바탕이
            <br>사람은 40조개의 삶바탕이이다.
            <br>사람은 40조개의 삶바탕이로 이루어져 있다.
            <br>
            <br>너비_삶바탕이=10^-5m
            <br>삶바탕이의 너비는 0.0001m이다.
            <br>
            <br>C6H12O6+O2→CO2+H2O
            <br>삶바탕이는 C6H12O6+O2를 CO2+H2O로 만든다.
            <br>삶바탕이는 C6H12O6와 O2를 맺음하여 CO2와 H2O를 만든다.
            <br>삶바탕이는 포도당과 산소를 맺어서 이산화탄소와 물을 만든다.
            <br>
            <br>사람*0.70=물
            <br>사람의 70%는 물이다.
            <br>사람의 70%는 물로 이루어져 있다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">DNA</h2>
        <p class="engSubs w3-xlarge">DeoxyriboNucleic Acid</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">DNA</h1>
        <p class="engSubs w3-medium">DeoxyriboNucleic Acid</p>
    </div>
    <div class="contents w3-center">
        <p>
            DNA_삶바탕이_사람
            <br>사람의 삶바탕이에는 DNA가 있다.
            <br>
            <br>H3PO4=인산
            <br>C5H10O4=디옥시리보스
            <br>C5H5N5=아데닌
            <br>C5H6N2O2=티민
            <br>C4H5N3O=시토신
            <br>C5H5N5O=구아닌
            <br>[아데닌,티민,시토신,구아닌]=염기
            <br>
            <br>DNA=인산+디옥시리보스+염기
            <br>
            <br>인산+디옥시리보스+[아데닌+티민]+디옥시리보스+인산
            <br>인산+디옥시리보스+[시토신+구아닌]+디옥시리보스+인산
            <br>인산+디옥시리보스+[티민+아데닌]+디옥시리보스+인산
            <br>인산+디옥시리보스+[구아닌+시토신]+디옥시리보스+인산
            <br>
            <br>DNA=DNA_여사람*1/2+DNA_남사람*1/2
            <br>DNA는 여사람의 DNA의 1/2과 남사람의 DNA의 1/2의 맺음이다.
            <br>DNA는 여사람과 남사람의 DNA가 맺어져서 만들어진다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">별하늘</h2>
        <p class="engSubs w3-xlarge">Observable universe</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">별하늘</h1>
        <p class="engSubs w3-medium">Observable universe</p>
    </div>
    <div class="contents w3-center">
        <p>
            별하늘의 나이는 138억해이다.
            <br>별하늘의 너비는 8.8*10^26m이다.
            <br>별하늘의 바탕크기는 10^53kg이다.
            <br>별하늘의 촘촘함크기는 9.9*10^-30g/cm^3이다.
            <br>별하늘의 더움크기는 2.72548K이다.
            <br>
            <br>해모임의 가른지름은 2빛해이다.
            <br>우리미리내의 가른지름은 5만빛해이다.
            <br>작은미리내모임의 가른지름은 5백만빛해이다.
            <br>라니아케아 큰미리내모임의 가른지름은 2억 5천만빛해이다.
            <br>
            <br>우리해붙이∈해모임
            <br>우리해붙이는 딸린다 해모임에
            <br>우리해붙이는 해모임에 딸린다.
            <br>
            <br>해모임은 우리미리내에 딸린다.
            <br>우리미리내는 작은미리내모임에 딸린다.
            <br>작은미리내모임은 라니아케아 큰미리내모임에 딸린다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">더작은바탕이</h2>
        <p class="engSubs w3-xlarge">Quark</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">더작은바탕이</h1>
        <p class="engSubs w3-medium">Quark</p>
    </div>
    <div class="contents w3-center">
        <p>
            덧작은바탕이의 덧뺄바탕크기는 +e이다.
            <br>빈작은바탕이의 덧뺄바탕크기는 0이다.
            <br>뺄바탕알갱이의 덧뺄바탕크기는 -e이다.
            <br>
            <br>더작은바탕이=쿼크=[(위,맵시,꼭대기,아래,이상한,바닥)쿼크]
            <br>더작은바탕이는 위, 맵시, 꼭대기, 아래, 이상한, 바닥쿼크로 나뉜다.
            <br>
            <br>위, 맵시, 꼭대기쿼크의 덧뺄바탕크기는 +2/3e이다.
            <br>아래, 이상한, 바닥쿼크의 덧뺄바탕크기는 -1/3e이다.
            <br>
            <br>덧작은바탕이=위쿼크+맵시쿼크+꼭대기쿼크
            <br>덧작은바탕이는 위, 맵시, 꼭대기쿼크의 맺음이다.
            <br>덧작은바탕이는 위, 맵시, 꼭대기쿼크가 맺어져서 이루어진다.
            <br>
            <br>빈작은바탕이는 아래, 이상한, 바닥쿼크가 맺어져서 이루어진다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">별하늘보기</h2>
        <p class="engSubs w3-xlarge">Radio telescope</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">별하늘보기</h1>
        <p class="engSubs w3-medium">Radio telescope</p>
    </div>
    <div class="contents w3-center">
        <p>
            별하늘보기_사람_우리해붙이
            <br>우리해붙이의 사람이 만든 별하늘보기
            <br>
            <br>별하늘보기의 지름은 70m이다.
            <br>별하늘보기의 빛보기는 5GHz에서 300GHz 사이이다.
            <br>
            <br>쪽글_별하늘보기_사람_우리해붙이
            <br>우리해붙이의 사람이 만든 별하늘보기의 쪽글
            <br>우리해붙이의 사람이 만든 별하늘보기에서 보낸 쪽글
            <br>우리해붙이의 사람이 별하늘보기를 통해 쪽글을 보냈다.
            <br>
            <br>떨림셈_쪽글=5.01GHz
            <br>쪽글의 떨림셈은 5.01GHz이다.
            <br>쪽글은 5.01GHz의 떨림셈으로 보냈다.
            <br>
            <br>한글_쪽글
            <br>쪽글의 한글
            <br>쪽글은 한글로 이루어져 있다.
            <br>쪽글은 한글로 쓰여있다.
        </p>
    </div>
    <div class="w3-center w3-hide-small">
        <h2 class="medium">쪽글</h2>
        <p class="engSubs w3-xlarge">The massage</p>
    </div>
    <div class="w3-center w3-hide-medium w3-hide-large">
        <h1 class="semi-medium">쪽글</h1>
        <p class="engSubs w3-medium">The massage</p>
    </div>
    <div class="contents w3-center">
        <p>
            더움크기_우리해붙이-(더움크기_우리해붙이-100해)=0.74°C
            <br>우리해붙이의 더움크기-(우리해붙이의 더움크기-100해)=0.74°C
            <br>우리해붙이의 더움크기-(100해 앞 우리해붙이의 더움크기)=0.74°C
            <br>우리해붙이의 더움크기에서 100해 앞 더움크기를 빼면 0.74°C이다.
            <br>우리해붙이의 더움크기는 100해 앞 더움크기와 견주어 0.74°C 높아졌다.
            <p style="font-size:1.4em">우리해붙이의 더움크기는 지난 100해 동안 0.74°C 높아졌다.<p>
                </p>
    </div>
</div>