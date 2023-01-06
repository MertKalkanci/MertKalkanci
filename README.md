### Hi there 👋

'''py
def tryToCode():
    try:
        with computer("think", "r") as work:
            return work.read()
    except Exception as e:
        print("Error : " + str(e))
        input("waiting for input to quit program")
        exit()
'''
