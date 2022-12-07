# HOW-TO-FIND-INDEX-OUT-OF-RANGE
t1=(10,100,50,40,30) st=int(input("enter start index: ")) en=int(input("enter end index: ")) n=len(t1) if st&lt;n and en&lt;n:     print(t1[st:en]) else:     print("index out of range")
