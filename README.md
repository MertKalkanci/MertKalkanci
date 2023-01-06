### My whole life be like:

```py
def TryToLive():
    try:
        with computer(life.half, "wr") as l:
            l.update()
            return l.read()
    except Exception as e:
        print("Error : " + str(e))
        input("waiting for input to quit program")
        exit()
```
