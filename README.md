hangul-jamo-js
==============

한글 자모 분리 라이브러리

## Usage

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

### HANGUL.startsWith(str)

    > HANGUL.startsWith('가마니', '강철')
    false
    > HANGUL.startsWith('강철', '가')
    true
    > HANGUL.startsWith('강철', '강ㅊ')
    true

