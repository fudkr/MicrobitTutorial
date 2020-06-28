# LED 반전시키기

## STEP1

'무한반복' 블록 안에 LED 반전 블록을 집어 넣는다.

```blocks
basic.forever(function () {
    led.toggle(0,0)
})
```

## STEP2

'x' 값에 0~4사이의 랜덤 정수를 발생시킨다.

```blocks
basic.forever(function () {
    led.toggle(randint(0, 4), 0)
})
```

## STEP3

'y' 값에 0~4사이의 랜덤 정수를 발생시킨다.

```blocks
basic.forever(function () {
    led.toggle(randint(0, 4), randint(0, 4))
})
```

## All the code

LED 반전 확인!

```blocks
basic.forever(function () {
    led.toggle(randint(0, 4), randint(0, 4))
})
```
makeCodeRender(“{{ site.makecode.home_url }}”, “{{ site.github.owner_name }}/{{ site.github.repository_name }}”);
