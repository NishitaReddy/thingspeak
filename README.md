# thingspeak
import urllib2
import time
import sys
x=100
base= 'https://api.thingspeak.com/update?api_key=Your Key &'  
while 1:
     
   f = urllib2.urlopen(base + "field1=%s&" % (x))
   time.sleep(2)
