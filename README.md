### Vax-Man. An Update

In accordance with EA Virtual Internship task, We are building a new game called Vax-Man. The rules are similar to Pac-Man with several notable exceptions:

- Vax-Man can kill a ghost if he comes into contact with it (vaccinates it).
- Contact with a ghost does not kill Vax-Man.
- Each ghost that has not yet been hit multiplies itself every 30 seconds (the infection grows).
- The goal of the game is to collect all the dots before the number of ghosts grows to 32 times the original number.
I'll be making major changes to the Pacman.py file to reflect Vax-man task.
## Identified Tasks                                                                             ##Progress
1. Vax-man killing (vaccinate) Ghost instead
2. Ghost *multiply* after time < 30sec 
3. Game ends as *Victory* when all dots are collected
4. Game ends as *Defeat* when Ghost growth is 32X original no of Ghost


### Pacman in Python with PyGame

This is a very minimal implementation of the Pacman game, having only one level and without ghosts strategy, not even with random movements (yes, the routes are programmed). However, we may improve this game in the future and everyone else interested can feel free to fork and contribute to this project.

Download installer from here: https://github.com/hbokmann/Pacman/blob/master/pacman.exe

![Pacman Game Window](https://raw.github.com/hbokmann/Pacman/master/images/pacman.jpg)


# Future development

* Fix Pacman's movement
* Ghosts moving algorithm and artificial intelligence
* Better design
* Better algorithm for the walls
* Additional levels?


Tested with [PyGame 1.9](http://pygame.org/ftp/pygame-1.9.2a0.win32-py3.2.msi ) and [Python 3.2 32bit](http://www.python.org/ftp/python/3.2.3/python-3.2.3.msi)


### Additional resources
* [Pac-Man Dossier - strategy of the ghosts movement](http://home.comcast.net/~jpittman2/pacman/pacmandossier.html)
* [HTML5 Pacman](http://arandomurl.com/2010/07/25/html5-pacman.html)
* [PyGame tutorials](http://programarcadegames.com/index.php?lang=en)
* [How To Write a Pacman Game in JavaScript](http://www.masswerk.at/JavaPac/pacman-howto.html)
* [Original Pacman game](http://originalpacman.com/)



### Support or Contact
Blog: http://www.bokmann.com

Twitter: https://twitter.com/hbokmann

Email: hans@bokmann.com
