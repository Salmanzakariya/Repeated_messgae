# Repeated_messgae
This Python script automates typing a message multiple times using `pyautogui`. It takes user input, types the message with a delay between each entry, and presses 'enter' after each message. Useful for automating repetitive tasks like sending multiple identical messages. #Python #Automation

import pyautogui
import time 
def re(a):
   message = 5
   while message >0:
     time.sleep(3)
     pyautogui.typewrite(a)
     time.sleep(2)
     pyautogui.press('enter')
     message=message-1


a=input("enter :")
print(re(a))
