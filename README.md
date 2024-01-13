<header>
     <h1>About me</h1>
     <p>Hello there! I'm Hubert, a first-year cybersecurity student at AGH University in Cracow.</p>        
 </header>

 <section>
     <h2>More about me</h2>
<p>I'm currently working on my project with my classmates. In this project, we're creating a <b>Snake</b> game which has 3 difficulty levels, and it's quite easy to play. All you have to do is to move the snake by pressing <b>W, A, S, D</b> buttons. Hopeffuly, everything will work as well as we planned at the very beggining.</p>
      <p>Here you've got some sample of the code:</p>
      <pre>
           <code>
               while True:
                   for event in pygame.event.get():
                       if event.type == pygame.QUIT:  # zamykanie okienka gry
                           pygame.quit()
                           sys.exit()
                       if event.type == screenUpdate: # update co 150 milisekund
                           mainGame.update()
                       if event.type == pygame.KEYDOWN: # pygame nasluchuje klikniecia klawiatury
                           if event.key == pygame.K_w:
                               if mainGame.snake.direction.y != 1:
                                   mainGame.snake.direction = Vector2(0,-1)
                           if event.key == pygame.K_s:
                               if mainGame.snake.direction.y != -1:
                                   mainGame.snake.direction = Vector2(0, 1)
                           if event.key == pygame.K_d:
                               if mainGame.snake.direction.x != -1:
                                   mainGame.snake.direction = Vector2(1, 0)
                           if event.key == pygame.K_a:
                               if mainGame.snake.direction.x != 1:
                                   mainGame.snake.direction = Vector2(-1, 0)
                   gameScreen.fill((175, 215, 70))  # kolorowanie tła
           </code>          
      </pre>
 </section>

 <section>
     <h2>LinkedIn</h2>
     <p>Fell free to visit my LinkedIn profile: <a href="(https://www.linkedin.com/in/hubert-iwanowski-727106218/)" target="_blank">My Profile</a></p> 
     <h2>GitHub Profile</h2>
     <p>GitHub: <a href="https://github.com/hubertiwan" target="_blank">hubertiwan</a></p>
</section>

 <footer>
     &copy; 2024 hubertiwan.github.io. All rights reserved.
 </footer>

