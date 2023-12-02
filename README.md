# notes
a

while 1 == 1:
    # make all aliens move right a bit
    for i in range(5):
        for ufo in alien_list:
            ufo.x += 10
        stage.wait(1)
        alienShoot()
    
    for ufo in alien_list:
        ufo.y -= 10
    stage.wait(1)
    alienShoot()
    
    # COPIED AND PASTED FROM ABOVE EXCEPT WE DO ufo.x -= 10 INSTEAD
    for i in range(5):
        for ufo in alien_list:
            ufo.x -= 10
        stage.wait(1)
        alienShoot()
    
    for ufo in alien_list:
        ufo.y -= 10
    stage.wait(1)
    alienShoot()

