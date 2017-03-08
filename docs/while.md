# While

Repeat code..


```block
while(true) {
}
```

The while loop has ...


{% block example1 %}
```blocks
input.onButtonPressed(Button.A, () => {
    let index = 4;
    while(index >= 0) {
        led.plot(index, index);
        index--;
    }
})
```
{% endblock %}

