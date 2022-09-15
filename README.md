English | [中文](https://github.com/eileenthg/hoyolab-resin-counter-3.0/blob/main/README.zh-tw.md)

Original by seriaati: [English](https://github.com/seriaati/hoyolab-resin-counter) | [中文](https://github.com/seriaati/hoyolab-resin-counter/blob/main/README.zh-tw.md)

# hoyolab-resin-counter
![hoyolab-resin-counter (Small)](https://user-images.githubusercontent.com/61446626/159615993-8801f175-84b7-4361-bf65-7fb70708341a.png)  
Hoyolab real-time notes feature but on desktop.

## Features
- Shows your current resin
- Shows how much time until resin is full + when it caps (MM/DD/YY, HH:MM:SS)
- Shows number of commissions completed
- Shows realm currency
- Shows how much time until realm currency is full + when it caps (MM/DD/YY, HH:MM:SS)
- Shows number of expeditions completed
- Super duper fast resin checking after you have setup your account

## Setting up hoyolab-resin-counter
- Download and install python from https://www.python.org/downloads (Remember to check "Add Python to PATH")
- If popped up, click "Disable PATH length limit"
- Download the latest realease of [real-time-notes.py](https://github.com/eileenthg/hoyolab-resin-counter-3.0/blob/main/real-time-notes.py) and place it somewhere

### Adding your account
- Login to your account on https://www.hoyolab.com
- Right click real-time-notes.py and "Edit with IDLE" -> "Edit with IDLE"
- Put in your uid at UID HERE. (Replace 800000000)
![image](https://user-images.githubusercontent.com/40307498/190306694-6928ced4-d644-4ad9-9ade-dc7fd1c955e7.png)

## Running hoyolab-resin-counter
- Whenever you want to check your resin (or other things), open up a command prompt
- Type ```pip install genshin```
- Head toward the directory where real-time-notes.py is located using the ```cd``` command
- For example
```cd C:\Users\eteil.000\Documents```
- Then run the tool by typing ```python real-time-notes.py```
- You should be able to see the results, an example of what you should see is shown below  
![image](https://user-images.githubusercontent.com/40307498/190310649-282b47b6-6516-4993-8387-eda21f00e3f1.png)
- This tool does not receive data in real-time, when you want to check again, press the upward arrow button on your keyboard to run the command again, or type ```python real-time-notes.py```
- If you don't want to do the directory thing all over again, just leave the command prompt opened

## Other things
- User data is obtained using [https://github.com/thesadru/genshin.py](https://github.com/thesadru/genshin.py)
### Why make this
- Real-time notes feature only on hoyolab app but not desktop version
- Even using the app, I have to make 1000 taps to reach the real-time notes menu
  - ++HoYoLAB has waaay too many ads these days
- I don't play on my phone and I use my laptop most of the time, so I always forget checking my resin
