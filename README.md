# python-1
#온도전환
#TempConvert.py
TempStr = input("온도 :")
if TempStr[-1] in ['F','f']:
        C = (eval(TempStr[0:-1] - 32)/1.8)
        print("전환후 온도{:.2f}C".format(C))
elif TempStr[-1] in ['C','c']:
        F = 1.8 * eval(TempStr[0:-1]) + 32
        print("전환후 온도{:.2f}F".format(F))
else:
        print("?")
