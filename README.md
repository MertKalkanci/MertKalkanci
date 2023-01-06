### My whole life be like:

```py
def tryToCode():
    try:
        with computer("live", "wr") as l:
            return l.read()
    except Exception as e:
        print("Error : " + str(e))
        input("waiting for input to quit program")
        exit()
```
