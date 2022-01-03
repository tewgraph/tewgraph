<img align="center" height="200" src="https://uploader.caliph.my.id/file/4TZyJ5.jpg"/>

---
```python
class say_hello:

    def __init__(self, text) -> None:
        self.text = text

    def __str__(self) -> str:
        return self.text

    def __repr__(self) -> str:
        return self.__str__()

if __name__ == "__main__":
    print(say_hello("Hola 👋, Yo soy Kvnxnl, Encantado de conocerlos a todos!"))
```