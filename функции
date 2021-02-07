import random as r
import math as m
import time as t

def okruglit(q):
    z=m.floor(q)
    if q-z>=0.5:
        return m.ceil(q)
    if q-z<0.5:
        return m.floor(q)

def srednee_arifmeticheskoe(z):
    a=len(z)
    b=0
    c=0
    while c<a:
        b=b+int(z[c])
        c+=1
    d=b/a
    return d    

def bolshee_is_chisel(z):
    a=len(z)
    b=0
    c=0
    while c<a:
        d=z[c]
        if d>b:
            b=d
        c+=1
    return b

def menshee_is_chisel(z):
    a=len(z)
    b=99999999999999999999999999999999999999999999999999999999999999999**999
    c=0
    while c<a:
        d=z[c]
        if d<b:
            b=d
        c+=1
    return b    

def time_time_time(a,d,z):
    a=a
    d=d
    z=z
    print(a)
    e=0
    b=int(a[3::])
    a=int(a[:2:])
    c=a*60+b
    while e<d-1:
        a=int(z[e])
        c=c+a
        if c>=1440:
            c=c-1440
        b=(c//60)
        if b//10==0:
            b=str(b)
            q="0"+b
            b=q
        x=(c%60)
        if x//10==0:
            x=str(x)
            q="0"+x
            x=q
        x=str(x)
        b=str(b)
        print(b+":"+x)
        e+=1
        
def otcat(a):
    t.sleep(a)
