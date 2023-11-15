# Safebrowse
Number 1 safest browser ever. NO COOKIES (so phishing won't work as far as I'm concerned). Discord, Tinder and Tiktok are blocked due to wierd people. (tiktok has a lot of famous content creators promoting scams)
This is the source code if you want to create your own version, don't trust me/the file or just if you want to see:

from tkinter import *
import webview
import pickle
url = input("Please Input URL : https://")
root = Tk()
if url == "discord.com":
    exit("Unsafe due to predators")
elif url == "tinder.com":
    exit("Unsafe due to predators")
else:
    webview.create_window("SafeBrowser", "https://" + url)
    webview.start()
    favourite = Button(root)
    favourite.pack()
