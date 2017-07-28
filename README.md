# hackerrank_quest

2)
n = int(raw_input())
    if n%2 ==1:
        print "Weird"
    elif n%2==0 and 2 <= n <= 5:
        print "not Weird"
    elif n%2==0 and 6 <= n <= 20:
        print "Wierd"
    else:
        print "Not Weird"
        
3)
if __name__ == '__main__':
    a = int(raw_input())
    b = int(raw_input())
    print a+b
    print a-b
    print a*b
    
4)
from __future__ import division
if __name__ == '__main__':
    a = int(raw_input())
    b = int(raw_input())
    print a//b
    print a/b
5)
if __name__ == '__main__':
    n = int(raw_input())
    for i in range(5):
        i=i*i
        print i

