# intro

`SceneSetup.intro();`

# intro-play-button

(...51)

[PLAY!](#intro-start) `publish("intro-to-game-1"); Game.OVERRIDE_CHOICE_LINE=true;`

# intro-start

(...500)

`clearText()`

n3: How fast do you want the text to scroll?

`publish("show_options_bottom")`

# intro-start-2

n3: This is a joke. please play the original.

```
publish("hide_tabs");
clearText();
```

(...1000)

`publish("intro-to-game-2")`

n2: THIS IS A HUMAN

(...600)

`clearText()`

(...300)

`publish("intro-to-game-3")`

# act1

```
SceneSetup.act1();
publish("hide_tabs");
music('battle', {volume:0.5});
```

(...300)

n: AND THIS IS THE HUMAN'S ANXIETY

n: _YOU_ ARE THE ANXIETY

(#act1_normal)


# act1_normal

```
hong({body:"putaway"});
sfx("rustle");
Game.OVERRIDE_TEXT_SPEED = 1.5;
```

h: No. Not listening. Not giving in.

```
sfx("rustle2");
hong({body:"phone1", mouth:"neutral", eyes:"neutral"})
```

n: YOUR JOB IS TO PROTECT YOUR HUMAN FROM *DANGER*

`bb({eyes:"look", mouth:"small_lock", body:"fear"})`

b: GET THE FUCK OFF TWITTER

```
bb({eyes:"normal", mouth:"normal", body:"normal"});
hong({eyes:"annoyed"});
```

h: Why the fuck do I not think, like, ever?

`hong({eyes:"neutral"});`

n: QUICK, WARN THEM ABOUT A *DANGER!*

```
bb({eyes:"look"});
```

[Oh, Trump did something stupid again!](#act1d_news)

[What if we start trending for the *wrong* reason?!](#act1d_subtweet)

[Aw, look! A cat drinking milk!](#act1d_milk)

# act1d_milk

`hong({mouth:"smile", eyes:"surprise"});`

h: Aww, that's adorable. I'll retweet it-

```
hong({mouth:"shock", eyes:"shock"});
bb({body:"scream"});
Game.OVERRIDE_TEXT_SPEED = 1.8;
```

b: CATS ARE LACTOSE INTOLERANT YOU SHOULD KNOW THIS YOU'RE A BAD PERSON

(...200)

```
bb({body:"normal", mouth:"normal", eyes:"fear"});
attack("20p", "bad");
publish("hp_show");
```



