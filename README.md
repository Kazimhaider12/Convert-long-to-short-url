# Convert-long-to-short-url

import pyshorteners

url  = input("Enter the url : ")

def shorturl(url):
    s = pyshorteners.Shortener()
    print(s.tinyurl.short(url))

shorturl(url)

