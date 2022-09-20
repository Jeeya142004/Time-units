# Time-units
a =int(input("Enter hour: "))
h=a/24
b =int(input("Enter minute: "))
c = int(input("Enter second: "))
d = int(input("Enter day: "))
e = int(input("Enter week: "))
w=e*7+1
f = int(input("Enter year: "))
print(a,"hours=", a*60, "minutes and", a*3600, "seconds and",a/24,"days and",a/24/7,"weeks and",h/365,"years")
print(b,"minutes=",b*60,"seconds and",b/60,"hours")
print(c,"seconds=",c/60,"minutes and",c/3600,"hours")
print(d,"days=",d/7,"weeks and",d/365,"years and",d*86400,"seconds")
print(e,"weeks=",e/52,"years and",e*7+1,"days and",w*86400,"seconds")
print(f,"years=",f*52,"weeks and",f*365,"days and",f*365*86400,"seconds")
