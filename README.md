# Competitive Programming Helper Discord bot
![Maintainer](https://img.shields.io/badge/Maintainer-CodingClub-blue)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![PyPi version](https://badgen.net/pypi/v/pip/)](https://pypi.org/project/pip)

This project is a Discord bot which helps a user in doing competitive programming efficiently.
This project aims to replace all the existent bots which are malfunctioning due to changes in their hosting clients, and also add [AtCoder](https://atcoder.jp/) as one of the judges supported, which none of the other existent bots supported.

We started off by figuring out the API requirements, thus ended up using APIs provided by [Codeforces](https://codeforces.com/apiHelp), [Kenkoooo](https://kenkoooo.com/atcoder#/table/)
and [Clist](https://clist.by/). Next, we worked on the database to be used for the project, and finally used Google's [Firebase](https://firebase.google.com/).
Finally, we created various functions that would enhance a user's experience on competitive programming platforms using [Python](https://www.python.org/) and used [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) for web scrapping. Lastly, all this was integrated using [discord.py](https://discordpy.readthedocs.io/en/stable/).

# Features

1. **Competitive Programming Judges supported**: [Codeforces](https://codeforces.com/) and [AtCoder](https://atcoder.jp/)
2. **Handle Identification**: Identifies handles of a user on the said judges, one user can have atmost one ID registered with the bot for a particular judge.
3. **Problem Recommendation**: Recommend random problem which the **user hasn't solved**, satisfying the conditions given by the user in the command
4. **Points and Leaderboard**: Provides points for problems recommended by the bot which the user solves and maintains leaderboards for the same
5. **Duels**: One user can challenge another user using this feature for a competitive programming duel
6. **Next Contests**: Provides a list of next ten contests in the future
7. **Stalk**: One user can stalk any other user on the judge using this feature, which provides the problems solved by that user and their rating
8. **Rating Change**: Provides the rating changes and results of a specific contest queried
9. **Graphs**: Provides graphs pertaining to various features such as performance, problems solved over time and ratings of problems solved over time

The commands for all these features and their usage can be retrieved by executing the command ```;help``` in the server.

# Usage

This bot is easy to set up and use. The bot can be installed locally by running the below command.

```git clone https://github.com/Sparsh752/TLE_Python.git```

Install the required dependencies:
1. [requests](https://requests.readthedocs.io/en/latest/user/install/)
2. [asyncio](https://pypi.org/project/asyncio/)
3. [bs4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/#installing-beautiful-soup)
4. [discord](https://pypi.org/project/discord.py/)
5. [datetime](https://pypi.org/project/DateTime/)
6. [firebase_admin](https://pypi.org/project/firebase-admin/)
7. [quickchart.io](https://pypi.org/project/quickchart-io/)
8. [nest_asyncio](https://pypi.org/project/nest-asyncio/)
9. [table2ascii](https://table2ascii.readthedocs.io/en/stable/)

Finally, the bot can be started by running the ``main.py`` file.

# Working

![image](https://github.com/Sparsh752/TLE_Python/assets/21035646/9182a9f9-32d8-4447-9a75-476cecf0dfbd)
![image](https://github.com/Sparsh752/TLE_Python/assets/21035646/a701f212-4323-4aa0-85a4-ef012a979a16)
![image](https://github.com/Sparsh752/TLE_Python/assets/21035646/2934f6ed-0c45-4de6-a3da-43e44eea16b4)


# Credits

This project was made by:
1. [Sparsh Mittal](https://github.com/Sparsh752)
2. [Adittya Gupta](https://github.com/Adittya-Gupta)
3. [Yash Raj Singh](https://github.com/Yash-jar)
4. [Rohan Mitra](https://github.com/rohan2411mitra)
5. [Satyam Chaurasia](https://github.com/satyam-ch)
6. [Gautam Sharma](https://github.com/g-s01)
7. [Dipit Patowari](https://github.com/DipitPatowari)
8. [Ayush Kumar](https://github.com/AyushUtk)
9. [Arnav Sharan](https://github.com/Arnavai)

