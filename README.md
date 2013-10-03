hangul-jamo-js
==============

한글 자모음 라이브러리.

**Pull requests are always welcome.**

## Interface

### HANGUL.startsWith(haystack, needle)

*haystack*이 *needle*로 시작하는지 여부 반환

    > HANGUL.startsWith('가마니', '강철')
    false
    > HANGUL.startsWith('강철', '가')
    true
    > HANGUL.startsWith('강철', '강ㅊ')
    true
    > HANGUL.startsWith('강철', '철')
    false

### HANGUL.toJamos(str)

    > HANGUL.toJamos('강철')
    'ㄱㅏㅇㅊㅓㄹ'

### HANGUL.toChosungs(str)

    > HANGUL.toChosungs('강철')
    'ㄱㅊ'

### HANGUL.toJoongsungs(str)

    > HANGUL.toJoongsungs('강철')
    'ㅏㅓ'

### HANGUL.toJongsungs(str)

    > HANGUL.toJongsungs('강철')
    'ㅇㄹ'

## License
[MIT](https://github.com/teampopong/hangul-jamo-js/blob/master/LICENSE)
